---
layout: docwithnav-trendz
title: Interacting with Trendz AI Assistance
description: Step-by-step guide to interact with Trendz AI Assistance.

trendz-assistance-overview:
  0:
    image: /images/trendz/ai/overview-start-new-chat.png
    title: 1.Press “New Chat”
  1:
    image: /images/trendz/ai/overview-save-topology-entities.png
    title: 2.Here you will see the popup with business entity selection - here you can define the entities that will be considered by AI for the current conversation. Select business entities that will be used for this chat (It’s possible to always modify them). Click “Save” to apply selections.
  2:
    image: /images/trendz/ai/overview-send-new-message.png
    title: 3.Write and send the question.
  3:
    image: /images/trendz/ai/overview-final-view.png
    title: 4.See the result.

trendz-assistance-capabilities-visualization:
  0:
    image: /images/trendz/ai/capabilities/1-simple-table.png
    title: Table (without dynamic columns)
  1:
    image: /images/trendz/ai/capabilities/2-line.png
    title: Line
  2:
    image: /images/trendz/ai/capabilities/3-pie.png
    title: Pie
  3:
    image: /images/trendz/ai/capabilities/4-bar.png
    title: Bar
  4:
    image: /images/trendz/ai/capabilities/5-heatmap.png
    title: Heatmap
  5:
    image: /images/trendz/ai/capabilities/6-heatmap-calendar.png
    title: Heatmap Calendar
  6:
    image: /images/trendz/ai/capabilities/7-card.png
    title: Card

trendz-assistance-capabilities-date-picker:
  0:
    image: /images/trendz/ai/capabilities/8-date-picker.png
    title: Apply a date picker

trendz-assistance-capabilities-date-fields:
  0:
    image: /images/trendz/ai/capabilities/9-date-fields.png
    title: Use date fields

trendz-assistance-capabilities-view-name:
  0:
    image: /images/trendz/ai/capabilities/10-view-name.png
    title: Assign a name for each column and visualization

trendz-assistance-capabilities-filter:
  0:
    image: /images/trendz/ai/capabilities/11-filter.png
    title: Add filters

trendz-assistance-capabilities-foreing-language:
  0:
    image: /images/trendz/ai/capabilities/12-foreign-language.png
    title: Answer questions in different languages

trendz-assistance-chat-page:
  0:
    image: /images/trendz/ai/chat-page-1.png
    title: The chat history will be shown on the left side of the screen (1). The visualization of the previously asked in this chat question will be located on the right side of the screen (2).
  1:
    image: /images/trendz/ai/chat-page-2.png
    title: If it is necessary it is possible to change the generated time range.
  2:
    image: /images/trendz/ai/chat-page-3.png
    title: If it is necessary it is possible to change or remove generated filters. 

trendz-assistance-send-new-msg:
  0:
    image: /images/trendz/ai/send-message-1.png
    title: Press the “New message” button
  1:
    image: /images/trendz/ai/send-message-2.png
    title: Type and send the message by pressing the “Send” icon on the left side of the input field.

trendz-assistance-edit-msg:
  0:
    image: /images/trendz/ai/edit-message-1.png
    title: Press the “Edit last message” button
  1:
    image: /images/trendz/ai/edit-message-2.png
    title: Modify this message, and send it by pressing the “Submit” icon on the left side of the input field.

trendz-assistance-check-msg:
  0:
    image: /images/trendz/ai/check-message-1.png
    title: You can check on of the previous messages by pressing on it. After the previously generated view/answer will appear on the right side of the screen.

trendz-assistance-edit-selected-msg:
  0:
    image: /images/trendz/ai/edit-selected-msg-1.png
    title: Press on the pencil icon on the left of the message to edit
  1:
    image: /images/trendz/ai/edit-selected-msg-2.png
    title: After that, it’s necessary to modify the selected message by typing inside it. You can confirm or cancel the change by pressing the buttons on the right side of the message. 

trendz-assistance-rerun-msg:
  0:
    image: /images/trendz/ai/rerun-msg.png
    title: Press on the refresh button on the right upper side of the selected message.

trendz-assistance-save-config:
  0:
    image: /images/trendz/ai/chat-save-config-1.png
    title: Press the “Save config” button
  1:
    image: /images/trendz/ai/chat-save-config-2.png
    title: Choose the view collection where you want to save the generated view config

