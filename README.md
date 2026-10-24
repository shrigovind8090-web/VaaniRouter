# Vaani Router — वाणी राउटर

**Voice router for Android.** Read any text on your phone with the *right* language,
the *right* voice and the *right* TTS engine — **word by word**.

Built for blind and low-vision users who use a screen reader (TalkBack, Jieshuo+),
and for anyone who reads text in more than one language.

Free. No ads. No accounts. Works offline. Nothing leaves your phone.

---

## The feature you will not find anywhere else

Most TTS apps read a whole sentence in **one** language. So a line like this —

> **Shri** गोविंद has sent you a **message**

— comes out wrong: the English engine tries to say "गोविंद" and mangles it, or the
Hindi engine reads the English words in Hindi.

**Vaani Router routes every single word to its own language.** Each word is spoken
in its own language, and you choose **which engine, which voice, which speed and
which pitch** that language uses. So the same line is read perfectly:

- `Shri` → English engine, English voice
- `गोविंद` → Hindi engine, Hindi voice
- `has sent you a` → English engine
- `message` → English engine

You can even give **one word** its own rule — a name, a place, a technical term —
and say exactly how it should sound.

This is **word routing**, and it is the heart of the app.

---

## What else it does

**Languages**
- Works with the languages you add — pick the engine and voice for each one.
- **Automatic language detection**, so you do not have to switch anything by hand.
  Detection is a real n-gram detector (the optimaize `language-detector` engine,
  70+ languages) and runs in the background so it never holds up speech.
- Any language your phone's engines support can be routed.

**Voices and engines**
- Use **any installed TTS engine** — Google, Samsung, Vinyas, Auto TTS, eSpeak,
  and any other engine on your phone.
- Separate engine + voice + speed + pitch per language.
- Voice character presets (echo, bass, gain, treble) for voices that need warmth.

**Per-app voice**
- Choose which language and voice reads **which app** — messages, news, books,
  everything.

**Pronunciation dictionary**
- Tell the app how to say a word, a name or a short phrase. Off by default; switch
  it on and manage your own entries.

**Vaani Reader**
- Paste or type text and read it aloud.
- One Play/Stop button, previous and next sentence, and a **saved reading position**
  so you continue from where you stopped — even in a very long text.

**Everything else**
- **Emergency Mode** — a fast way to change reading behaviour with the volume keys.
- **Background reading** with a foreground service, so it keeps working.
- **Settings backup and restore** to a file, so you never lose your setup.
- **Diagnostics and a speech log**, right at the top of Settings, when something
  needs looking into.
- **Speech log** records every engine start, voice change and error.
- A welcome video on a fresh start.

---

## Accessibility

- 100% English interface, designed to be used with a screen reader.
- Every control is reachable and announced properly.
- No separate "grant permission" buttons lying around — a feature asks for the
  permission it needs, at the moment you turn it on, and explains why.
- Large touch targets, clear headings, no decorative clutter.

---

## Install

1. Download the latest `.apk` from the **Releases** section of this repository.
2. Open it on your phone and allow installation from this source when asked.
3. Open **Vaani Router**, add the languages you read, and choose a voice for each.
4. Set Vaani Router as your **screen reader's** text-to-speech engine (or use it
   from inside the app with Vaani Reader).

Android 7.0 (API 24) and above.

---

## Notes

- The app is **free** and stays free.
- No internet is needed for reading. Nothing is collected, uploaded or shared.
- Your settings, dictionary and rules live only on your phone.
- The reading engine path is deliberately left untouched build after build, so
  voice quality never regresses.

---

## Support and feedback

- Telegram bot: https://t.me/techdrishtibot
- Telegram group: https://t.me/Techdrishti
- Telegram channel: https://t.me/tech_drishti
- YouTube: @TechDrishti-o6c
- WhatsApp community: https://chat.whatsapp.com/IJGG6AhSudzD1NSwfQuCpX
- WhatsApp channel: https://whatsapp.com/channel/0029VbDEYaH6rsQyXMCcGo1S
- Email: shrigov8090@gmail.com

---

**Tech Drishti** · Made in India · वाणी राउटर
