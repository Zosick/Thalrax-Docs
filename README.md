# Thalrax Documentation

Welcome to the official documentation hub for **Thalrax**, a private, high-performance Discord bot designed for advanced server security, moderation, and comprehensive logging.

## 🛡️ Core Security Features

Thalrax includes a suite of automated modules designed to protect your community:

* **Anti-Hijack**: The "Internal Affairs" unit. It monitors audit logs for suspicious administrative actions (e.g., unauthorized role grants, dangerous permission changes) and automatically reverts them. It also includes **Anti-Nuke** protection to detect and ban users attempting mass destruction (channels/bans).
* **Anti-Link**: Protects the server from scams and malicious sites using the **Google Safe Browsing API** and **URLhaus** database. It can also block unauthorized Discord invites.
* **Anti-Raid**: Automatically kicks accounts that are too new (minimum age check) or detects high-velocity join spikes to prevent bot raids.
* **Anti-Spam**: Intelligent rate-limiting that mutes users who spam messages or mass-mention users/roles.
* **Security Audit**: A diagnostic tool that scans your server for vulnerabilities (insecure permissions, dangerous roles, risky webhooks) and can automatically fix them.

## ⚙️ Moderation & Management

* **Verification Gate**: A two-step verification system requiring new members to solve a CAPTCHA and agree to server rules before gaining access.
* **Interactive Settings**: All configurations are managed via a GUI-based panel (`/settings-panel`), allowing admins to toggle modules and set log channels easily.
* **Whitelisting**: Robust immunity system allowing specific roles or channels to bypass security checks.

## 📝 Logging System

Thalrax provides detailed audit logs for server events:
* **Ghost Ping Detection**: Logs deleted messages that mentioned users.
* **Message Audit**: Logs message edits and deletions.
* **Member Activity**: Logs joins, leaves, and voice channel activity.
* **Server Changes**: Logs role updates and channel modifications.

## ⚖️ Legal Documents

By using Thalrax, you agree to the following terms:

* [**Terms of Service**](tos.html) - Rules regarding the usage of the bot.
* [**Privacy Policy**](privacy.html) - Details on data collection (IDs, logs) and retention.

## 📞 Contact

For support, inquiries, or to report issues, please contact the developer at:
`thalraxdev.zset0@passinbox.com`
