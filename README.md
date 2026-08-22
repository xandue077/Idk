# BotVault — Discord Bot Directory

A unique multi-bot Discord website designed for GitHub Pages.

## Add a bot

Open `script.js` and add another object inside the `bots` array.

Example:

```js
{
  name: "My New Bot",
  description: "My bot does useful things.",
  category: "Utility",
  icon: "🤖",
  color: "#5865f2",
  tags: ["Tools", "Commands"],
  clientId: "123456789012345678",
  permissions: "2147483648"
}
```

The website automatically creates the card and Discord invite button.

## Discord Client ID

Use your Discord application's **Application ID / Client ID**.

Never put the Bot Token on this website.

## GitHub Pages

1. Create a GitHub repository.
2. Upload `index.html`, `style.css`, and `script.js`.
3. Open Settings → Pages.
4. Choose Deploy from a branch.
5. Select `main` and `/ (root)`.
6. Save.

## Custom .com domain

After buying your domain, use:

Repository → Settings → Pages → Custom domain

Then configure DNS at your domain registrar according to GitHub's instructions.

## Notes

This is a static website, so you can host it on GitHub Pages for free. Discord OAuth2 handles the bot invite; your bot itself still needs to be running on a host.
