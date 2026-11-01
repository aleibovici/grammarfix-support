# GrammarFix Privacy Policy

Last updated: 1 November 2026

GrammarFix fixes the grammar of text you select on your Mac. It has no accounts, no analytics, no advertising and no tracking. The developer does not collect, receive or store any of your data.

## The text you fix

What happens to the text depends on the provider you choose in Settings:

- **Apple (on-device):** the text is corrected by Apple's on-device model and never leaves your Mac.
- **OpenRouter, Claude (Anthropic) or OpenAI:** the text, along with any extra instructions you've written, is sent directly from your Mac to that provider over an encrypted connection, using your own API key. GrammarFix asks for your permission the first time it sends text to each provider. The provider handles the text under its own privacy policy. OpenRouter passes the text on to the company that runs the model you choose.

GrammarFix does not save your text. So you can get back the original after a fix, your last 10 fixes are kept in memory on your Mac, under Recent Fixes in the menu. They are never written to disk or sent anywhere, and they are cleared when you quit GrammarFix or choose Clear Recent Fixes. If a provider has no API key or a request fails, the Apple on-device model is used instead when it's available.

## API keys

API keys you enter are stored in the macOS Keychain on your Mac. Each key is only sent to the provider it belongs to.

## Model lists

When a cloud provider is selected in Settings, GrammarFix asks that provider for its list of available models. This request contains no text you've written.

## Clipboard

The Mac App Store version works through the macOS Services menu: macOS hands GrammarFix the selected text and puts the fix back in place, so the clipboard isn't used. The direct-download version from GitHub, which can also fix text with its own keyboard shortcut, briefly uses the clipboard to read your selection and paste the fix, and restores what was there before as soon as the fix is pasted.

## Settings

Your preferences (provider, model, shortcuts, language, extra instructions, per-app instructions and the emoji option) are stored locally on your Mac. With per-app instructions, only the instructions are sent with your text, never the app's name.

## This website

The website at https://grammarfixai.app counts page visits with Cloudflare Web Analytics, which doesn't use cookies, doesn't build a profile of you and doesn't follow you to other sites. The site loads no ads and no third-party fonts. Links to the Mac App Store include a campaign name so App Store Connect can show which page a download came from; Apple handles that under its own privacy policy.

## Children

GrammarFix is not directed at children and collects no data from anyone.

## Changes

Any changes to this policy will be published in this file, with a new date at the top.

## Contact

Questions about this policy can be raised as an issue at https://github.com/aleibovici/grammarfix-support/issues.
