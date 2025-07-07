---
title: Data Schema & Sample
hide:
  - navigation
---

All media files are saved to `<Your Downloads Folder>/tidaltales/<username>/`. For each story—whether it's an image or a video—Tidal Tales stores a single image: either the image itself or, in the case of videos, the preview cover frame provided by Instagram. 

## Full Schema

| Column | Type | Description |
|--------|------|-------------|
| **ID** | int | Sequential identifier per capture session |
| **Time of Posting** | ISO-8601 string | Original timestamp in uploader’s timezone |
| **Type of Content** | enum(`Image`,`Video`) | Media type |
| **video_path** | str | Relative path in downloads folder |
| **image_path** | str | Same for images |
| **Username** | str | Instagram handle |
| **Video Length (s)** | float | Duration of video stories |
| **Expiration** | ISO-8601 string | When Instagram will delete the story |
| **Caption** | str |   |
| **Is Verified** | bool | Blue-tick account |
| **Stickers** | json | Array of stickers present in the story (e.g., tags, mentions) |
| **Accessibility Caption** | str | Alt-text shown by Instagram |
| **Attribution URL** | str | |
| **Story Media** | json | Nested JSON describing embedded posts |
| **Story Hashtags** | json | List of hashtags used |
| **Story Questions** | json | User-generated question sticker data |
| **Story Sliders** | json | Emoji slider sticker interactions |
| **Story CTA** | json | Call-to-action button (link, swipe-up) |
| **Story Countdowns** | json | Countdown sticker data |
| **Story Locations** | json | Location tags attached to the story |


### Sample Row

| ID | Time of Posting | Type of Content | video_path | image_path | Username | Video Length (s) | … |
|----|-----------------|-----------------|------------|------------|----------|------------------|---|
| 42 | 2025-07-07T08:12:56+02:00 | image |  | `@bundestag/3672348659658584240.jpg` | `@bundestag` | 15.0 | … |

> **Next Steps:** Visit the chapter [Data Preprocessing on our course website](https://social-media-lab.net/processing/preprocessing.html) to extract any image-text (OCR) and transcribe audio.