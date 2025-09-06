# Welcome to InnovAIte
### The AI-Powered Startup Engine at Deakin University

**InnovAIte** is a student-led Capstone Company at Deakin University, dedicated to trialing and validating the AI tools, methods, and frameworks that will power **SPARK**—Australia's first AI-native startup engine, launching in 2026.

Our mission is to understand and demonstrate how AI can dramatically compress startup development cycles from months to days. By doing so, we aim to make entrepreneurship radically more accessible to everyone, regardless of their technical background.

---

## Our Core Programs

We operate through two foundational programs designed to explore the full spectrum of AI's potential in an entrepreneurial context.

### 🎓 AI Generalist Program
This program focuses on equipping non-technical users with the practical skills to leverage AI effectively. Through research and workshops, we create educational resources that demystify AI for academic and professional use.

*   **Key Focus Areas**: Generative AI for academic writing, AI-enhanced teaching tools, administrative automation, and prompt engineering fundamentals.
*   **Key Outputs**: We have developed functional prototypes like an AI-powered **Thesis Generator** (using Cohere), a personalized **Research Assistant web app**, and a tool for managing **AI attribution**.

### 💻 AI Prototyping Lab
This lab is a hands-on incubator for rapidly developing and testing AI-powered applications. We build Minimum Viable Products (MVPs) to prove how AI can accelerate the journey from idea to a functional prototype.

