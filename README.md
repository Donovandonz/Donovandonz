## Hi there 👋

<!--
# 👋 Hi, I'm Donovan Donz

```python
"""
Donovan Donz – Technical Portfolio (Data, DevOps, Cloud)
Location: Malaysia
Open to: Data Analyst / DevOps / Cloud roles
"""

class DonovanDonzPortfolio:
    """
    A multi‑domain technical portfolio.
    Focus: Data analytics, DevOps pipelines, Cloud infrastructre solutions.
    """

    def __init__(self):
        self.name = "Donovan Donz"
        self.location = "Malaysia"
        self.roles = ["Data Analyst", "DevOps Enthusiast", "Cloud Practitioner"]

    # ================== DATA ANALYSIS ==================
    class DataAnalysis:
        """Tools & projects for data analytics and visualisation."""

        @staticmethod
        def tools() -> list:
            return ["Excel (Advanced)", "SQL", "Tableau", "Power BI", "Python (pandas, numpy, matplotlib, seaborn)"]

        @staticmethod
        def projects() -> dict:
            return {
                "Sales Dashboard": "Power BI + SQL – real‑time KPIs and forecasting",
                "Python Learning": "Cleaned a small dataset with pandas and made a bar chart with matplotlib",
                "Market Story": "Tableau – interactive story on gaming industry trends (public dataset)",
                "Excel Automation": "VBA macros + Power Query – automated monthly reporting"
            }

    # ================== DEVOPS ==================
    class DevOps:
        """CI/CD, containerisation, orchestration, infrastructure as code."""

        @staticmethod
        def tools() -> list:
            return ["Git/GitHub Actions", "Docker", "Kubernetes (K3s)", "Terraform (basic)", "Linux (Ubuntu)"]

        @staticmethod
        def projects() -> dict:
            return {
                "CI/CD Pipeline": "GitHub Actions → Docker Hub → self‑hosted server",
                "Home K3s Cluster": "Deployed a REST API with auto‑scaling and monitoring",
                "Terraform VM": "Provisioned a cloud VM (Oracle Cloud / Scaleway) from scratch"
            }

    # ================== CLOUD – TELEGRAM STORAGE ==================
    class CloudTelegramStorage:
        """Custom cloud solution using Telegram Bot API and object storage."""

        @staticmethod
        def description() -> str:
            return """
            A personal cloud storage system built with:
            - Python + aiogram (Telegram bot framework)
            - S3‑compatible object storage (Minio / AWS S3)
            - Docker container running on a VPS
            Features: password‑protected upload/download, temporary shareable links, auto backup.
            """

        @staticmethod
        def stack() -> list:
            return ["Python", "aiogram", "Docker", "Minio", "Telegram Bot API", "SQLite (metadata)"]

    # ================== EDUCATION ==================
    class Education:
        """Academic background (example – adapt to your real education)."""

        @staticmethod
        def degrees() -> list:
            return [
                "Bachelor’s in Computer Science (Data Analytics track) – Malaysia",
                "Professional Certifications: Google Data Analytics, AWS Cloud Practitioner (in progress)"
            ]

    # ================== WHAT I'M LOOKING FOR ==================
    @staticmethod
    def open_to() -> dict:
        return {
            "Roles": ["Data Analyst", "Data Engineer", "Junior DevOps", "Cloud Support"],
            "Commitment": "Internship / Full‑time / Freelance",
            "Availability": "Immediate",
            "Location": "Malaysia (remote or on‑site)"
        }


if __name__ == "__main__":
    me = DonovanDonzPortfolio()
    print("📊 Data tools:", me.DataAnalysis.tools())
    print("🛠️ DevOps tools:", me.DevOps.tools())
    print("☁️ Cloud stack:", me.CloudTelegramStorage.stack())
    print("🎯 Open to:", me.open_to()["Roles"])**Donovandonz/Donovandonz** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
