# Portfolio

Hello! This is my portfolio file. Below I will list some projects sources and demos, that I was made ever.

Most of my code is covered by NDAs, so, I will publish a link to a public sites, and give the sources where it possible.

## Bank card payment form (old) for Yandex.Money NBCO LLC.

Developed at 2014-2015 years.

Here i was develop both user interface and business logic. Interface is still unchanged, 
so you may go to this link https://clck.ru/AWyoV and try to pay 1 rouble for me :) You don't need an Yandex.Money 
account to do this.

Tech stack are: XScript (proprietary server-side engine), XSLT, HTML, CSS, jQuery.

## Universal payment form for Yandex.Money NBCO LLC.

Developed in 2015.

Here i was develop server-side business logic only. Interface is changed, but business logic still the same. 
so you may go to this link https://clck.ru/AWyqf and try to pay more 1 rouble for me :) also, you still don't need an 
Yandex.Money account to do this.

Tech stack is node.js.


## REST API for landings service

Developed in 2019

Landings generator service API for Protocol.One, allowes CRUD operations with landings, publishing anl external domains set. https://github.com/ProtocolONE/ptah-api

Tech stack: Node.js, Koa, MongoDB, Swagger

## OAuth authorization middleware module

Developed in 2019

This is an NPM module Koa middleware to provide OAuth authorization for Protocol.One, using it's own auth provider (Auth1). This middleware perform login, logout, and token refresh operations. https://github.com/ProtocolONE/authone-jwt-verifier-node/

Tech stack: Node.js, Koa, Redis, Ava test framework

## TexJar transactions sync service

Developed in 2019

This is a very simple service for PaySuper infrastructure, that syncing US-based transactions from RabbitMQ queue to taxjar.com service (which is automatically calculating sales taxes) https://github.com/paysuper/paysuper-taxjar-transactions-sync

Tech stack: Go, Resty, RabbitMq

## Payment links service

Developed in 2019

This is a service for PaySuper infrastructure, something like url shortener, that provides fullfilling shopping basket with predefined set of products and prepare order to make payment. It provides GRPC interface for communicate with main PaySuper Management Service. https://github.com/paysuper/paysuper-payment-link

Tech stack: Go, GoMicro, GRPC, Redis

## Onlinepay merchant cabinet for Onlinepay PTE

Developed in 2017.

Single page application. This is only demo of early beta-version of application, and it works with json stub, not 
with real backend server. But some base functionality is available, and you can try it on http://test2.strigo.ru
(credentials is test@test.com and 123 as password).

Tech stack is Angular 5, typescript, Redux, Globalize.js for localization engine, Angular CLI, Bootstrap 3.

## iOS banking application integration with Apple Pay.

Developed in 2016-2017

Here was no demo or source, because of NDA. But... if you have and AkBars bank mobile app for iOS, you can try add 
your card to Apply Pay )

It was very specific work, because original app was an Web Single Page Application, wrapped by Cordova container. 
In such apps, native OS functionality can me used inside container through special plugins (it works as a bridge 
between OS and site in WebView)
All good, but there is no plugins for Apple Pay card provisioning in whole Cordova ecosystem... 
So, I was write it by myself. Web side - on javascript, and native side - on Objective C. 

Tech stack: Cordova, Objective C, javascript, backbone. 

## Onlinepay web site

Developed in 2018.

Simple, high-speed an low-weight web site. Very fluid and adopted for any mobile devices, starting from iPhone 5.

I proud, that it contains only 1 bitmap image, and all other images are vector. It gives hi-quality scaling and very 
small file size. 

Another key feature - all resources are minified as much as possible. Thanks for Webpack, SVGO, optiPNG, UglifyJs and
 other tools :)
 
You can see this site in publiс at https://onlinepay.com/
 
Tech stack: node.js as backend engine, typescript as main language, EJS as template engine, SASS, Post-CSS, Bootstrap
 4, jQuery, Webpack
 
## Onlinepay Web Wallet
 
Developed in 2018.

Web version of Onlinepay Wallet application for Android and iOS.

