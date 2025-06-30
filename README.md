# RoboCLIP

✅ Goal:
Train a MobileCLIP-style model (lightweight CLIP) on the COCO captions dataset to align images and text in a compact model for downstream robotics tasks (e.g., captioning, vision-language reasoning).

🎯 Objectives
Input: Image(s) + text query

Output: Caption, classification, localization, instruction following, etc.

📉 Constraints
On-device inference (low latency)

Limited compute: ARM CPU, Jetson, Coral, etc.

Real-time response (e.g., ≤100ms per inference)

Possibly limited memory (RAM < 2GB)
