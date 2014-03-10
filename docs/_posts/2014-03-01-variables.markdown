---
layout: post
title:  "Variables"
date:   2014-03-01 19:53:19
categories: 0.0.1
tags: variables list
---

Princess includes default values for all styles that can be manipulated from one main files: `source/helpers/_var.scss`.

## Variables

### Font families

{% highlight css %}
$font: 'Helvetica', 'Arial', sans-serif;
$fontAccent: 'Georgia', serif;
$fontMono: 'Source Code Pro', 'Courier New', monospace;
{% endhighlight %}

### Typography attributes

Always `em`.

{% include alert_must_be_number.html %}

{% highlight css %}
$fontSize: 1.1;
$fontWeight: 400;
$lineHeight: 1.5;
{% endhighlight %}

### Margins and padding

Always `px`.

{% include alert_must_be_number.html %}

{% highlight css %}
$padding: 20;
$margin: 20;
{% endhighlight %}

### Modules

{% highlight css %}
$transition: 500ms;
{% endhighlight %}

## Color variables

Swatches are listed below.

* `$text`
 - `$textLight`
 - `$textLightest`

* `$primary`
 - `$primaryLight`
 - `$primaryLightest`

* `$accent`
 - `$accentLight`
 - `$accentLightest`
 - `$accentDark`
 - `$accentDarkest`

* `$alert`
 - `$alertLight`
 - `$alertLightest`

* `$gray`
 - `$grayDark`
 - `$grayDarkest`

## Color themes

Princess includes a number of color schemes to get you going. You can view the individual color schemes in `source/helpers/_themes.scss`.

### Adding your own theme

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

### Theme: Default

* `$text` <div class="box prncs-background-text"></div> <div class="box prncs-background-textLight"></div> <div class="box prncs-background-textLightest"></div>
* `$primary` <div class="box prncs-background-primary"></div> <div class="box prncs-background-primaryLight"></div> <div class="box prncs-background-primaryLightest"></div>
* `$accent` <div class="box prncs-background-accent"></div> <div class="box prncs-background-accentLight"></div> <div class="box prncs-background-accentLightest"></div> <div class="box prncs-background-accentDark"></div> <div class="box prncs-background-accentDarkest"></div>
* `$alert` <div class="box prncs-background-alert"></div> <div class="box prncs-background-alertLight"></div> <div class="box prncs-background-alertLightest"></div>
* `$gray` <div class="box prncs-background-gray"></div> <div class="box prncs-background-grayDark"></div> <div class="box prncs-background-grayDarkest"></div>