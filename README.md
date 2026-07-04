# बोलो · Bolo — Talk in Your Language

**Bolo** is a simple picture-based communication board (an **AAC device**) for people who
cannot speak. You tap pictures to build a sentence, then press **🔊 Speak** to say it out loud.

It is made for India: the parent or user can pick **any Indian language** with one tap on the
side, and every word — and the spoken voice — changes to that language.

---

## What it can do

- **Tap pictures to talk.** Big, clear buttons with an emoji + the word. Tapping also says the word.
- **Build a sentence** at the top, then press **Speak** to hear the whole thing.
- **Choose your language** from the side bar: English, हिन्दी, বাংলা, தமிழ், తెలుగు, मराठी,
  ગુજરાતી, ಕನ್ನಡ, മലയാളം, ਪੰਜਾਬੀ, ଓଡ଼ିଆ, اردو.
  - The words, the buttons, and the **voice** all switch to that language.
  - English + Hindi are **built in** and work instantly, even with no internet.
  - Other languages are downloaded **once** and then **saved on the device**, so they work
    offline after the first time.
- **Add your own word.** Type any word in the box — it is translated into the chosen language,
  spoken, and added as a new button.
- **⌫ (Delete last)** removes the last word, **Clear** empties the sentence.

## Works everywhere

It is one web page, so it runs the same on a **tablet, mobile phone, and computer**. The layout
adjusts to the screen and the buttons stay big and easy to tap.

## How to run it

- **Easiest:** double-click `index.html` to open it in any web browser (Chrome recommended).
- **On a phone/tablet:** put `index.html` online (e.g. GitHub Pages) and open the link, or use
  a simple local server:
  ```
  python -m http.server 8000
  ```
  then open `http://localhost:8000` in the browser.
- **Add to home screen** on a phone/tablet so it opens like an app.

## Notes

- Spoken voices depend on the device. Most phones and tablets already have Hindi and English
  voices; other Indian-language voices may need to be installed from the device's
  *Settings → Language / Text-to-speech* for the best sound.
- Translations for the extra languages use a free public translation service the first time a
  language is opened; after that they are stored on the device.
