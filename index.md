---
title: Welcome
layout: home
nav_order: 1
---

{% seo title=false %}

{% if page.title == "Welcome" %}
<title>Scale Siri Shortcut projects and maintain them long-term | Cherri</title>
{% endif %}

{% if page.title != "Welcome" %}
<title>{{ page.title }} | {{ site.title }}</title>
{% endif %}

<div style="text-align: center">
  <img src="https://github.com/electrikmilk/cherrilang.org/assets/4368524/70975782-10d5-4ee0-a69f-00dc74443ffc" width="400px"/>
</div>

# Scale your Shortcut projects and maintain them long-term.

**Cherri** (pronounced cherry) is a <a href="https://apps.apple.com/us/app/shortcuts/id1462947752" ref="noreferrer noopener" target="_blank">Siri Shortcuts</a> programming language, that compiles directly to a valid Shortcut you can then run on your Apple devices.

<br/>

<div class="code-example" markdown="1">
```ruby
/* Hello, Cherri! */

#define glyph smileyFace
#define color yellow

@message = "Hello!"
alert("Message: {message}", "Alert")
```
<span class="fs-5">
[Try Me!](https://playground.cherrilang.org){: .btn .btn-red }
</span>
</div>
