# Demo Bank Website + Genesys Cloud Messenger

This repository contains a simple demo banking website designed to showcase **Genesys Cloud Web Messaging** and support an **Agent Copilot** demo for a financial services contact center.

The site includes:
- A basic homepage for **Demo Bank**
- A small products section
- A FAQs section
- A floating chat entry point in the bottom-right area
- A placeholder for the **Genesys Messenger snippet**

## Project purpose

This project is intended for demo environments where customer interactions happen through **web messaging** in Genesys Cloud.

It can be deployed as a static site using providers such as:
- Netlify
- Vercel
- GitHub Pages

## Files

- `index.html` — Main static webpage for the demo site

## Before you deploy

You need to complete the following steps in **Genesys Cloud**:

1. Create and publish a **Messenger Configuration**
2. Create a **Web Messaging Deployment**
3. Copy the **Genesys Messenger install snippet**
4. Paste the snippet into the HTML file before the closing `</body>` tag
5. Make sure your deployment allows your website domain

## Local use

Because this is a static HTML page, you can open it directly in a browser or serve it locally with a simple local server.

Example using Python:

```bash
python -m http.server 8000
