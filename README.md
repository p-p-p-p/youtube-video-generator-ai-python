
# YouTube Video Generator Using Generative AI & Python

#### Due to certain reasons, I am unable to share the code online.
## Workflow
![workflow](https://github.com/user-attachments/assets/9e115c28-d1b4-404b-b87c-836155f6888a)
## Result
https://github.com/user-attachments/assets/b54f51ee-cbbe-48cf-966e-433037f5468b

## Overview

This project involves generating YouTube videos using various generative AI models and tools. The system automates the entire process, from script generation to video upload, using open-source models and libraries.

### Components

1. **Generative AI Models:**
   - **Script Generation:** Large language models like ChatGPT, Meta LLaMA, and Google Gemini are used to generate video scripts, titles, and tags.
   - **Text-to-Image & Text-to-Video:** Different open-source generative AI models are used for creating visuals and video content from text prompts.[ Better results can be achieved as more advanced open-source models become available. Companies are continually releasing new models, improving the quality and capabilities of generative AI. ]
   - **Background Music & SFX:** Open-source generative AI models are used to create background music and sound effects.

2. **Tools & Libraries:**
   - **FFmpeg, Pillow, OpenCV:** These tools are used for video processing, image manipulation, and other tasks.
   - **Python Scripts:** Automate tasks like text-to-speech, video generation, and uploading.

### Current Automation

Currently, video generation requires manually clicking a button in Google Colab to trigger the video creation. This is a temporary solution due to budget constraints, which prevent the use of ChatGPT, Google Gemini API, and GPU-enabled servers. As a result, the system is not fully automated yet.

### Future Automation

1. **Scheduled Requests:** The system is designed to send automated requests to LLMs daily at 6 pm to generate video content.
2. **Full Automation:** Generates videos based on trending topics, including script, visuals, and background audio.
3. **Upload & Monitoring:** Uses YouTube Data API v3 to upload videos and integrates with Discord or Telegram bots for monitoring.
4. **Database:** MongoDB is used to store history and track video generation and upload status.

### Current Status

Due to budget constraints, I am currently handling tasks manually rather than using API services for models like ChatGPT or other LLaMA APIs. The system is designed to run continuously, generating and uploading videos daily. The use of GPU-enabled servers for this process can be costly.

### Future Goals

- Automate the entire video generation and uploading process.
- Integrate additional open-source generative AI models as they become available.
- Optimize the system to reduce costs and improve efficiency.

For more details or if you have any questions, feel free to reach out directly.
