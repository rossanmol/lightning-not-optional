---
theme: default
background: https://logicwebmedia.s3.amazonaws.com/wp-content/uploads/20170328153215/website-speed-ranking-factors-graphic.jpg
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## Building Lightning-Fast Web

  Presentation slides for developers.
drawings:
  persist: false
transition: slide-left
css: unocss
title: Building Lightning-Fast Web
---

# Building Lightning-Fast Web

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <a href="https://github.com/rossanmol" target="_blank" alt="GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
transition: fade-out
---

# aBouT Me ❤️

<div class="grid grid-cols-12 gap-10">
	<div class="col-span-4 bg-slate-100 p-6 gap-4 rounded-md">
		<img src="/assets/me.jpg" class="rounded shadow mb-4" />
		<div class="font-bold">Rostislav Dascal</div>
		<div>@BetssonGroup</div>
	</div>
	<div class="grid gap-4 grid-cols-5 relative col-span-8 p-4">
		<img src="/assets/tara.png" class="rounded shadow  col-span-2 relative rotate-1 left-2" />
		<img src="/assets/coffee.jpg" class="rounded shadow rotate--2" />
		<img src="/assets/malta.jpg" class="rounded shadow rotate--1 col-span-2 row-span-2" />
		<img src="/assets/travel.jpg" class="rounded shadow rotate-1" />
		<img src="/assets/food.jpg" class="rounded shadow rotate--1" />
		<img src="/assets/malta_sea.jpg" class="rounded shadow roatate--3"/>
	</div>
</div>

---
transition: fade-out
---

# Tech Stack  ❤️

<div class="grid grid-cols-12 gap-10">
	<div class="col-span-4 bg-slate-100 p-6 gap-4 rounded-md">
		<img src="/assets/me.jpg" class="rounded shadow mb-4" />
		<div class="font-bold">Rostislav Dascal</div>
		<div>@BetssonGroup</div>
	</div>
	<div class="grid gap-4 grid-cols-5 relative col-span-8 p-4 items-center">
		<img src="/assets/tech/vercel.jpg" class="rounded  roate-1" />
		<img src="/assets/tech/nextjs.webp" class="rounded  roate-1" />
		<img src="/assets/tech/astro.svg" class="rounded  roate-1" />
		<img src="/assets/tech/cloudflare.png" class="rounded  roate-1" />
		<img src="/assets/tech/upstash.svg" class="rounded  roate-1" />
		<img src="/assets/tech/react.png" class="rounded  roate-1" />
		<img src="/assets/tech/nodejs.svg" class="rounded  roate-1" />
		<img src="/assets/tech/tailwind.png" class="rounded  roate-1" />
		<img src="/assets/tech/stencil.png" class="rounded  roate-1" />
		<img src="/assets/tech/appwrite.png" class="rounded  roate-1" />
		<img src="/assets/tech/trpc.svg" class="rounded  roate-1" />
		<img src="/assets/tech/vscode.png" class="rounded  roate-1" />
		<img src="/assets/tech/angular.png" class="rounded  roate-1" />
	</div>
</div>

<v-click>
	<div class="text-8xl fixed right-20 bottom-20 animate-[ping_2s_cubic-bezier(0,0,0.2,1)_infinite]">
		❤️
		<span class="absolute inset-0 top--2 justify-center items-center flex w-full h-full text-red-200 text-xl font-bold">SSR</span>
	</div>
</v-click>

---
layout: fact
---

# We have a Problem 😢!

---
layout: default
---

```html {9-10}
<!doctype html>
<html lang="en">
	<head>
		<meta charset="utf-8">
		<title>Love jQuery ❤️</title>
	</head>
	<body>
		<main>...</main>
		<script type="text/javascript" src="./jquery.min.js" />
		<script type="text/javascript" src="./all-the-js-in-the-world.js" />
	</body>
</html>

```
<img src="/assets/diagrams/jquery.svg" class="max-w-100 mx-auto"/>


---
layout: default
---

```html {9-10}
<!doctype html>
<html lang="en">
	<head>
		<meta charset="utf-8">
		<title>Love Angular ❤️</title>
	</head>
	<body>
		<main>...</main>
		<script type="text/javascript" src="./vendor.js" />
		<script type="text/javascript" src="./main.js" />
	</body>
</html>

```
<img src="/assets/diagrams/angular.png" class="max-w-35 mx-auto"/>


---
layout: default
---

# A random package.json

```json
"dependencies": {
    "@angular/animations": "^14.2.0",
    "@angular/cdk": "^14.2.0",
    "@angular/common": "^14.2.0",
    "@angular/compiler": "^14.2.0",
    "@angular/core": "^14.2.0",
    "@angular/elements": "^14.2.0",
    "@angular/forms": "^14.2.0",
    "@angular/localize": "^14.2.0",
    "@angular/material": "^14.2.0",
    "@angular/platform-browser": "^14.2.0",
    "@angular/platform-browser-dynamic": "^14.2.0",
    "@angular/router": "^14.2.0",
    "ajv": "8.11.0",
    "arrive": "2.4.1",
    "bootstrap": "4.6.1",
    "bootstrap-material-design": "4.1.3",
    "bootstrap-notify": "3.1.3",
    "chartist": "0.11.4",
    "classlist.js": "1.1.20150312",
    "eslint": "^8.11.0",
    "express": "4.17.3",
    "googleapis": "99.0.0",
    "hammerjs": "2.0.8",
    "jquery": "3.6.0",
    "moment": "2.29.1",
    "perfect-scrollbar": "1.5.5",
    "popper.js": "1.16.1",
    "rxjs": "~7.5.0",
    "tslib": "^2.3.0",
    "zone.js": "~0.11.4",
    "web-animations-js": "2.3.2"
  },
```

