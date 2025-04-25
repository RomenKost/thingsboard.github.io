---
layout: docwithnav-trendz
title: AI Widget Summary
description: Step-by-step guide to set up AI Widget Summary.

trendz-ai-summary-trendz-widget-example:
  0:
    image: /images/trendz/ai/widget-ai-summary/trendz-widget-example-1.png
    title: 1. Press the "AI summary" button in the upper corner of the widget.
  1:
    image: /images/trendz/ai/widget-ai-summary/trendz-widget-example-2.png
    title: 2. See view the AI summary at the top of the Trendz widget.

trendz-ai-summary-trendz-enable-button:
  0:
    image: /images/trendz/ai/widget-ai-summary/trendz-setting-common.png
    title: Open the desired view. Go to "View Settings".
  1:
    image: /images/trendz/ai/widget-ai-summary/trendz-enable-button-1.png
    title: Go to the "View Mode Fields" section. Choose the preferred mode to show or hide the AI Summary button.
  2:
    image: /images/trendz/ai/widget-ai-summary/trendz-enable-button-2.png
    title: Save the changes.

trendz-ai-summary-trendz-set-up-prompt:
  0:
    image: /images/trendz/ai/widget-ai-summary/trendz-setting-common.png
    title: Open the desired view. Go to "View Settings".
  1:
    image: /images/trendz/ai/widget-ai-summary/trendz-set-up-prompt-1.png
    title: Go to the "AI Assistant" section. Choose the preferred prompt from the dropdown menu. 
  2:
    image: /images/trendz/ai/widget-ai-summary/trendz-set-up-prompt-2.png
    title: Save the changes.
---

* TOC 
{:toc}

AI Widget Summary is a flexible feature that allows integration of AI capabilities into any ThingsBoard Widgets,
including full customization of AI prompts and the interaction flow.

Several ways are available for integrating AI summaries with different types of widgets.

## ThingsBoard Widgets

## Trendz Widgets

AI summary is already integrated into the Trendz Widgets. To retrieve the AI summary for a Trendz widget, 
press the **AI summary** button in the upper corner of the screen. After that, you will be able to view the AI summary 
at the top of the Trendz widget.

{% include images-gallery.html imageCollection="trendz-ai-summary-trendz-widget-example" %}

### Enable AI Summary Button

By default, the AI summary button is disabled for views created before Trendz 1.13.1 and for views created during the 
period when the **AI Assistant Use AI Model** flag was disabled for self-hosted users 
(Find out more about how to set up the AI Assistant module for self-hosted users [here](/docs/trendz/custom-ai-model-configuration/)).

To enable/disable the AI summary button, follow these steps:

1. Open the desired view.
2. Go to **View Settings**.
3. Go to the **View Mode Fields** section.
4. Choose the preferred mode to show or hide the AI Summary button.
5. Save the changes.

Note: button in Trendz application will always be shown (even with checkbox )

{% include images-gallery.html imageCollection="trendz-ai-summary-trendz-enable-button" %}

### Set Up AI Summary Prompt

Additionally, it is possible to choose a prompt that can be used to generate the AI summary.

To set up the AI summary prompt:

1. Open the desired view.
2. Go to **View Settings**.
3. Go to the **AI Assistant** section.
4. Choose the preferred prompt from the dropdown menu.
5. Save the changes.

{% include images-gallery.html imageCollection="trendz-ai-summary-trendz-set-up-prompt" %}

Find out more about creating your own prompts that perfectly fit your task [here](/docs/trendz/ai-assistance-prompts/).

## Use Cases

## Next Steps

{% assign currentGuide = "AiAssistant" %}{% include templates/trndz-guides-banner.md %}
