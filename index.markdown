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
                    <a href="{{ plugin.url }}"><img src="assets/images/{{ plugin.shortname }}.png" width="250px" height="164"></a>
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
                <!-- <a role="button" href="https://secure.2checkout.com/checkout/buy?merchant=250387521599&amp;style=default5f046eb833d53&amp;tpl=default&amp;prod=71865DCEF5&amp;qty=1" class="btn btn-primary btn-lg text-uppercase buy-button">buy
                    <i class="fas fa-shopping-cart" style="
                            margin-left: 5px;
                            margin-right: 5px;
                        "></i>20€</a> -->
            </div>
        </div>
    </div>

{% endfor %}
</div>
