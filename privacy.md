
# Privacy Policy — YouTube Uploader

Last updated: November 19, 2026

## 1. Overview

YouTube Uploader is a Reddit application that monitors publicly available videos from the CORTIS YouTube channel and helps prepare Reddit link posts.

## 2. Information Processed

The app processes publicly available YouTube information, including:

- Video titles
- Video descriptions and metadata where needed
- Video identifiers
- Video publication dates
- Video durations

The app also stores video processing statuses and translated titles to help prevent duplicate posts.

## 3. Translation Service

When an English video title is unavailable, the app may send the public Korean YouTube video title to the DeepL API to obtain an English translation.

Only the video title needed for translation is sent to DeepL. The app does not intentionally send Reddit user data, account information, or private subreddit content to DeepL.

The DeepL API key is configured as a secret app setting rather than being included in the app's source code. It is used to authenticate translation requests.

## 4. Reddit Data

The app uses Reddit's provided permissions to interact with the subreddit and create posts. When a moderator runs the manual backfill feature, the app checks their Reddit user ID and moderator permissions to verify that they are authorized to use the feature.

This information is used for permission verification and is not sent to DeepL or used for translation.

## 5. Third-Party Services

The app uses:

- YouTube Data API
- DeepL API
- Reddit Devvit platform

Each service has its own privacy policy and data-handling practices.

## 6. Data Storage

The app uses Reddit's provided storage facilities to maintain video records, translations, and processing statuses.

## 7. Data Security

The app uses the security and permission mechanisms provided by Reddit Devvit. API keys are configured as secret app settings. No online service can guarantee absolute security.

## 8. Changes to This Policy

This policy may be updated when the app's functionality or data practices change.

## 9. Contact

For questions about this privacy policy, please contact the app creator through Reddit.
