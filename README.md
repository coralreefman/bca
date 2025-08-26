# Bootstrapping Computational Art

<img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fimg.huffingtonpost.com%2Fasset%2F5b6b3e792000009f00379402.jpeg%3Fops%3Dscalefit_720_noupscale&f=1&nofb=1" width=30%>

Baron Munchausen demonstrating an act of [Bootstrapping](https://www.huffpost.com/entry/pull-yourself-up-by-your-bootstraps-nonsense_n_5b1ed024e4b0bbb7a0e037d4).

## To Do:

- [x] Replace anaconda with miniconda & venv install manual to readme
- [x] Add requirements.txt & add pip install instructions (talk about optional / required)
- [x] Add how to install ffmpeg to readme
- [x] Check and update LLM tool list (Additional Tools & Deployments)
- [x] Add section about scraping
- [ ] Add RAG notebooks  
- [ ] Clean up dev branch 
- [ ] Update Planning in bca25 branch  
- [ ] BringYourOwnData -> Data represented as something else, look at data in different ways (is there a good example?) -> david kreisel? edwin van der heyde ms word as music -> jpeg editing (headers / change numbers / inspect headers / inspect)
- [ ] Add References to bottom of readme  
- [ ] Add ‘the clock’ movie from 70’s, videogrep, paul sharits, michael snow etc. to video nb

## Ideas / Topics

- Notebook about emergence/complexity with CA, genetic algos and neural networks, autopoesis  
- Add kernels to matrix nb, like edge detection, blur etc.
- Notebook about sorting, (sorting algos, pixel sorting etc.) that we could place after the noise nb.
- Show differences between parametric / procedural / generative approaches
- Digital vs analogue 
- How to write pseudo code, flowcharts, instructions (Sol LeWitt) (idea is machine)
- Mapping as alchemy
- add section with different code editors (VScode, sublime, nano, vim/neovim, Emacs)
- dichotomy human / machine / transhumanism / technosolutionism 
- technical metaphors and analogies (from steam engine to ai)

## Course Outline
In this super practical workshop we will get you going with programming simple computational artworks. The focus is on learning the basics. Topics might include: recursion, randomness, generative algorithms, rule sets, data processing, web scraping, hacking, text generation, chaotic systems, and some machine learning. We will use the programming language Python, so some experience with programming is required! In the morning we will discuss some theory, and study examples from computer art history. This will take about 1 hour, and will be followed by coding examples and hands-on help on the individual student’s project.  
As Artificial Intelligence and Machine Learning is developing at a rapid rate, we will look at how this can help us with generative art and how we can code more effectively with AI-assist.

## Requirements

### Git

Git helps us keep track of changes in our code and makes it easy to share and collaborate.
To be precise, it is a free and open source distributed version control system.
Macs should have it preinstalled, otherwise you can download it here:

https://github.com/git-guides/install-git

### Clone this repository

Clone this repository. To do so, first change your directory to the location where you would like to install it using the `cd` command in your terminal. On Mac you could for example `cd Desktop` and press enter.

Now you can write the following in your terminal:  

`git clone https://github.com/coralreefman/bca.git`  

If that doesn't work, just download the .zip from the code button above and unzip on your computer.

### Python Environment Setup

A Python environment keeps different projects and their packages separate, which prevents a lot of problems when working on multiple projects or when sharing code with others.  

Here are some common ways to manage Python environments:  

### Miniconda (Recommended)
Miniconda is a minimal installer that includes only Python, conda (package manager), and a few other essential packages. It's much lighter than Anaconda (480 MB vs. 4.4 GB) and gives you more control over which packages to install.

You can download Miniconda here:
https://www.anaconda.com/download  

Or install it directly from the command line:
https://www.anaconda.com/docs/getting-started/miniconda/install#quickstart-install-instructions  


### Anaconda

Anaconda is a full distribution that comes with a lot of Python packages pre-installed. While comprehensive, it can be overkill for most users and takes up significant disk space. Only choose this option if you need the full suite of data science packages immediately.
You can find the install instructions for your platform here:
https://www.anaconda.com/docs/getting-started/anaconda/install  

Once miniconda or anaconda is installed you can open a terminal or anaconda prompt (for windows). If it was installed correctly you should see `(base)` next to your username. Alternatively you can type `conda` in your terminal to check if it works.

To create an environment for this class enter the following into your terminal:

```bash
# Create environment
conda create --name bca python=3.12
```  

This command will set up an environment called 'bca' using python 3.12.

To activate the environment in your current terminal session, simply type:

```bash
# Activate environment
conda activate bca
```

After activating your conda environment:
```bash
# Install required packages to the new environment
pip install -r requirements.txt
```

### Python venv (Lightweight Alternative)
If you already have Python installed, you can use the built-in `venv` module. This is the most lightweight option as it's included with Python and doesn't require additional installers. However, it only manages Python packages and doesn't include additional tools like conda.

First, install Python from:
https://www.python.org/downloads/

Then create a virtual environment:
```bash
# Create environment
python -m venv bca

# Activate environment
# On Mac/Linux:
source bca/bin/activate
# On Windows:
bca\Scripts\activate

# Install required packages to the new environment
pip install -r requirements.txt
```

The `requirements.txt` file contains a list of Python packages needed to run the code in our notebooks. You can either install them all at once using the command above, or install packages one by one as you need them while working through the notebooks.

### Jupyter Lab

Jupyter Lab lets us write and run code in the browser, see results immediately, and mix code with text and images. It's great for experimenting and learning. It's included in requirements.txt, but if you haven't installed that yet:  

```bash
pip install jupyterlab
```

to run jupyter:
```bash
jupyter lab
```

### FFmpeg Installation (Optional)

FFmpeg is required for video processing in some of our notebooks. It can be a bit of a pain to install, but here are some easy ways to get it working:

Using conda (if you installed Miniconda/Anaconda) - this is probably the easiest way:
```bash
conda install ffmpeg
```

Using Homebrew on Mac, also super straightforward:
```bash
brew install ffmpeg
```

For Windows users, a bit more involved:
1. Download from: https://www.gyan.dev/ffmpeg/builds/ (recommended "essentials" build)
2. Extract the archive
3. Add the `bin` folder to your system's PATH environment variable

For Linux users:
```bash
# Ubuntu/Debian
sudo apt install ffmpeg

# Fedora
sudo dnf install ffmpeg
```

To check if it worked, just type:
```bash
ffmpeg -version
```

## Planning

On each day in the morning we will have an introduction to several topics ranging from chaos and randomness to machine learning and neural networks, after which you will have some time to work on your projects.

| Day | Date   | Description            | Focus                               | Notes |
|-----|--------|------------------------|-------------------------------------|-------|
| 1   |        |                        |                                     |       |
| 2   |        |                        |                                     |       |
| 3   |        |                        |                                     |       |
| 4   |        |                        |                                     |       |
|-----|--------|------------------------|-------------------------------------|-------|
| 5   |        |                        |                                     |       |
| 6   |        |                        |                                     |       |
| 7   |        |                        |                                     |       |
| 8   |        |                        |                                     |       |


## LLM tools
_Last updated: 2025-07-29_

### Chatbots and Language Models

**Mistral AI**
- https://mistral.ai
- Free chat version, downloadable model weights, paid fine-tuning

**ChatGPT & OpenAI**
- https://chat.openai.com
- Free and paid chat versions, plugins
- https://platform.openai.com/playground
- API access and playground for experimentation

**Claude & Anthropic**
- https://claude.ai
- Free chat version with large context window
- https://console.anthropic.com
- Claude API and playground

**Meta AI (LLaMA)**
- https://ai.meta.com
- Free chat version, downloadable model weights

**Google AI Platform**
- https://gemini.google.com/
- Free and paid chat versions
- https://cloud.google.com/vertex-ai
- Full AI/ML development platform with:
  - Gemini API access
  - Model training and deployment
  - Notebooks with free GPU/TPU
  - AutoML for custom models
- Student credits available through Google Cloud

### AI-Assisted Development Tools

**Cursor**
- https://www.cursor.so
- Code editor (VS Code fork) with free and paid versions

**v0.dev**
- https://v0.dev
- Web UI generation for React/CSS

**Replit**
- https://replit.com
- Online IDE with built-in AI features
- Good for: quick experiments, sharing code

**GitHub Copilot**
- https://github.com/features/copilot
- Code completion and generation (paid)

### AI-Enhanced Search Engines

**Perplexity AI**
- https://www.perplexity.ai
- Search engine with cited sources

### PDF Parsing

**Docling**
- https://github.com/docling-project/docling

**olmOCR**
- https://github.com/allenai/olmocr

**marker**
- https://github.com/datalab-to/marker


### Additional Tools

**Hugging Face**
- https://huggingface.co
- ML model hub, tutorials, courses
- Active community, good documentation

**Google Colab**
- https://colab.research.google.com
- Free Jupyter notebooks with GPU/TPU options, easy sharing
- Good for ML experiments

**Transformers (Hugging Face)**
- https://huggingface.co/docs/transformers
- Essential library for working with AI models
- Huge collection of pre-trained models
- Great documentation and examples

### AI Image & Video Tools

**ComfyUI**
- https://github.com/comfyanonymous/ComfyUI
- Visual node-based interface for Stable Diffusion and other models
- Great for understanding AI image generation
- Runs locally, highly customizable

**Stable Diffusion**
- https://stability.ai
- Open source image generation
- Many web UIs and implementations

## AI Learning Resources

**Fast.ai**
- https://www.fast.ai
- Free courses on deep learning and AI

**DeepLearning.AI**
- https://www.deeplearning.ai
- AI courses and specializations

## YouTube Tutorials

**Socratica - Python Course**
- https://www.youtube.com/watch?v=bY6m6_IIN94&list=PLi01XoE8jYohWFPpC17Z-wWhPOSuh8Er-&pp=iAQB
- Comprehensive Python programming course

**3blue1brown - Neural Networks**
- https://www.youtube.com/watch?v=aircAruvnKk&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi&pp=iAQB
- Visual explanations of neural network concepts

**3blue1brown - Explainers**
- https://www.youtube.com/watch?v=aircAruvnKk&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi&pp=iAQB
- In-depth explanations of various mathematical concepts

**Andrej Karpathy - Intro to LLM's**
- https://youtu.be/zjkBMFhNj_g?si=jsJmkYrKSgEIWU0H
- Introduction to Large Language Models

**Andrej Karpathy - Neural Networks: Zero to Hero**
- https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ
- Comprehensive course on neural networks from basics to advanced topics

**Computerphile**
- https://www.youtube.com/@Computerphile
- Wide range of computer science topics explained in-depth

## Scraping Tools

### Video
**yt-dlp** (formerly youtube-dl)
- https://github.com/yt-dlp/yt-dlp
- Downloads videos from YouTube and 1000+ other sites
- Much faster than youtube-dl and actively maintained
```bash
# Install with pip
pip install yt-dlp
```

### Images
**gallery-dl**
- https://github.com/mikf/gallery-dl
- Downloads image galleries from 200+ sites
- Works with pixiv, deviantart, twitter, etc.
```bash
# Install with pip
pip install gallery-dl
```

**img2dataset**
- https://github.com/rom1504/img2dataset
- Downloads and processes large image datasets
- Good for AI training data collection

### Social Media Platforms 
**instaloader**
- https://github.com/instaloader/instaloader
- Includes many options to scrape Instagram
```bash
pip install instaloader
```

**PRAW**
- https://github.com/praw-dev/praw
- Reddit API wrapper
- Good for collecting text data
```bash
pip install praw
```

### Web Scraping

**requests**
- Essential HTTP library for Python
- Base of most scraping tools
```bash
pip install requests
```

**BeautifulSoup4**
- Standard Python library for parsing HTML
- Great for structured data extraction
```bash
pip install beautifulsoup4
```

**Selenium**
- For sites that need JavaScript
- Controls actual browser, good for complex sites
```bash
pip install selenium
```

**Playwright**
- Alternative to Selenium
- Better automation and less detection
```bash
pip install playwright
playwright install
```

_“In the computer field, the moment of truth is a_
_running program; all else is prophecy.”_

Herbert Simon

