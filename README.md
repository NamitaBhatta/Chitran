चित्रण: An Automated Festive Poster Generator with Wishes in Nepali Language

📌 Overview

Creating festival posters manually can be a repetitive and time-consuming task especially in Nepal, where more than 50 festivals are celebrated annually. This system aims to automate the generation of festival posters in Nepali using English prompts, making it easier for designers and the general public to quickly create vibrant and culturally rich visuals.

✨ What It Does

This tool generates festival posters in two phases:

🗣 Text Generation:

Converts an English prompt into a Nepali festival wish using a fine-tuned M2M-100 model.

🖼 Image Creation & Integration:

Generates a festival-themed image using a Latent Diffusion Model, applies the image’s color style to the text, and uses saliency mapping to smartly place the text on the image.


🔧 Tech Stack

M2M-100 (Translation)

Latent Diffusion Model (Image Generation)

Saliency Mapping (Text Placement)

Python, PyTorch, OpenCV
