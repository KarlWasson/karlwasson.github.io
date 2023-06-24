---

layout: default
title: 5. Keep it Short
parent: Plain Language for Technical Writing
nav_order: 5
---
# Keep it Short

{: .no_toc }

## Table of contents

{: .no_toc .text-delta }

1. TOC
{:toc}

---
Reducing duplication, redundancy, and unnecessary language is essential to creating concise, reader-centric content. The following guidelines will help you achieve this goal:

1. **Link to existing information:** Whenever possible, provide links to existing relevant information. This makes it easier for readers to access additional details and simplifies the maintenance of your content.

2. **Use short paragraphs:** Limit each paragraph to focus on a single subject or step. Breaking down information into smaller, bite-sized paragraphs makes it easier for readers to digest the content. Aim for at most seven lines per paragraph.

3. **Utilize short sentences:** Each sentence should address only one subject. Avoid complexity and confusion by keeping your sentences concise. Aim to use 20 words or fewer per sentence.

---

## Activity 5: Apply the guidelines and rewrite for a non-technical audience:

In JavaScript, you can make an HTTP request using either the XMLHttpRequest object or the fetch API. With XMLHttpRequest, you create a new instance, specify the method (e.g., GET, POST), URL, and set up an onreadystatechange event handler to handle the response. Once the request is complete (readyState 4) and the status is 200 (OK), you can process the response. The fetch API is a newer approach that returns a promise. You pass the URL to fetch, handle the response using then, and parse the JSON data. If the response is not successful, you can throw an error. Both methods allow you to customize headers and handle various types of requests and are commonly used for making HTTP requests in JavaScript.
