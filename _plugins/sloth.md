---
layout: plugins
price: 20
name: Sloth
shortname: sloth
tagline: Slew Rate Limiter
date: 2024-01-01
---

<p style="text-align: right">
<a href="https://example.org" class="w3-button">Purchase {{page.price}}€</a>
</p>

![Sloth UI](/assets/images/sloth_looping.gif)


# {{page.tagline}}

Sloth is a slew rate limiter plugin. In electronics "slew rate" is the change of voltage over time. 
When the input signal at an amplifier switches instantly, the output will not immediately change, but "slew" to the new value at a certain rate.

While in modern electronics slew rates are no concern, some valued older designs feature a limited slew rate. 
This in itself imposes a characteristic sound.
Applying slew rate limiting can result in a variety of effects, including in denser signals, subtle darkening of the tone, enhanced texture of sounds up to massively mangled and crushed effects.

Sloth brings the concept of slew rate limiting to the digital domain as a unique tool for artists, mixers and sound designers.

The UI is rendered on the GPU, offloading the CPU for the crucial part: audio processing. Additionally the plugin is freely resizable. 
Themes and other modifications can easily be done via convenient `json` configuration files.

# Links

- [Manual](assets/manuals/sloth_manual_v0.3.0.pdf)
- [Purchase ({{page.price}}€)](https://darkpalacestudio.tentary.com/p/kod0B9)
