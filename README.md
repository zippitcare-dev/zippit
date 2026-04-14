# ZIPPit PWA — Deployment Guide

## Files in this folder
- index.html   → The complete app
- manifest.json → PWA manifest (makes it installable)
- sw.js         → Service worker (offline support)

## Step 1 — Create GitHub Account (if you don't have one)
1. Go to https://github.com
2. Sign up for a free account

## Step 2 — Create a New Repository
1. Click the "+" icon → "New repository"
2. Name it: zippit
3. Set to PUBLIC
4. Click "Create repository"

## Step 3 — Upload Files
1. Click "uploading an existing file" link
2. Drag and drop ALL 3 files: index.html, manifest.json, sw.js
3. Click "Commit changes"

## Step 4 — Enable GitHub Pages
1. Go to Settings tab of your repository
2. Scroll to "Pages" section in left sidebar
3. Under "Source" → select "Deploy from a branch"
4. Branch: main, Folder: / (root)
5. Click Save
6. Wait 2 minutes → your URL appears:
   https://YOUR-USERNAME.github.io/zippit/

## Step 5 — Install on Android Phone
1. Open the URL above in Chrome on your phone
2. Tap the 3-dot menu (⋮) in Chrome
3. Tap "Add to Home screen"
4. Tap "Add"
5. ZIPPit icon appears on your home screen!

## Default Login
- Any user you see → PIN (first user PIN is 1234 as set in Apps Script)
- Go to More → Users & PINs to add your team

## Sharing with your team
Just send the GitHub Pages URL to your team members.
They open it in Chrome → Add to Home screen → Done!
All data syncs via Google Sheets automatically.
