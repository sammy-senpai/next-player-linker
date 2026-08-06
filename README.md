# Next Player Linker

Ever tried to share a video with friends and ended up sending them a long, messy URL that opens in the browser and plays badly? Next Player Linker fixes that.

It turns any direct video link (like `.m3u8` or `.mp4`) into a clean, shareable web link. When your friends open that link on their Android phone, the video starts playing instantly — right inside the **Next Player** app, with the title and artwork already loaded. No fiddling with players, no complex settings, no browser controls.

## How It Works

Here's the whole journey, from start to finish:

**1. You open the Link Generator page.**

You paste your video link (the `.m3u8` or `.mp4` file) into a simple form, along with the title of the movie or show. You can also add a poster image, a banner, and a short description — but those are optional.

**2. The page gives you a shareable link.**

One click and you have a tidy link like `.../next-player-linker/index.html?url=...&title=...`. Copy it, and share it anywhere — WhatsApp, SMS, social media.

**3. Your friend opens the link on their phone.**

The page recognizes the video link you packed into it and shows a nice little play card with the poster, title, and synopsis. There's a single **Play** button.

**4. Next Player takes over.**

Tapping Play hands the stream straight to the Next Player app on their device, which opens it automatically and starts playing — no extra steps, no confusion.

**5. What if Next Player isn't installed?**

No problem. The link automatically redirects them to a simple install page with buttons for **GitHub** and **Google Play**. Once the app is installed, they tap to play and the video starts.

That's it. One link, a few taps, and the video plays — even for people who aren't tech-savvy.

## Try It

1. Grab any direct video link (`.m3u8` or `.mp4`).
2. Open the **Link Generator** page and fill in the video link and a title.
3. Copy the generated link and open it on an Android phone.
4. Install Next Player if prompted, then tap play.

## The Pages at a Glance

- **Link Generator** — where you create the shareable link.
- **Stream page** — what your friends see when they open the link; this is what launches Next Player.
- **Install page** — shown only when Next Player isn't installed, so they can grab it fast.

## About Next Player

[Next Player](https://github.com/anilbeesetti/nextplayer) is a free, open-source video player for Android. This project simply makes it easier for you to get your videos playing in it — no account, no setup, just a link.

## Built With

- Plain **HTML, CSS, and JavaScript** — no frameworks, no dependencies, nothing to install.
- The **Next Player** app, an open-source project by [Anil Beesetti](https://github.com/anilbeesetti).
