# 🛡️ Smart Tourist Safety Monitoring & Incident Response System

A web-based platform for ensuring tourist safety using **Blockchain, AI, Geo-fencing, and Real-time Dashboards**. 
Built for **SIH 2025 (Internal Hackathon Prototype)**. 

🔗 Repo: [smart-tourist-safety](https://github.com/Sinchana-N25/smart-tourist-safety)

---

## 🚀 Features

- **Blockchain Digital ID**: Secure tourist identity with KYC-lite data, valid only for the trip duration. 
- **AI Anomaly Detection**: Flags unusual movement, inactivity, or risky zone entry. 
- **Police Dashboard**: Real-time heatmaps, alert logs, digital ID verification, and auto E-FIR generation. 
- **Weather Alerts**: Integration with APIs to notify about hazardous weather conditions. 
- **Secure & Scalable**: End-to-end encryption, JWT auth, modular architecture. 

---

## 🛠 Contributing & Git Workflow

We follow a **feature branch → dev → main** workflow.

- **main** → always stable, production-ready code. 
- **dev** → integration branch (all features are merged here first). 
- **feature branches** → each member works on their own branch (e.g., `frontend-setup`, `backend-api`, `ai-anomaly`). 

### Steps to Contribute

1.  **Clone repo (first time only):**
    ```bash
    git clone [https://github.com/Sinchana-N25/smart-tourist-safety.git](https://github.com/Sinchana-N25/smart-tourist-safety.git)
    cd smart-tourist-safety
    git checkout dev
    ```

2.  **Create your feature branch (from dev):**
    ```bash
    git checkout dev
    git pull origin dev     # sync with latest dev
    git checkout -b feature/<your-feature-name>
    ```

    **Example:**
    ```bash
    git checkout -b feature/frontend-login
    ```

3.  **Make your changes & commit:**
    ```bash
    git add .
    git commit -m "Added login page UI"
    ```

4.  **Push your branch to GitHub:**
    ```bash
    git push origin feature/frontend-login
    ```

5.  **Open a Pull Request (PR):**
    - Go to GitHub → “Compare & Pull Request”.
    - Target branch = `dev`.
    - Wait for review/approval.

6.  **Merging to `main`:**
    - Only repo admins will merge `dev` → `main` after testing.

### 📌 Notes

- Don’t commit directly to `main`.
- Always pull the latest `dev` before starting new work.
- Keep commits clean & meaningful.
- For setup help, check `docs/` or ask in the team channel.
