---
layout: post
title:  "Variables"
date:   2014-03-01 19:53:19
categories: 0.0.1
tags: variables list
---

Princess includes default values for all styles that can be manipulated from two main files: `source/helpers/_var.scss` or `source/helpers/_colors.scss`.

This page deals with `source/helpers/_var.scss`, which covers everything except for colors. For information on changing colors, see [Colors]({% post_url 2014-03-01-colors %}).

## Defaults

### Font families

For information on using @font-face, see [@font-face]({% post_url 2014-03-01-font-face %}).

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