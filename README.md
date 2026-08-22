# Discord Bot Website

A simple GitHub Pages website for your Discord bot.

## 1. Add your Discord Client ID

Open `script.js` and replace:

`YOUR_DISCORD_CLIENT_ID`

with your Discord application's **Application ID / Client ID**.

Example:

`const CLIENT_ID = "123456789012345678";`

## 2. Upload to GitHub

Create a new GitHub repository and upload:

- index.html
- style.css
- script.js

## 3. Turn on GitHub Pages

In your repository:

Settings → Pages → Deploy from a branch

Select:

- Branch: main
- Folder: / (root)

Save it.

Your site will be available at a GitHub Pages address such as:

https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/

## 4. Custom .com domain

After you buy your .com domain, open:

GitHub repository → Settings → Pages → Custom domain

Enter your domain and save.

Then configure the DNS records at your domain registrar as GitHub instructs.

## Important

The website does not contain your bot token. Never put your Discord bot token in HTML, CSS, JavaScript, GitHub, or any public website.
