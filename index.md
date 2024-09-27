---
title: "Getting started"
keywords: sample homepage
tags: [starting, wifi]
sidebar: mydoc_sidebar
permalink: index.html
summary: These brief instructions will help you get started quickly with the KatPad by configuring the WIFI and entering in the programmer mode.
---

<!-- {% include note.html content="If you're cloning this theme, you're probably writing documentation of some kind. I have a blog on technical writing here called <a alt='technical writing blog' href='http://idratherbewriting.com'>I'd Rather Be Writing</a>. If you'd like to stay updated with the latest trends, best practices, and other methods for writing documentation, consider <a href='https://tinyletter.com/tomjoht'>subscribing</a>. I also have a site on <a href='http://idratherbewriting.com/learnapidoc'>writing API documentation</a>." %} -->

## The KatPad
![KatPad Map](/images/katpad-pic-01.jpg){:width="540"}

Hello!

To get your KatPat set up, please follow the instructions below.

### 1. Configure your WIFI


First, plug your KatPad on your computer. Then, after the splash screen:


1 - Press and hold the knob for ~2 seconds, you will enter in the settings menu.

2 - Select Programmer Mode > ON

3 - You will be back to the main screen and you can see now `CONFIGURE WIFI` in the top

4 - ON your computer, go to WIFI configuration and connect to KATPAD-WIFI-AP and inform the password: `craftslab3d`

5 - Open your browser and go to : [http://katpad-programmer.local/settings](http://katpad-programmer.local/settings)


![config wifi](/images/katpad-settings-configwifi.png){:width="640"}


6 - On Wi-Fi > Wi-Fi Network inform your network name (SSID) and the password, then `Save`. Your KatPadt will restart.

7 - After the splash screen, go to `Settings > Programmer Mode` and select `ON`. You'll be back to the main screen and you can see in the top: `Connecting...`. It can take some time.

8 - If the status changes to `PROGRAMMER MODE`, means that your WiFi was configured with success, you're good to go.


{% include tip.html content="If the KatPad is taking too long to connect, verify the distance to the modem, it can't be so far." %}

{% include note.html content="KATPAD-WIFI-AP is the Access Point created by the KatPad to configure your macropad for the first time. It doesn't intend to be used normally since your computer won't access the internet" %}


### 2. Introducing the Screen  

![KatPad Map](/images/katpad-screen-06.png){:width="740"}


Your KatPad has a OLED screen to assist you with information such as current layer, layer's key map, knob map, status and settings.
Bellow you can find a quick map of the screen.

![KatPad Map](/images/katpad-screen-map-01.png){:width="1040"}




<!-- ### 2. Install Jekyll

If you've never installed or run a Jekyll site locally on your computer, follow these instructions to install Jekyll:

* [Install Jekyll on Mac][mydoc_install_jekyll_on_mac]
* [Install Jekyll on Windows][mydoc_install_jekyll_on_windows] -->


{% include links.html %}
