# Need Help?

Before seeking assistance, please make sure you have first tried these following:

- **Updating** Jellyseerr to the latest version.
- **Stopping and restarting** Jellyseerr.
- **Restarting** your machine.
- **Clearing** your browser cache.
- **Analyzing** your logs, you just might find the solution yourself!
- **Searching** the [documentation](../README.md), [installation guide](../getting-started/installation.md), and [FAQs](./faq.md).

If you still have questions after troubleshooting on your own, feel free to ask on [Discord](https://discord.gg/ckbvBtDJgC)! (Please review our [Code of Conduct](https://github.com/fallenbagel/jellyseerr/blob/develop/CODE_OF_CONDUCT.md) before posting.)

Be sure to also include a link to your logs. (Please see [How can I share my logs?](#how-can-i-share-my-logs) below.)

## What should I include when requesting support?

Please try to include as much information as possible. A vague statement like "it doesn't work" provides very little to go on, and makes it difficult for us to help you.

Try to answer the following questions:

- What version of Jellyseerr are you running? (You can find this in Settings → About → Version.)
- How did you install Jellyseerr? Are you using the official Docker or snap images, or images published by a third-party?
- How are you accessing Jellyseerr?
  - Are you accessing Jellyseerr through your reverse proxy or via a local IP address?
  - What browser are you using? What browser extensions are enabled?
- What were you trying to do, and how did you attempt it?
  - What command did you enter?
  - What did you click on?
  - What settings did you change?
  - Did you follow official instructions, or a third-party guide?
  - Provide a step-by-step list of what you tried.
  - Provide a brief description of your setup.
- What exactly do you see?
  - Did something happen?
  - Did something not happen?
  - Are there any error messages showing?
  - Provide screenshots to help us see what you are seeing.
  - Share your Jellyseerr logs, which show exactly what happened and are often critical for identifying issues (see [How can I share my logs?](#how-can-i-share-my-logs) below).

## How can I share my logs?

1. Locate the current log file at `<your Jellyseerr config directory>/logs/overseerr.log`.
2. Open the log file and **copy its contents** into a [**secret gist** on GitHub](https://gist.github.com/). If you upload your logs elsewhere, we may ask you to share them again via GitHub Gist.
3. **Share the link/URL to your secret gist** in the [`#support` channel in our Discord server](https://discord.gg/ckbvBtDJgC).
