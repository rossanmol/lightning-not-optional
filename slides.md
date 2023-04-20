---
theme: default
background: >-
  https://logicwebmedia.s3.amazonaws.com/wp-content/uploads/20170328153215/website-speed-ranking-factors-graphic.jpg
class: text-center
fonts:
  serif: Gloria Hallelujah
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

<!--
We will go through the journey of building a lightining fast application.
There is so much to cover on this topic, but we only have 30 minutes.
My goal is too show you some cool features and get you excited so that you go home and start building something cool

Plan -> Journey of building a lightining fast application.
Limit -> 30 minutes
Goal -> Show some cool features, so that you go home and build something cool
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

<!--
A little bit about me...

I love cooking, and coffee is something that I love even more
That's my cat Tara, she is "helping me" with most of the work.

I come from a tiny and sunny island called Malta
The summer season is coming, and you're just 1 flight away.
So pack your lagguages, and come! :)
-->

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
Here is the technologies I use in my day to day projects

Some special ones here are NextJS, TRPC and MeiliSearch.

And of course, something which I have focused a lot in my career is SSR.
-->

---
class: bg-slate-200
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
		<img src="/assets/diagrams/qr-poll.png" class="max-w-50"/>
	</div>
</div>

<!--
I forgot to mention that I love Eurovision

It's an event with so much culture, and so many great songs.
And of course, the best part is voting.

I have a small request for all of you, if you can...
Open Pagespeeg, enter the URL of a website you worked on recently, or just any website you know.

And then scan QR code from Step 2, and submit the overall score you got.
-->

---
layout: fact
---

<div class="grid justify-center gap-10">
	<h4>Time to build a website</h4>
	<img src="/assets/diagrams/hacking.gif" class="max-h-50"/>
</div>

<!--
So...


it's time to build a very beautiful website...


We get the laptop out, start typing...
-->

---
layout: fact
---

<div class="grid justify-center gap-10">
	<img src="/assets/diagrams/coffee.png" class="max-h-35"/>
</div>

<!--
Oh, we forgot the coffee...
So let's get coffee first

The smell is just so good...
-->

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

<!--
And after a very short time...

Our code probably looks like that
-->

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

<!--
And to add some interactivity we can use jQuery
And let's not forget the huge file called "all the js in the world"

Oh well, maybe we could make use of a framework which will add some kind of lazy loading...
-->

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

<!--
Angular is cool, so let's use that.
-->

---
layout: fact
class: bg-slate-600 text-slate-100 text-center
---

<img src="/assets/diagrams/wireframe.webp" class="max-w-100 mx-auto"/>

<div className="fixed top-20 left-60 text-5xl">✨</div>
<div className="fixed top-60 left-70 text-5xl">✨</div>
<div className="fixed top-75 right-65 text-5xl">✨</div>
<div className="fixed top-30 left-55 text-5xl">✨</div>

<div className="fixed bottom-15 right-50 text-6">😍</div>

<!--
And the site is ready, so beautiful and nice.
-->

---
layout: fact
---

## We have a Problem 😢!

