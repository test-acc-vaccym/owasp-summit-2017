---
layout       : blocks/working-session
title        : Juice Shop Live-Release
type         : workshop
track        : Juice Shop
technology   : Node
description  : Live release of OWASP Juice Shop to publish all the work achievements of the summit and see Travis-CI & friends in action in the process.
status       : Final stage
organizers   : Bjoern Kimminich
when-day     : Fri
when-time    : AM-1
locked       : true
location     : Villa-5
participants :
invited      : Ade Yoseman Putra, Amani Altarawneh, Dinis Cruz, Francois Raynaud, Ingo Hanke, Madhu Akula, Stefano Di Paola, Tiago Mendo, Timo Pagel, Victor Vidigal Ribeiro, Josh Grossman
---

## Why

> [OWASP Juice Shop Project](https://www.owasp.org/index.php/OWASP_Juice_Shop_Project "OWASP Juice Shop Project")
> is an intentionally insecure webapp for security training written
> entirely in JavaScript and which encompasses the entire OWASP Top Ten
> and other severe security flaws. Juice Shop is written in Node.js,
> Express, and AngularJS. The application contains more than 30
> challenges of varying difficulty where the user should exploit the
> underlying vulnerabilities. Apart from being useful for hacker and
> awareness training, pentesting proxies or security scanners can also
> use Juice Shop as a "guinea pig" application to check how well their
> tools cope with JavaScript-heavy application frontends and REST APIs.

![Juice Shop Release](https://owaspsummit.org/Working-Sessions/Juice-Shop/juice-shop_release.png)

## What

Live release of OWASP Juice Shop to publish all the work achievements of
the summit and see Travis-CI & friends in action in the process.

![Juice Shop logo](https://github.com/bkimminich/juice-shop/raw/master/app/public/images/JuiceShop_Logo_100px.png)

## Outcomes

This working session will perform a live release utilizing the entire
CI/CD stack Juice Shop utilizes:

- New version of Juice Shop live on Heroku:
  <https://juice-shop.herokuapp.com>
- New version of Juice Shop CTF-extension live on NPM:
  <https://www.npmjs.com/package/juice-shop-ctf-cli>
- Release of latest Juice Shop pre-packaged distributions on GitHub:
  <https://github.com/bkimminich/juice-shop/releases/latest>
- Release of latest Juice Shop pre-packaged distributions on
  Sourceforge: <https://sourceforge.net/projects/juice-shop/>

## Who

The target audience for this Working Session is:

- everyone who was involved any Juice Shop-related session throughout
  the summit
- everyone who'd like to see the power of CI/CD automation with GitHub,
  Travis-CI and friends

---

## Working materials

| Juice Shop (`master` branch)                                                                                                                                                | CTF-Extension (`master` branch)                                                                                                                                                |
|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [![GitHub release](https://img.shields.io/github/release/bkimminich/juice-shop.svg)](https://github.com/bkimminich/juice-shop/releases/latest)                              | [![GitHub release](https://img.shields.io/github/release/bkimminich/juice-shop-ctf.svg)](https://github.com/bkimminich/juice-shop-ctf/releases/latest)                         |
| [![Build Status](https://travis-ci.org/bkimminich/juice-shop.svg?branch=master)](https://travis-ci.org/bkimminich/juice-shop)                                               | [![Build Status](https://travis-ci.org/bkimminich/juice-shop-ctf.svg?branch=master)](https://travis-ci.org/bkimminich/juice-shop-ctf)                                          |
| [![Build status](https://ci.appveyor.com/api/projects/status/903c6mnns4t7p6fa/branch/master?svg=true)](https://ci.appveyor.com/project/bkimminich/juice-shop/branch/master) | [![Dependency Status](https://gemnasium.com/badges/github.com/bkimminich/juice-shop-ctf.svg)](https://gemnasium.com/github.com/bkimminich/juice-shop-ctf)                      |
| [![Test Coverage](https://codeclimate.com/github/bkimminich/juice-shop/badges/coverage.svg)](https://codeclimate.com/github/bkimminich/juice-shop)                          | [![Coverage Status](https://coveralls.io/repos/github/bkimminich/juice-shop-ctf/badge.svg?branch=master)](https://coveralls.io/github/bkimminich/juice-shop-ctf?branch=master) |
| [![Code Climate](https://codeclimate.com/github/bkimminich/juice-shop/badges/gpa.svg)](https://codeclimate.com/github/bkimminich/juice-shop)                                | [![Code Climate](https://codeclimate.com/github/bkimminich/juice-shop-ctf/badges/gpa.svg)](https://codeclimate.com/github/bkimminich/juice-shop-ctf)                           |
| [![bitHound Overall Score](https://www.bithound.io/github/bkimminich/juice-shop/badges/score.svg)](https://www.bithound.io/github/bkimminich/juice-shop)                    | [![bitHound Overall Score](https://www.bithound.io/github/bkimminich/juice-shop-ctf/badges/score.svg)](https://www.bithound.io/github/bkimminich/juice-shop-ctf)               |

### Content

...add content...
