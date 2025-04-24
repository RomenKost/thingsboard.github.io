---
layout: docwithnav-trendz
title: AI Widget Summary
description: Step-by-step guide to set up AI Widget Summary.
---

* TOC 
{:toc}

AI Widget Summary is a flexible feature that allows integration of AI capabilities into any ThingsBoard Widgets,
including full customization of AI prompts and the interaction flow.

Several ways are available for integrating AI summaries with different types of widgets.

## ThingsBoard Widgets

It's possible to add an AI Summary to all widgets,
<a href="#" onclick="
fetch('http://localhost:8888/trendz/module/trendz-ai-summary.js')
.then(res => res.blob())
.then(blob => {
const url = window.URL.createObjectURL(blob);
const a = document.createElement('a');
a.style.display = 'none';
a.href = url;
a.download = 'trendz-ai-summary.js';
document.body.appendChild(a);
a.click();
window.URL.revokeObjectURL(url);
});
return false;
">Download Native Trendz Library</a>

## Trendz Widgets

## Use Cases

## Next Steps

{% assign currentGuide = "AiAssistant" %}{% include templates/trndz-guides-banner.md %}
