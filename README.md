<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=WerList99&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32&desc=Developer%20|%20Tech%20Blogger%20|%20Firefox%20Extension%20Maker&descSize=16&descAlignY=52" width="100%"/>
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=3B82F6&center=true&vCenter=true&random=false&width=600&lines=Building+Firefox+Extensions+%F0%9F%A6%8A;Writing+Python+Tools+%F0%9F%90%8D;Blogging+About+Windows+%26+Tech+%E2%9C%8D%EF%B8%8F;Open+Source+Contributor+%F0%9F%9A%80)](https://git.io/typing-svg)
[![Blog](https://img.shields.io/badge/Blog-werlist99-FF5722?style=for-the-badge&logo=blogger&logoColor=white)](https://werlist99.blogspot.com/)
[![AMO](https://img.shields.io/badge/Firefox_Add--ons-AMO-FF7139?style=for-the-badge&logo=firefox&logoColor=white)](https://addons.mozilla.org/en-US/firefox/user/19705561/)
[![Extensions Hub](https://img.shields.io/badge/Extensions_Hub-extefw99-4285F4?style=for-the-badge&logo=blogger&logoColor=white)](https://extefw99.blogspot.com/)
[![Telegram](https://img.shields.io/badge/Telegram-@werlist99-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/werlist99)
</div>
---
## 👨‍💻 About Me
```yaml
name: WerList99
location: Morocco 🇲🇦
roles:
- Firefox Extension Developer
- Python Desktop App Developer
  - Tech Blogger & Content Creator
currently_working_on:
  - OmniSend Pro (Multi-channel messaging tool)
  - Firefox WebExtensions for Mozilla AMO
  - Windows optimization guides
learning:
  - Advanced Python (asyncio, packaging)
  - Browser extension APIs
  - SEO & content marketing
fun_fact: "I automate everything I do more than twice"
🚀 What I Do
🦊 Firefox Extensions
Building and publishing WebExtensions on Mozilla AMO. Privacy tools, productivity add-ons, and browser utilities.

🐍 Python Development
Desktop applications with CustomTkinter, automation scripts, bulk messaging tools, and utilities.

✍️ Tech Blogging
Windows optimization guides, troubleshooting tutorials, software reviews, and productivity tips.

📦 Open Source
Sharing tools, scripts, and projects on GitHub. Contributing to the developer community.

🛠️ Tech Stack
Languages & Frameworks
Python JavaScript HTML5 CSS3 JSON Markdown

Tools & Platforms
Firefox Windows Git GitHub VS Code Blogger

Messaging & APIs
SMTP Telegram API WhatsApp Twilio

📌 Featured Projects
#	Project	Description	Tech	Stars
🚀
OmniSend Pro
Multi-channel bulk messaging (Email, WhatsApp, SMS, Telegram)
Python
Stars
🦊
Firefox Extensions
WebExtensions published on Mozilla AMO
JS
View on AMO
✍️
Tech Blog
Windows optimization & troubleshooting guides
Blogger
—
📦
Extensions Hub
Firefox add-ons catalog & documentation
Web
—
📊 GitHub Stats
  
📈 Activity Graph
Activity Graph

🏆 GitHub Trophies
Trophies

🐍 Contribution Snake
Snake animation
💡 Random Dev Quote
Quote

💡 "Fix it, automate it, write about it."

Profile Views
```
For the Snake Animation to work:
Create a file at .github/workflows/snake.yml in your zougar99 repo with this content:

name: Generate Snake
on:
schedule:
- cron: "0 0 * * *"
workflow_dispatch:
jobs:
build:
runs-on: ubuntu-latest
steps:
- uses: Platane/snk@v3
with:
github_user_name: zougar99
outputs: |
dist/github-snake-dark.svg?palette=github-dark
- uses: crazy-max/ghaction-github-pages@v3.1.0
with:
target_branch: output
build_dir: dist
env:
GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
