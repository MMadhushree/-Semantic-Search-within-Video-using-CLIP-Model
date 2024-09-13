
# Semantic Search within Video using CLIP Model

This project demonstrates a semantic search system implemented within video content using OpenAI's CLIP model. By leveraging CLIP's ability to understand both images and text, this system allows you to extract visual features from video frames and perform text-based queries to find relevant moments in the video.

## Features

- Uses the CLIP model to encode and compare text and video frames.
- Supports semantic search over video content.
- Extracts video frames and processes them for feature extraction.
- Designed for video indexing and retrieval tasks.

## Dependencies
- Python 3.x
- PyTorch
- OpenAI CLIP
- yt-dlp
- OpenCV
- PIL (Pillow)


## How It Works
- The video is split into frames using OpenCV.
- Each frame is processed through the CLIP model to extract visual features.
- A text query is embedded into the same feature space as the frames, allowing for semantic similarity comparison.
- The most relevant frames are returned based on the query.
