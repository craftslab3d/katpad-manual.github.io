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

The KatPad is a 3D printed macropad in ICED PETG plastic and powered with the Sugoi-Macropad-Firmware created by Crafts Lab 3D.

The Sugoi-Macropad-Firmware has your own Programmer Software (Server Based) which makes it totally autonomous and free of a 3rd party software.  

To get your KatPat set up, please follow the instructions below.

### 1. Configure your WIFI


First, plug your KatPad on your computer. Then, after the splash screen:


1 - Press and hold the knob for ~2 seconds, you will enter in the settings menu.

2 - Select Programmer Mode > ON

3 - You will be back to the main screen and you can see now `CONFIGURE WIFI` in the top

4 - ON your computer, go to WIFI configuration and connect to KATPAD-WIFI-AP and inform the password: `craftslab3d`

5 - Open your browser and go to : [http://katpad-programmer.local/settings](http://katpad-programmer.local/settings)


![config wifi](/images/katpad-settings-configwifi.png){:width="640"}


6 - On `Wi-Fi > Wi-Fi Network` inform your network name (SSID) and the password, then `Save`. Your KatPadt will restart.

7 - After the splash screen, go to `Settings > Programmer Mode` and select `ON`. You'll be back to the main screen and you can see in the top: `Connecting...`. It can take some time.

8 - If the status changes to `PROGRAMMER MODE`, means that your WiFi was configured with success, you're good to go.

9 - Now you can try to access: [http://katpad-programmer.local/](http://katpad-programmer.local/) and create your first macro!


{% include tip.html content="If the KatPad is taking too long to connect, verify the distance to the modem, it can't be so far." %}

{% include note.html content="KATPAD-WIFI-AP is the Access Point created by the KatPad to configure your macropad for the first time. It doesn't intend to be used normally since your computer won't access the internet" %}


### 2. Knowing your KatPad  

![KatPad Map](/images/katpad-screen-06.png){:width="740"}

Let's start with the basics!
Your KatPad has an OLED screen, a keypad and a knob.
The knob has some important functions:

1 - `Single Press`: it goes to the next layer when in the main screen or, when in the MENU, is used to choose an option.

2 - `Long Press` (hold for about ~2 sec): you enter in the MENU.

3 - `Rotation`: When in the main screen, is used as a normal key, you can map the clockwise and the counter clockwise direction! For example, you can map the volume, zoom for the desired application or any other key or macro.

In the other hand, when in the MENU, it's used to navigate among the options.



### 3. OLED Screen  

Your KatPad has an OLED screen to assist you with information such as current layer, layer's key map, knob map, status and menu settings.

Bellow you can find a quick screen map.

<!-- ![KatPad Map](/images/katpad-screen-map-01.png){:width="1040"} -->
<div class="img-enlargeble">
<a href="/images/katpad-screen-map-01.png">
    <img src="/images/katpad-screen-map-01.png" width="880" />
</a>
</div>


#### 3.1. Main Screen

<p><span class="image left">
<img src="/images/katpad-main-screen.png" alt=""/>
</span>
<br><br>
The main screen you have all you need to know when using the KatPad: knob map, current layer and keys map.
</p>
<br><br><br>

<p><span class="image right">
<img src="/images/katpad-menu-screen.png" alt="" />
</span>
<br><br>
In the 1st screen of the menu you can find all options available: lights, Programmer Mode, Reset WIFI, Restart and About
</p>

<!-- ![KatPad Screen](/images/katpad-main-screen.png){:width="350"}

The main screen you have all you need to know when using the KatPad: knob map, current layer and keys map.


#### 3.2. Menu Options
![KatPad Screen](/images/katpad-menu-screen.png){:width="300"}

In the 1st screen of the menu you can find all options available: lights, Programmer Mode, Reset WIFI, Restart and About -->
<br><br><br><br><br>

<p><span class="image left">
<img src="/images/katpad-lights-screen.png" alt=""/>
</span>
<br><br>
The main screen you have all you need to know when using the KatPad: knob map, current layer and keys map.
</p>
<br><br><br><br><br>

<p><span class="image right">
<img src="/images/katpad-lights-opt-screen.png" alt="" />
</span>
<br><br>
In the 1st screen of the menu you can find all options available: lights, Programmer Mode, Reset WIFI, Restart and About
</p>

<!-- #### 3.2.1 Lights
![KatPad Screen](/images/katpad-lights-screen.png){:width="300"}


#### 3.2.2 Lights Option
![KatPad Screen](/images/katpad-lights-opt-screen.png){:width="300"}
 -->

 <br><br><br><br><br>
 <p><span class="image left">
 <img src="/images/katpad-lights-mode-screen.png" alt=""/>
 <img src="/images/katpad-base-mode-screen.png" alt="" />
 </span>
 <br><br>
 The main screen you have all you need to know when using the KatPad: knob map, current layer and keys map.
 </p>
 <br><br><br><br><br>
 <br><br><br><br><br>
 <p><span class="image right">
 <img src="/images/katpad-light-color-screen.png" alt="" />
 <img src="/images/katpad-base-color-screen.png" alt="" />
 </span>
 <br><br>
 In the 1st screen of the menu you can find all options available: lights, Programmer Mode, Reset WIFI, Restart and About
 </p>

<!-- #### 3.2.3 Lights Mode
![KatPad Screen](/images/katpad-lights-mode-screen.png){:width="300"}
![KatPad Screen](/images/katpad-base-mode-screen.png){:width="300"} -->

<!-- #### 3.2.4 Lights Color
![KatPad Screen](/images/katpad-light-color-screen.png){:width="300"}
![KatPad Screen](/images/katpad-base-color-screen.png){:width="300"} -->


<br><br><br><br><br><br><br><br><br><br>

<p><span class="image left">
<img src="/images/katpad-light-bright-screen.png" alt=""/>
<img src="/images/katpad-base-bright-screen.png" alt=""/>
</span>
<br><br>
The main screen you have all you need to know when using the KatPad: knob map, current layer and keys map.
</p>
<br><br><br><br><br><br><br><br><br><br>

<p><span class="image right">
<img src="/images/katpad-prog-mode-screen.png" alt="" />
</span>
<br><br>
In the 1st screen of the menu you can find all options available: lights, Programmer Mode, Reset WIFI, Restart and About
</p>
<!--
#### 3.2.5 Lights Brightness
![KatPad Screen](/images/katpad-light-bright-screen.png){:width="300"}
![KatPad Screen](/images/katpad-base-bright-screen.png){:width="300"}


#### 3.3. Programmer Mode
![KatPad Screen](/images/katpad-prog-mode-screen.png){:width="300"}
 -->

 <br><br><br><br><br>

 <p><span class="image left">
 <img src="/images/katpad-reset-wifi-screen.png" alt=""/>
 </span>
 <br><br>
 The main screen you have all you need to know when using the KatPad: knob map, current layer and keys map.
 </p>
 <br><br><br><br><br>

 <p><span class="image right">
 <img src="/images/katpad-restart-screen.png" alt="" />
 </span>
 <br><br>
 In the 1st screen of the menu you can find all options available: lights, Programmer Mode, Reset WIFI, Restart and About
 </p>
 <br><br><br><br><br>

 <p><span class="image left">
 <img src="/images/katpad-about-screen.png" alt=""/>
 </span>
 <br><br>
 The main screen you have all you need to know when using the KatPad: knob map, current layer and keys map.
 </p>
 <br><br><br><br><br>


<!-- ### 2. Install Jekyll

If you've never installed or run a Jekyll site locally on your computer, follow these instructions to install Jekyll:

* [Install Jekyll on Mac][mydoc_install_jekyll_on_mac]
* [Install Jekyll on Windows][mydoc_install_jekyll_on_windows] -->


{% include links.html %}
