<div align="center">

<p>
  <img src="https://github.com/user-attachments/assets/81fe6816-44cc-4c61-97c7-f3c099650966" alt="Banana Slides" width="860">
</p>
<p>
  <a href="https://trendshift.io/repositories/22056" target="_blank">
    <img src="https://trendshift.io/api/badge/repositories/22056" alt="Anionex%2Fbanana-slides | Trendshift" width="265" height="58">
  </a>
  <br>
  <a href="https://hellogithub.com/repository/Anionex/banana-slides" target="_blank">
    <img src="https://abroad.hellogithub.com/v1/widgets/recommend.svg?rid=c8a0ee51918e4353af08012b8472b85e&claim_uid=CtDTm2jbUHhVGBr&theme=neutral" alt="Featured｜HelloGitHub" width="265" height="58">
  </a>
</p>
<p>
  <a href="#-项目缘起"><b>Simplified Chinese</b></a>
  &nbsp;•&nbsp;
  <a href="README_EN.md"><b>English</b></a>
</p>
<p>
  <a href="https://github.com/Anionex/banana-slides/stargazers"><img src="https://img.shields.io/github/stars/Anionex/banana-slides?style=flat-square&color=FFD700" alt="GitHub Stars"></a>
  <a href="https://github.com/Anionex/banana-slides/network"><img src="https://img.shields.io/github/forks/Anionex/banana-slides?style=flat-square&color=FFD700" alt="GitHub Forks"></a>
  <a href="https://github.com/Anionex/banana-slides/watchers"><img src="https://img.shields.io/github/watchers/Anionex/banana-slides?style=flat-square&color=FFD700" alt="GitHub Watchers"></a>
  <a href="https://github.com/Anionex/banana-slides"><img src="https://img.shields.io/badge/version-v0.4.0-44cc11?style=flat-square" alt="Version"></a>
  <a href="https://github.com/Anionex/banana-slides/blob/main/LICENSE"><img src="https://img.shields.io/github/license/Anionex/banana-slides?color=0055aa&style=flat-square" alt="License"></a>
  <br>
  <img src="https://img.shields.io/badge/Docker-Build-4A90D9?logo=docker&logoColor=white&style=flat-square" alt="Docker Build">
  <a href="https://deepwiki.com/Anionex/banana-slides"><img src="./assets/badge-deepwiki-flat.svg" alt="Ask DeepWiki"></a>
</p>

<p>
  <b>A native AI PPT generation application based on nano banana pro 🍌</b><br>
  <b>Go from idea to presentation in minutes—no tedious layout required, request revisions verbally, and step towards a true "Vibe PPT"</b>
</p>
<p>
  <a href="https://bananaslides.online/"><b>🚀 Online Demo</b></a>
  &nbsp;|&nbsp;
  <a href="https://docs.bananaslides.online/"><b>📖 Documentation</b></a>
  &nbsp;|&nbsp;
 <a href="https://github.com/Anionex/banana-slides#-%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95"><b>Deployment</b></a>
</p>
<p>
  If this project is useful to you, feel free to <b>Star 🌟</b> & <b>Fork 🍴</b>
</p>

</div>

## 🔥 Latest Updates

