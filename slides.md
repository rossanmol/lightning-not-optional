---
theme: default
background: https://logicwebmedia.s3.amazonaws.com/wp-content/uploads/20170328153215/website-speed-ranking-factors-graphic.jpg
class: text-center
fonts:
  serif: 'Gloria Hallelujah'
highlighter: shiki
lineNumbers: true
info: |
  ## Building Lightning-Fast Web
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
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-gray">
    <carbon-logo-github />
  </a>
    <a href="https://twitter.com/rossanmol" target="_blank" alt="GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-gray">
    <carbon-logo-twitter />
  </a>
	<a href="https://linkedin.com/in/rossanmol" target="_blank" alt="GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-gray">
    <carbon-logo-linkedin />
  </a>
</div>

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
		<img src="/assets/tech/meilisearch.png" class="rounded  roate-1" />
	</div>
</div>

<v-click>
	<div class="text-8xl fixed right-20 bottom-20 animate-[ping_2s_cubic-bezier(0,0,0.2,1)_infinite]">
		❤️
		<span class="absolute inset-0 top--2 justify-center items-center flex w-full h-full text-red-200 text-xl font-bold">SSR</span>
	</div>
</v-click>

<!--
- NextJS to build an application over the weekend.
- Astro works like a very good alternative for simpler websites, - where you don't need much interactivity.
- Vercel to help me get this apps to the users.
-
-->

---
class: 'bg-slate-200'
---
<h2 class="font-serif">And... 12 points go to...</h2>

<img src="/assets/diagrams/eurovision.png" class="max-w-20 absolute top-5 left-100">
<div class="grid grid-flow-col gap-20 mt-20">
	<div class="grid justify-center justify-items-center items-start rounded-lg bg-white p-4">
		<h4 class="underline">Step 1: Open Pagespeed</h4>
		<div>Enter a URL of a website</div>
		<img src="/assets/diagrams/qr-pagespeed.png" class="max-w-50"/>
	</div>
	<div class="grid justify-center justify-items-center  bg-white rounded-lg p-4">
		<h4 class="underline">Step 2: Vote!</h4>
		<div>Select the PageSpeed score you got</div>
		<img src="/assets/diagrams/qr-pagespeed.png" class="max-w-50"/>
	</div>
</div>


---
layout: fact
---

<div class="grid justify-center gap-10">
	<h4>Time to build a website</h4>
	<img src="/assets/diagrams/hacking.gif" class="max-h-50"/>
</div>

---
layout: fact
---

<div class="grid justify-center gap-10">
	<img src="/assets/diagrams/coffee.png" class="max-h-35"/>
</div>

---
layout: default
---

```html
<!doctype html>
<html lang="en">
	<head>
		<meta charset="utf-8">
		<title>Love Love Peace Peace ❤️</title>
	</head>
	<body>
		<main>...</main>
	</body>
</html>

```



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

# package.json

```json {all} {maxHeight:'400px'}
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
		<span class="text-red text-center">😁 hint: ~10 lines below... </span>
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
layout: fact
---

## We have a Problem 😢!

---


<img src="/assets/diagrams/pagespeed_result.webp" class="max-w-100 mx-auto"/>


---

# Why is performance important?
- 53% of visitors abandon the site if it loads in more than 3s according to a <a href="https://www.blog.google/products/admanager/increase-speed-of-your-mobile-site-wi/" target="_blank">study by google</a>.
- 2x more revenue <a href="https://support.google.com/webmasters/answer/9205520?hl=en" target="_blank">observed</a> for sites that loaded in 5 seconds instead of 19 seconds.
- Google <a href="https://developers.google.com/search/blog/2010/04/using-site-speed-in-web-search-ranking" target="_blank">confirmed</a> that PageSpeed and Core Web Vitals score affect SEO performance.
- When a site meets the Core Web Vitals thresholds, <a href="https://support.google.com/webmasters/answer/9205520?hl=en" target="_blank" >research</a> showed that users were 24% less likely to abandon page load.
- With each 100ms reduction in Largest Contentful Paint (LCP), web conversion rate for Farfetch <a href="https://web.dev/farfetch/?sjid=6308638093187460259-EU" target="_blank">increased</a> by 1.3%.

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

# Besides some differences...

<div class="grid grid-cols-3 gap-1 mt-10">
	<div class="font-bold bg-slate-300 rounded text-center">Feature</div>
	<div class="font-bold bg-slate-300 rounded text-center">NodeJS</div>
	<div class="font-bold bg-slate-300 rounded text-center">Browser API</div>
	<div class="font-bold bg-slate-300 rounded text-center">DOM</div>
	<div class="font-bold bg-slate-200 rounded text-center">❌</div>
	<div class="font-bold bg-slate-200 rounded text-center">✅</div>
	<div class="font-bold bg-slate-300 rounded text-center">Window</div>
	<div class="font-bold bg-slate-200 rounded text-center">❌</div>
	<div class="font-bold bg-slate-200 rounded text-center">✅</div>
	<div class="font-bold bg-slate-300 rounded text-center">File System</div>
	<div class="font-bold bg-slate-200 rounded text-center">✅</div>
	<div class="font-bold bg-slate-200 rounded text-center">❌</div>
	<div class="font-bold bg-slate-300 rounded text-center">Environment</div>
	<div class="font-bold bg-slate-200 rounded text-center">Server</div>
	<div class="font-bold bg-slate-200 rounded text-center">Client</div>
	<div class="font-bold bg-slate-300 rounded text-center">Type of apps</div>
	<div class="font-bold bg-slate-200 rounded text-center">Web</div>
	<div class="font-bold bg-slate-200 rounded text-center">CLI/Services</div>
	<div class="font-bold bg-slate-300 rounded text-center">...</div>
	<div class="font-bold bg-slate-200 rounded text-center">...</div>
	<div class="font-bold bg-slate-200 rounded text-center">...</div>
</div>



---
layout: default
transition: slide-up
---


#### JS in Browser

```ts
const a = 4;
const b = 38;

