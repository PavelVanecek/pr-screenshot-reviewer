---
permalink: /privacy.html
---
# Privacy Policy — PR Screenshot Reviewer

_Last updated: 2026-10-13_

PR Screenshot Reviewer ("the app") is developed by Pavel Vanecek. This policy explains what happens to your
data when you use it. Short version: **the developer collects no personal data.** The app talks to GitHub on
your behalf, and the data it handles goes only to GitHub. If you buy access to private repositories, the
purchase is handled by Google Play.

## What the developer collects

No personal data. The app has no analytics, advertising, tracking or crash-reporting services, and no
account system. No data is sent to the developer or to any third party other than GitHub, and Google Play
for an in-app purchase (see Purchases below).

## Data the app handles on your device

To work, the app uses the following, and it stays on your device except when sent to GitHub:

- **GitHub access token.** Obtained when you sign in with GitHub (device flow, `public_repo` scope). Stored
  encrypted with the Android Keystore. Used only to call GitHub's API.
- **GitHub App tokens**, only if you connect private repositories in Settings. A second access token and a
  refresh token, issued to the app's GitHub App when you approve it (device flow). They work only in the
  repositories you install the GitHub App on, with the permissions GitHub shows you when you install it.
  Both are stored encrypted with the Android Keystore, together with their expiry times. The access token
  expires after a few hours and the app renews it from GitHub using the refresh token.
- **GitHub username and pull request authors' usernames and avatars**, received from GitHub and shown in
  the app. Avatar images are loaded from GitHub's servers (`avatars.githubusercontent.com`).
- **Repository setting** you enter or pick (owner/name), the names of the last five repositories you used,
  and app preferences.
- **Repository suggestions**: when you choose a repository, the app asks GitHub for public repositories you
  contributed to or belong to, and for open pull requests awaiting your review, so it can offer them for
  one-tap selection. If you connected private repositories, it also asks GitHub which private repositories
  the GitHub App is installed on. They are only shown, not stored.
- **Cached GitHub content**: pull request metadata, changed image files and HTTP cache tags, so the app
  loads faster and works offline. Pull request metadata is removed when you change repository. Downloaded
  screenshots are kept across repository changes, so returning to a repository does not download them
  again; each is removed 30 days after it was last shown, or when you clear the image cache in Settings.
- **Pending actions** (for example a review or comment written while offline), held until they are sent to
  GitHub.
- **Home screen widgets**, if you add them: they show pull request titles, authors and screenshots from the
  cached GitHub content on your home screen, where anyone who can see your screen can see them. The pull
  request pinned to the screenshot widget, and which screenshot each widget is showing, are stored on the
  device.
- **Feedback on individual screenshots**: the comments, rejections and tasks you write about a screenshot,
  with a link to the resulting GitHub comment or issue once it is sent. Kept so the app can show what you
  said about each screenshot; removed when the pull request is closed or you change repository.

The GitHub username, access tokens and the reviews, comments and issues you write are sent to GitHub only, to provide
the app's functionality. The developer never receives them, and they are not sold or shared with anyone else.

Android backup is disabled, so none of this is copied to cloud backups.

## Purchases

Reviewing private repositories is a one-time in-app purchase, sold through Google Play's billing system.
The payment happens between you and Google: the app never sees your card or other payment details. The app
asks Google Play only whether the purchase is owned by the Google account on the device, and stores nothing
about it. As the seller, the developer receives from Google Play a record of each order (such as an order
number, the product, the price and the country), not your payment details and not your GitHub identity; the
two are never linked. Google's handling of purchase data is governed by the
[Google Privacy Policy](https://policies.google.com/privacy). If you never buy anything, none of this applies.

## Communication with GitHub

The app connects to `github.com`, `api.github.com`, `raw.githubusercontent.com` (screenshots; those of
private repositories come from `api.github.com`) and `avatars.githubusercontent.com` (profile pictures). Reviews and
comments you submit, and issues you create from a screenshot, are published to GitHub under your account in
the repository you are reviewing. GitHub's handling of that data is governed
by the [GitHub Privacy Statement](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement).
All connections use HTTPS.

The app normally contacts GitHub only while you use it. While a home screen widget is placed, it also
refreshes from GitHub in the background about once an hour, fetching the same pull request data the app
shows; removing all widgets stops this.

## Permissions

- **Internet** and **network state** — to reach GitHub and to know when you are offline.
- **Google Play billing** — to offer the in-app purchase and check whether it is owned.

## Deleting your data

- **Sign out** in Settings to remove the access tokens from the device. **Disconnect** under Private
  repositories removes only the GitHub App tokens.
- **Remove the widgets** from your home screen to stop background refreshes and clear what they show.
- **Uninstall** the app, or clear its storage in Android settings, to remove all locally stored data.
- **Revoke access** at <https://github.com/settings/applications>. If you connected private repositories,
  also revoke the GitHub App at <https://github.com/settings/apps/authorizations> and uninstall it from your
  repositories at <https://github.com/settings/installations>.
- **Purchases** are kept by Google Play in your Google account, not by the app; see your order history in
  Google Play.

The app has no account of its own, so there is nothing to delete on the developer's side. Content you
posted to GitHub is managed on GitHub.

## Children

The app is a developer tool and is not directed at children.

## Changes

Updates to this policy will be published at this same address with a new date.

## Contact

corkscreewe@gmail.com
