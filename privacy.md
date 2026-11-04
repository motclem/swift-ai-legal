---
title: Privacy Policy
---
# Swift AI Privacy Policy

Last updated: 4 November 2026

Swift AI is a Mac app that runs AI coding assistants for Xcode on your own Mac. This policy explains what information the app uses and where it goes.

## The short version

- Swift AI has no servers, no accounts, no analytics, no advertising, and no tracking.
- We (the developer) never receive your code, your prompts, or anything else you do in the app.
- AI models run on your Mac. Your conversations and settings are stored only on your Mac.

## Where your code and prompts go

When you chat with Swift AI in Xcode, your prompts and the parts of your project the assistant reads are processed by:

- **A local model**, which runs entirely on your Mac.
- **Apple's on-device model** (Apple Intelligence), which also runs on your Mac.
- **Apple's Private Cloud Compute**, only if you turn it on in Swift AI's settings. It is off by default. Requests sent there are handled under Apple's privacy policy.

Swift AI's model service, which the assistants use to reach the local model, accepts connections only from your own Mac (127.0.0.1). It is not reachable from the network.

## Downloading models

When you download a model, Swift AI fetches its files from Hugging Face (huggingface.co). Hugging Face can see your IP address and which model you downloaded, as with any download. Swift AI does not sign in to Hugging Face or send it anything about you or your code. Hugging Face's privacy policy applies to those downloads.

## Other assistants

Swift AI can set up separately installed assistants, such as Pi and OpenCode, so that Xcode can use them with Swift AI's local model. These are third-party programs, installed by you, with their own privacy policies. Swift AI does not control what they send elsewhere.

## What is stored on your Mac

- Settings and downloaded models, in `~/Library/Application Support/SwiftAI`.
- Conversation history, so you can resume a chat, in `~/Library/Application Support/SwiftAI/Sessions`.
- Logs, in `~/Library/Logs/SwiftAI`. These include the messages exchanged with Xcode, which can contain your prompts and code. They help diagnose problems and never leave your Mac unless you choose to share them.

## Keeping and deleting your data

- Delete the folders above to remove your conversations, logs, settings, and models.
- Deleting the app and those folders removes everything Swift AI stored.
- Because we hold no data about you, there is nothing for us to delete or send you on request.

## Children

Swift AI is not directed at children under 13.

## Changes

If this policy changes, the updated version will appear at the same web address, with a new "Last updated" date.

## Contact

Questions about this policy: jurist-paired.02@icloud.com