<!--
But... We have a problem :(
-->

---

<img src="/assets/diagrams/pagespeed_result.webp" class="max-w-100 mx-auto"/>

<!--
Pagespeed does not like our site.

According to it, it takes around 9s for the website to load for an average user.

Oh, and the score of 44 is quite good, I was lucky enough to see a score of 0, yes , it's possible :D
-->

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

<!--
So let's go through our application...

We have a couple of NPM packages that we depend on...
-->

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

<!--
And... if we inspect our bundle size, our app measures almost a megabyte...
-->

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

<!--
And let's not forget the analytics and tracking scripts, and maybe some polyfills for older browsers...

All that adds up in size, and each user will have to download that, and rely on their hardware to run the application.
-->

---

# Why is performance important?
- 53% of visitors abandon the site if it loads in more than 3s according to a <a href="https://www.blog.google/products/admanager/increase-speed-of-your-mobile-site-wi/" target="_blank">study by google</a>.
- 2x more revenue <a href="https://support.google.com/webmasters/answer/9205520?hl=en" target="_blank">observed</a> for sites that loaded in 5 seconds instead of 19 seconds.
- Google <a href="https://developers.google.com/search/blog/2010/04/using-site-speed-in-web-search-ranking" target="_blank">confirmed</a> that PageSpeed and Core Web Vitals score affect SEO performance.
- When a site meets the Core Web Vitals thresholds, <a href="https://support.google.com/webmasters/answer/9205520?hl=en" target="_blank" >research</a> showed that users were 24% less likely to abandon page load.
- With each 100ms reduction in Largest Contentful Paint (LCP), web conversion rate for Farfetch <a href="https://web.dev/farfetch/?sjid=6308638093187460259-EU" target="_blank">increased</a> by 1.3%.

<img src="/assets/diagrams/old-android-phone.jpeg" class="max-w-50 mx-auto">

<!--
I could go through each bullet point on this slide...

But in the end it all boils down to the fact, that we as developers are responsible not only to build beautiful and shiny websites, but also ensure that our users get to see them.

A user will open your website, if it lagging or loads in more than 2 or 3 seconds, the user will press back and try another one.
-->

---
layout: default
class: bg-slate-600 text-slate-100 text-center
---

# Client Side Rendering (SPA)

<div class="grid justify-center gap-5">
	<img src="/assets/diagrams/csr.png" class="rounded max-w-150 roate-1" />
</div>

<span class="text-gray text-italic absolute bottom-1 left-0 right-0 mx-auto text-xs">* Diagram borrowed from nextjs.org</span>

<!--
So that's what we have with Client Side Rendering.

We send some HTML and Javascript to the user

The user sees a white page

And then the HTML is computed by the processing power of the user.
-->

---
layout: default
class: bg-slate-600 text-slate-100 text-center
---

# Client Side Rendering (SPA)

<div class="grid justify-center gap-5">
	<img src="/assets/diagrams/network-4g.png" class="rounded max-w-150 roate-1" />
</div>

<!--
That is highly reliant on the network of the user, but also the Device of the user.
-->

---
layout: default
class: bg-slate-600 text-slate-100 text-center
---

# Server Side Rendering
<div class="grid justify-center gap-5">
	<img src="/assets/diagrams/ssr.png" class="rounded max-w-150 roate-1" />
</div>
<span class="text-gray text-italic absolute bottom-1 left-0 right-0 mx-auto text-xs">* Diagram borrowed from nextjs.org</span>

<!--
With server side rendering, you can process the HTML on the server, and send the final version of the HTML to the user.

We can then reduce the bundle sizes by just shipping code that requires interaction only.
-->

---
layout: default
class: bg-slate-600 text-slate-100 text-center
---

# CSR vs SSR
<div class="grid justify-center gap-5">
	<img src="/assets/diagrams/csr.png" class="rounded max-w-100 roate-1" />
	<img src="/assets/diagrams/ssr.png" class="rounded max-w-100 roate-1" />
</div>
<span class="text-gray text-italic absolute bottom-1 left-0 right-0 mx-auto text-xs">* Diagrams borrowed from nextjs.org</span>

<!--
From user perspective, it is definetely more ideal to see some kind of UI at an earlier stage, so that should help with retaining more customers.
-->

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

<!--
And SSR is actually not a new concept...
Web Development was powered by SSR by default when most of logic would be either in PHP or C#.

Most of the logic was handled by the Server, and the user would just see the final HTML. 

But then Single Page Applications came in, and all the logic moved to the browser.
-->

---
layout: default
---

<div class="grid gap-5 justify-items-center">
	<img src="/assets/diagrams/nodejs.svg" class="max-w-30 mb-10" />
	<div class="bg-slate-200 rounded p-2">NodeJS announced in 2009 by Ryan Dahl</div>
	<div class="bg-slate-200 rounded p-2">Built on Google V8</div>
	<div class="bg-slate-200 rounded p-2">NPM announced in 2011</div>
</div>

<!--
In 2009 Ryan Dahl announced NodeJS, and shorty after NPM was announced as well, which allowed developers to share code via packages.

The ecosystem which followed after was just huge...
When you write code, there is a hich chance that there is NPM package that already does that.
-->

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
	<div class="font-bold bg-slate-200 rounded text-center">CLI/Services</div>
	<div class="font-bold bg-slate-200 rounded text-center">Web</div>
	<div class="font-bold bg-slate-300 rounded text-center">...</div>
	<div class="font-bold bg-slate-200 rounded text-center">...</div>
	<div class="font-bold bg-slate-200 rounded text-center">...</div>
</div>

<!--
Ok, so we have NodeJS and JS in the browser.

How are they different?

There quite a few, but mainly, Node does not have access to DOM and Window, while Browser does.

And Browser does not have direct access to file system while NodeJS does.

And of course, with NodeJS you would be building Server applications such as different Services or CLIs, while with browser JS you can build web applications.
-->

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

<!--
But if you had to look at these two snippets...

You would realise...

that it's all same...
-->

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

<!--
And I did mention that NodeJS does not have access to DOM

but that didn't stop developers from creating a virtual DOM interface and deploy those to NPM...


So if you have a website, and you want to run it on the website, using a package such as happy-dom, JSDOM or LinkeDOM you can just render it on the server.
-->

---
layout: center
---

# NextJS 13 Demo Time

<!--
Soo... it's time for a Demo
-->

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

<!--
NextJS is react based open source web development frame that allows developers to create dynamic web pages with great user experience and SEO through technologies such as Server Side Rendering.

All that, with the greatest developer experience.
-->

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

<!--
Now! It's time for Demo Time.

We will be going through a small application I built using NextJS 13, my goal was to do it under 2 hours.

Feel free to scan the QR code, if you would like to check it out.
-->

---
layout: default
class: bg-slate-600 text-slate-100 text-center
---

# FS-based routing

<div class="flex justify-center justify-items-center flex-col gap-10">
	<div class="flex justify-center">
		<img src="/assets/diagrams/route-segments.webp" class="max-w-150">
	</div>
</div>

<div class="text-gray text-italic absolute bottom-1 w-full text-center text-xs">* Diagram borrowed from nextjs.org</div>

<!--
File based routing:
	- Easy to split code based on route
    - Easy for Edge to identify which file should be used for a specific URL
    - Easy to define logic which is based on route, such as SEO (.
-->

---
layout: default
class: bg-slate-600 text-slate-100 text-center
---

# FS-based routing

<div class="flex justify-center justify-items-center flex-col gap-10">
	<div class="flex justify-center">
		<img src="/assets/diagrams/php-fs.jpeg" class="max-w-150">
	</div>
</div>

<!--
It is also extremely similar to the websites we were building back in the days with PHP. That did work well.
-->

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

<!--
Fetching different data sources is all handled on the server, and new snapshots for HTML are generated whenever anything changes.

All that is done in the background, while users enjoy the best experience.
-->

---
layout: default
class: bg-slate-600 text-slate-100 text-center
---

# Traditional SSR


<div class="flex justify-center">
	<img src="/assets/diagrams/ssr-hydration.webp" class="max-w-150">
</div>
<div class="text-gray text-italic absolute bottom-1 w-full text-center text-xs">* Diagram borrowed from nextjs.org</div>

<!--
At the beginning of the presentation, I went through SSR whichi processes the whole site, and after some time sends it to the user.

What if that is slow?
-->

---
layout: default
class: bg-slate-600 text-slate-100 text-center
---

# Streaming SSR

<div class="flex justify-center">
	<img src="/assets/diagrams/ssr-streaming.webp" class="max-w-150">
</div>

<div class="text-gray text-italic absolute bottom-1 w-full text-center text-xs">* Diagram borrowed from nextjs.org</div>

<!--
NextJS uses HTTP Streaming to Send parts of the website while it continues rendering the rest. This provides a great user experience, where user sees content as soon as possible.
-->

---
layout: default
---

# Server Side Components

<div class="grid grid-cols-[4fr_100px_100px] gap-1">
	<div class="p-1 text-sm bg-slate-300 rounded">What do you need to do?</div>
	<div class="p-1 text-sm bg-slate-300 rounded text-center">Server</div>
	<div class="p-1 text-sm bg-slate-300 rounded text-center">Browser</div>
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

<!--
Server side components are just better for more intensive tasks, especially where a lot of javascript is required, and that ideally remains on the server.
-->

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

<!--
There are many other technologies which do great things for the web, and it would be unfair for me not to mention them...

Toolls such as NuxtJS, Astro, Gatsby, Lit, Qwik, Remix and Analog.
-->


---
layout: default
---

# 👏👏👏

<div class="flex justify-center">
	<img src="/assets/diagrams/pagespeed_result.png" class="max-w-120">
</div>

<!--
And hopefully, your journey of creating your new project will be rewarded with great user experience, and a high pagespeed score.
-->

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
- <a href="https://clerk.com/" target="_blank">**The authentication you need**</a>
- <a href="https://app.warp.dev/referral/W665GY" target="_blank">**The terminal for the 21st century**</a>

<!--
I also have some cool links for you, check them out if you have some time.

Some special ones which I really wanted to menion is Zod and TurboRepo, these tools are so simple, but they can improve your application by a huge lot.
-->

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

<!--
Thank you very much!
-->
