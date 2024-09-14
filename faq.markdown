---
layout: page
title: FAQ
permalink: /faq/
---

# What file-formats are available for your plugins?
All of our plugins are available in the following formats:
- **Windows**: VST3, CLAP
- **macOS** AU, VST3, CLAP
- **Ubuntu** VST3, CLAP


# What are the system requirements for your plugins?
- 64 Bit
- OpenGL 3 or Higher


# What form of DRM/copy-protection is used in your plugins?
Our plugins do not come with any form of DRM (Digital Rights Management) and are considered
DRM-Free meaning that you own what you buy, no strings attached.



# How many computers can I install and use the plugin on?
You can install and use our plugins on as many computers are you like.



# Do the plugins require an internet connection to function?
No, all of your plugins *run completely offline* and do not require any form of internet
connection.

Darkpalace Studio plugins will **never**
- Try to "call home"
- Require any sort of online service
- Include any sort of revocation or invalidation mechanism
- Track any of our users for data



# How can I purchase any of your plugins?
All of our plugins are sold through Tentary which you can access by clicking the "Buy" button
located at the top of the designated plugin page which will take you to the payment provider
which handles secure payment and taxes. Tentary also provides you a way to download the files.

You can also find all of our plugins on the [Tentary Shop](https://darkpalacestudio.tentary.com/)



# Do you offer sales?
We believe that our plugins are offered at a reasonable price considering the current market and
therefor will not offer any sales or bundle-deals.

Note that we do offer Affiliate links where a percentage of the price is a commission. 
The price, however, for the customer will stay the same.



# Do you offer any plugin subscriptions?
We do not offer any subscription options and/or services.



# Will I have to pay for future updates?
All of our plugins come with free life-time updates.



# Do you offer demo versions or trials?
As of this moment, no. As a new and small plugin develop, time management is a crucial and difficult part.
Building a demo is a lot of effort regarding development and maintenance.  Also it goes against our principle of no DRM-protection.

Because of that we believe that it's worth more to spend our time on adding new features and 
building more awesome audio plugins.



# Do you offer refunds?
Due to our plugins not containing any form of DRM (Digital Rights Management) we generally do not
issue any refunds. Our reasoning is that a customer could buy one of our products, request a refund 
and then continue to use our products.

In the case there are any technical issues with one of our products, feel free to get in touch so
that we can discuss potential solutions.



# Your sales strategy is different from Y! Can you do Z?
Most like not, most companies are focussing a lot of time and effort into generating as much revenue 
as possible by utilizing various strategies such as:
- False advertisement as to what a product actually does
- Offering bundles as 'to-good-to-be-true'
- High upgrade fees
- DRM (login, dongles, etc)
- Subscription based services
- Vendor lock-ins

And many more tools from the [Enshittification](https://www.wired.com/story/tiktok-platforms-cory-doctorow/) toolbox.
At Darkpalace Studio we believe in the concept of "[You Buy it, You own it](https://doctorow.medium.com/https-pluralistic-net-2023-12-08-playstationed-tyler-james-hill-2ba28bfdbefc)"



# Some of these themes look great! Can I create my own?
Yes! All of our plugins are highly customizable, take a look at the respective manual for more details and feel free to contact us if there are any questions.



# The plugin does not load on macOS

**Fixed as of October 2024**

Starting with Sloth v1.1.2 and Chameleon 1.1.0 the macOS version of the plugins are codesigned.

For older versions on macOS an extra step is required to get the plugin to load correctly.

More info can be found in
- [this website](https://disable-gatekeeper.github.io/)
- [this blogpost](https://www.osirisguitar.com/how-to-make-unsigned-vsts-work-in-macos-catalina/), 
- [this reddit thread](https://www.reddit.com/r/ableton/comments/g1dn3z/fixing_plugins_for_use_in_macos_catalina/) or 
- [this website](https://syntheway.com/fix-au-vst-vst3-macos.htm).



# The plugin appears to look incorrectly scaled
Windows is known to not always be consistent, this including letting applications know
of the ui-scaling factor it uses. Because of this the GUI of Darkpalace Studio plugins can
often look out of proportions. In order to address this you will have to change a value in
the json file of the theme you are using.

- **Win**: `C:\Users\Public\Documents\Darkpalace Studio\[pluginName]`
- **Mac**: `/Users/Shared/Darkpalace Studio/[pluginName]`
- **Linux**: `~/.config/Darkpalace Studio/[pluginName]`

After this open the respective JSON file for the current theme and look for the value
custom_ui_scaling_factor key which should be located at the top of the file.

Once you’ve found this, change is to a decimal value representing your display-scaling
value. e.g. If your display-scaling is set to 125% in windows, change the value of 
custom_ui_scaling_factor to 1.25



# When running the windows installer an error pops-up regarding installing the VST (Error 183)
Windows is known to have issues with file-locking. Before running the installer, please make sure
that any VST-Host applications are closed and, if present, try to delete the already existing
plugin files before installation.



# When I try opening the plugin UI nothing shows up (But it does not crash)
This is a known issue with some DAWs. For now this can be fixed by going to
the respective plugin folder and deleting a file called `_editor.json`. The file can be located
in the following folders:

- **Win**: `C:\Users\Public\Documents\Darkpalace Studio\[pluginName]`
- **Mac**: `/Users/Shared/Darkpalace Studio/[pluginName]`
- **Linux**: `~/.config/Darkpalace Studio/[pluginName]`



# I have technical issues. Where can I get help?
If you have any other issues not listed here in the FAQ or simply have a question, feel free
to reach out to us via the official support email: `darkpalacestudio@posteo.com`. 

Please include the following information in your mail (if appropriate). They tremendously help to solve the problem faster
- Description of the problem
- Screenshots/video recording
- Operating System and DAW (including versions)
- Name of the plugin and version (displayed in the footer bar of the plugin)
- System specs
- Report from DXDiag or similar
