# githubAutoCLI
# Om-GitCLI 🧠🚀

> A natural language-powered GitHub automation CLI using OpenAI GPT-4o + GitHub REST API.

**Om-GitCLI** lets developers manage GitHub repositories, branches, commits, and analyze code using natural language commands from the terminal.

---

## 🛠 Features

👉 Translate plain English commands into GitHub actions
👉 Automate repository creation, branch management, and pull requests
👉 Push commits with messages using simple text
👉 List all repos/files/branches for a GitHub user
👉 Read and summarize code from any file in a public/private GitHub repo
👉 AI-powered understanding of GitHub/DevOps queries

---

## 💡 Example Commands

```bash
Om-Gitcli "create a private repo named my-ai-cli"
Om-Gitcli "push code to dev with message updated login route"
Om-Gitcli "list all repos for user tcoders16"
Om-Gitcli "read code from src/index.ts in repo githubAutoCLI owned by tcoders16 on branch main"
Om-Gitcli "analyze function parseCommandFromInput in openaiService.ts"
Om-Gitcli "create branch feature-xyz from dev in repo test-repo owned by tcoders16"
```

---

## 📆 Installation

### 1. Clone this repo

```bash
git clone https://github.com/tcoders16/githubAutoCLI.git
cd githubAutoCLI
```

### 2. Install dependencies

```bash
npm install
```

### 3. Set environment variables

Create a `.env` file in the root and add your keys:

```env
OPENAI_API_KEY=your-openai-key
GITHUB_TOKEN=your-github-token
```

### 4. Build the CLI

```bash
npm run build
```

### 5. Link the CLI globally

```bash
npm link
```

Now you can run:

```bash
Om-Gitcli
```

---

## 🎨 Intro UI

On first launch, you'll see an ASCII-styled banner, image (via `catimg`), intro guide, supported features, and example prompts.

---

## 🧬 How It Works

1. **Text Input →** Natural language typed into terminal
2. **OpenAI GPT-4o →** Converts to structured JSON
3. **GitHub API →** Executes GitHub operations based on parsed JSON
4. **Terminal Output →** Displays results using styled terminal UI

---

## 🦖 Tech Stack

* TypeScript + Node.js
* OpenAI GPT-4o
* GitHub REST API v3
* CLI UI: `chalk`, `boxen`, `figlet`, `ora`
* Utilities: `commander`, `dotenv`, `axios`

---

## 🧪 Future Roadmap

* ✅ Code summarization + function analysis
* 🔢 Voice-to-command integration
* 🔢 PR review summaries
* 🔢 Jenkins/GitHub Actions CI/CD integration
* 🔢 Contributor insights, branch health checks

---

## 👨‍💻 Developer

**Omkumar Solanki**
AI Engineer | MERN Dev | iOS Dev | Web3 Strategist

* GitHub: [@tcoders16](https://github.com/tcoders16)
* LinkedIn: [Omkumar Solanki](https://linkedin.com/in/omkumar-solanki-atluxuarywxtchbusinessmandeveloper2/)

---

## 📄 License

[MIT](LICENSE)

---

*Designed and developed with ♥ by Omkumar Solanki. Follow for updates.*
