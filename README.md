# Resume Maxxer🧏🏻‍♂️

AI-Driven No-Code Resume Optimization Tool Built with n8n Automation

---

## 🚀 Overview

Resume Maxxer🧏🏻‍♂️ is an end-to-end, AI-powered workflow for automating resume rewriting and optimization. Built using the no-code platform n8n, this project integrates multiple APIs (OpenAI Gemini, Gmail, Airtable, GitHub, Overleaf) to dynamically tailor and deliver ATS-friendly resumes based on user-submitted job descriptions.

---

## 💡 Key Features

- **AI-Powered Keyword Enhancement:** Automatically rewrites your resume for each job description using state-of-the-art LLMs.
- **No-Code, API-First Design:** Seamless integration with OpenAI Gemini, Gmail, Airtable, GitHub, and Overleaf through n8n.
- **One-Click Automation:** Users upload their resume and job description—everything else is handled for them.
- **LaTeX Formatting:** Outputs resume in polished LaTeX Overleaf template.
- **Instant Email Delivery:** Resumes are emailed directly to the user.
- **Scalable Data Flow:** Tracks and manages user data and jobs in Airtable.
- **Community Proof:** Supported 150+ users in placement season in just 2 weeks.

---

## 🛠️ Technologies & Integrations

- **n8n (No-code Automation)**
- **OpenAI Gemini API**
- **Google Gmail API**
- **Airtable API**
- **GitHub API**
- **Overleaf API**

---

## 🌐 How It Works

1. **User Triggers Workflow:** User uploads their resume and job description through an n8n web form.
2. **Gemini JD & OCR:** The Gemini AI analyzes the JD, performs OCR on the resume, and extracts their content.
3. **Deep Research:** AI runs background research on the role and company for smarter keyword/context selection.
4. **Resume Rewriting:** OpenAI intelligently rewrites your resume, optimizing for the job while preserving your authentic experience.
5. **LaTeX Rendering:** Another model converts the new content into LaTeX, embedding it in a pre-built Overleaf template.
6. **GitHub API Upload:** The LaTeX file is pushed to a public GitHub repo.
7. **Overleaf Project Creation:** Overleaf API creates a live project using the hosted LaTeX code.
8. **Automated Email:** The completed Overleaf resume link is sent to the user by email along with further editing instructions.

---

## 📁 Repository Contents

- **/workflow/** – n8n workflow JSONs
- **/docs/** – Setup guide, usage instructions
- **/samples/** – Sample resumes and LaTeX templates
- Screenshots and architecture diagrams

---

## 🚦 Deployment & Usage

1. Download the workflow JSON file from this repository.
2. Import the JSON file into your n8n instance.
3. Set up and update all required API keys (OpenAI Gemini, Gmail, Airtable, GitHub, Overleaf) in your environment or n8n credentials.
4. Create a new Airtable base with all the required fields as documented.
5. Run the workflow—users can now submit their resume and job description, and the automation takes care of the rest.
6. Track usage, logs, and analytics conveniently in your Airtable dashboard.


---

## 🤝 Contribution

- Open to PRs, feature requests, issue reporting, and fork-based customization.
- Please raise an issue if you have ideas for new integrations or features.

---

## 📜 License

This project is licensed under the MIT License. See [LICENSE](./LICENSE) for more.

---