console.log(a + b); // 42
```

#### NodeJS

```ts
const a = 4;
const b = 38;

console.log(a + b); // 42
```

<v-click>
	<h1 class="mt-20 text-center">It's all same</h1>
</v-click>

---
layout: default
---

```ts
import { Window } from 'happy-dom'; // alternatives JSDOM / LinkeDOM

const { document } = new Window({
	innerWidth: 1024,
	innerHeight: 768,
	url: 'http://localhost:8080'
});
document.write(`
    <html>
        <head>
             <title>Test page</title>
        </head>
        <body>
			<div class="container"> </div>
            <script>
                const element = document.createElement('div');
                const container = document.querySelector('.container');
                element.innerHTML = 'SSR is awesome!';
                container.appendChild(element);
            </script>
        </body>
    </html>
`);

// Will output "SSR is awesome!"
console.log(document.querySelector('.container div').innerHTML);
```


---
layout: center
---


# NextJS Demo Time

---
layout: center
---

# But before that...

---
layout: default
---

# What is NextJS?

<div class="mx-auto text-gray mt-20">
... is an <strong class="text-2xl text-black">open-source web development framework</strong> created by the private company Vercel providing <strong class="text-2xl text-black">React-based</strong> web applications with <strong class="text-2xl text-black">server-side rendering</strong> and static website generation.

With Next.js, developers can create <strong class="text-2xl text-black">dynamic web pages</strong> that can be pre-rendered and served statically or rendered on the server, providing a <strong class="text-2xl text-black">better user experience</strong> in terms of speed and search engine optimization (<strong class="text-2xl text-black">SEO</strong>). Next.js also comes with features such as automatic code splitting, static file serving, and easy integration with data sources such as APIs and databases.
</div>
---
layout: default
---

# Demo Time 🎉

<div class="flex justify-center justify-items-center flex-col gap-10">
	<div class="flex justify-center">
		<a href="https://lightining-not-optional-app.vercel.app" class="inline" target="_blank">lightining-not-optional-app.vercel.app</a>
	</div>
	<div class="flex justify-center">
		<img src="/assets/diagrams/qr.app.png" class="max-w-100">
	</div>
</div>

---
layout: default
---

# Server Side Components

<div class="grid grid-cols-[4fr_100px_100px] gap-1">
	<div class="p-1 text-sm bg-slate-300 rounded">What do you need to do?</div>
	<div class="p-1 text-sm bg-slate-300 rounded text-center">Browser</div>
	<div class="p-1 text-sm bg-slate-300 rounded text-center">Server</div>
	<div class="p-1 text-sm bg-slate-200 rounded">Fetch data.</div>
	<div class="p-1 text-center">✅</div>
	<div class="p-1 text-center">⚠️</div>
	<div class="p-1 text-sm bg-slate-200 rounded">Access backend resources (directly)</div>
	<div class="p-1 text-center">✅</div>
	<div class="p-1 text-center">❌</div>
	<div class="p-1 text-sm bg-slate-200 rounded">Keep sensitive information on the server (access tokens, API keys, etc)</div>
	<div class="p-1 text-center">✅</div>
	<div class="p-1 text-center">❌</div>
	<div class="p-1 text-sm bg-slate-200 rounded">Keep large dependencies on the server / Reduce client-side JavaScript</div>
	<div class="p-1 text-center">✅</div>
	<div class="p-1 text-center">❌</div>
	<div class="p-1 text-sm bg-slate-200 rounded">Add interactivity and event listeners (onClick(), onChange(), etc)</div>
	<div class="p-1 text-center">❌</div>
	<div class="p-1 text-center">✅</div>
	<div class="p-1 text-sm bg-slate-200 rounded">Use State and Lifecycle Effects (useState(), useReducer(), useEffect(), etc)</div>
	<div class="p-1 text-center">❌</div>
	<div class="p-1 text-center">✅</div>
	<div class="p-1 text-sm bg-slate-200 rounded">Use browser-only APIs</div>
	<div class="p-1 text-center">❌</div>
	<div class="p-1 text-center">✅</div>
	<div class="p-1 text-sm bg-slate-200 rounded">Use custom hooks that depend on state, effects, or browser-only APIs</div>
	<div class="p-1 text-center">❌</div>
	<div class="p-1 text-center">✅</div>
</div>

<div class="text-gray text-italic absolute bottom-1 w-full text-center text-xs">* Diagram borrowed from nextjs.org</div>
---
layout: default
---




# Next-Gen Caching

<div class="mt-10"></div>
```ts
// the below API call takes ~1.5s to fetch
fetch('https://example.com/api/cats', {
	next: {
		revalidate: 60
	}
});

