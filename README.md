# LBRCE Attendance Bot

## Overview
Automated attendance tracking bot for LBRCE ERP system with Telegram notifications and GitHub Actions scheduling (7AM & 4PM IST).

## Features
- ✅ Automated attendance tracking from LBRCE ERP system
- ✅ Telegram notifications with subject-wise attendance
- ✅ Absence detection and alerts
- ✅ GitHub Actions scheduling (7 AM & 4 PM IST)
- ✅ Attendance history stored in GitHub

## Setup
1. Fork or clone this repository
2. Add repository secrets:
   - `ERP_USERNAME`
   - `ERP_PASSWORD`
   - `BOT_TOKEN` (Telegram bot token)
   - `CHAT_ID` (Your Telegram chat ID)
   - `GH_TOKEN` (GitHub personal access token)
3. The bot will automatically run at scheduled times

## Technologies
- Python 3.11
- Selenium (Web scraping)
- BeautifulSoup4 (HTML parsing)
- Telegram Bot API
- GitHub Actions
