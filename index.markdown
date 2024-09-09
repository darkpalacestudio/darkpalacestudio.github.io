---
layout: default
---

# Audio Plugins

<div class="row">
{% for plugin in site.plugins %}
<div class="col-bottom-pad">
        <div class="text-center product_box">
            <div class="product_image">
                <!-- Start: Image -->
                    <a href="{{ plugin.url }}"><img src="assets/images/{{ plugin.shortname }}.webp" display="block" max-width="250px" height="auto"></a>
                <!-- End: Image -->
            </div>
            <div class="product_info" style="padding-bottom: 8px; width: 100%">
                <!-- Start: Name -->
                <a href="{{ plugin.url }}">
                    <span class="big_text_header">{{ plugin.name }}</span>
                    <span class="small_text_header">{{ plugin.tagline }}</span>
                </a>
                <!-- End: Name -->
            </div>
            <div style="">
            </div>
        </div>
    </div>

{% endfor %}
</div>
