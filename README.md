# Decluttering with Val — Website

Hey Val! This is your website's code. Below is everything you need to get set up on your own computer so you can make changes, see them live, and publish updates — all by chatting with an AI assistant called **Claude Code**.

You won't need to learn how to code. You just describe what you want in plain English, and Claude Code will make the changes for you.

---

## Before We Start: How This All Works

Your website is made up of a handful of files (HTML for content, CSS for styling, JavaScript for animations). These files live in two places:

1. **On your computer** — where you make changes and preview them privately
2. **On the internet** — the live version that anyone can visit

Here's the journey a change takes:

```
You tell Claude what to change
        ↓
Claude edits the files on your computer
        ↓
You preview it locally (only you can see it)
        ↓
You tell Claude to "save and publish"
        ↓
Your live website updates for everyone
```

There are three services that make this work:

| Service | What It Does | Analogy |
|---------|-------------|---------|
| **Git** | Tracks every change ever made to your files, like a detailed history log | Think of it like "Track Changes" in Google Docs, but for your whole website |
| **GitHub** | Stores your files online so they're backed up and accessible from any computer | Like Google Drive, but specifically designed for code |
| **Vercel** | Takes your files from GitHub and turns them into a live website anyone can visit (Kedar manages this) | The "Publish" button that makes everything go live |

You won't need to learn how any of these work. Claude handles all of it. But it helps to know they exist so the process makes sense.

---

## What You'll Be Installing

| Tool | What It Does |
|------|-------------|
| **VS Code** | A free app where you view your website files and talk to Claude |
| **Claude Code** | An AI assistant that lives inside VS Code and makes changes for you |

That's it — just two things.

---

## Step 1: Create Your Accounts

You'll need accounts on three free services. Set these up first:

### GitHub Account (where your code is stored)
1. Go to **https://github.com/signup**
2. Create an account with your email
3. Choose a username (something simple like `valorganizes` works great)
4. Verify your email when they send you a confirmation

### Anthropic Account (to use Claude Code)
1. Go to **https://console.anthropic.com**
2. Click **Sign Up** and create an account
3. Add a payment method when prompted — Claude Code charges a small amount per session (usually a few dollars for a full working session)

You don't need a Vercel account — the website is hosted under Kedar's Vercel. When you're ready to make changes go live, just push to GitHub and ask Kedar to deploy, or he can set it up to deploy automatically.

---

## Step 2: Install VS Code

1. Go to **https://code.visualstudio.com**
2. Click the big **Download** button (it detects your computer type automatically)
3. Open the downloaded file and drag it into your **Applications** folder (Mac) or run the installer (Windows)
4. Open VS Code

---

## Step 3: Install Claude Code in VS Code

1. Open **VS Code**
2. Click the **Extensions** icon on the left sidebar (it looks like four small squares)
3. In the search bar at the top, type **Claude Code**
4. Find **"Claude Code"** by Anthropic and click **Install**
5. After it installs, you'll see a Claude icon in your left sidebar — click it
6. It will ask you to sign in — use the Anthropic account you created in Step 1

---

## Step 4: Get Your Website Files

Now you need to download ("clone") your website's files from GitHub onto your computer. This is a one-time setup.

1. Open **VS Code**
2. Open the Claude Code panel (click the Claude icon in the left sidebar)
3. Type this into the chat:

```
Clone the repository https://github.com/kedarshashi/decluttering-website
and open it in VS Code
```

Claude will download all your website files and open them. You should see files like `index.html`, `about.html`, `services.html`, etc. in the left sidebar.

**What just happened?** Claude used Git to copy all the website files from GitHub (the online backup) to a folder on your computer. From now on, you'll work with these local files.

---

## Step 5: Preview Your Website Locally

Before making changes, let's make sure you can see your website on your own computer.

Tell Claude:

```
Start a local server so I can preview my website in the browser
```

Claude will start a preview and give you a link like `http://localhost:3000`. Click it — your website will open in your browser.

**Important:** This is a **local preview** — only you can see it. Nobody else on the internet can access this link. Think of it like a private draft. This is where you'll check your changes before making them live.

---

## Making Changes to Your Website

This is the fun part. Just open the Claude Code panel and describe what you want in plain English. Here are some examples:

### Changing text
```
Change the hero headline to "Transform your space. Transform your life."
```

### Changing colors
```
Make the accent color a dusty rose instead of terracotta
```

### Adding a new section
```
Add a testimonials section on the home page with 3 quotes from clients
```

### Changing photos
```
Replace the about page portrait with the file val-soundhealing-01.jpg
from the Photos folder. Make sure to optimize it for the web first.
```