// in reality... it's almost instant
```
---
layout: default
class: 'bg-slate-600 text-slate-100 text-center'
---
# Traditional SSR


<div class="flex justify-center">
	<img src="/assets/diagrams/ssr-hydration.webp" class="max-w-150">
</div>
<div class="text-gray text-italic absolute bottom-1 w-full text-center text-xs">* Diagram borrowed from nextjs.org</div>

---
layout: default
class: 'bg-slate-600 text-slate-100 text-center'
---
# Streaming SSR

<div class="flex justify-center">
	<img src="/assets/diagrams/ssr-streaming.webp" class="max-w-150">
</div>

<div class="text-gray text-italic absolute bottom-1 w-full text-center text-xs">* Diagram borrowed from nextjs.org</div>


---
layout: default
---
# Other tools to built great Websites

<div class="grid gap-20 grid-cols-3 relative col-span-8 p-4 items-center justify-items-center mt-20">
	<img src="/assets/other/nuxtjs.png" class="rounded max-h-15 roate-1" />
	<img src="/assets/other/astro.svg" class="rounded max-h-15  roate-1" />
	<img src="/assets/other/gatsby.png" class="rounded max-h-15  roate-1" />
	<img src="/assets/other/lit.png" class="rounded max-h-15  roate-1" />
	<img src="/assets/other/qwik.png" class="rounded max-h-15  roate-1" />
	<img src="/assets/other/remix.png" class="rounded max-h-10  roate-1" />
</div>


---
layout: default
---
# 👏👏👏

<div class="flex justify-center">
	<img src="/assets/diagrams/pagespeed_result.png" class="max-w-120">
</div>



---
layout: default
---

# Cool links 😎

- **These slides**: <a href="https://lightning-not-optional.vercel.app" target="_blank">lightning-not-optional.vercel.app</a>
- **Meow app**: <a href="https://lightining-not-optional-app.vercel.app" target="_blank">lightining-not-optional-app.vercel.app</a> (notice the typo 😭)
- <a href="https://nextjs.org/blog/next-13" target="_blank">**NextJS 13 Announcement** </a>
- <a href="https://beta.nextjs.org/docs/api-reference/metadata#file-based-metadata" target="_blank">**File-based Metadata** </a>
- <a href="https://zod.dev/" target="_blank">**Zod** </a>
- <a href="https://turbo.build/" target="_blank">**Turborepo + Turbopack** </a>
- <a href="https://clerk.com/">**The authentication you need**</a>
- <a href="https://app.warp.dev/referral/W665GY">**The terminal for the 21st century**</a>
---
layout: center
---

# Thank You!
<div class="abs-br m-6 flex gap-2">
  <a href="https://github.com/rossanmol" target="_blank" alt="GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-gray">
    <carbon-logo-github />
  </a>
    <a href="https://twitter.com/rossanmol" target="_blank" alt="GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-gray">
    <carbon-logo-twitter />
  </a>
	<a href="https://linkedin.com/in/rossanmol" target="_blank" alt="GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-gray">
    <carbon-logo-linkedin />
  </a>
</div>
