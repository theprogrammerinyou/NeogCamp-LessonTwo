---
title: OCR Website
tags: [React, Python, Web Sockets, Opensearch]
timestamp: 2023-10-20
image:
  src: /images/ocr-app-fe.png
  alt: ""
description: An OCR app which lets you know which chapter of which subject of which class is a student studying. Built using opensearch, python, websockets, this is the most interesting project i have worked on. Please give it a read.
demoLink: https://ocr-app-fe.vercel.app
codeLink: https://github.com/tonhazarika/OCR-APP-FE
---

This was a freelance project, which helped me understand python, websockets, opensearch. The idea of the project was to help students understand the doubts, and provide more learning resources to students of class VI - X. The website, ideally lets the student know which subject, which chapter, which sub chapter, which page number the student is studying. This also suggests youtube videos, mcq questions and also lets user ask doubts using speech to text and does answer using text to speech API of browser.

I was responsible of making the frontend, backend and every feature present on the app. There were three different sections involved, naming automatic section where user automatically gets the subject, chapter, sub chapter, page number details. Manual section where user can select specific part of the page by drawing a rectangle on the book and the website would tell what part is he/she studying, and suggest vidoes, or answer doubts. This section involved using OpenAI API to get answers of users doubts. The third and last section helped user asking doubts by speaking  in the mic, this feature heavily utilized the speech to text API of the browser.
