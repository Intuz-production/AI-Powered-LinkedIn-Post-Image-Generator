# Intuz — Your automation partner, one workflow at a time.

<p align="center">
  <picture>
    <img alt="Banner Image" src="https://github.com/user-attachments/assets/210f97fc-0fce-404a-b647-7dfe1302cd37" />
  </picture>
</p>

# Automate LinkedIn post creation with image using Google Gemini & DALL-E

Intuz helps organizations orchestrate AI, automation, and enterprise systems through scalable workflows. Our repository showcases proven implementations across healthcare, operations, customer support, document processing, sales, and back-office functions, enabling teams to accelerate automation initiatives without starting from scratch.

[Website](https://intuz.com) · [N8N Creator](https://n8n.io/creators/intuz/) · [Workflow Automation](https://www.intuz.com/workflow-automation-services/) · [For Custom Workflow Automation](https://www.intuz.com/get-started/)

---

This n8n template from [Intuz](https://www.intuz.com/) delivers a complete AI-powered solution for automated LinkedIn posts, including unique content, custom images, and optimized hashtags.

Use cases are many: Generate and schedule tailored LinkedIn content for different use cases. By feeding the AI specific prompts, you can create specific posts depending on the topics and visuals to maintain consistency and an online presence.

## How it works

Maintaining a consistent and engaging presence on LinkedIn can be time-consuming, requiring constant ideation, content creation, and manual posting. This workflow takes that burden off your shoulders, delivering a fully automated solution for generating and publishing high-quality LinkedIn content.

* **Scheduled Content Engine:** Each day (or on your chosen schedule), the workflow kicks into gear, ensuring a fresh stream of content.
* **Smart Topic & Content Generation:** Using the power of Google Gemini, it intelligently crafts unique content topics and then expands them into full, engaging posts, ensuring your message is always fresh and relevant.
* **Dynamic Image Creation:** To make your posts stand out, the workflow leverages an AI image generator (like DALL-E) to produce a custom, eye-catching visual that perfectly complements your generated text.
* **SEO-Optimized Hashtag Generation:** Google Gemini then analyzes your newly created post and automatically generates a set of relevant, trending, and SEO-friendly hashtags, significantly boosting your content's reach and discoverability.
* **Seamless LinkedIn Publishing:** Finally, all these elements—your compelling text, unique image, and powerful hashtags—are merged and automatically published to your LinkedIn profile, establishing you as a thought leader with minimal effort.

### How to Use: Quick Start Guide

This guide will get your AI LinkedIn Content Automation workflow up and running in n8n.

**Import Workflow Template:**

* Download the template's JSON file and import it into your n8n instance via **"File" > "Import from JSON."**

**Configure Credentials:**

* **Google Gemini:** Set up and apply your API key credentials to all **"Google Gemini Chat Model"** nodes.
* **AI Image Generation (e.g., OpenAI):** Create and apply API key credentials for your chosen image generation service to the **"Generate an Image"** node.
* **LinkedIn:** Set up and apply OAuth credentials to the **"Create a post"** node for your LinkedIn account.

**Customize Schedule & AI Prompts:**

* **Schedule Trigger:** Double-click **"Schedule Trigger 1"** to set how often your workflow runs, such as daily or weekly.
* **AI Prompts:** Review and edit the prompts within the **"Content Topic Generator," "Content Creator,"** and **"Hashtag Generator / SEO"** nodes to guide the AI for your desired content style and topics.

**Test & Activate:**

* **Test Run:** Click **"Execute Workflow"** to perform a test run and verify all steps are working as expected.
* **Activate:** Once satisfied, toggle the workflow **"Active"** switch to enable automated posting on your defined schedule.

[Image Example](https://n8niostorageaccount.blob.core.windows.net/n8nio-strapi-blobs-prod/assets/image_example_60c02b019f.PNG)

[LinkedIn Post Example](https://n8niostorageaccount.blob.core.windows.net/n8nio-strapi-blobs-prod/assets/Linked_In_Post_Example_232589f318.PNG)

#### Requirements

To use this workflow template, you will need:

* **n8n Instance:** A running n8n instance (cloud or self-hosted) to import and execute the workflow.
* **Google Gemini Account:** For content topic generation, content creation, and hashtag generation (requires Google Gemini API Key) from Google AI Studios.
* **AI Image Generation Service Account:** For creating images, such as an OpenAI DALL-E API Key or similar service that the **"Generate an Image"** node uses.
* **LinkedIn Account:** For publishing the generated posts (requires LinkedIn OAuth Credentials for n8n connection).

## Connect with us

* **Website:** https://www.intuz.com/n8n-workflow-automation-templates
* **Email:** [getstarted@intuz.com](mailto:getstarted@intuz.com)
* **LinkedIn:** https://www.linkedin.com/company/intuz
* **Get Started:** https://n8n.partnerlinks.io/intuz

## For Custom Workflow Automation

Click here - [Get Started](https://www.intuz.com/get-started/)
