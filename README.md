# Smart-Bedside-Clock---iPhone-6-Friendly
This is a simple, lightweight, **smart bedside clock** web page designed for older iPhones (like iPhone 6) to be used as a **bedside clock with live weather info**.


Smart Bedside Clock - iPhone 6 Friendly

This is a simple, lightweight, smart bedside clock web page designed for older iPhones (like iPhone 6) to be used as a bedside clock with live weather info.

Features

24-hour digital clock set to a configurable timezone (default: Tunis, Africa/Tunis)

Current weather for a configurable location (default: Tunis), fetched live from wttr.in — no API key needed

Dark theme optimized for overnight charging on LCD screens

Uses funky Google Font DynaPuff for a clean, stylish look

Fully contained in a single HTML file for easy hosting (e.g., GitHub Pages)

How to Use

Clone or download this repository.

Open index.html in a browser (works on desktop or mobile).

To host on GitHub Pages:

Create a new GitHub repository.

Upload index.html.

Go to Settings > Pages, select the main branch and root folder.

Visit your GitHub Pages URL to see the bedside clock.

On your iPhone:

Open the GitHub Pages URL in Safari.

Tap Share > Add to Home Screen for fullscreen access.

Optionally enable Guided Access to lock the screen and keep it always on.

Set Auto-Lock to Never and enable Night Shift for best experience.

How to Customize

Change Location for Weather and Timezone

Open index.html in a text editor.

Find these lines inside the <script> tag:

// Timezone setting
const timeZone = 'Africa/Tunis';

// Weather fetch URL
const weatherUrl = 'https://wttr.in/Tunis?format=%t+%C';

Replace 'Africa/Tunis' with your desired IANA timezone (like 'Europe/Paris').

Replace 'Tunis' in the weatherUrl with your city name or location (like 'Paris', 'London', or 'New York').

Change Font or Colors

Modify the <link> tag in <head> to use a different Google Font if you like.

Change colors and font sizes inside the <style> tag.

Troubleshooting

If weather doesn’t load, check your internet connection.

Make sure wttr.in is reachable from your network.

The clock uses your device's time but displays it in the configured timezone.

Credits

Weather data provided by wttr.in — a free weather service.

Font used: DynaPuff by Google Fonts.

Enjoy your smart bedside clock!
