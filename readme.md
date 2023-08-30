# Better GitHub to Discord Webhook API

## What is this?

This is a simple API that allows you to have changes, commits, and pull requests from GitHub sent to a Discord webhook.

## How do I use it?

1. Create a Discord webhook & copy the URL.
   The URL should look something like this: `https://discordapp.com/api/webhooks/1234567890/abcdefghijklmnopqrstuvwxyz`.

2. Trim off the first parts up until the numbers, and the last parts after the letters.
   The URL should now look something like this: `1234567890/abcdefghijklmnopqrstuvwxyz`.

3. And then add the api location on the website, like so: `https://example.com/api/git/?hook=1234567890/abcdefghijklmnopqrstuvwxyz`.

4. Add the URL to your GitHub repository's webhook settings.

## What does it look like?

![Screenshot of a commit message.](https://xdbl.dev/image?i=e9c313.png)