trendz-assistance-topology:
  0:
    image: /images/trendz/ai/chat-topology-1.png
    title: You can access the Topology Entities tab by starting a new chat or by clicking on the selected business entities next to the Topology Entities label in the upper left corner of the screen.
  1:
    image: /images/trendz/ai/chat-topology-2.png
    title: Specify which business entities or business entity fields AI Assistance needs to know.
  2:
    image: /images/trendz/ai/chat-topology-3.png
    title: It is also possible to specify the description for a business entity or its fields.
---

* TOC
{:toc}

AI assistance is a powerful feature that enables the creation of various visualizations. It allows you to generate
different visualizations according to the request given in the free-speech form and specify the necessary details
like date range, time grouping, aggregation, filtering, etc.

To interact with the AI Assistant, follow these simple steps:
1. To access AI Assistance, click on the icon![image](/images/trendz/ai/overview-ai-assistance-icon.png) labeled *Assistant*
   located on the left side of the workspace. Press **New Chat**.
2. Here you will see the popup with business entity selection - here you can define the entities that will be considered
   by AI for the current conversation. Select **business entities** that will be used for this chat (It’s possible to always modify them).
   Click **Save** to apply selections.
3. Write and send the question.
4. See the result.

{% include images-gallery.html imageCollection="trendz-assistance-overview" %}

⚠️ *Note*: It’s necessary to set up own model to use the AI Assistance in self-hosted installation.

## Capabilities
AI Assistance offers powerful features to help you make informed decisions and optimize your workflow. Explore its capabilities below:

**1.Generate different types of visualizations**

The available visualizations are:

* Table
* Dynamic table
* Line chart
* Pie chart
* Bar chart (Vertical,  Horizontal, Stacked)
* Scatter Plot
* Heatmap
* Heatmap calendar
* Card (without compared value)
* Card with line
  {% include images-gallery.html imageCollection="trendz-assistance-capabilities-visualization" %}

**2. Apply a date picker**

Apply a date picker (by default for this week):
{% include images-gallery.html imageCollection="trendz-assistance-capabilities-date-picker" %}

**3. Use date fields**
{% include images-gallery.html imageCollection="trendz-assistance-capabilities-date-fields" %}

**4. Assign a name for each column and visualization**
{% include images-gallery.html imageCollection="trendz-assistance-capabilities-view-name" %}

**5. Add filters**
{% include images-gallery.html imageCollection="trendz-assistance-capabilities-filter" %}

**6. Answer questions in different languages**
{% include images-gallery.html imageCollection="trendz-assistance-capabilities-foreign-language" %}

**7. Handle conversation**

The current version of the AI Assistant can remember context and generate answers based on all user messages, specifications, and responses.
{% include images-gallery.html imageCollection="trendz-assistance-capabilities-conversation" %}

## Chat Page

After sending a message in a new chat or selecting a previously initialized chat, you will be redirected to the **Chat Page**. The chat history appears on the left side of the screen (1), and the visualization of the selected question in this chat appears on the right side of the screen (2).

If necessary, you can adjust the generated time range or modify/remove applied filters.  
{% include images-gallery.html imageCollection="trendz-assistance-chat-page" %}

On this page, you can:

* **Type and send a new message**:
  * You can type your message, and send it by clicking the *Send* icon on the right side of the input field.  
    {% include images-gallery.html imageCollection="trendz-assistance-send-new-msg" %}

* **Edit the last message**:
  * You can modify the message, and submit it by clicking the *Submit* icon on the right side of the input field.
  * This can be useful if the AI Assistant returned incorrect results, and you want to provide more details.  
    {% include images-gallery.html imageCollection="trendz-assistance-edit-msg" %}

* **Check the selected message**:
  * You can click on any message to view its previously generated answer on the right side of the screen.  
    {% include images-gallery.html imageCollection="trendz-assistance-check-msg" %}

* **Regenerate the answer**:
  * You can click the *Refresh* button at the top right of the message block to regenerate the assistant's answer.
  * This can be helpful if the response was incorrect.  
    {% include images-gallery.html imageCollection="trendz-assistance-rerun-answer" %}

