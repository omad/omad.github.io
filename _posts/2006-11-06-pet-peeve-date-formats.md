---
title: 'Pet Peeve: Date Formats!'
author: Damien
layout: post
permalink: /2006/11/pet-peeve-date-formats/
categories:
  - Code
  - Tips
---
There is nothing that annoys me more than the variety of different ways different countries write their dates!

The main problem affecting me occurs with Australian/UK and US formats, there is often no way to tell which is which. Most well designs APIs avoid them both, and sensibly order elements year-month-day, but many people decide dates are simple and reimplement it themselves, *fools*. The PHP date functions expect things to be ordered in the American way, and blindly produce errors for the unwary programmer.

Java *solved* the problem by adding layers of confusion. If you want to use dates in Java in a particular format, you need to learn about dates, and then date formaters, and then locales, and then cross your fingers and hope for the best.

**Beware the evil dates!**