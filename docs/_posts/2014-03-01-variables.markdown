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

All "light", "lightest", "dark", and "darkest" colors are automatically generated from the base color.

To change these colors, you'll have to create your own color theme.

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
