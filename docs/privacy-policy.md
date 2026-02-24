# Framed Leaderboard Privacy Policy

Last updated: February 24, 2026

## Overview

Framed Leaderboard is a Slack app that tracks game results posted in selected Slack channels and displays leaderboards for supported games.

## Data We Collect

The app stores the minimum data needed to operate:

- Slack workspace/team ID
- Slack channel IDs selected by admins for monitoring
- Slack user IDs and display names/real names used in leaderboards
- Game result statistics per user (wins, losses, points/weight, streaks)
- Monthly leaderboard history (including monthly winners and co-leaders)
- App installation metadata required for Slack OAuth (workspace installation record and bot token metadata)

## How We Use Data

We use stored data only to:

- Monitor selected channels for supported game result messages
- Calculate and display leaderboards in Slack
- Calculate monthly winners and monthly history
- Authorize the app in installed Slack workspaces

## Data Sharing

We do not sell data or share it with third parties except:

- Slack APIs (to operate the app)
- Hosting/infrastructure providers used to run the app (for example Heroku and Redis provider)

## Data Retention

Data is retained while the app remains installed, unless you request deletion earlier.

When the app is uninstalled or bot tokens are revoked, the app attempts to delete workspace-specific leaderboard and installation data automatically.

## Security

We use secrets and tokens provided by Slack and environment-based credentials for infrastructure services. Access is limited to operating the app.

No system can guarantee absolute security, but we aim to use reasonable safeguards appropriate for a small Slack app service.

## Your Choices / Deletion Requests

Workspace admins can request deletion of workspace data by contacting support (see Support page/contact).

Please include:

- Workspace name
- Workspace/team ID (if available)
- Confirmation you are a workspace admin

## Changes to This Policy

We may update this policy from time to time. Material changes will be reflected by updating the "Last updated" date.

## Contact

For privacy questions or deletion requests, contact:

- jmichealmurphy@gmail.com
