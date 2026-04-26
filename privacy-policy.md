# Privacy Policy for Prompt Expert

Last updated: April 26, 2026

Prompt Expert is a browser extension for Microsoft Edge. It helps users improve and structure prompts on supported AI chat pages.

## What Prompt Expert does

Prompt Expert adds buttons such as Improve, Pro, Save, and Undo to supported AI chat pages.

When you click Improve or Pro, the extension reads the text from the active prompt field and sends it directly from your browser to the API provider selected in the extension settings.

Currently supported API providers are:

- Groq
- Google Gemini

Prompt Expert does not operate its own backend server. The extension author does not receive your prompts, API keys, or generated results through a Prompt Expert server.

## Supported websites

Prompt Expert is designed to work on supported AI chat pages listed in the extension manifest, including:

- ChatGPT
- Claude
- Google Gemini
- NotebookLM
- Grok
- DeepSeek

Copilot and Perplexity are not supported in this stable release.

## Data sent to external API providers

When you click Improve or Pro, the following data may be sent to the selected API provider:

- The text currently present in the active prompt field
- Instructions needed to improve or structure the prompt
- Technical API parameters required to process the request

The data is sent directly from your browser to the selected provider API using your own API key.

Prompt Expert does not control how Groq or Google process data on their side. Please review their official privacy and data policies before using their API services.

## API keys

Prompt Expert requires your own API key for the selected provider.

API keys are stored in your browser extension storage.

By default, API keys are stored locally in the browser. You may also choose session-only storage, if available, which keeps the key only for the current browser session. In session-only mode, you may need to enter the key again after restarting the browser.

Prompt Expert does not send your API key to the extension author.

API keys are used only to call the selected API provider.

## Local storage

Prompt Expert stores some data locally in your browser, including:

- Selected language
- Selected API provider
- Basic and Pro mode settings
- API key storage mode
- API keys, depending on your selected storage mode
- Temporary cache of prompt results
- Local export history used by the Save button

This data is stored on your device using browser extension storage.

## User controls

You can remove your API key at any time in the extension settings.

You can switch between local API key storage and session-only storage, if supported by your browser.

You can clear locally stored extension data by removing the extension or clearing extension storage in the browser.

Prompt text is sent to the selected API provider only after you click Improve or Pro.

You can stop using the extension on supported websites by disabling or removing the extension in Microsoft Edge.

## Save / export feature

The Save button lets you save the current prompt to a local file named `prompt_export.md`.

The file is saved through your browser's download system, usually into your default Downloads folder unless your browser settings specify otherwise.

Prompt Expert may keep a bounded local export history in browser storage so the saved file can contain recent saved prompts.

## Clipboard

If automatic insertion into a supported website fails, Prompt Expert may copy the improved prompt to your clipboard as a fallback, so you can paste it manually.

## Analytics and tracking

Prompt Expert does not include analytics, advertising trackers, or behavioral tracking scripts.

Prompt Expert does not collect browsing history for analytics or marketing purposes.

## Remote code

Prompt Expert does not load or execute remote JavaScript code.

The extension uses local extension files and communicates only with the selected API provider endpoints needed to process your request.

## Data sharing

Prompt Expert does not sell your data.

Prompt Expert does not share your data with the extension author through its own backend, because the extension does not have its own backend server.

Your prompt text is shared only with the API provider you select when you click Improve or Pro.

## Third-party providers

Your use of Groq or Google Gemini is subject to the terms and privacy policies of those providers.

You should not send sensitive personal data, confidential business information, passwords, secrets, private API keys, or regulated data unless you understand and accept the policies of the selected provider.

Check the current pricing, limits, and data policies on the selected provider's official website.

## Children's privacy

Prompt Expert is not intended to knowingly collect data from children.

## Changes to this policy

This privacy policy may be updated when the extension changes how it processes or stores data.

The latest version should be available at:

https://q3master.github.io/Prompt_Expert/privacy-policy.html

## Contact

If you have questions about this privacy policy, contact:

q3master@protonmail.com
