---
permalink: /privacy.html
---
# Privacy Policy — PR Screenshot Reviewer

_Last updated: 2026-09-21_

PR Screenshot Reviewer ("the app") is developed by Pavel Vanecek. This policy explains what happens to your
data when you use it. Short version: **the developer collects no personal data.** The app talks to GitHub on
your behalf, and the data it handles goes only to GitHub.

## What the developer collects

No personal data. The app has no analytics, advertising, tracking or crash-reporting services, and no
account system. No data is sent to the developer or to any third party other than GitHub.

## Data the app handles on your device

To work, the app uses the following, and it stays on your device except when sent to GitHub:

- **GitHub access token.** Obtained when you sign in with GitHub (device flow, `public_repo` scope). Stored
  encrypted with the Android Keystore. Used only to call GitHub's API.
- **GitHub username and pull request authors' usernames and avatars**, received from GitHub and shown in
  the app. Avatar images are loaded from GitHub's servers.
- **Repository setting** you enter (owner/name) and app preferences.
- **Cached GitHub content**: pull request metadata, changed image files and HTTP cache tags, so the app
  loads faster and works offline.
- **Pending actions** (for example a review or comment written while offline), held until they are sent to
  GitHub.

The GitHub username, access token and the reviews and comments you write are sent to GitHub only, to provide
the app's functionality. The developer never receives them, and they are not sold or shared with anyone else.

Android backup is disabled, so none of this is copied to cloud backups.

## Communication with GitHub

The app connects to `github.com`, `api.github.com` and `raw.githubusercontent.com`. Reviews and
comments you submit are published to GitHub under your account. GitHub's handling of that data is governed
by the [GitHub Privacy Statement](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement).
All connections use HTTPS.

## Permissions

- **Internet** and **network state** — to reach GitHub and to know when you are offline.

## Deleting your data

- **Sign out** in Settings to remove the access token from the device.
- **Uninstall** the app, or clear its storage in Android settings, to remove all locally stored data.
- **Revoke access** at <https://github.com/settings/applications>.

The app has no account of its own, so there is nothing to delete on the developer's side. Content you
posted to GitHub is managed on GitHub.

## Children

The app is a developer tool and is not directed at children.

## Changes

Updates to this policy will be published at this same address with a new date.

## Contact

corkscreewe@gmail.com
