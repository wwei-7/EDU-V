# Mini-Sample of EDU-V Directory Structure

**This is a sample of the EDU-V dataset, which will be released publicly later.**

## 1. original lecture video

The **original lecture video** about **python programming**, which serves as the source for all annotations.

https://www.bilibili.com/video/BV1pJ4m157qQ/?spm_id_from=333.1387.homepage.video_card.click&vd_source=d51cdb16be094ccba8d9f54efa88fa0b

## 2. knowledge concept annotation.txt

The annotation file contains **all concept annotation segments** of the original lecture video in the format:  **[start-time] [end-time] [knowledge concept]**.

```text
knowledge concept annotation.txt:

00:01:22,700 --> 00:02:02,700 String 
00:02:03,329 --> 00:02:43,329 String
00:02:44,819 --> 00:03:24,819 String

00:04:52,379 --> 00:05:32,379 Integer (Int)
...
```

## 3. Concept Frame & OCR/

This folder contains: 1) **Concept Frames** annotated by our pipeline, and 2) **corresponding OCR texts** for each concept annotation segments.

## 4. Subtitles/

This folder contains 10-second **subtitle** aligned with the **Concept Frame** in each concept annotation segment.
