---
permalink: /privacy.html
---
# Privacy Policy — PR Screenshot Reviewer

_Last updated: 2026-09-21_

PR Screenshot Reviewer ("the app") is developed by Pavel Vanecek. This policy explains what happens to your
data when you use it. Short version: **the developer collects no personal data.** The app talks to GitHub on
your behalf, and may send anonymous crash and error reports so problems can be fixed.

## What the developer collects

No personal data. The app has no analytics, advertising or tracking, and no account system.

**Crash and error reports.** When the app crashes or hits an unexpected error, it may send a technical
report to the developer so the problem can be identified and fixed. A report contains only technical
information, such as:

- the exception type, message and stack trace
- app version and build number
- Android version, device model and manufacturer
- basic app state at the time of the error (for example, which screen was open)

Reports contain no user identifiers: no name, email address, GitHub username or access token, no advertising
ID or other persistent device identifier, and no repository names, pull request contents or screenshots. Reports
cannot be linked to you. They are used only to diagnose and fix problems, never for advertising or profiling,
and are not sold or shared for any other purpose. Reports are handled by a crash-reporting service acting on
the developer's behalf, and are kept only as long as needed to fix the problem.

Apart from these reports, no data is sent to the developer or to any third party other than GitHub.

## Data the app handles on your device

To work, the app uses the following, and it stays on your device except when sent to GitHub:

- **GitHub access token.** Obtained when you sign in with GitHub (device flow, `public_repo` scope). Stored
  encrypted with the Android Keystore. Used only to call GitHub's API.
- **Repository setting** you enter (owner/name) and app preferences.
- **Cached GitHub content**: pull request metadata, changed image files and HTTP cache tags, so the app
  loads faster and works offline.
- **Pending actions** (for example a review or comment written while offline), held until they are sent to
  GitHub.

Android backup is disabled, so none of this is copied to cloud backups.

## Communication with GitHub

The app connects to `github.com`, `api.github.com` and `raw.githubusercontent.com`, and, for crash reports, to the crash-reporting service described above. Reviews and
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
