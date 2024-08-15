---
layout: page
title: FAQ
permalink: /faq/
---

# What plugin formats are available?
- **Windows**: VST3, CLAP
- **macOS** AU, VST3, CLAP
- **Ubuntu** VST3, CLAP


# What are the plugin system requirements?
- 64 bit
- OpenGL 3 or higher


# What kind of copy protection is used?
There is no copy protection or any other form of DRM (digital rights management) used in Darkpalace Studio plugins.


# How many computers can I use the plugin on?
You can use the plugin on as many computers as you like. 


# Is an internet connection required?
Once downloaded, all Darkpalace Studio plugins run completely offline.

Darkpalace Studio plugins will **never**

- try to "call home"
- require any sort of online service
- include any sort of revocation or invalidation mechanism


# How can I purchase any of the plugins?
Click the buy button on the plugin website. It will take you to the payment provider which handles secure payment and download of the actual files.

You can find all plugins also on the [shop](https://darkpalacestudio.tentary.com/)


# Do you offer sales?
Darkpalace Studio plugins are offered at a reasonable fixed price.
Setting fixed prices is a very fair option for all involved parties.
Thus there will be no sales or any bundle deals.


# Do you offer any plugin subscriptions?
There are no subscription options. 


# Will I have to pay for future updates?
All future updates are free to owners.


# Do you offer demo versions or trials?
No. As a small plugin developer time management is a crucial part. Building a demo version is actually a lot of effort.
I'd rather spend that time on building great quality audio plugins and add new features.

More importantly, a demo or trial version will require some sort of mute/noise feature. This is just a lightweight DRM to me. 
We have all been burned by existing DRMs of other companies, so this is out of the question.


# Do you offer refunds?
As the plugins contain no DRM or licensing, there is generally no refund option.


# Your sales strategy is different from Y! Can you do Z?
Most likely no. Most companies are in for the money, not for the customer.
That is why they offer/require bundles, sales, high upgrade fees, DRM, hardware dongles, subscription models and other pieces from the [Enshittification](https://www.wired.com/story/tiktok-platforms-cory-doctorow/) toolbox. 
At Darkpalace Stdio things are handled differently. Here it is "[Buy it, own it](https://doctorow.medium.com/https-pluralistic-net-2023-12-08-playstationed-tyler-james-hill-2ba28bfdbefc)".


# Can I create my own theme for a plugin?
Yes. All Darkpalace Studio plugins are highly customizable. Please take a look at the respective manual explaining the details.


# The plugin does not load on macOS
On macOS an extra step is required to get the plugin to load correctly.

More info can be found in
- [this website](https://disable-gatekeeper.github.io/)
- [this blogpost](https://www.osirisguitar.com/how-to-make-unsigned-vsts-work-in-macos-catalina/), 
- [this reddit thread](https://www.reddit.com/r/ableton/comments/g1dn3z/fixing_plugins_for_use_in_macos_catalina/) or 
- [this website](https://syntheway.com/fix-au-vst-vst3-macos.htm).


# The plugin looks weird with display scaling
Windows does not consistently forward display scaling to plugins.

If you are using windows settings to scale your screen and the plugin looks wei+rd, you can fix this by changing the value `custom_ui_scaling_factor` in the config file of your plugin, e.g.`C:\Users\Public\Documents\Darkpalace Studio\sloth\sloth_ui.json`.

When your Windows Settings show a display scaling of 125%, you need to set `custom_ui_scaling_factor` to `1.25`
respectively.


# The windows installer complains about installing the vst3 (error 183)
Please try to delete any old vst3 manually and run the installer again.

# The plugin UI does not open (but it does not crash)
This can be fixed by deleting the `editor.json` file in the respective folder:

- **Win**: `C:\Users\Public\Documents\Darkpalace Studio\[pluginName]`
- **Mac**: `/Users/Shared/Darkpalace Studio/[pluginName]`
- **Linux**: `~/.config/Darkpalace Studio/[pluginName]`


# I have technical issues. Where can I get help?
Please contact me via the official support email: 'darkpalacestudio@posteo.com'. 

Please include the following information in your mail (if appropriate). They tremendously help to solve the problem faster
- Description of the problem
- Screenshots/video recording
- Operating System and DAW (including versions)
- Name of the plugin and version (displayed in the footer bar of the plugin)
- System specs
- Report from dxdiag or similar