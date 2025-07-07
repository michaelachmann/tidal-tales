---
title: Rationale
hide:
  - navigation
---

Instagram Stories disappear after 24 hours and are **under-represented in digital trace datasets**.  
Their ephemerality may encourage more candid or spontaneous messaging, and enable real-time engagement strategies that differ from feed posts. **In [our arXiv paper](https://arxiv.org/abs/2409.01880) we argue that ignoring Stories introduces a systematic bias toward more “archivable” content and against casual, rapid-fire communication styles.**

## Twice-Daily “Tidal” Schedule

Running the plugin at two fixed points guarantees **complete 24-hour coverage** while minimising researcher effort. Hence the name *Tidal Tales*: Tidal Tales reflects the plugin’s twice-daily collection rhythm, inspired by the ebb and flow of tides, which ensures consistent coverage without overwhelming researchers. See our example schedule:

| Time Slot | Rationale | 
|-----------|-----------|
| **09:00** | Captures content posted overnight and early morning. |
| **21:00** | Captures afternoon & evening material. |

### Sampling Logic

1. **Systematic, not random** – avoids the “path-of-least-resistance” bias of ad-hoc grabbing.  
2. **Temporal coverage** – ensures consistent sampling across typical posting hours.  
3. **Replicability** – a clock-based rule can be audited and repeated by other labs.

## From Capture to Analysis

* **Local-first philosophy** – media and metadata are stored on the researcher’s drive to remain compliant with GDPR data-minimisation principles.  
* **CSV schema** – see the [Data Schema](data-schema.md#full-schema) page.  

For data cleaning tutorials and additional processing steps, [refer to the course website](https://social-media-lab.net). For an overview and download instructions, return to the [homepage](index.md) or head to the [plugin](plugin.md) page.

