---
"@mastra/observability": patch
---

Fixed observability flush and shutdown returning before background trace-cap cleanup finishes, so exporters can send the final abort records before lifecycle completion.