As this application target group includes peoples from Africa and Latin America, so, the ley requirements for it are support for old browsers (IE8+), 
and working in non-js mode, such as on Opera Mini with extremal traffic economy enabled.

You may try it for free at https://wallet.onlinepay.com/login/ - use your phone number as login, and in minute you 
receive an sms with password, and new account will be created for you. You will no be applied for any chagres or 
fees, no sms or email spam :)

Tech stack: node.js as backend engine, typescript as main language, EJS as template engine, SASS, Post-CSS, Bootstrap
 3, jQuery, Webpack, Globalize.js as internationalization engine. 

Also, application includes some microservices, such as card payment gateway, that written on Ruby on Rails.
 
## Population Zero account cabinet

Developed in 2018

This is side-project, what is called "Friends asked for help" :) Work contains of two parts - first is write static 
layout for html pages of gamer's cabinet of Population Zero game, and second is to integrate it to the server engine 
as dynamic template, with variables output, ajax requests to api, etc.

Now, you can see demo of static layout at http://test3.strigo.ru/ and sources are also available at https://github.com/JamesKotov/populationzero-layout

Intergrated templates in production you can see at https://account.pzonline.com/login - they are original for now 
(december 2018), but i have no warranties, that it will be stay unchanged in future. 

Tech stack: HTML, SASS, post-css, javascript, webpack, and PHP Symphony framework used on backend

## Extended filters for HostCMS

Development started at 2014

There are many online stores in internet, and many content management systems. Some years ago I was like to use 
HostCMS for making online stores and other sites, because in very powerful even in free version and includes a good 
shop engine.

This engine can filter goods on page by some properties, but filtering vas very simple. So I write an module to 
provide an extended filtering and sorting. Now you become to see what properties are actual, what prices range 
applies to selected conditions, how many items are meet the conditions, order goods by popularity, or by values of 
any good' property and many more. 

It is must have for good online shop, so this module is commercial and is for sale, so I can not show you a sources, 
but you may see a demo page - http://test.strigo.ru/shop/camcorder/ (filtering block at the right column) or read 
some documentation (in russian, sorry) - http://hostcmsblog.ru/blog/extendedfilters/#install

(BTW, on the same site http://hostcmsblog.ru/blog/ you may see some another my old code for HostCMS)

Tech stack: PHP 5+, MySQL, XSLT, javascript, css, html, HostCMS.

## API Example

Developed in 2019

Test work for interview - yet another book store api. Every book may have many authors. https://github.com/JamesKotov/koa-db-test

Tech stack: Node.js, Koa, MySQL

## Cloud storage example

Developed in 2018

A test work for interview in one little payment company. Test legend - we are building a competitor to Amazon S3 
offering, and now need to create an API application.

Some more details in repository README - https://github.com/JamesKotov/my-cloud-storage

Tech stack: PHP, MySQL, Slim, Propel

## Calories calculator

Developed in 2016 

Yet another test task for interview :)

Simple single page application, that implements Calories calculator based on Harris-Benedict equation. Working with 
Ajax requests was required by task.

Here is sources https://github.com/JamesKotov/calories-calculator and here is demo - http://strigo.ru/cc/

Tech stack: Angular.JS 1.4, Bootstrap 3, and PHP for server-side ajax handler.

## Sites parser

Developed in 2015

Another project form series called "Friends asked for help". 

Parser for other online stores. What is the best html parser engine? The internet browser is! So, we will load and 
parse site's pages with javascript directly in browser's console ) I recommend to use Chrome.

Sources - https://github.com/JamesKotov/chrome-sites-parser 

Tech stack: jQuery, lodash, Q promises library, and of course some piece of PHP.

## Daily balances widget for Dzenmoney

Developed in 2010

Very old test work for interview to DzenMoney company. It implements special widget for user's daily financial 
operations and balances. Uses ajax for dynamic content loading while scroll.

Sources - https://github.com/JamesKotov/dzen, demo - http://strigo.ru/dzen/

Tech stack: jQuery, YIU-2 as CSS framework.
 
