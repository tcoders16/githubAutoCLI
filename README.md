Om-GitAI: Conversational GitHub Automation CLI

Om-GitAI is a powerful AI-powered command-line tool that allows developers to interact with GitHub using natural language. Built with TypeScript, OpenAI GPT-4o, and GitHub REST APIs, this CLI enables voice-like DevOps workflows.

🚀 What is Om-GitAI?

Om-GitAI is your AI assistant for automating GitHub workflows directly from the terminal. Just speak to it in plain English:

Om-GitAI "create a private repo named ai-pipeline"

Om-GitAI will parse your instruction, generate a structured JSON command using GPT-4o, and perform the GitHub operation using secure API requests.

⸻

💡 Why Use Om-GitAI?
	•	Eliminate repetitive GitHub tasks
	•	No need to remember GitHub CLI commands or REST API endpoints
	•	Focus more on code, less on DevOps overhead
	•	Boost developer productivity with LLM-powered command execution

⸻

🛠 Supported Commands

You can execute tasks like:
	•	✅ Create repositories (public/private)
	•	✅ Push code to branches with commit messages
	•	✅ Create new branches from source branches
	•	✅ Open pull requests between branches
	•	✅ List all your GitHub repositories
	•	✅ Analyze any file’s content or functions using AI
	•	✅ Read code from any file in a GitHub repo
	•	✅ Look over recent commits and functions
	•	✅ Answer DevOps, GitHub, or code-related questions

⸻

🧠 How It Works
	1.	You input a natural language command
	2.	GPT-4o transforms it into a structured JSON action
	3.	The CLI securely executes the GitHub API request

Example:

Om-GitAI "create a pull request from dev to main in repo github-cli titled Add auth layer"


⸻

🔍 Complex Prompt Examples

Om-GitAI "read code from src/index.ts in today repo on branch 28-May"
Om-GitAI "summarize what the utils/logger.ts file does in repo githubAutoCLI"
Om-GitAI "what functions are defined in api.js on branch staging"
Om-GitAI "create a new branch feature/payment from main in repo checkout-api"


⸻

🧪 Use Cases
	•	🚀 Launch GitHub repos with one-line prompts
	•	📄 Understand legacy project code with summaries
	•	🔧 Debug quickly by searching code functions via prompt
	•	💬 Ask AI questions like “how to trigger deploy from GitHub?”
	•	🎯 Analyze active pull requests and contributors

⸻

🧰 Tech Stack
	•	🧠 OpenAI GPT-4o
	•	🔧 TypeScript
	•	📦 Node.js
	•	📡 GitHub REST API
	•	🎨 Chalk, Boxen, Figlet for CLI UI
	•	📁 Axios, dotenv, commander, fs

⸻

⚙ Installation

npm install -g githubautocli

Make sure to:
	•	Add your .env with a valid OPENAI_API_KEY and GITHUB_TOKEN

OPENAI_API_KEY=your_openai_key_here
GITHUB_TOKEN=your_github_token_here


⸻

🧭 Getting Started

To initiate the CLI with its boot message and branding:

Om-GitAI

Once initialized, you can run any command like:

Om-GitAI "list all repositories for user omkumarsolanki"


⸻

👤 Author

Omkumar Solanki
AI Engineer | Full-Stack Dev | iOS + Web3 Enthusiast
🔗 GitHub • LinkedIn

⸻

📜 License

MIT License © 2024 Omkumar Solanki

⸻

