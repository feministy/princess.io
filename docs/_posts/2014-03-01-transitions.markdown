---
layout: post
title:  "Transitions"
date:   2014-03-01 19:55:19
categories: 0.0.1
tags: modules mixins
---


This module applies a set of subtle transitions to the elements on your page.

## Usage

To use all of the default transitions, include the module in your file:

```
@import "modules/transitions";
```

## Elements

* `a`: transitions all elements to/from the hover state. Uses `$transition` to determine time.

## Mixins

To use the mixins:

```
@import "helpers/mixins/transitions";
```

### Inclued mixins

* [`transitionAll`](#transitionAll)

<a name="transitionAll"></a>`transitionAll(time)`

Transitions all elements for a set period of time.

<dl>
  <dt>Default</dt>
  <dd>0.3s</dd>
  <dt>Arguments</dt>
  <dd>Time; in s or ms (ex: 1s, 500ms)</dd>
  <dt>Usage (without args)</dt>
  <dd><code>@include transitionAll;</code></dd>
  <dt>Usage (with args)</dt>
  <dd><code>@include transitionAll(800ms);</code></dd>
</dl>