<v-click>
	<div class="absolute bottom-0 left-0 right-0 mx-auto grid justify-center items-center justify-items-center">
		<span class="text-red text-center">😁 hint: 20 lines more below... </span>
		<img src="/assets/diagrams/arrow-down.png" class="max-w-20" />
	</div>
</v-click>


---
layout: default
transition: fade

---

```html {9-10}
<!doctype html>
<html lang="en">
	<head>
		<meta charset="utf-8">
		<title>Love Angular ❤️</title>
	</head>
	<body>
		<main>...</main>
		<script type="text/javascript" src="./vendor.js" /> // 425kb
		<script type="text/javascript" src="./main.js" /> // 372kb
	</body>
</html>
```
<img src="/assets/diagrams/angular.png" class="max-w-35 mx-auto"/>


---
layout: default
---

```html {9-13}
<!doctype html>
<html lang="en">
	<head>
		<meta charset="utf-8">
		<title>Love Angular ❤️</title>
	</head>
	<body>
		<main>...</main>
		<script type="text/javascript" src="./vendor.js" /> // 425kb
		<script type="text/javascript" src="./main.js" /> // 372kb
		<script type="text/javascript" src="./analytics.js" /> // + {x} kb
		<script type="text/javascript" src="./tracking.js" /> // + {x} kb
		<script type="text/javascript" src="./polyfills.js" /> // + {x} kb
	</body>
</html>
```
<img src="/assets/diagrams/angular.png" class="max-w-35 mx-auto"/>

---
layout: default
class: 'bg-slate-600 text-slate-100 text-center'
---


# Client Side Rendering (SPA)

<div class="grid justify-center gap-5">
	<img src="/assets/diagrams/csr.png" class="rounded max-w-150 roate-1" />
</div>

<span class="text-gray text-italic absolute bottom-1 left-0 right-0 mx-auto text-xs">* Diagram borrowed from nextjs.org</span>

---
layout: default
class: 'bg-slate-600 text-slate-100 text-center'
---


# Server Side Rendering
<div class="grid justify-center gap-5">
	<img src="/assets/diagrams/ssr.png" class="rounded max-w-150 roate-1" />
</div>
<span class="text-gray text-italic absolute bottom-1 left-0 right-0 mx-auto text-xs">* Diagram borrowed from nextjs.org</span>

---
layout: default
class: 'bg-slate-600 text-slate-100 text-center'
---


# CSR vs SSR
<div class="grid justify-center gap-5">
	<img src="/assets/diagrams/csr.png" class="rounded max-w-100 roate-1" />
	<img src="/assets/diagrams/ssr.png" class="rounded max-w-100 roate-1" />
</div>
<span class="text-gray text-italic absolute bottom-1 left-0 right-0 mx-auto text-xs">* Diagrams borrowed from nextjs.org</span>

---
layout: default
---
# SSR via PHP

```php
<!DOCTYPE html>
<html>
  <head>
    <title>Products Demo Page</title>
    <link href="4-style.css" rel="stylesheet">
    <script src="5-script.js"></script>
  </head>
  <body>
    <div id="our-books"><?php
      require "2-products.php";
      foreach ($products as $p) { ?>
		<div class="bookWrap" data-id="<?=$p["product_id"]?>">
			<img class="bookImg" src="book.png">
			<div class="bookTitle"><?=$p["product_name"]?></div>
			<div class="bookDesc"><?=$p["product_description"]?></div>
		</div>
      <?php }
    ?></div>
  </body>
</html>
```
<div class="flex justify-end">
	<img src="/assets/diagrams/php.png" class="max-w-20" />
</div>

---
layout: default
---



<div class="grid gap-5 justify-items-center">
	<img src="/assets/diagrams/nodejs.svg" class="max-w-30 mb-10" />
	<div class="bg-slate-200 rounded p-2">NodeJS announced in 2009 by Ryan Dahl</div>
	<div class="bg-slate-200 rounded p-2">Build on Google V8</div>
	<div class="bg-slate-200 rounded p-2">NPM announced in 2011</div>
</div>

---
layout: default
---

# NodeJS introduced in ~2009 P2w (storytelling)


---
layout: default
---

# Why do we need SSR / SSG?

---
layout: default
---

# NextJS 13 Features

---
layout: default
---




# Hydration


---
layout: default
---

# Partial Hydration

---
layout: default
---

# Server Side Components


---
layout: default
---

# Streaming SSR / SSG


---
layout: default
---

# Next-Gen Caching


---