*   **Key Outputs**: We have successfully built and deployed several platforms, including:
    *   **[NoCodeJam.AI](http://nocodejam.ai/)**: A live platform for hosting AI-assisted no-code hackathons.
    *   **[InnovAIte Website](https://innovalte-deakin.web.app/)**: The central hub for our company, built with a Supabase backend.
    *   **Socratic Crumbs**: A multimodal chatbot with voice and vision capabilities for enhanced learning.
    *   **[Skill Quest Sprint](https://preview--skill-quest-sprint.lovable.app/)**: A platform for mastering new skills through 30-day guided sprints.

---

## Current Validation Projects (Trimester 2 2025)

Building on our foundation, we are currently validating a new wave of ambitious projects that span education, accessibility, and impact ventures.

1.  **Artificial Assessment Intelligence for Educators (AAIE)**: Developing a custom-trained LLM to assist educators with AI-aware assessment design and feedback.
2.  **AI Assisted Navigation Device**: Prototyping an assistive device to improve mobility and accessibility for people with disabilities.
3.  **Venture Pipeline Management System**: Designing a system to help track and support the growth of inclusive businesses in Southeast Asia.
4.  **AI Organisation Design**: Exploring how AI can transform organizational workflows, with the goal of creating a next-generation AI-powered project planner.

---

## 💻 Contribution and Collaboration Rules

To ensure our collaboration is smooth and our codebase remains clean and stable, please adhere to the following guidelines.

### 🚫 Locking the `main` Branch
The `main` branch is our source of truth and is always production-ready.
-   Direct pushes to `main` are **not allowed**.
-   All contributions must be submitted via **pull requests (PRs)**.
-   PRs merged into `main` must have at least one approved review.

### 🔁 Creating Pull Requests (PRs)
All changes—whether code, documentation, or assets—must go through a Pull Request. Every PR should:
-   Be linked to an issue or task in our project tracker (where applicable).
-   Have a clear, descriptive title and a summary of the changes.
-   Be assigned to at least one reviewer for feedback.

### 👀 Code Review Requirements
Code reviews are critical for maintaining quality.
-   Every PR must be reviewed and approved by **at least one** team member before merging.
-   Reviewers should check for:
    -   **Clarity & Maintainability**: Is the code easy to understand and build upon?
    -   **Alignment**: Does it follow our team's coding standards and conventions?
    -   **Functionality**: Does it solve the intended issue or add the feature correctly?

### 🌿 Branching Strategy
We use a feature-branch workflow to keep our `main` branch stable.
-   **✅ Always branch off from the latest `main` branch.**
-   Branch names should be descriptive and follow this convention:
    ```
    feature/[feature-name]
    fix/[issue-number]-[bug-name]
    docs/[document-name]
    release/[version-tag]
    ```
-   Once your work is complete, open a PR to merge your branch back into `main`.

---

## 🚀 How to Contribute (Fork → Commit → Pull Request)  
Follow these steps whenever you want to contribute code or documentation:

### 1. Fork the repository  
🔹 Go to the project repository on GitHub.  
🔹 Click the **Fork** button (top right) to create your own copy under your GitHub account.

### 2. Clone your fork  
```bash
git clone https://github.com/<your-username>/<repo-name>.git  
cd <repo-name>
```

### 3. Add the upstream remote (original repo)**  
This keeps your fork synced with the main project:  
```bash
git remote add upstream https://github.com/<org-name>/<repo-name>.git
```

### 4. Create a feature branch  
Always create a new branch for your work:  
```bash
git checkout -b feature/<short-description>
```

### 5. Make your changes locally  
🔹 Edit files / add new code.  
🔹 Test your changes before committing.

### 6. Stage and commit your changes  
```bash
git add .  
git commit -m "feat: add [suitable commit message]"
```
💡 Use clear, descriptive commit messages.

### 7. Push your branch to your fork  
```bash
git push origin feature/<branch>
```

### 8. Open a Pull Request (PR)  
🔹 Go to your fork on GitHub.  
🔹 Click **Compare & pull request**.  
🔹 Select the base branch as `main` in the original repo, and your branch as the compare branch.  
🔹 Add a description of what you changed and why.  
🔹 Request at least one reviewer.

✅ That’s it! Once your PR is reviewed and approved, it can be merged into the main repository.

---

### 🔐 Limiting Admin Access
To protect our repositories, access is managed strictly.
-   **Admin rights** are reserved for team leads.
-   All other team members will have **collaborator/contributor** access.
-   Each team must designate one person to hold admin access for their repository and communicate this to the leadership team.

### ✅ Best Practices
-   **💾 Commit Frequently and Meaningfully**: Small, atomic commits help us track changes. Use clear, conventional commit messages (e.g., `fix: corrected user XP calculation logic`). **Avoid vague messages** like `Updated code`.
-   **📌 Use Issues for Tracking**: Open an issue for any bug, feature request, or significant task. Use labels to categorize them (e.g., `bug`, `enhancement`, `documentation`).
-   **📚 Keep Documentation Updated**: Update the `README.md` and other relevant documentation whenever setup steps, dependencies, or workflows change.
-   **🧪 Test Locally Before Submitting a PR**: Ensure your code runs and passes all basic checks (linting, building, tests) on your local machine before opening a pull request.
-   **📬 Be Responsive**: Reply to code review comments and issue discussions promptly to keep the development process moving forward.

---

### 🧠 Data Handling and Ethics
-   **📊 Use Curated and Ethical Datasets**: Always check the source, license, and potential biases of any dataset. Document all data sources in a `DATA_SOURCES.md` file.
-   **🧼 Document Data Preprocessing**: All data cleaning and preprocessing steps must be documented in reproducible scripts.
-   **🔒 Respect Privacy**: **Never commit sensitive data**. This includes student info, API keys, or personally identifiable information. Use `.gitignore` and environment variables for secrets.
-   **⚖️ Bias and Fairness Checks**: Regularly test models for unfair outcomes across different user groups.

### 🧪 Model Development Practices
-   **🧱 Baseline First**: Always start with a simple baseline model or heuristic. This provides a benchmark to measure the performance of more complex architectures.

---

## Technology and Collaboration

Our stack includes core development technologies, major AI platforms, and a suite of innovative AI-native tools that allow for rapid prototyping.

![GitLab](https://img.shields.io/badge/GitLab-330F63?style=for-the-badge&logo=gitlab&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Google AI](https://img.shields.io/badge/Google%20AI-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97743?style=for-the-badge)
![Bolt.new](https://img.shields.io/badge/Bolt.new-1389FD?style=for-the-badge&logo=stackblitz&logoColor=white)
![Cursor](https://img.shields.io/badge/Cursor-00E393?style=for-the-badge)
![Windsurf](https://img.shields.io/badge/Windsurf-00A99D?style=for-the-badge)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)

---

All our project code and ongoing work can be explored in our public-facing repositories.

- **[Explore our Projects on GitLab](https://gitlab.deakin.edu.au/innovaite)**
- **[Watch our Demos on YouTube](https://www.youtube.com/@InnovAIteDeakin)**

We are proud to be supported by a dedicated team of academic staff and industry mentors from Deakin University and beyond.
