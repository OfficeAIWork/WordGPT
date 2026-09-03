<div align="center">

# OfficeAI.Chat

### Formerly WordGPT — All-in-One AI Content Creation & Document Processing Plugin, deeply adapted for all office scenarios, covering content creation, document processing, smart formatting, and multilingual translation.

English | [简体中文](./README.md)

[![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Xinchuang%20%7C%20Linux-blue?style=flat-square)](https://github.com/OfficeAIWork/WordGPT)
[![Office](https://img.shields.io/badge/Compatible-Office%20%7C%20WPS-orange?style=flat-square)](https://github.com/OfficeAIWork/WordGPT)
[![License](https://img.shields.io/badge/License-Proprietary-red?style=flat-square)](https://github.com/OfficeAIWork/WordGPT)

[Download](#-download) · [Features](#-features) · [Installation](#-installation) · [Contact Us](#-contact-us)

---

</div>

## Introduction

OfficeAI.Chat (formerly WordGPT) is an AI-powered plugin deeply integrated into office workflows. It covers core office needs including content creation, document processing, smart formatting, and multilingual translation, significantly boosting document productivity.

| Core Capabilities | Description |
| :--- | :--- |
| **Intelligent Content Generation** | Connect to private knowledge bases or online search to generate papers, resumes, blog posts, press releases, product copy, business emails, screenplays, work summaries, and more — with one click. Simultaneously produce mind maps, illustrations, data charts, and PPT slides |
| **Comprehensive Text Refinement** | Full-text proofreading, sentence polishing, content condensation, expansion, and abridgment — intelligently detects grammar issues and logical gaps, outputting an optimized revision |
| **Multilingual Translation** | Supports instant translation across dozens of languages for foreign-language writing, document translation, and cross-border office needs |
| **Smart Auto-Formatting** | One-click document formatting and style unification — eliminates tedious manual layout work |

> **System Requirements:** Windows (Win10+ recommended) · macOS · Domestic Xinchuang OS · Linux · Office 2012+ · Latest version of WPS

---

## Installation

### Download

| Source | Link |
| :--- | :--- |
| Official Website | [https://officeai.chat](https://officeai.chat) |

#### Installer Downloads by Platform

| Installer | Platform | Size | Download |
| :--- | :--- | :--- | :--- |
| OfficeAI.Chat-Windows.rar | Windows 10/11 (x64) | ~74 MB | [Download](https://github.com/OfficeAIWork/WordGPT/releases/download/v1.0.0/OfficeAI.Chat-Windows.rar) |
| OfficeAI.Chat-macOS.rar | macOS 10.15+ (Intel/Apple Silicon) | ~182 MB | [Download](https://github.com/OfficeAIWork/WordGPT/releases/download/v1.0.0/OfficeAI.Chat-macOS.rar) |
| OfficeAI.Chat-Linux.rar | Linux (Ubuntu/CentOS, etc.) | ~113 MB | [Download](https://github.com/OfficeAIWork/WordGPT/releases/download/v1.0.0/OfficeAI.Chat-Linux.rar) |
| OfficeAI.Chat-DomesticOS.rar | Domestic OS (UOS/Kylin) | ~161 MB | [Download](https://github.com/OfficeAIWork/WordGPT/releases/download/v1.0.0/OfficeAI.Chat-DomesticOS.rar) |

> [!IMPORTANT]
> Please close Office, WPS, and other related software before installation. On computers without administrator privileges, it is recommended to temporarily disable antivirus software during installation and re-enable it afterward.

### Installation Steps

**Step 1: Install the Plugin**

Double-click or run `setup.exe` as administrator, and follow the wizard by clicking "Next" to complete the installation.

![Installation Screen](./Images/01-setup.png)

![Installation Steps](./Images/02-installation-steps.png)

**Step 2: Confirm Installation**

Open Office (Word / Excel / PowerPoint) and click to confirm the installation when prompted.

![](./Images/03-office-confirm.png)

### Software Updates

Click the "Update Software" button to automatically check for and install the latest version. If a new version is available, wait for the download to complete and follow the wizard to finish the update. Reopen Word or WPS when done.

| Update Menu | Update Screen |
| :---: | :---: |
| ![Update Menu](./Images/08-update-menu.png) | ![Update Screen](./Images/09-update-screen.png) |

### Login & Model Configuration

#### Option 1: User Login (Limited-Time Free)

![Login Screen](./Images/04-login.png)

- Check "OfficeAI.Chat Model Service", enter your username and password, then click "OK"
- New users can click "Register" to create an account
- Forgotten passwords can be reset via phone number

#### Option 2: Custom Model API (Free Forever)

![](./Images/05-custom-api.png)

Check "Custom Model Service" and configure as follows:

| Setting | Description |
| :--- | :--- |
| **Model ID** | Recommended: DeepSeek DeepSeek-V4-Flash, Zhipu GLM5.1, Alibaba Qwen3.7-Max, OpenAI GPT-5.5 (for users outside China) |
| **API Key** | Copy the API Key from your LLM management console and paste it here |
| **API Url** | Copy the API Url from your LLM management console and paste it here (ensure it ends with the `/v1` version path) |

> [!TIP]
> The software comes pre-configured with standard API endpoints for popular platforms such as DeepSeek, Zhipu, and Alibaba Bailian — selecting one will auto-fill the address. For intranet use, you can run Ollama for fully offline operation with the address format: `http://[server-IP]:11434/v1`

---

## Features

### Feature Menu

![](./Images/10-feature-menu.png)

### OfficeAI Agent

![](./Images/07-officeai-agent.png)

The OfficeAI Agent is an intelligent office assistant capable of autonomous task decomposition and execution. Simply provide a natural-language goal, and the agent will automatically plan the workflow and carry out the task — replacing tedious, repetitive manual operations.

#### AI Operation Modes

| Mode | Description |
| :--- | :--- |
| **Auto** | Intelligently determines the operation mode |
| **In-Place Replace** | Generated content replaces the selected text in-place within the document |
| **Annotation** | Generated content is inserted as a right-side annotation in the document |
| **Chat Only** | Generated content appears only in the current chat window |

#### Knowledge Base Reference

Check the box or type `@` in the chat input box to reference your personal knowledge base, enabling content generation based on knowledge base documents.

#### Document Editing & Processing

| Feature | Description |
| :--- | :--- |
| Polish & Rewrite | Optimize text to make sentences smoother, more professional, and idiomatic |
| Expand & Enrich | Extend content with additional details and descriptions |
| Summarize | Extract core insights from long texts for quick comprehension |
| Translate | Multilingual translation with automatic source language detection |
| Find & Replace | Batch-replace specified text throughout the document |
| Punctuation Conversion | Bulk conversion between Chinese and English punctuation marks |
| Remove Blank Characters | Delete redundant spaces and blank characters from the document |

#### Formatting & Beautification

| Feature | Description |
| :--- | :--- |
| One-Click Formatting | Auto-format documents according to official, academic, or custom styles, or describe formatting requirements in natural language |
| Set Text Format | Modify font, size, color, bold, italic, alignment, and more |
| Batch Resize Images | Uniformly adjust the dimensions of all images in the document |
| Background Color | Set the document page background color |
| Remove Header Line | Remove the border line at the bottom of the header with one click |
| Grammar Check | Toggle spelling and grammar checking on/off |

#### Intelligent Generation

| Feature | Description |
| :--- | :--- |
| Mind Map | Generate a mind map from a topic to organize knowledge frameworks |
| Knowledge Graph | Visualize relationships between concepts |
| Data Charts | Analyze data and generate visual charts |
| AI Image Generation | Generate images from text descriptions |
| Map Markers | Annotate locations and display them visually on a map |
| Create Tables | Generate structured tables such as comparison and data summary tables |

> [!TIP]
> Here are some example prompts for the Agent:
>
> - "Format this article using the official document style with one click"
> - "Polish and rewrite the selected paragraphs to sound more professional"
> - "Summarize the key points of this article"
> - "Generate a mind map based on this topic"
> - "Convert all English punctuation in the text to Chinese punctuation"
> - "Generate an illustration about artificial intelligence"

---

### Generate Outline

Select a keyword or key phrase, click "Generate Outline", and choose from Precision, Balanced, or Creative modes to suit your needs.

![Generate Outline](./Images/14-generate-outline.gif)

### Generate Article

Select an outline or phrase, click "Generate Article". Also supports Precision, Balanced, and Creative modes.

![Generate Article](./Images/15-generate-article.gif)

### Polish & Refine

Select the paragraphs you want to polish, click "Polish & Refine". The optimized result is presented as annotations for easy comparison with the original text. Once satisfied, you can copy and replace it directly in the document.

![Polish & Refine](./Images/16-polish-refine.gif)

### Summarize

Select paragraphs and click "Summarize". The result is displayed as annotations for easy comparison with the original text.

![Summarize](./Images/17-summarize.gif)

### Rewrite (Expand / Condense)

- **Expand**: Select a phrase and click "Expand" to enrich the content. Repeated execution will continue to expand the text.
- **Condense**: Select a paragraph and click "Condense" to streamline the text without changing the original meaning.

![Rewrite](./Images/18-rewrite.png)

### Chinese-English Translation

Select text to translate between Chinese and English. The source language is detected automatically.

![Translation](./Images/19-translation.gif)

### Mind Map

> [!WARNING]
> Only supported in Word; WPS is not currently supported.

- **Summary Mode**: Select article paragraphs → Click "Mind Map" → "Balanced Mode" to auto-generate a paragraph structure map.
- **Predictive Mode**: Select a keyword → Click "Mind Map" → "Creative Mode" to auto-generate a brainstorming mind map.

![Mind Map](./Images/22-mind-map.png)

### Smart Illustrations

Select a keyword or phrase and click "Smart Illustrations" to auto-generate a relevant image for your article.

![Smart Illustrations](./Images/23-smart-illustration.png)

### Auto-Formatting

Three built-in formatting styles — "Custom", "Academic Paper", and "Official Document" — with support for custom settings. Once your style is configured, click "Auto-Format" to apply formatting to the entire document.

| Formatting Entry | Formatting Settings |
| :---: | :---: |
| ![Auto-Formatting](./Images/25-auto-formatting.png) | ![Formatting Settings](./Images/26-formatting-settings.png) |

Tutorial Video: [Bilibili Tutorial](https://www.bilibili.com/video/BV1Vm42157Qj/)

### Image to Text

Two recognition modes are supported:

- **Screenshot OCR**: Capture a specified area of the screen for OCR recognition
- **Image File OCR**: Select a JPG, PNG, or other supported image file for recognition

### PDF Tools

![PDF Tools](./Images/27-pdf-tools.png)

- **Import PDF**: Select a PDF file and convert it to a Word document with formatting preserved
- **Export PDF**: Export the current document as a PDF file

> [!TIP]
> Click the "PDF Toolkit" button to open the universal PDF Toolkit, which includes a variety of PDF-related file conversion and editing features.

![PDF Toolkit](./Images/40-pdf-toolkit.png)

### Generate PPT

Click "Generate PPT", enter the document summary in the topic field, and click "Generate Outline" to quickly create a PPT outline. Fine-tune as needed, and the system will auto-generate a fully formatted PPT presentation.

![Generate PPT](./Images/29-generate-ppt.png)

Tutorial Video: [Bilibili Tutorial](https://www.bilibili.com/video/BV1mH4y1F7K9/)

---

## Personal Knowledge Base

Click the "Personal Knowledge Base" button to open the KHub knowledge base page in a popup window, where you can browse and manage knowledge base content directly. Knowledge base content must be created and maintained on the KHub knowledge base site.

### 1) Log In to the Knowledge Base

Log in with your OfficeAI.Chat account — a knowledge base is automatically created for each user. Custom model or enterprise users can configure their knowledge base account in the "Knowledge Base" tab under Settings. After logging in, you'll enter the KHub knowledge base management page, with the knowledge base list on the left and the content area on the right.

![Knowledge Base Login](./Images/34-kb-login.png)

### 2) Create a Knowledge Base

1. After logging in, click the "New Knowledge Base" button to open the creation dialog
2. Fill in the knowledge base name and description, then complete the creation

![Create Knowledge Base](./Images/35-kb-create.png)

### 3) Import Documents

Select a knowledge base on the left, then click the "Import Document" button. Three import methods are supported:

| Import Method | Description |
| :--- | :--- |
| Upload File | Supports PDF / Word(docx) / TXT / Markdown formats, up to 15MB per file (subject to site configuration) |
| Paste Text | Directly paste text content to import as a single document |
| Paste URL | Enter a web page URL to automatically crawl and import the page content |

![Import Documents](./Images/36-kb-import.png)

### 4) Wait for Document Learning

After import, the system automatically performs vectorized learning (chunking → vectorization & indexing → summary & tag generation). The status transitions from **Learning** → **Learned**.

- Only documents with **Learned** status will be retrieved and referenced by AI
- If the status shows **Learning Failed**, you can delete the document and re-import it

### 5) View Document Details

In the document list, click the **Details (i)** icon on the right side of a document row to open the document details dialog, where you can view and maintain the document metadata generated during learning:

![Document Details](./Images/37-kb-details.png)

- **Summary** — A document summary auto-generated during learning; click the edit icon to manually modify and save
- **Tags** — Topic tags auto-generated during learning; supports adding, deleting, and editing/saving
- **Relationship Graph** — Displays the document's relationships with other content in the knowledge base as a knowledge graph, helping you map out document connections

![Knowledge Base Relationship Graph](./Images/38-kb-relationship-graph.png)

### 6) Reference the Knowledge Base in Conversations

Once document learning is complete, return to the OfficeAI Agent panel in WPS or Office. Check the box or use `@` to reference the knowledge base before asking a question — the AI will answer based on the knowledge base content and include reference sources.

> [!TIP]
> Click the citation source in the AI's response to open the original document in a popup and navigate to the corresponding paragraph. PDF / Word / TXT / Markdown documents all support online preview without conversion, and the site also provides knowledge graph and other features to help you navigate document relationships.

---

## Uninstallation

Go to Windows Control Panel → Programs and Features, find "OfficeAI.Chat Office Agent Suite", right-click and select "Uninstall".

![Uninstall](./Images/32-uninstall.png)

---

## Contact Us

Add us on WeChat, WeChat ID: **WordGPT_KF**

<div align="center">

![WeChat Support](./Images/33-wechat-support.png)

---

*If this project has been helpful to you, please give us a Star!*

</div>
