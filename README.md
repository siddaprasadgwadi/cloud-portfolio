# Cloud Portfolio — AWS S3 + CloudFront + GitHub Actions

Personal portfolio site hosted on AWS, auto-deployed via CI/CD pipeline.

## Live Site
https://d1smt1e3i2a651.cloudfront.net

## Architecture
GitHub Push → GitHub Actions → S3 Sync → CloudFront Invalidation

## Tech Stack
- AWS S3 (static website hosting)
- AWS CloudFront (CDN + HTTPS)
- AWS IAM (least-privilege access)
- AWS ACM (SSL certificate)
- GitHub Actions (CI/CD pipeline)

## What it does
Every git push to main automatically deploys to production in ~11 seconds.