* **Check Assistant's Interpretation**:
  * You can click the *Assistant's Interpretation* label at the top left of the message.
  * This can help verify whether the AI Assistant correctly understood your request.  
    {% include images-gallery.html imageCollection="trendz-assistance-check-interpretation" %}

* **Save Config**:
  * You can use this button to save the generated view to a selected view collection.  
    {% include images-gallery.html imageCollection="trendz-assistance-save-config" %}

* **Review Generated View**:
  * You can click the *See Details* button at the top right of the screen to review the generated view.
  * This helps verify whether the AI Assistant correctly selected Business Entities, Business Entity Fields, and Aggregations.  
    {% include images-gallery.html imageCollection="trendz-assistance-check-view-config" %}
* * You can also access additional settings by clicking the *Settings* button in the top right corner of the screen.  
    {% include images-gallery.html imageCollection="trendz-assistance-check-view-settings" %}
* * To exit this tab, you can click the *Back* button.  
    {% include images-gallery.html imageCollection="trendz-assistance-exit-view-config" %}

* **Generate Chat Summary**:
  * You can click the *Get Chat Summary* button at the top right of the screen.
  * This feature helps analyze and identify anomalies or correlations in the generated view configuration.  
    {% include images-gallery.html imageCollection="trendz-assistance-generate-chat-summary" %}
* * The chat summary will appear at the top of the screen.  
    {% include images-gallery.html imageCollection="trendz-assistance-chat-summary-example" %}

## Chat Topology Entities
To answer the query, AI Assistance should analyze the provided topology. It could be challenging to analyze the topology with hundreds of business entities and/or business entity fields, 
which could damage the accuracy of the AI Assistance. To increase the accuracy of the AI Assistance you can use the **Topology Entities window**.

You can access the Topology Entities tab by starting a new chat or by clicking on the selected business entities next to the Topology Entities label in the upper left corner of the screen.

To increase the accuracy of AI Assistance, you can specify which business entities or business entity fields it needs to know.

It is also possible to specify the description for a business entity or its fields. It could be useful when fields have unrepresentative names.

{% include images-gallery.html imageCollection="trendz-assistance-topology" %}

All selected business entities and business entity fields affect only the chat in which you selected them. All added/changed descriptions affect all chats at the same time.

## Best practices

* **Use the Topology Entities tab:** To increase the accuracy of AI Assistance, especially when dealing with complex topologies, specify which business entities 
  or fields are relevant.
* **Provide descriptions for business entity fields:** If field names are unclear, adding descriptions can improve AI Assistance accuracy.
* **Edit messages to add specifications:** Since the current AI Assistant version does not remember previous messages, editing the last message is the best way 
to provide additional details or correct errors.
* **Use your own model:** For self-hosted applications or to avoid cloud token limits, configure and use your own large language model.
* **Select the right model:** When using your own model, choose the one that best suits your needs and budget, considering factors like performance and 
cost efficiency.
* **Provide clear instructions to the AI Assistant:** When creating a new message or editing an old one to get the correct results from the AI Assistant provide as many details as possible.

## Limitations

### Token limitation (applicable only for cloud)

The number of messages you can send each month depends on your subscription type. When you`re using the Trendz AI model on the cloud, there are no additional charges.

To not be related to these limits, it’s possible to use your own model. To find out how to not be related to these limits, refer to the [Custom AI Model Configuration page](/docs/trendz/custom-ai-model-configuration/) for more details.

### Rate limits

The count of sent messages per minute should be less than:
* 6 for each user
* 20 for each customer
* 50 for each tenant

### Missing default system model (applicable only for self-hosted)

It’s impossible to use the default large language model for self-hosted clients. To find out how to enable the AI Assistant feature for self-hosted installation, please refer to the [Custom AI Model Configuration page](/docs/trendz/custom-ai-model-configuration/).

### Feature limitations

AI Assistance cannot:
  * Create anomaly or prediction models, create calculation fields
  * Create cards with the compared value 
  * Specify view/view field settings

These features will be added in future releases.

⚠️ This is a beta function, that could return incorrect results.

## Next Steps

{% assign currentGuide = "AiAssistant" %}{% include templates/trndz-guides-banner.md %}