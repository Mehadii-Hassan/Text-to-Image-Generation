<h1 align="center">🎨 Stable Diffusion Text-to-Image</h1>

<p align="center">
  <strong>Generate stunning images from text prompts using Stable Diffusion</strong><br>
  Powered by <code>diffusers</code>, <code>transformers</code>, and <code>PyTorch</code>.
</p>

<hr>

<h2>📌 Project Overview</h2>

<p>
This project demonstrates <strong>Text-to-Image generation</strong> with <strong>Stable Diffusion</strong> models.  
Using 🤗 HuggingFace's <code>diffusers</code> library, you can transform creative prompts into high-quality AI-generated images.  
It also shows how to adjust key parameters such as inference steps, resolution, and multiple image generation.
</p>

<ul>
  <li>🖼️ <strong>Text-to-Image</strong>: Convert natural language into realistic art</li>
  <li>⚙️ <strong>Custom Parameters</strong>: Tune inference steps, width, height, and more</li>
  <li>🎭 <strong>Creative Prompts</strong>: Experiment with various artistic styles</li>
  <li>🚀 <strong>GPU Support</strong>: Optimized for CUDA acceleration</li>
</ul>

<hr>

<h2>🚀 Features</h2>

<ul>
  <li>✅ Generate AI art with just a prompt</li>
  <li>⚡ Powered by <code>dreamlike-art/dreamlike-diffusion-1.0</code></li>
  <li>📊 Customize outputs with <code>num_inference_steps</code>, <code>num_images_per_prompt</code></li>
  <li>🖼️ Support for different image resolutions</li>
</ul>

<hr>

<h2>🧠 How It Works</h2>

<ol>
  <li>Install dependencies (<code>diffusers</code>, <code>torch</code>, <code>transformers</code>)</li>
  <li>Load the Stable Diffusion pipeline from HuggingFace</li>
  <li>Enter a text prompt to generate images</li>
  <li>Customize parameters for different artistic outputs</li>
</ol>

<hr>

<h2>📂 Folder Structure</h2>

<pre>
stable-diffusion-text2image/
├── Text_to_Image_Generation.ipynb        ← Main script for generation
├── requirements.txt                      ← Dependencies
└── README.md                             ← Documentation
</pre>

<hr>

<h2>⚙️ Setup Instructions</h2>

<ol>
  <li>Clone the repository</li>
  <pre><code>git clone https://github.com/yourusername/stable-diffusion-text2image</code></pre>

  <li>Install dependencies</li>
  <pre><code>pip install -r requirements.txt</code></pre>

  <li>Run the script</li>
  <pre><code>python text2image.py</code></pre>
</ol>

<hr>

<h2>🧪 Sample Outputs</h2>

- **Prompt 1**  
  <code>"dreamlikeart, a grungy woman with rainbow hair, travelling between dimensions"</code>  
  🖼️ → AI-generated futuristic artwork  

- **Prompt 2**  
  <code>"A girl is sitting on a chair & She is accompanied by her tiger. Make sure to keep it cinematic"</code>  
  🖼️ → Cinematic image with tiger companion  

- **Prompt 3**  
  <code>"dreamlike, beautiful girl enjoying the Eid festival, draped in traditional Bangladeshi attire"</code>  
  🖼️ → Festival-inspired AI art 🎉  

<hr>

<h2>🙌 Credits</h2>

<p>
Created by <strong>Mehadi Hassan</strong> as part of HuggingFace Diffusers learning projects.  
</p>

<hr>

<p align="center">⭐ Star this repo if you love AI-generated art!</p>
