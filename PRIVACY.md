# GrammarFix Privacy Policy

Last updated: 26 November 2026

GrammarFix fixes the grammar of text you select on your Mac. It has no accounts, no analytics, no advertising and no tracking. The developer does not collect, receive or store any of your data.

GrammarFix is made by Andre Leibovici, an individual developer in New Zealand, who is responsible for this policy. You can reach the developer at support@grammarfixai.app.

## The text you fix

What happens to the text depends on the provider you choose in Settings:

- **Apple (on-device):** the text is corrected by Apple's on-device model and never leaves your Mac.
- **OpenRouter, Claude (Anthropic) or OpenAI:** the text, along with any extra instructions you've written and any of your Words to keep that appear in it, is sent directly from your Mac to that provider over an encrypted connection, using your own API key. GrammarFix asks for your permission the first time it sends text to each provider. The provider handles the text under its own privacy policy. OpenRouter passes the text on to the company that runs the model you choose.
- **Custom server:** the text, instructions and any Words to keep that appear in it are sent to the OpenAI-compatible server whose address you entered, with your API key if you gave one. If that server runs on your Mac, such as Ollama or LM Studio, the text stays on your Mac; if it runs elsewhere, whoever operates it handles the text under their own terms. GrammarFix asks for your permission the first time, and again whenever you change the server's address.

You choose the order the providers are tried in Settings. A fix goes to the first one that's set up, with an API key or a server address, and to the next only if that one fails. Apple's on-device model ends the order: providers after it are never sent your text, so putting Apple first keeps every fix on your Mac. GrammarFix asks your permission for every provider a fix might reach before the first fix that could use them.

GrammarFix does not save your text. So you can get back the original after a fix, your last 10 fixes are kept in memory on your Mac, under Recent Fixes in the menu. They are never written to disk or sent anywhere, and they are cleared when you quit GrammarFix or choose Clear Recent Fixes.

## API keys

API keys you enter are stored in the macOS Keychain on your Mac. Each key is only sent to the provider, or the custom server, it belongs to.

## Model lists

When a cloud provider or a custom server is selected in Settings, GrammarFix asks it for its list of available models. This request contains no text you've written.

When you click Test in Settings, GrammarFix sends that provider a fixed sample sentence ("Teh meeting are on tuesday…") to check it works. The sample is the same for everyone and contains no text you've written.

## Clipboard

In the Mac App Store version, fixes made through the Services menu don't use the clipboard: macOS hands GrammarFix the selected text and puts the fix back in place. Fix Copied Text, in the menu bar menu, is for apps without a Services menu: when you choose it, it reads the text you copied and puts the fix on the clipboard for you to paste. The direct-download version from GitHub, which can also fix text with its own keyboard shortcut, briefly uses the clipboard to read your selection and paste the fix, and restores what was there before as soon as the fix is pasted.

## Settings

Your preferences (the provider order, models, the custom server's address, shortcuts, language, how much to change, when to review changes, extra instructions, Words to keep, per-app and per-website instructions and the emoji option) are stored locally on your Mac, as are the last few requests you typed in Fix with Instructions, so they can be offered again. None of them are sent anywhere, except the instructions and Words to keep that go with your text as described above, and the custom server's address, which is where that text goes. With per-app and per-website instructions, only the instructions are sent with your text, never the name of the app or the website.

## Websites in Safari and Chrome

In the Mac App Store version you can give a website in Safari its own instructions. To know which website you're writing on, GrammarFix includes a Safari extension called GrammarFix Websites. It is off until you turn it on in Safari's settings, and it sees only the websites you allow it on there. It never asks about other websites.

For a website you've allowed, the extension tells GrammarFix its name, such as mail.google.com, when it's on Safari's front tab. It doesn't read the page, the full address or what you type. GrammarFix keeps only the latest name, on your Mac, to choose the instructions for a fix, and replaces it each time the front tab changes. No browsing history is kept, and the website's name is never sent to a provider or anywhere else. Turn the extension off in Safari at any time and fixes in Safari use Safari's instructions.

From GrammarFix 1.11, Chrome works the same way with the GrammarFix Websites extension for Chrome, which you add from the Chrome Web Store. It asks for no websites when you add it; you allow it on one website at a time from its button in Chrome's toolbar, and it tells GrammarFix about only those. When you click that button it shows the name of the website you're on, so that you can allow it; nothing about that website reaches GrammarFix until you do. It passes the website's name, such as mail.google.com, to a small helper inside GrammarFix that Chrome starts, which leaves it on your Mac for GrammarFix in the same way, with a made-up label for the Chrome profile it came from so that two profiles don't get mixed up. To let Chrome find that helper, Connect Chrome… in GrammarFix's settings adds one file to Chrome's folder, in the folder you choose. When the extension is turned off or removed, or Chrome quits, GrammarFix forgets the website and fixes in Chrome use Chrome's instructions. The extension can't be turned on in incognito windows, so there Chrome's instructions apply too.

The extension for Chrome uses the website's name only for this, as the Chrome Web Store User Data Policy requires, including its Limited Use requirements. It is not sold, not passed to anyone else and not used for advertising.

## This website

The website at https://grammarfixai.app counts page visits with Cloudflare Web Analytics, which doesn't use cookies, doesn't build a profile of you and doesn't follow you to other sites. The site loads no ads and no third-party fonts. Links to the Mac App Store include a campaign name so App Store Connect can show which page a download came from; Apple handles that under its own privacy policy.

## Children

GrammarFix is not directed at children and collects no data from anyone.

## Changes

Any changes to this policy will be published in this file, with a new date at the top.

## If you contact the developer

The app sends the developer nothing. If you email support@grammarfixai.app or open an issue on GitHub, the developer receives what you write and your email address or GitHub name, and uses them only to answer you. Email to that address is forwarded by Cloudflare to the developer's own mailbox. GitHub issues are public and are handled by GitHub under its own privacy policy. Emails are deleted when they're no longer needed to help you.

## Your rights

If you live in the European Union, the United Kingdom or another country with similar privacy laws, you can ask to see, correct or delete any personal data the developer holds about you, which can only be what you sent yourself. Email support@grammarfixai.app. You can also complain to the data protection authority where you live.

## Contact

Email support@grammarfixai.app, or raise a question as an issue at https://github.com/aleibovici/grammarfix-support/issues.
