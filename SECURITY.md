# Vixora website security

This repository powers the public, static Vixora website on GitHub Pages. It contains no authentication backend, payment processing or private user database.

## Reporting vulnerabilities

Please report suspected security issues privately to **vixora.tech@gmail.com** with the subject **Vixora website security**. Avoid posting exploit details, credentials, private information or security tokens in public GitHub issues.

Include the affected URL, a minimal description and safe steps to reproduce if possible. Do not test against other people's accounts or data.

## Baseline

- Use HTTPS for published site links and assets.
- Keep this repository public only for intended website content; never commit secrets, credentials, signing keys, app-private Firebase configuration or private operational files.
- Restrict repository write permissions and protect the `main` branch against accidental force pushes and deletion through repository settings.
- Keep the website static and dependency-light; review any added scripts, trackers or forms before publishing.
- Review app Privacy/Terms content and Google Play disclosures when data handling, permissions, SDKs or account features change.

Repository permissions, branch rules and GitHub Pages HTTPS enforcement must be checked in GitHub Settings; this document does not configure them.
