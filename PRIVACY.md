# Sandbox Runner — Privacy Policy

**Last updated:** October 31, 2026
**Developer:** Luca Chang
**Contact:** 0naxarraxan0@gmail.com

## Summary

Sandbox Runner has no servers of its own. The developer does not receive, see, store, sell or share any of your data. Everything the app does happens on your device and inside your own Google account (Google Drive and Google Colab).

## What the app accesses, how, and why

| Data | How the app gets it | What it is used for | Where it stays |
|---|---|---|---|
| Your Google account name, email address and profile picture | Sign in with Google | To sign you in and show which account is connected | Your device and Google |
| Files the app creates in your Google Drive | Google Drive permission limited to files this app creates (`drive.file`). The app cannot see any other files in your Drive | Holds a "Sandbox Model Runner" folder containing the notebook, a status file, the memory database and temporary message files | Your Google Drive |
| Messages you type and the model's replies | Written to temporary files in that folder | So the notebook running in your own Google Colab session can read each message and write back the reply | Your Google Drive and your Colab session. Each message file is deleted after its reply is delivered |
| Session summaries ("Memory") | Written by your Colab notebook when you end a session | A short summary of the session, the model used, the number of messages and the time | memory.sqlite in your Google Drive |
| Generation settings (max tokens, temperature, top-p, top-k, repetition penalty) | Entered by you in the app | Sent with each message to your notebook | Your device |

The in-app Colab window shows Google's Colab website. Your sign-in there is handled by Google.

The app contains no analytics, advertising or tracking, and the developer does not track you across apps or websites.

## Third parties

The only company that receives your data is **Google LLC**, which provides Sign in with Google, Google Drive and Google Colab. Your data there is in your own Google account and is protected under [Google's Privacy Policy](https://policies.google.com/privacy). The developer shares no data with anyone else.

The AI models you choose are downloaded by your Colab notebook from Hugging Face. Your messages are not sent to Hugging Face.

Sandbox Runner's use of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.

## Keeping and deleting your data

- **Message files** are deleted automatically after each reply.
- **Memory summaries** stay in your Google Drive until you delete `memory.sqlite` or the "Sandbox Model Runner" folder.
- **To delete everything:** delete the "Sandbox Model Runner" folder from your Google Drive, then delete the app (this removes the settings stored on your device).
- **To withdraw consent:** sign out in the app, and remove Sandbox Runner at [myaccount.google.com/connections](https://myaccount.google.com/connections).

Because the developer never receives your data, there is nothing stored on the developer's side to delete. You can still contact us with any request or question.

## Content 

The app runs openly available AI models that you choose from its list. Their output is not filtered and may sometimes be inaccurate or inappropriate. 

## Changes

If this policy changes, the new version will be posted here with a new "Last updated" date.

## Contact
0naxarraxan0@gmail.com