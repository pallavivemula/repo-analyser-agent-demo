# 🚀 GitHub Repo Analyser Agent

A simple, interactive web application that analyses public GitHub repositories and displays important repository information in a clean, modern dashboard.

## 📌 Project Overview

The **GitHub Repo Analyser Agent** helps developers quickly understand a GitHub repository without manually navigating through multiple pages.

Users can enter a public GitHub repository URL to view repository statistics, programming languages, recent commits, contributors, and README content.

## ✨ Features

- 🔗 **Repository Search:** Analyse repositories using their GitHub URL.
- ⭐ **Repository Statistics:** View stars, forks, and open issues.
- 💻 **Language Analysis:** Display programming languages used in the repository.
- ⚡ **Recent Commits:** View the latest commits, authors, and dates.
- 🧑‍💻 **Top Contributors:** Display contributors and their contribution counts.
- 📘 **README Preview:** Read repository documentation directly in the dashboard.
- 📊 **Repository Snapshot:** View the primary language, default branch, creation date, license, and topics.
- 🎨 **Modern UI:** Responsive dark-themed interface.
- ⚠️ **Error Handling:** Display helpful messages for invalid URLs, missing repositories, and API errors.

## 🛠️ Technologies Used

- **HTML5** — Web page structure.
- **CSS3** — Styling and responsive design.
- **JavaScript** — Application logic and dynamic content.
- **GitHub REST API** — Retrieves public repository information.

## 📂 Project Structure

```text
repo-analyser-agent/
├── index.html       # Main application
└── README.md        # Project documentation
```

## 🚀 Getting Started

### Prerequisites

- A web browser such as Chrome or Edge.
- Visual Studio Code (recommended).
- An internet connection.

### Installation

**Step 1: Clone the repository**

```bash
git clone https://github.com/YOUR-USERNAME/repo-analyser-agent.git
```

Replace `YOUR-USERNAME` with your GitHub username.

**Step 2: Open the project folder**

```bash
cd repo-analyser-agent
```

**Step 3: Run the application**

Open `index.html` in your browser, or open the folder in Visual Studio Code and run it using the Live Server extension.

### Usage

1. Launch the application.
2. Enter a public GitHub repository URL.
3. Click **Analyse Repository**.
4. Explore the repository statistics and analysis sections.

Example repository:

```text
https://github.com/octocat/Hello-World
```

## 🔌 API Integration

The application uses the GitHub REST API to retrieve information about public repositories.

Example API endpoint:

```text
https://api.github.com/repos/octocat/Hello-World
```

Other endpoints provide language statistics, commits, contributors, and README information.

**Note:** Unauthenticated GitHub API requests have rate limits. If the limit is reached, wait before trying again.

## 🔒 Limitations

- The current version supports public repositories.
- Repository information requires an internet connection.
- API rate limits may temporarily prevent requests.
- The application displays repository information but does not yet use an AI model for advanced code analysis.
- Security vulnerability scanning and automated code-quality recommendations are not currently implemented.

## 🔮 Future Enhancements

- Integrate an AI model to explain repository code.
- Generate automated code-quality reports.
- Detect potential security issues using appropriate scanning tools.
- Analyse project structure and dependencies.
- Add downloadable analysis reports.
- Introduce GitHub authentication for supported private-repository workflows.

## 🎯 Project Objective

The main objective is to simplify GitHub repository exploration by presenting essential repository information in one accessible dashboard.

## 👩‍💻 Author

**Your Name**

GitHub: `https://github.com/YOUR-USERNAME`

## 📄 License

This project can be distributed under the MIT License if you choose to use those terms. Add a `LICENSE` file to the repository to apply the license formally.
