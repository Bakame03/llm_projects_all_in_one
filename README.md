# Bakame03's AI Engineering Journey 🚀

A comprehensive collection of LLM projects, exercises, and clean code from my learning roadmap.

## 🎯 About This Repository
This repository tracks my progression from AI Enthusiast to AI Engineer. It serves as a central hub for my code, API integrations, and practical exercises, focusing on building scalable and clean AI applications.

## 🛠️ Tech Stack
* **Languages:** Python
* **Environment Management:** `uv` (Lightning-fast package manager)
* **Models & APIs:** Google AI Studio (Gemini Models), OpenAI API compatibility
* **Tools:** Jupyter Notebooks, Cursor/Antigravity(my favorite) IDE

## 📂 Projects & Exercises
| Project | Description | Status |
| :--- | :--- | :--- |
| `01_api_setup` | Setting up the `uv` environment and testing the Gemini API. | ✅ Done |
| `02_website_summarizer` | Extracting website content via web scraping and using a Frontier LLM (Gemini) with System/User prompts to generate smart markdown summaries. | ✅ Done |
| `03_tokenization_and_llm_memory` | Exploring subword tokenization with `tiktoken` and handling the stateless nature of APIs by building conversational memory. | ✅ Done |
| `04_brochure_generator_and_llm_chaining` | Building a business solution by chaining LLM calls, enforcing structured JSON outputs for decision making, and implementing response streaming. | ✅ Done |
| `05_coming_soon` | More advanced AI engineering projects are on the way. Stay tuned! 🚀 | ⏳ Planned |

## 🚀 How to Run Locally

Follow these straightforward steps to set up the project on your machine (PC, Mac, or Linux).

### Step 1: Clone the Repository
Open your terminal or command prompt and run:
```bash
git clone [https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git](https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git)
cd YOUR-REPO-NAME
```
*(Note: Replace `YOUR-USERNAME/YOUR-REPO-NAME` with your actual GitHub repository link).*

### Step 2: Install `uv` (The Blazingly Fast Package Manager)
This project uses `uv` to manage Python environments effortlessly. 
* Install it by following the official guide: [uv installation](https://docs.astral.sh/uv/getting-started/installation/)
* Once installed, restart your terminal and verify it works by typing: `uv --version`

### Step 3: Install Dependencies
You don't need to manually create a virtual environment; `uv` handles it automatically! Just run this single command in your project root:
```bash
uv sync
```
This will instantly set up the `.venv` folder and install all required packages (Jupyter, python-dotenv, openai, etc.).

### Step 4: Configure Your API Key
1. In the root directory of the project, create a new file and name it **EXACTLY** `.env` (nothing before the dot, nothing after the "v").
2. Add your Google AI Studio API key to this file like so:
   ```text
   GOOGLE_API_KEY=your_actual_api_key_here
   ```
3. **Save the file!**

### Step 5: IDE Setup & Running the Code (Cursor, VS Code or Antigravity)
1. Open the project folder in Antigravity (or VS Code).
2. Go to the **Extensions** tab and ensure you have both the **Python** (by Microsoft) and **Jupyter** (by Microsoft) extensions installed.
3. Open any `.ipynb` notebook file (like `day1.ipynb`).
4. Click **Select Kernel** in the top right corner.
5. Choose **Python Environments...** and select the kernel marked with a star: `.venv (Python 3.12.x) .venv/bin/python`.

You are now ready to hit `Shift + Enter` and run the AI projects!
