---
layout: post
title:  "Color themes"
date:   2014-03-01 19:53:19
categories: 0.0.1
tags: customizations
---

Princess includes a number of color themes to get you going. You can view the individual color themes in `source/helpers/_themes.scss`.

## Adding your own theme

To add your own theme, use this base code and add it to `source/helpers/_themes.scss`.:

{% highlight css %}
$myColorScheme: (
  text: #000,
  background: #000,
  primary: #000,
  accent: #000,
  alert: #000,
  gray: #000,
)
{% endhighlight %}

Inside of `source/helpers/_var.scss`, change `$theme: $default;` to:

{% highlight css %}
$theme: $myColorScheme;
{% endhighlight %}

All of the colors will update after you compile.

## Existing themes

The first color swatch is the bast color. Subsequent swatches are light, lightest, dark, or darkest, depending on the color.

## Default

* `$text` <div class="box prncs-background-text"></div> <div class="box prncs-background-textLight"></div> <div class="box prncs-background-textLightest"></div>
* `$primary` <div class="box prncs-background-primary"></div> <div class="box prncs-background-primaryLight"></div> <div class="box prncs-background-primaryLightest"></div>
* `$accent` <div class="box prncs-background-accent"></div> <div class="box prncs-background-accentLight"></div> <div class="box prncs-background-accentLightest"></div> <div class="box prncs-background-accentDark"></div> <div class="box prncs-background-accentDarkest"></div>
* `$alert` <div class="box prncs-background-alert"></div> <div class="box prncs-background-alertLight"></div> <div class="box prncs-background-alertLightest"></div>
* `$gray` <div class="box prncs-background-gray"></div> <div class="box prncs-background-grayDark"></div> <div class="box prncs-background-grayDarkest"></div>