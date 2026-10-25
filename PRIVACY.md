# Privacy policy — DSH Drive

**Last updated: 2026-10-25**

DSH Drive is a personal desktop tool. It runs on the owner's own computer and connects to the
owner's own Google account. There are no other users.

## What the application accesses

- Files and folders in the owner's Google Drive, limited in practice to a single designated folder
  used for build artifacts.
- Nothing else: no Gmail, no Calendar, no contacts, no YouTube, no Photos.

## Where data goes

- Build files are read from the owner's local disk and written to the owner's Google Drive.
- Nothing is sent to any third-party server. The application has no backend: the OAuth token and
  the files stay between the owner's computer and Google's API.

## What is stored

- An OAuth refresh token, stored locally in the rclone configuration file on the owner's computer.
- No analytics, no telemetry, no logs of file contents.

## Sharing

- No data is sold, shared, or disclosed to anyone.
- No data is used for advertising or profiling.

## Deletion and revocation

- The application never deletes files from Google Drive.
- Access can be revoked at any time at https://myaccount.google.com/permissions; revoking removes
  the stored token's ability to act.

## Contact

glorhius@gmail.com
