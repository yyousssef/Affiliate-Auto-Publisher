# Affilliate-Auto-publisger 
An automated affiliate marketing workflow built using **n8n**.  
This system collects affiliate products daily, formats content automatically, and publishes posts to social platforms — creating a fully automated income stream.

---

## 🚀 Features
- Fetches affiliate products using RSS/API.
- Extracts title, price, images, and affiliate links.
- Auto-generates marketing post text.
- Publishes posts to Facebook Pages or Telegram.
- Runs daily without any human intervention.

---

## 🧩 Workflow Structure
**Node 1 — RSS Parser**  
Fetches products from affiliate RSS feeds (e.g., EgyMerch, Jumia, Amazon).

**Node 2 — Prepare Post Content**  
Formats title, price, link, and image into a ready-to-publish post.

(Optional) **Node 3 — Social Media Publisher**  
Publishes automatically to Facebo
