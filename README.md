# Mini-Sample Directory Structure

## 1. mini-sample.mp4

The **original lecture video** about **python programming**, which serves as the source for all annotations.

See in our appendix.zip in supplement material.

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
