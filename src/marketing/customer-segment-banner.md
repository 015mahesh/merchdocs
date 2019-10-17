---
conditions: Default.EE-B2B
title: Customer Segments with Banners
group: customers
---

{: .bs-callout .bs-callout-info }
DEPRECATED: [Page Builder]({{ site.baseurl }}{% link cms/page-builder.md %})’s advanced content tools replace the previous banner functionality as described in this topic. We keep this content in the user guide as a convenience for those whose stores have customizations that prevent them from using Page Builder.

A [banner]({{ site.baseurl }}{%- link cms/banners.md -%}) can target a specific [customer segment]({{ site.baseurl }}{%- link marketing/customer-segments.md -%}), and be incorporated into a [cart price rule]({{ site.baseurl }}{%- link marketing/price-rules-cart.md -%}). Because customer segments are dynamic, the price rule can adjust to changes in customer activity.

![Banners list]({{ site.baseurl }}{%- link images/images-ee/banners-list.png -%}){: .zoom}
_Banners_

## Associate a customer segment with a banner

1. On the _Admin_ sidebar, go to **Content** > Elements > **Banners**.

1. Open a new or existing banner:
    - To use a new banner, click <span class="btn">Add Banner</span> in the upper-right corner.
    - To use an existing banner, select the banner checkbox use the **Actions** menu to choose **Edit**.

1. Set **Customer Segments** to `Specified` and select each customer segment that you want to target with the banner.

    ![Select targeted customer segments]({{ site.baseurl }}{%- link images/images-ee/banner-properties-customer-segment.png -%}){: .zoom}
    _Targeted Customer Segment_

1. In the left panel, choose **Related Promotions** and select the checkbox of each related promotion.

    ![Select related promotions]({{ site.baseurl }}{%- link images/images-ee/banner-related-cart-price-rule.png -%}){: .zoom}
    _Related Promotions_

1. Update the other banner settings as needed.

    For details about other banner properties, see [Complete the banner properties]({% link cms/banner-create.md#step-1-complete-the-banner-properties %})

1. When complete, click <span class="btn">Save Banner</span>.
