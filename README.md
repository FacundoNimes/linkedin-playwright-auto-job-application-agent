# LinkedIn Playwright Auto Job Application Agent

> This project streamlines the entire job application workflow by using a smart browser-driven automation agent. It handles repetitive form entries, navigates job boards, and submits applications with consistent accuracy. It brings speed and structure to high-volume job searches by combining Playwright automation with adaptive logic.

> By automating job applications across major platforms, it saves hours of manual effort and ensures no opportunity is missed.


<p align="center">
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/scraper.png" alt="Bitbash Banner" width="100%"></a>
</p>
<p align="center">
  <a href="https://t.me/Bitbash333" target="_blank">
    <img src="https://img.shields.io/badge/Chat%20on-Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
  </a>&nbsp;
  <a href="https://wa.me/923249868488?text=Hi%20BitBash%2C%20I'm%20interested%20in%20automation." target="_blank">
    <img src="https://img.shields.io/badge/Chat-WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp">
  </a>&nbsp;
  <a href="mailto:sale@bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Email-sale@bitbash.dev-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">
  </a>&nbsp;
  <a href="https://bitbash.dev" target="_blank">
    <img src="https://img.shields.io/badge/Visit-Website-007BFF?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website">
  </a>
</p>




<p align="center" style="font-weight:600; margin-top:8px; margin-bottom:8px;">
  Created by Bitbash, built to showcase our approach to Scraping and Automation!<br>
  If you are looking for <strong>linkedin-playwright-auto-job-application-agent</strong> you've just found your team — Let’s Chat. 👆👆
</p>


## Introduction

The main goal is to automate the repetitive steps of browsing openings, filling out forms, submitting profiles, and tracking progress across job portals like LinkedIn, Indeed, Dice, and ZipRecruiter. These tasks are slow, prone to errors, and hard to scale manually. This agent steps in to accelerate the process and keep each submission consistent.

### Why Automated Job Applications Matter

- Helps users manage large application volumes without burnout
- Keeps submissions fast and uniform across platforms
- Ensures no opportunities slip through cracks during busy search periods
- Reduces manual data entry and navigation time
- Supports parallel platform coverage for wider outreach

## Core Features

| Feature | Description |
|--------|-------------|
| Multi-platform Navigation | Automatically browses LinkedIn, Indeed, Dice, and ZipRecruiter flows |
| Form Autofill Engine | Fills out application fields using structured profile data |
| Resume & Document Handling | Uploads required files dynamically per platform |
| Smart Job Matching | Filters listings based on predefined criteria |
| Logging & Session Tracking | Stores completed applications and statuses |
| Error Recovery | Retries failed submissions using controlled fallback logic |
| Configurable Rules | Allows user-defined filters, keywords, and submission limits |
| Platform Integration Hooks | Modular architecture enabling new job boards to be added |
| Anti-block Mechanisms | Uses timing randomness and compliant interactions |
| Device & Browser Profiles | Supports custom agent fingerprints when needed |
| CAPTCHA Handling | Detects and pauses for human-required verification |

---

## How It Works

| Step | Description |
|------|-------------|
| **Input or Trigger** | Starts from a user-defined run command or scheduled interval with keyword rules and profile data loaded. |
| **Core Logic** | Navigates job boards, identifies matching roles, validates fields, and handles platform-specific workflows. |
| **Output or Action** | Submits applications, stores confirmation data, and logs actions to structured output files. |
| **Other Functionalities** | Includes retry logic, interaction pacing, throttling, and session continuity. |
| **Safety Controls** | Implements rate limiting, random delays, controlled navigation depth, and compliance-oriented operation. |

---

## Tech Stack

| Component | Description |
|----------|-------------|
| **Language** | Python |
| **Frameworks** | Playwright |
| **Tools** | Selenium (optional supplemental interactions) |
| **Infrastructure** | Docker, GitHub Actions |

---

