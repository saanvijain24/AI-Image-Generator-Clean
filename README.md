
#  AI Image Generator

This is a simple web-based AI Image Generator built using HTML, CSS, and JavaScript. It uses the Hugging Face Inference API to generate images from text prompts using the `stabilityai/stable-diffusion-2` model.



## Features

- Generate AI-based images using natural language prompts
- Simple and clean UI
- Responsive design
- Uses Hugging Face API (via fetch)
-has 2 themes-light and dark

## Tech Stack

- HTML
- CSS
- JavaScript
- Hugging Face Inference API (`stable-diffusion-2` model)


##  Demo

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5322991c-6111-4de1-80fd-96ee669a7cdb" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7659f187-d17d-4c96-9be1-3321044a612b" />

![WhatsApp Image 2025-07-26 at 17 57 41_9321823c](https://github.com/user-attachments/assets/a9041688-2f91-4e1d-bfae-a089d4944ade)

![WhatsApp Image 2025-07-26 at 17 57 50_c4571f52](https://github.com/user-attachments/assets/bdb0498e-6c45-4e0a-9d36-7c92df40db60)
![WhatsApp Image 2025-07-26 at 17 58 07_d3867dfc](https://github.com/user-attachments/assets/41ef2b61-d2d0-4b6c-b80e-eef65d38ab09)
![WhatsApp Image 2025-07-26 at 17 58 17_5e797941](https://github.com/user-attachments/assets/b58f5d50-b5f1-408f-8d1a-e81a2c8ebe09)
![WhatsApp Image 2025-07-26 at 17 58 55_89e3c9f8](https://github.com/user-attachments/assets/d5f48fca-68f6-425f-87fd-e3707bd8384e)
![WhatsApp Image 2025-07-26 at 17 59 18_0c5c0a3e](https://github.com/user-attachments/assets/91013f52-a86f-4a4f-a2b3-97e0e53a8984)




## 📂 Folder Structure

```

AI-Image-Generator/
│
├── index.html        # Main HTML file
├── style.css         # CSS styles
├── script.js         # JavaScript with API call
├── preview\.png       # Optional screenshot
└── README.md         # This file

````

##  How It Works

1. User enters a text prompt.
2. JavaScript sends a POST request to Hugging Face API.
3. The API responds with an image blob.
4. The image is displayed on the page.

---

## 🔐 Setup Instructions

### 1. Get a Hugging Face API Key

- Sign up at [https://huggingface.co](https://huggingface.co)
- Go to **Settings > Access Tokens**
- Create a new **read access token**

### 2. Insert Your Token in `script.js`

```js
const API_KEY = "your_huggingface_token_here";
````

❗ **Do NOT commit your token to GitHub!** Use `.env`, or remove it before pushing.

---

## ⚠️ Warning

If your Hugging Face token is committed by mistake:

* Delete the token from Hugging Face.
* Remove it from all commits.
* Make a new clean commit history before pushing.

##  Acknowledgements

* [Hugging Face](https://huggingface.co/)
* [Stable Diffusion 2](https://huggingface.co/stabilityai/stable-diffusion-2)

```



