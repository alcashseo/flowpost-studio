# FlowPost Studio — Professional Social Media Auto-Publisher

FlowPost Studio is a premium desktop automation application built on **PySide6 (Qt)** and **Playwright** designed for creators, marketers, and agencies. It simplifies social media management by allowing bulk, scheduled, and automated publishing of Reels, Videos, Stories, Images, and Text posts across multiple platforms including **Facebook (Meta Business Suite), Twitter (X), Instagram, and TikTok**.

---

## 🌟 Key Features

* **Redesigned Modern GUI:** A sleek, user-friendly dark-mode interface built with high-performance Qt widgets.
* **Bulk Auto-Uploader:** Upload hundreds of Reels, videos, images, and text posts directly into posting queues.
* **Smart Posting Engine:** Space out your posts naturally with custom scheduling intervals and randomized gap options (jitter delay) to mimic human browsing behavior and protect accounts.
* **Multi-Platform & Multi-Account Support:** 
  * **Facebook:** Manage and post to multiple pages simultaneously.
  * **Instagram:** Direct automated publishing support.
  * **Twitter (X) & TikTok:** Modern automation pipeline.
* **Proxy & IP Rotation:** Built-in support for proxy pools and automatic IP rotation to manage high-volume publishing operations.
* **Offline Access:** Securely caches licensing states locally so that active/trial subscriptions continue to work even when internet connectivity is interrupted.

---

## 🚀 How It Works

```mermaid
graph TD
    A[Add Social Account] --> B[Fetch Pages / Profiles]
    B --> C[Set Target Folder & Schedules]
    C --> D[Add Media / Reels / Videos]
    D --> E[Start Auto-Publishing Queue]
    E --> F[Playwright Browser Automation]
