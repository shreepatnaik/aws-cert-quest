# 🎯 AWS ML Certification Quest

A gamified 6-week study tracker for the **AWS Certified Machine Learning Engineer – Associate (MLA-C01)** exam.

![AWS ML Quest](https://img.shields.io/badge/AWS-ML_Engineer_Associate-FF9900?style=for-the-badge&logo=amazon-aws)
![Status](https://img.shields.io/badge/Status-In_Progress-blue?style=for-the-badge)

## 🚀 Live Demo

**[https://shreepatnaik.github.io/aws-cert-quest/](https://shreepatnaik.github.io/aws-cert-quest/)**

## ✨ Features

- **Click-to-complete quests** — 30 daily tasks across 6 weeks
- **XP & Leveling system** — Recruit → Cadet → Apprentice → ... → AWS Warrior
- **12 Achievements** — Unlock badges for streaks, milestones, and boss fights
- **Streak tracking** — Keep your study streak alive
- **Progress persists** — Uses localStorage, survives browser restarts
- **Confetti celebrations** — Because you deserve it
- **Mobile-friendly** — Study on the go
- **Zero dependencies** — Single HTML file, React via CDN

## 📋 Study Plan

| Week | Focus | Exam Weight |
|------|-------|-------------|
| 1 | AWS Foundations + Data Preparation | 28% |
| 2 | Data Prep + Model Dev Intro | 26% |
| 3 | ML Model Development | 26% |
| 4 | Deployment + Monitoring | 22% + 24% |
| 5 | Practice Exams + Weak Areas | All |
| 6 | Final Review + EXAM DAY | All |

## 🛠️ Setup

No build step needed. It's a single `index.html` file.

### Host on GitHub Pages

1. Create a new repo (e.g., `aws-cert-quest`)
2. Upload `index.html` to the repo
3. Go to **Settings → Pages → Source → Deploy from branch → main**
4. Your tracker will be live at `https://<username>.github.io/aws-cert-quest/`

### Run locally

```bash
# Just open the file
open index.html

# Or use a local server
python -m http.server 8000
# Then visit http://localhost:8000
```

## 📊 Exam Details

| Detail | Info |
|--------|------|
| Exam Code | MLA-C01 |
| Cost | $150 USD |
| Duration | 170 minutes, 65 questions |
| Passing Score | 720 / 1000 |
| Format | Multiple choice + multiple response |

## 📚 Recommended Resources

- [Stephane Maarek + Frank Kane Udemy Course](https://www.udemy.com/course/aws-certified-machine-learning-engineer-associate-mla-c01/) (~$15 on sale)
- [Tutorials Dojo Practice Exams](https://portal.tutorialsdojo.com/courses/aws-certified-machine-learning-engineer-associate-mla-c01-practice-exams/) (~$15)
- [AWS Skill Builder Free Plan](https://skillbuilder.aws)
- [SageMaker Studio Lab](https://studiolab.sagemaker.aws) (Free, no AWS account needed)

## 📝 License

MIT — Feel free to fork and customize for your own certification journey.
