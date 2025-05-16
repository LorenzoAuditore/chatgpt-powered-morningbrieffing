# chatgpt-powered-morningbrieffing
An iOS Shortcut that leverages ChatGPT to deliver a highly personalized morning briefing read to you by Siri

## Requirements

### Minimal Requirements

- An iOS device capable of running iOS 18.4
- the ChatGPT app on the same device & ChatGPT account on free tier.
- Saved Memories feature activated.

### Recommended Requirements
- A recent iOS device. Anything from iPhone 12 *and* capable of running iOS 18.4. Ideally —but optional, Apple-Intelligence-capable device.
- The **ChatGPT app** and a **ChatGPT account on the $20 tier**. For greater performance, $200 tier is possible but entirely optional.
- Saved Memories feature activated.
- Customize ChatGPT feature activated and populated.

## Step-by-Step

1. Download the ShortCut.

2. Install the ShortCut.

3. Run it once and give all permissions asked.

### Optional

You can Automate the morning briefing by going to the Shortcuts app => Automations => [Pick a trigger] => Choose the Shortcut as the triggered action.

___

### Notes and Troubleshooting

By default, this Shortcut will run with ChatGPT 4.1. However, you can change it to ChatGPT-4o if you encounter some errors.

But ChatGPT 4.1 is slow and can sometimes lead to a "timeout" error in the Shortcut, essentially stopping the Shortcut.

Sometimes, timeout errors happen randomly. It does not mean the Shortcut does not work, but only that OpenAI servers might experience a slowdown. You might also want to **restart your iOS device**.

___

### Additional Troubleshooting

Note: All errors may have one simple cause: lack of connectivity or speed. Make sure you check for that before troubleshooting further.

#### #1 Most Common Error — TIMEOUT Error

**Causes**: 

Timeout errors are random. They can happen when: 

1. ChatGPT servers are unusually busy.
2. The ChatGPT app has not been opened before using this Shortcut, or is not up-to-date. 
3. You are not logged in ChatGPT. 
4. The GPT model you are using is ressource-intensive for ChatGPT servers and takes longer than usual to respond. (To know what GPT model you are using, scroll down to the “Ask ChatGPT” action).
5. Some other idiosyncractic factor.

Note: on MacOS, you usually need to have the ChatGPT desktop app opened for this Shortcut to run. On iOS and iPadOS, it is usually sufficient for the app to run in the background (i.e., to be one of the last three apps you have used).

**Solutions**: 

1. Wait and try later. Sometimes, servers are just busy.
2. Switch to a different model (ChatGPT-4o is recommended).
3. Open your ChatGPT app. Make sure you are logged in. 
4. Close ChatGPT. Close Shortcuts. Open three different apps. Re-open ChatGPT. Re-open Shortcuts. Use this Shortcut.
5. Restart your device and reopen ChatGPT first, Shortcuts second.


#### #2 Most Common Error – “Shortcut could not determine what model to use”.

**Causes**:

This error sometimes happen when:

1. Your ChatGPT app is not opened (i.e. running in the background) or you’re not logged in.
2. The Shortcuts app is experiencing a glitch. It sometimes happens after first installing the Shortcut, or restarting your device, or updating your OS (iOS, iPadOS, MacOS), or updating your ChatGPT app.


**Solutions**: 

1. Open your ChatGPT app and make sure you’re logged in.
2. Close your Shortcuts and/or ChatGPT app, open three new apps, then reopen Shortcuts and/or ChatGPT. *Note: “closing” means “sliding the app up” in app Exposé. Just switching to a different app does not close it.
3. Restart your device and reopen ChatGPT first, Shortcuts second.