- **[2026-06-23]**: Page-by-page templates launched — Supports both single and multi-template modes. Upload images or PDFs to build a project template library. AI automatically analyzes template styles and provides one-click smart matching for each page, with manual binding also available. Switch between both modes at any time. ([Documentation](https://docs.bananaslides.online/zh/features/templates))
- **[2026-04-25]**: Asset Toolbox launched — Added three new modes: whole image editing, selection editing (overlay/replace), and smart erase, built on top of the original asset generation. One-stop operation with a unified entry point.
- **[2026-04-25]**: Supports login and account binding via OpenAI official OAuth. Once bound, Codex can be used directly as a text/image generation provider without manually entering an API Key. Plus accounts can generate 100+ 2K images every five hours ([Tutorial](https://ziy68cvfvu3.feishu.cn/wiki/LDSOwPzkhiNonkkNTF1ct2VBnNc)) (Based on OpenAI official OAuth PKCE authorization flow, non-reverse engineered).
- **[2026-04-25]**: Supports saving custom text style description templates. Includes naming, color tagging, and persistent reuse, eliminating the need for repetitive input.
- **[2026-04-23]**: Added support for the gpt-image-2 model. Editable background effects during export have also been improved due to upgraded model capabilities (Select "Generative Acquisition" under Settings - Export Options - Background Acquisition).
- **[2026-04-11]**: Supported [CLI operations and added agent skills](https://docs.bananaslides.online/cli).
- **[2026-03]**: Added several features and optimizations, such as extra fields, multi-aspect ratio settings, etc.
- **[2026-02-09]**: New Features and Optimizations
  * New Features
    * Supports pasting and instant recognition of images on the home page, outline, and description cards, with an improved interactive experience.
    * Manual outline chapter editing: Supports manually adjusting the chapter (part) a page belongs to.
    * Docker multi-architecture: Image supports amd64 / arm64 builds.
    * I18n + Dark Mode: Added Chinese/English switching; supports Light/Dark/System themes; full component adaptation for dark mode.
  * Fixes and Experience Optimizations
    * Fixed export-related 500 errors, reference file association timing, outline/page data misalignment, incorrect task polling items, infinite polling for description generation, image preview memory leaks, and partial failure handling for batch deletions.
    * Optimized format example tips, HTTP error message copy, Modal closing experience, cleaned up old project localStorage, and removed redundant prompts for first-time project creation.
    * Various other optimizations and fixes.

## ✨ Project Origins

Have you ever found yourself in this predicament: your presentation is due tomorrow, but your slides are still a blank slate; your mind is full of brilliant ideas, but your passion is drained by tedious layout and design?

We long to quickly create presentations that are both professional and well-designed. While traditional AI PPT generation apps generally meet the need for "speed," they still face the following issues:

- 1️⃣ Only able to choose from preset templates, unable to flexibly adjust styles
- 2️⃣ Low degree of freedom, making multi-round revisions difficult
- 3️⃣ Similar visual output, suffering from severe homogenization
- 4️⃣ Low material quality, lacking specific relevance
- 5️⃣ Fragmented text-image layout, poor design sense

These flaws make it difficult for traditional AI PPT generators to simultaneously satisfy our dual needs for "speed" and "beauty." Even those claiming to be "Vibe PPT" are far from being "Vibe" enough in my eyes.

However, the emergence of the nano banana🍌 model has changed everything. I tried using 🍌pro to generate PPT pages and found that the results—whether in quality, aesthetics, or consistency—were excellent. Furthermore, it can accurately render almost all the text requested in the prompt and follow the style of reference images. So, why not build a native "Vibe PPT" application based on 🍌pro?

## 👨‍💻 Applicable Scenarios

1. **Beginners**: Quickly generate beautiful PPTs with zero entry barrier, requiring no design experience and reducing the hassle of template selection.
2. **PPT Professionals**: Reference AI-generated layouts and combinations of text and visual elements to quickly gain design inspiration.
3. **Educators**: Quickly convert teaching content into illustrated lesson plan PPTs to enhance classroom impact.
4. **Students**: Quickly complete assignment presentations, allowing them to focus on content rather than layout and formatting.
5. **Professionals**: Rapidly visualize business proposals and product introductions with quick adaptation to various scenarios.

<p>
  <b>🎯Goal: Lower the barrier for PPT creation, enabling everyone to quickly create beautiful and professional presentations.</b>
</p>

## 🎨 Result Examples

<div align="center">

| | |
|:---:|:---:|
| <img src="https://github.com/user-attachments/assets/d58ce3f7-bcec-451d-a3b9-ca3c16223644" width="500" alt="Case 3"> | <img src="https://github.com/user-attachments/assets/c64cd952-2cdf-4a92-8c34-0322cbf3de4e" width="500" alt="Case 2"> |
| **Software Development Best Practices** | **DeepSeek-V3.2 Technical Showcase** |
| <img src="https://github.com/user-attachments/assets/383eb011-a167-4343-99eb-e1d0568830c7" width="500" alt="Case 4"> | <img src="https://github.com/user-attachments/assets/1a63afc9-ad05-4755-8480-fc4aa64987f1" width="500" alt="Case 1"> |
| **R&D and Industrialization of Intelligent Production Line Equipment for Prepared Dishes** | **The Evolution of Money: A Journey from Shells to Paper Currency** |

</div>

View more <a href="https://github.com/Anionex/banana-slides/issues/2" > Case Studies </a>

## 🎯 Features

### 1. Flexible and Diverse Creative Paths

Supports three starting methods: **Ideas**, **Outlines**, and **Page Descriptions**, catering to different creative habits.
- **One-sentence generation**: Enter a topic, and AI automatically generates a well-structured outline and page-by-page content descriptions.
- **Natural language editing**: Supports modifying outlines or descriptions using "Vibe" prompts (e.g., "Change page three to a case study"), with AI adjusting in real time.
- **Outline/Description mode**: Supports both one-click batch generation and manual adjustment of details.

<img width="2000" height="1125" alt="image" src="https://github.com/user-attachments/assets/7fc1ecc6-433d-4157-b4ca-95fcebac66ba" />

### 2. Powerful Asset Parsing Capabilities

- **Multi-format Support**: Upload PDF/Docx/MD/Txt and other files for automatic backend content parsing.
- **Intelligent Extraction**: Automatically identify key points, image links, and chart information within the text to provide rich materials for generation.
- **Automatic Image Archiving**: Images parsed from documents are automatically added to the project asset library after being associated with reference files, allowing for direct reuse later.
- **Style Reference**: Support for uploading reference images or templates to customize the PPT style.

<img width="1920" height="1080" alt="File Parsing and Material Processing" src="https://github.com/user-attachments/assets/8cda1fd2-2369-4028-b310-ea6604183936" />

### 3. "Vibe" Style Natural Language Modification

No longer limited by complex menu buttons, issue modification commands directly through **natural language**.
- **Partial Redrawing**: Make verbal-style modifications to unsatisfactory areas (e.g., "change this chart to a pie chart").
- **Full-page Optimization**: Generate high-definition, style-consistent pages based on nano banana pro🍌.

<img width="2000" height="1125" alt="image" src="https://github.com/user-attachments/assets/929ba24a-996c-4f6d-9ec6-818be6b08ea3" />

### 4. Out-of-the-box Format Export

- **Multi-format Support**: One-click export to standard **PPTX** or **PDF** files.
- **Playback Settings**: Enable page transition animations before exporting to PPTX. Supports classic effects including Fade, Push, Wipe, Split, Blinds, Checkerboard, Clock, and more, with the option to multi-select for random application.
- **Perfect Fit**: Default 16:9 aspect ratio; no manual layout adjustments required, ready for direct presentation.

<img width="1000" alt="image" src="https://github.com/user-attachments/assets/3e54bbba-88be-4f69-90a1-02e875c25420" />
<img width="1748" height="538" alt="PPT与PDF导出" src="https://github.com/user-attachments/assets/647eb9b1-d0b6-42cb-a898-378ebe06c984" />

### 5. Editable PPTX Export (Beta)

- **Export images to high-fidelity PPT slides with clean backgrounds and freely editable images and text**
- See https://github.com/Anionex/banana-slides/issues/121 for related updates
<img width="1000"  alt="image" src="https://github.com/user-attachments/assets/a85d2d48-1966-4800-a4bf-73d17f914062" />

### 6. One-click Export Explainer Video

- **One-click conversion of slides into presentation videos (MP4) with AI voiceovers and subtitles**
- AI automatically generates colloquial narrations based on page descriptions and content
- Supports configuration of multiple expression styles, languages, and voice timbres

<br>

**🌟 Comparison with notebooklm slide deck features**
| Feature | notebooklm | This Project | 
| --- | --- | --- |
| Page Limit | 15 pages | **Unlimited** | 
| Post-editing | Prompt-based modification | **Selection editing + Voice-guided editing** |
| Asset Addition | Cannot add after generation | **Add freely after generation** |
| Export Formats | Supports PDF, (non-editable image) pptx | **Export to PDF, (image or editable) pptx, presentation video** |
| Watermark | Watermark in free version | **No watermark, free to add/delete elements** |

> Note: This comparison may become outdated as new features are added.

## 🗺️ Roadmap

| Status | Milestone |
| --- | --- |
| ✅ Completed | Create PPT via three paths: ideas, outlines, and page descriptions |
| ✅ Completed | Parse Markdown-formatted images in text |
| ✅ Completed | Add more assets to individual PPT slides |
| ✅ Completed | Vibe-based verbal editing of selected areas on single PPT slides |
| ✅ Completed | Asset Module: Asset generation, uploading, etc. |
| ✅ Completed | Support for uploading and parsing various file formats |
| ✅ Completed | Support for Vibe-based verbal adjustments to outlines and descriptions |
| ✅ Completed | Initial support for exporting editable .pptx files |
| 🔄 In Progress | Support for multi-layered, precise background removal in editable .pptx exports |
| 🔄 In Progress | Web Search |
| 🔄 In Progress | Agent Mode |
| ✅ Completed | TTS narration video export (multi-voice in CN/EN/JP, subtitles) |
| 🚍 Partial | Optimize frontend loading speed |
| 🧭 In Planning | Online playback feature |
| 🧭 In Planning | Simple animations and slide transition effects |
| 🚍 Partial | Multi-language support |
| | |

## 📦 Usage

### (New) One-click deployment using application templates

This is the simplest way. No need to install Docker or download the project; you can access the application directly after creation.

1. One-click deploy and start this application via Rainyun (High bandwidth, suitable for HD image generation and downloading. Free trial available for new users)
- [Image & Text Tutorial](https://ziy68cvfvu3.feishu.cn/wiki/B5RIwg3OUiCfo9kyadzcR9CInnc?from=from_copylink)

[![Deploy on Rainyun](https://rainyun-apps.cn-nb1.rains3.com/materials/deploy-on-rainyun-cn.svg)](https://app.rainyun.com/apps/rca/store/7549/anionex_)

2. Coming Soon

### Using Docker Compose🐳

Quickly start frontend and backend services using Docker Compose.

<details>
  <summary>📒 Instructions for Windows/Mac Users</summary>

If you are using **Windows or macOS**, please [install **Docker Desktop**](https://docs.docker.com/desktop/setup/install/windows-install/) first and ensure Docker is running (check the system tray icon on Windows; check the menu bar icon on macOS), then follow the same steps in the documentation.

> **Tip**: If you encounter issues, Windows users should enable the **WSL 2 backend** in the Docker Desktop settings (recommended); also, ensure that ports **3011** and **5011** are not occupied.

</details>

0. **Clone the repository**
```bash
git clone https://github.com/Anionex/banana-slides
cd banana-slides
```

1. **Configure environment variables**

Create the `.env` file (refer to `.env.example`):
```bash
cp .env.example .env
```

**(Optional, can also be configured in the UI after startup, [click here for the tutorial](https://ziy68cvfvu3.feishu.cn/wiki/GiNawdmpiinSRqkGspocqEWAnkh?from=from_copylink ))** Edit the `.env` file to configure necessary environment variables:

<details>
<summary>Click to expand details</summary>
  
> **The LLM interface in this project follows the AIHubMix platform format. It is recommended to use [AIHubMix (click here to access)](https://aihubmix.com/?aff=17EC) to obtain an API key and reduce migration costs.**<br>
> **Friendly reminder: The Google nano banana pro model interface has higher costs; please be mindful of usage expenses.**
```env

# AI Provider Format Configuration (gemini / openai / vertex)

AI_PROVIDER_FORMAT=gemini

# Gemini Format Configuration (Used when `AI_PROVIDER_FORMAT=gemini`)

GOOGLE_API_KEY=your-api-key-here
GOOGLE_API_BASE=https://generativelanguage.googleapis.com

# Proxy Example: https://aihubmix.com/gemini

# OpenAI Format Configuration (Used when AI_PROVIDER_FORMAT=openai)

OPENAI_API_KEY=your-api-key-here
OPENAI_API_BASE=https://api.openai.com/v1

# Proxy Example: https://aihubmix.com/v1

# Vertex AI Configuration (AI_PROVIDER_FORMAT=vertex)

# Requires GCP Project and Service Account Key

# VERTEX_PROJECT_ID=your-gcp-project-id

# VERTEX_LOCATION=global

# GOOGLE_APPLICATION_CREDENTIALS=./gcp-service-account.json

# Lazyllm Format Configuration (Used when AI_PROVIDER_FORMAT=lazyllm)

# Select Vendors for Text and Image Generation

TEXT_MODEL_SOURCE=deepseek        # Text generation model provider
IMAGE_MODEL_SOURCE=doubao         # Image editing model provider
IMAGE_CAPTION_MODEL_SOURCE=qwen   # Image captioning model provider

# API Keys for Various Providers (Only configure the ones you intend to use)

```env
DOUBAO_API_KEY=your-doubao-api-key            # Volcengine/Doubao
DEEPSEEK_API_KEY=your-deepseek-api-key        # DeepSeek
QWEN_API_KEY=your-qwen-api-key                # Alibaba Cloud/Tongyi Qwen
GLM_API_KEY=your-glm-api-key                  # Zhipu GLM
SILICONFLOW_API_KEY=your-siliconflow-api-key  # SiliconFlow
SENSENOVA_API_KEY=your-sensenova-api-key      # SenseTime SenseNova
MINIMAX_API_KEY=your-minimax-api-key          # MiniMax
...
```

> Banana Slides explicitly packages the LazyLLM online provider SDKs used by domestic vendors:
> `volcengine-python-sdk[ark]` for Doubao, `dashscope` for Qwen/Wanxiang, and `zhipuai` for GLM/Zhipu.
> LazyLLM also exposes `lazyllm install online-advanced`, but the PyPI wheel may not publish that group as a standard install extra, so Docker/prebuilt images rely on these explicit dependencies instead.
  
</details>


**Use the new editable export configuration method to achieve better results for editable exports**: You need to obtain an API KEY from the [Baidu Smart Cloud Platform](https://console.bce.baidu.com/iam/#/iam/apikey/list) (click here to enter) and fill it in the `BAIDU_API_KEY` field in the `.env` file (there is sufficient free usage quota). For details, see the instructions in https://github.com/Anionex/banana-slides/issues/121


<details>
  <summary>📒 Vertex AI Configuration Guide (For GCP Users)</summary>

Google Cloud Vertex AI allows calling Gemini models via GCP service accounts; new users can use trial credits. Configuration steps:

1. Go to the [GCP Console](https://console.cloud.google.com/), create a service account and download the JSON key file.
2. Save the key file as `gcp-service-account.json` in the project root directory.
3. Set the following in `.env`:
   ```env
   AI_PROVIDER_FORMAT=vertex
   VERTEX_PROJECT_ID=your-gcp-project-id
   VERTEX_LOCATION=global
   ```
4. If using Docker deployment, you also need to uncomment the relevant lines in `docker-compose.yml`, mount the key file into the container, and set the `GOOGLE_APPLICATION_CREDENTIALS` environment variable.

> `gemini-3-*` series models require `VERTEX_LOCATION=global`

</details>

2. **Start the Service**

**⚡ Use Pre-built Images (Recommended)**

The project provides pre-built frontend and backend images on Docker Hub (synced with the latest version of the main branch). You can skip the local build steps to achieve rapid deployment:

```bash

# Start with Pre-built Images (No building from scratch required)

docker compose -f docker-compose.prod.yml up -d
```

Image Names:
- `anoinex/banana-slides-frontend:latest`
- `anoinex/banana-slides-backend:latest`

After startup, you can go to **Settings → About → Check for Updates** within the application. The app will determine if an update is available based on the current version SHA; it will also use the current Git SHA for judgment when running from source code.

**Build Images from Scratch**

```bash
docker compose up -d
```


> [!TIP]
> If you encounter network issues, you can uncomment the mirror source configurations in the `.env` file and then re-run the startup command:
> ```env
> # Uncomment the following in the .env file to use China mirror sources
> DOCKER_REGISTRY=docker.1ms.run/
> GHCR_REGISTRY=ghcr.nju.edu.cn/
> APT_MIRROR=mirrors.aliyun.com
> PYPI_INDEX_URL=https://mirrors.cloud.tencent.com/pypi/simple
> NPM_REGISTRY=https://registry.npmmirror.com/
> ```


3. **Access the Application**

- Frontend: http://localhost:3011
- Backend API: http://localhost:5011

4. **View Logs**

```bash
```

# View Backend Logs (Last 200 Lines)

docker logs --tail 200 banana-slides-backend

# View Backend Logs in Real-time (Last 100 Lines)

docker logs -f --tail 100 banana-slides-backend

# View Frontend Logs (Last 100 Lines)

docker logs --tail 100 banana-slides-frontend
```

5. **Stop Services**

```bash
docker compose down
```

6. **Update Project**

**Using pre-built images (docker-compose.prod.yml)**

You can also go to **Settings → About → Check for Updates** within the application first to see if a new version is available.

```bash
docker compose -f docker-compose.prod.yml pull
docker compose -f docker-compose.prod.yml up -d
```

**Using local build (docker-compose.yml)**

Note: If you have manually modified the code, this method is not applicable. You must first revert the code to the version at the time it was pulled.

```bash
git pull 
docker compose down
docker compose build --no-cache
docker compose up -d
```

**Note: Thanks to the excellent developer friend [@ShellMonster](https://github.com/ShellMonster/) for providing the [Newbie Deployment Tutorial](https://github.com/ShellMonster/banana-slides/blob/docs-deploy-tutorial/docs/NEWBIE_DEPLOYMENT.md), which is specially designed for beginners without any server deployment experience. You can [click the link](https://github.com/ShellMonster/banana-slides/blob/docs-deploy-tutorial/docs/NEWBIE_DEPLOYMENT.md) to view it.**

### Deploy from Source

#### Environment Requirements

- Python 3.10 or higher
- [uv](https://github.com/astral-sh/uv) - Python package manager
- Node.js 16+ and npm
- [FFmpeg](https://ffmpeg.org/) - Required for exporting explanation videos; must include support for `libass` / `ass` subtitle filters
- A valid Google Gemini API key
- (Optional) [LibreOffice](https://www.libreoffice.org/) - Required when using the "PPT Renovation" feature to upload PPTX files, used for converting PPTX to PDF. **It is recommended to convert PPTX to PDF locally before uploading**. Reason: LibreOffice may cause layout misalignment during server-side rendering due to missing fonts (such as Microsoft YaHei, Calibri, etc.) and cannot fully restore some special effects. LibreOffice is not required if you upload PDF files directly. Docker users who still need to support PPTX uploads within the container can run:
  ```bash
  docker exec -it banana-slides-backend bash -c "apt-get update && apt-get install -y libreoffice-impress && rm -rf /var/lib/apt/lists/*"
  ```
  > Note: LibreOffice installed this way will be lost when the container is rebuilt and will need to be reinstalled.

#### Backend Installation

0. **Clone the repository**
```bash
git clone https://github.com/Anionex/banana-slides
cd banana-slides
```

1. **Install uv (if not already installed)**
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

2. **Install dependencies**

Run the following command in the project root directory:
```bash

# macOS (Homebrew)

brew install ffmpeg-full
brew unlink ffmpeg 2>/dev/null || true
brew link --overwrite --force ffmpeg-full

# Ubuntu / Debian

sudo apt-get update
sudo apt-get install -y ffmpeg libass9

# Then install Python dependencies

uv sync
```

This will automatically install all dependencies based on `pyproject.toml`.

3. **Configure Environment Variables**

Copy the environment variable template:
```bash
cp .env.example .env
```

# Then, following the method mentioned above, open and edit the `.env` file to configure your API key.

# 1Panel

<div align="center">
    <a href="https://1panel.cn/" target="_blank">
        <img src="https://github.com/1Panel-dev/1Panel/blob/master/frontend/src/assets/logo.png?raw=true" width="100" height="100" alt="1Panel">
    </a>
    <p>1Panel is a next-generation Linux server management panel.</p>
</div>

<p align="center">
	<a href="https://github.com/1Panel-dev/1Panel/releases"><img src="https://img.shields.io/github/v/release/1Panel-dev/1Panel?color=brightgreen&logo=github" alt="release"></a>
	<a href="https://github.com/1Panel-dev/1Panel/actions/workflows/backend.yml"><img src="https://github.com/1Panel-dev/1Panel/actions/workflows/backend.yml/badge.svg" alt="backend"></a>
	<a href="https://github.com/1Panel-dev/1Panel/actions/workflows/frontend.yml"><img src="https://github.com/1Panel-dev/1Panel/actions/workflows/frontend.yml/badge.svg" alt="frontend"></a>
	<a href="https://github.com/1Panel-dev/1Panel/stargazers"><img src="https://img.shields.io/github/stars/1Panel-dev/1Panel?logo=github" alt="stars"></a>
	<a href="https://github.com/1Panel-dev/1Panel/network/members"><img src="https://img.shields.io/github/forks/1Panel-dev/1Panel?logo=github" alt="forks"></a>
	<a href="https://github.com/1Panel-dev/1Panel/blob/master/LICENSE"><img src="https://img.shields.io/github/license/1Panel-dev/1Panel?logo=github" alt="license"></a>
</p>

---

### Core Features

* **Fast Deployment**: Quickly deploy web environments and applications via the App Store.
* **Efficient Management**: Manage Linux servers through a web interface, supporting container management, database management, file management, monitoring, and more.
* **Secure and Reliable**: Built on the principle of minimum privilege, it provides security reinforcement functions such as firewalls and Fail2ban.
* **Modern UI**: Developed with a modern front-end tech stack (Ant Design), offering an excellent user experience.

### Core Advantages

* **Efficient**: Based on Go and Vue.js, featuring low resource consumption and high performance.
* **Cloud-Native**: Full support for containerized application management (Docker / Docker Compose).
* **Rich Features**: Integrated with a local App Store for one-click installation and updates of common software.
* **Safe and Stable**: Offers open-source code, high transparency, and high security.

### One-Click Installation

#### RedHat / CentOS
```bash
curl -sSL https://resource.fit2cloud.com/1panel/package/quick_start.sh -o quick_start.sh && sh quick_start.sh
```

#### Ubuntu
```bash
curl -sSL https://resource.fit2cloud.com/1panel/package/quick_start.sh -o quick_start.sh && sudo bash quick_start.sh
```

#### Debian
```bash
curl -sSL https://resource.fit2cloud.com/1panel/package/quick_start.sh -o quick_start.sh && bash quick_start.sh
```

### Offline Installation

1. Download the 1Panel offline installation package from the [Release](https://github.com/1Panel-dev/1Panel/releases) page.
2. Upload the installation package to the target server's `/tmp` directory.
3. On the target server, extract the installation package: `tar zxvf 1panel-v1.0.0-linux-amd64.tar.gz`.
4. Enter the extracted directory: `cd 1panel-v1.0.0-linux-amd64`.
5. Run the installation script: `bash install.sh`.

### Contribution

1Panel is an open-source project, and we welcome everyone to participate in its development and contribution. If you find any issues or have any suggestions, please feel free to submit an [Issue](https://github.com/1Panel-dev/1Panel/issues) or [Pull Request](https://github.com/1Panel-dev/1Panel/pulls).

### Development Environment

If you wish to build or develop 1Panel locally, please refer to the following steps:

#### Front-end
1. Development environment: Node.js 18+, pnpm.
2. Enter the `frontend` directory and install dependencies: `pnpm install`.
3. Start the project: `pnpm run dev`.
4. Build the project: `pnpm run build`.

#### Back-end
1. Development environment: Go 1.22+.
2. Enter the root directory and download dependencies: `go mod tidy`.
3. Start the project: `go run cmd/server/main.go`.
4. Build the project: `go build -o 1panel cmd/server/main.go`.

### License

1Panel is licensed under the [GPL v3](https://github.com/1Panel-dev/1Panel/blob/master/LICENSE) license.

#### Front-end Installation

1. **Enter the frontend directory**
```bash
cd frontend
```

2. **Install dependencies**
```bash
npm install
```

3. **Configure API address**

The frontend will automatically connect to the backend service specified by `BACKEND_PORT` via Vite proxy (default `http://localhost:5011`). To modify this, please set `BACKEND_PORT` in the `.env` file at the project root.

#### Start Backend Service

> (Optional) If you have important local data, it is recommended to back up the database before upgrading:  
> `cp backend/instance/database.db backend/instance/database.db.bak`
> Note: Under the default configuration, templates, assets, and final products are stored in the `uploads/` folder.

```bash
cd backend
uv run alembic upgrade head && uv run python app.py
```

The backend service will start at `http://localhost:5011`.

Visit `http://localhost:5011/health` to verify that the service is running correctly.

#### Start the Front-end Development Server

```bash
cd frontend
npm run dev
```

The frontend development server will start at `http://localhost:3011`.

Open your browser to access and use the application.

## 🛠️ Technical Architecture

### Front-end Tech Stack

React 18 + TypeScript + Vite 5 + Zustand

### Backend Tech Stack

Python 3.10+ + Flask 3.0 + uv + SQLite

## Communication Group

Suggestions for new features or feedback are welcome. I will also answer your questions ~~at my own pace~~.

<img width="312" alt="image" src="https://github.com/user-attachments/assets/e1273f35-7539-4c5f-b737-d79213b84fed" />

Follow the author on social media, where I share information about this project and AI:

<p>
  <a href="https://x.com/anion_ex"><img src="https://img.shields.io/badge/X-@anion__ex-000000?style=flat-square&logo=x&logoColor=white" alt="X (Twitter)"></a>
  <a href="https://www.xiaohongshu.com/user/profile/62e8f580000000001902fc9d"><img src="https://img.shields.io/badge/小红书-Anion-FF2442?style=flat-square&logo=xiaohongshu&logoColor=white" alt="小红书"></a>
  <a href="https://space.bilibili.com/477162339"><img src="https://img.shields.io/badge/Bilibili-Anion-00A1D6?style=flat-square&logo=bilibili&logoColor=white" alt="Bilibili"></a>
</p>

## **🔧 Frequently Asked Questions**

See the [Official Documentation](https://docs.bananaslides.online/zh/faq)

You can also ask questions directly on DeepWiki 
<a href="https://deepwiki.com/Anionex/banana-slides"><img src="https://deepwiki.com/badge.svg" alt="Ask DeepWiki"></a>

## 🤝 Contribution Guidelines

Welcome to contribute to this project via
[Issue](https://github.com/Anionex/banana-slides/issues)
and
[Pull Request](https://github.com/Anionex/banana-slides/pulls)!

> **Important:** Please read [CONTRIBUTING.md](CONTRIBUTING.md) before contributing

## 📄 License

This project is open-sourced under the **GNU Affero General Public License v3.0 (AGPL-3.0)**. It is free to use for non-commercial purposes, such as personal learning, research, experimentation, education, or non-profit scientific research activities;

If you have any questions or are interested in cooperation, please contact: davidyang042@gmail.com



<h2>🚀 Sponsor </h2>
<br>
<div align="center">
<a href="https://aihubmix.com/?aff=17EC">
  <img src="./assets/logo_aihubmix.png" alt="AIHubMix" style="height:48px;">
</a>
<p>Thanks to AIHubMix for sponsoring this project</p>
</div>


<div align="center">

 <br>

<a href="https://api.chatfire.site/login?inviteCode=A15CD6A0"><img width="200" alt="image" src="https://github.com/user-attachments/assets/d6bd255f-ba2c-4ea3-bd90-fef292fc3397" />
</a>


Thanks to AI Huobao for sponsoring this project
 
</div>

## Acknowledgements

- Project contributors:

[![Contributors](https://contrib.rocks/image?repo=Anionex/banana-slides)](https://github.com/Anionex/banana-slides/graphs/contributors)

- [Linux.do](https://linux.do/): A new ideal community

## Sponsorship

Open source is not easy 🙏 If this project is valuable to you, feel free to buy the developer a coffee ☕️

<img width="240" alt="image" src="https://github.com/user-attachments/assets/fd7a286d-711b-445e-aecf-43e3fe356473" />

Thank you to the following friends for their generous sponsorship and support of the project:
> @雅俗共赏、@曹峥、@以年观日、@John、@胡yun星Ethan, @azazo1、@刘聪NLP、@🍟、@苍何、@万瑾、@biubiu、@law、@方源、@寒松Falcon、@刘星宇&小陀螺AIGC
> If you have any questions about the sponsorship list, please <a href="mailto:davidyang042@gmail.com">contact the author</a>

## 📈 Project Statistics

<a href="https://www.star-history.com/#Anionex/banana-slides&type=Timeline&legend=top-left">

 <picture>

   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=Anionex/banana-slides&type=Timeline&theme=dark&legend=top-left" />

   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=Anionex/banana-slides&type=Timeline&legend=top-left" />

   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=Anionex/banana-slides&type=Timeline&legend=top-left" />

 </picture>

</a>

<br>