### Changing layout
```
On mobile, make the services show as a horizontal scrollable row
instead of stacking vertically
```

After Claude makes a change, **refresh your local preview** in the browser (Cmd+R on Mac, Ctrl+R on Windows) to see the update. Remember — at this point, only you can see the changes. Your live website hasn't changed yet.

You can be as specific or as general as you want. Claude will figure out which files to change and do it for you.

---

## Saving and Publishing Your Changes

Once you're happy with how things look in your local preview, it's time to save your work and make it live. There are two parts to this:

### Part 1: Save Your Work (Committing)

A **commit** is like clicking "Save" — but smarter. It creates a snapshot of your work with a note about what changed. This way, you can always go back to any previous version if needed.

Tell Claude:

```
Commit my changes with a message describing what I changed
```

Claude will save a snapshot. Your changes are now safely recorded on your computer — but they're still not live yet.

### Part 2: Push Your Changes Online (Pushing)

Now you need to send your saved changes to GitHub (the online backup). Tell Claude:

```
Push my changes to GitHub
```

Your changes are now backed up online and visible in the GitHub repository.

### Part 3: Make It Live (Deploying)

The live website is hosted under Kedar's Vercel account. Once you've pushed your changes to GitHub, just text Kedar and let him know — he'll deploy the update and your live site at **https://decluttering-with-val.vercel.app** will be updated for everyone to see.

### The Shortcut

If you want to save and push in one step, just tell Claude:

```
Commit my changes and push to GitHub
```

Claude handles both at once.

### What Just Happened — In Plain English

```
1. COMMIT  →  Claude saved a snapshot of your changes (like hitting "Save")
2. PUSH    →  Claude uploaded that snapshot to GitHub (your online backup)
3. DEPLOY  →  Kedar publishes the update to the live website
```

---

## Your Daily Workflow

Here's what a typical session looks like:

```
1. Open VS Code
2. Open Claude Code (click the Claude icon)
3. Tell Claude to start the local preview server
4. Describe the changes you want
5. Preview them in your browser
6. When you're happy, tell Claude to commit and push to GitHub
7. Text Kedar to deploy, then check your live site
8. Done!
```

---

## Helpful Things to Ask Claude

You can type these into Claude Code at any time:

| What to type | What it does |
|---|---|
| `Show me what the home page looks like right now` | Claude reads the code and describes the current state |
| `Undo the last change you made` | Reverts the most recent edit |
| `What did I change since the last commit?` | Shows you what's different from the last saved version |
| `What files make up this website?` | Claude explains the project structure |
| `Make the site look more modern` | Claude will redesign elements with a fresh aesthetic |
| `The site looks broken on my phone, fix it` | Claude will investigate and fix mobile issues |
| `Show me the history of changes` | Lists all previous commits (saved snapshots) |

---

## Your Website Files — A Quick Map

```
decluttering-website/
  index.html          ← Home page
  about.html          ← About Val page
  services.html       ← Services page
  contact.html        ← Contact / inquiry form page
  css/styles.css      ← All the visual styling (colors, fonts, spacing)
  js/main.js          ← Animations and interactive behavior
  images/             ← Optimized photos used on the site
  Photos/             ← Original full-size photos (not uploaded to the site)
```

You don't need to memorize this — Claude knows where everything is.

---

## If Something Goes Wrong

Don't panic! Your work is never lost because Git keeps a history of every saved version.

### Something looks weird after a change
```
Something looks wrong on the site. Can you check what happened and fix it?
```

### You want to undo everything since your last save
```
Undo all changes since the last commit
```

### The live site looks different from your local preview
Text Kedar to redeploy, or ask Claude:
```
Did I forget to push my latest changes to GitHub?
```

### You're not sure what changed
```
Show me what's different between my local files and what's on the live site
```

---

## Key Terms Cheat Sheet

If you see any of these words and forget what they mean, here's a quick reference:

| Term | Plain English |
|------|--------------|
| **Repository (repo)** | The folder that contains all your website files, along with their full history |
| **Clone** | Downloading a copy of the repository to your computer |
| **Commit** | Saving a snapshot of your changes with a description |
| **Push** | Uploading your saved snapshots from your computer to GitHub |
| **Deploy** | Publishing your website so everyone can see the latest version |
| **Local / Localhost** | Your private preview — only visible on your computer |
| **Live site** | The public version at decluttering-with-val.vercel.app |
| **Branch** | Don't worry about this for now — you're working on the main one |

---

## Need Help?

Reach out to Kedar — he set this all up and can help troubleshoot anything.
