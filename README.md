# Bootstrapping Computational Art

<img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fimg.huffingtonpost.com%2Fasset%2F5b6b3e792000009f00379402.jpeg%3Fops%3Dscalefit_720_noupscale&f=1&nofb=1" width=30%>

Baron Munchausen demonstrating an act of [Bootstrapping](https://www.huffpost.com/entry/pull-yourself-up-by-your-bootstraps-nonsense_n_5b1ed024e4b0bbb7a0e037d4).

## To Do:

- [ ] Add RAG notebook  
- [ ] Clean up dev branch 
- [ ] Add requirements.txt & add pip install instructions (talk about optional / required)
- [ ] Update Planning in bca25 branch  
- [ ] Replace anaconda with miniconda & venv install manual to readme
- [ ] Add how to install ffmpeg to readme
- [ ] Check and update LLM tool list (Additional Tools & Deployments)
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

Git is a free and open source distributed version control system.
Macs should have it preinstalled, otherwise you can download it here:

https://github.com/git-guides/install-git

### Anaconda for python

Anaconda is a package manager, an environment manager, and Python distribution that contains a collection of many open source packages.
You can find the install instructions for your platform here:

https://docs.anaconda.com/anaconda/install/index.html

Once anaconda is installed you can open a terminal or anaconda prompt (for windows). If it was installed correctly you should see `(base)` next to your username. Alternatively you can type `conda` in your terminal to check if it works.

To create an environment for this class enter the following into your terminal:

`conda create --name bca python=3.12`  

This command will set up an environment called 'bca' using python 3.12.

To activate the environment in your current terminal session, simply type:

`conda activate bca`

### Jupyter Lab

We will use Jupyter to work with python notebooks directly in the browser.
Once you have Anaconda up and running and activated your environment you can simply install jupyter with pip by entering:

`pip install jupyterlab`

to run jupyter:
`jupyter lab`

### Clone this repository

Finally clone this repository. To do so, first change your directory to the location where you would like to install it using the `cd` command in your terminal. On Mac you could for example `cd Desktop` and press enter.

Now you can write the following in your terminal:  

`git clone https://github.com/coralreefman/bca.git`  

If that doesn't work, just download the .zip form the code button above and unzip on your computer.

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
_Last updated: 2025-07-24_

### Chatbots and Language Models

**Mistral AI**
- https://mistral.ai
- Free chat version, downloadable model weights, paid fine-tuning

**ChatGPT**
- https://chat.openai.com
- Free and paid chat versions, fine-tuning options, plugins

**Claude AI**
- https://claude.ai
- Limited free chat version, reasoning capabilities

**Meta AI (LLaMA)**
- https://ai.meta.com
- Free chat version, downloadable model weights

**Google Gemini**
- https://gemini.google.com/
- Free and paid chat versions

### AI-Assisted Development Tools

**GitHub Copilot**
- https://github.com/features/copilot
- Code completion and generation (paid)

**Cursor**
- https://www.cursor.so
- Code editor (VS Code fork) with free and paid versions

**v0.dev**
- https://v0.dev
- Web UI generation for React/CSS

### AI-Enhanced Search Engines

**Perplexity AI**
- https://www.perplexity.ai
- Search engine with cited sources

### Additional Tools

**Hugging Face**
- https://huggingface.co
- Open-source AI community, model hub, and development tools

**OpenAI Playground**
- https://platform.openai.com/playground
- Experimentation platform for OpenAI's models

**Anthropic AI**
- https://www.anthropic.com
- Advanced AI research and development (claude)

### Free or Low-Cost Deployment and Cloud Compute

**Google Colab**
- https://colab.research.google.com
- Free Jupyter notebooks with GPU/TPU options, easy sharing

**Kaggle Kernels**
- https://www.kaggle.com/code
- Free notebooks, GPUs, and datasets for data science

**Hugging Face Spaces**
- https://huggingface.co/spaces
- Free hosting for ML demo apps, integration with Hugging Face models

**Streamlit**
- https://streamlit.io
- Easy web app creation for ML projects, free community cloud hosting

**Gradio**
- https://gradio.app
- Simple ML web interfaces, free hosting via Hugging Face Spaces

**Paperspace**
- https://www.paperspace.com/artificial-intelligence
- Free tier available, GPU-powered notebooks and deployments

### Learning Resources

**Fast.ai**
- https://www.fast.ai
- Free courses on deep learning and AI

**DeepLearning.AI**
- https://www.deeplearning.ai
- AI courses and specializations

### YouTube Tutorials

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

## Scraping Tools (TBD)

### Video
youtube-dl / ytdlp

### Images
gallery-dl

### Social Media Platforms 
instagram

_“In the computer field, the moment of truth is a_
_running program; all else is prophecy.”_

Herbert Simon