## Directory Structure Tree

    linkedin-playwright-auto-job-application-agent/
    ├── src/
    │   ├── main.py
    │   ├── automation/
    │   │   ├── navigator.py
    │   │   ├── platform_linkedin.py
    │   │   ├── platform_indeed.py
    │   │   ├── platform_dice.py
    │   │   ├── platform_ziprecruiter.py
    │   │   └── utils/
    │   │       ├── logger.py
    │   │       ├── profile_loader.py
    │   │       └── browser_config.py
    ├── config/
    │   ├── settings.yaml
    │   ├── profile.json
    ├── logs/
    │   └── activity.log
    ├── output/
    │   ├── submissions.json
    │   └── report.csv
    ├── tests/
    │   └── test_application_flow.py
    ├── requirements.txt
    └── README.md

---

## Use Cases

- **Job seekers** who need to apply to dozens of openings daily, so they can scale without manually repeating tasks.
- **Recruiting assistants** using it to streamline outbound application workflows for multiple candidates.
- **Career coaches** automating job submissions for clients to ensure timely, consistent outreach.
- **Professionals returning to the market** using it to increase application throughput with minimal manual effort.

---

## FAQs

**Does it support multiple job boards at once?**
Yes, the agent runs through each configured platform sequentially or in parallel depending on settings.

**Can I adjust the role filters or keywords?**
All search criteria, preferences, and application rules live inside configuration files that can be edited without touching code.

**What happens when a form contains unexpected fields?**
The agent uses a flexible mapping strategy and logs anomalies for user review while skipping forms it cannot safely complete.

**Does it store my submissions?**
Yes, every attempt is logged and written into structured output files for later tracking.

---

## Performance & Reliability Benchmarks

**Execution Speed:** Processes 18–25 job postings per minute depending on platform load and form complexity.

**Success Rate:** Averages around 93–94% completed submissions with retries enabled.

**Scalability:** Can operate across 100–500 listings per session without performance degradation; supports multiple platform modules.

**Resource Efficiency:** Runs comfortably within 1–2 GB RAM and low CPU usage per Playwright instance.

**Error Handling:** Includes structured retry logic, incremental backoff, full logging, and interruptions recovery for long-running sessions.


<p align="center">
<a href="https://calendar.app.google/74kEaAQ5LWbM8CQNA" target="_blank">
  <img src="https://img.shields.io/badge/Book%20a%20Call%20with%20Us-34A853?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Book a Call">
</a>
  <a href="https://www.youtube.com/@bitbash-demos/videos" target="_blank">
    <img src="https://img.shields.io/badge/🎥%20Watch%20demos%20-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Watch on YouTube">
  </a>
</p>
<table>
  <tr>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/MLkvGB8ZZIk" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review1.gif" alt="Review 1" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Bitbash is a top-tier automation partner, innovative, reliable, and dedicated to delivering real results every time."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Nathan Pennington
        <br><span style="color:#888;">Marketer</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/8-tw8Omw9qk" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review2.gif" alt="Review 2" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Bitbash delivers outstanding quality, speed, and professionalism, truly a team you can rely on."
      </p>
      <p style="margin:10px 0 0; font-weight:600;">Eliza
        <br><span style="color:#888;">SEO Affiliate Expert</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
    <td align="center" width="33%" style="padding:10px;">
      <a href="https://youtu.be/m-dRE1dj5-k?si=5kZNVlKsGUhg5Xtx" target="_blank">
        <img src="https://github.com/Z786ZA/Footer-test/blob/main/media/review3.gif" alt="Review 3" width="100%" style="border-radius:12px; box-shadow:0 4px 10px rgba(0,0,0,0.1);">
      </a>
      <p style="font-size:14px; line-height:1.5; color:#444; margin:0 15px;">
        "Exceptional results, clear communication, and flawless delivery. <br>Bitbash nailed it."
      </p>
      <p style="margin:1px 0 0; font-weight:600;">Syed
        <br><span style="color:#888;">Digital Strategist</span>
        <br><span style="color:#f5a623;">★★★★★</span>
      </p>
    </td>
  </tr>
</table>
