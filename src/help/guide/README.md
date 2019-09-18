---
title: Getting Started
lang: en-US
---

## Installation

Download the latest stable release of Tachiyomi from
[GitHub](https://github.com/inorichi/tachiyomi/releases/latest).

`tachiyomi-vX.Y.Z.apk`

If you want to try new features before they get to the stable release,
you can download the dev version [here](http://tachiyomi.kanade.eu/latest).

Open and install the `.apk` file you just downloaded from GitHub.

<figure class="centered">
	<img height="145" intrinsicsize="1000x500" width="300"
	  :src="$withBase('/assets/media/installprompt.png')">
</figure>

## Installing an extension

Now that Tachiyomi is installed, open the app and navigate to the
`Extensions` tab.

In this guide we will use MangaDex, our most popular extension.
Press the `Install` button and accept the installation prompt that
will be shown.

If you're getting stopped by a security prompt and don't know what to do
you can read this FAQ section: ["How do I allow third-party installations
on my phone?"](/help/faq/extensions/#how-do-i-allow-third-party-installations).

<figure class="centered">
	<video autoplay crossorigin="use-credentials" height="534"
	  intrinsicsize="500x100" loading="lazy" loop="loop" muted="muted"
	  playsinline="playsinline" :poster="$withBase('/assets/media/extensioninstaller.png')"
	  preload="none" width="300">
		<source :src="$withBase('/assets/media/extensioninstaller.webm')" type="video/webm" />
		<source :src="$withBase('/assets/media/extensioninstaller.mp4')" type="video/mp4" />
	</video>
</figure>

## Adding manga to your library

Now that you've installed the MangaDex extension it should show up in
the `Catalogues` tab. The items appearing here are called `Sources`
(can also be called Catalogues), an extension can contains multiple sources.

To find and add manga, you can now either use the `Latest` button on your
source, or you can use `Browse` and search for it.

Now that you've found manga that you want to add to your library, click
on it and then press the blue bookmark button.

It should now appear in your `My Library` tab, ready to be read!

<figure class="centered">
	<video autoplay crossorigin="use-credentials" height="534"
	  intrinsicsize="500x1000" loading="lazy" loop="loop" muted="muted"
	  playsinline="playsinline" :poster="$withBase('/assets/media/addtolibrary.png')"
	  preload="none" width="300">
		<source :src="$withBase('/assets/media/addtolibrary.webm')" type="video/webm" />
		<source :src="$withBase('/assets/media/addtolibrary.mp4')" type="video/mp4" />
	</video>
</figure>