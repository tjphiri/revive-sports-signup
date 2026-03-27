# Sports Signup Sheets

7-a-side team allocation with playoff brackets for football and netball.

## Features

- **Auto team allocation**: Players are randomly distributed across 2-4 teams (7 players each)
- **Playoff brackets**: 
  - 2 teams: Best-of-three series
  - 3 teams: Round robin
  - 4 teams: Semi-finals + Final
- **Score tracking**: Enter match results directly in the brackets
- **CSV export**: Download team rosters and match results
- **Auto-save**: Data persists in browser (survives page refresh)
- **iPad optimized**: Touch-friendly interface

## Deploy to GitHub Pages (3 minutes)

### Step 1: Create GitHub repository

1. Go to [github.com](https://github.com) and sign in
2. Click the **+** icon (top right) → **New repository**
3. Name it: `sports-signup` (or anything you like)
4. Make it **Public**
5. Click **Create repository**

### Step 2: Upload files

1. On your new repository page, click **uploading an existing file**
2. Drag and drop these 3 files:
   - `index.html`
   - `football_signup.html`
   - `netball_signup.html`
3. Scroll down and click **Commit changes**

### Step 3: Enable GitHub Pages

1. Go to **Settings** (top menu of your repository)
2. Click **Pages** (left sidebar)
3. Under **Source**, select **main** branch
4. Click **Save**
5. Wait 1-2 minutes, then refresh the page
6. You'll see: "Your site is live at `https://yourusername.github.io/sports-signup/`"

### Step 4: Share the link

Your shareable URLs:
- Landing page: `https://yourusername.github.io/sports-signup/`
- Football: `https://yourusername.github.io/sports-signup/football_signup.html`
- Netball: `https://yourusername.github.io/sports-signup/netball_signup.html`

Replace `yourusername` with your actual GitHub username.

## How to use

1. Open the form on your iPad
2. Type player names and tap "Add player"
3. Teams are auto-balanced (players randomly distributed)
4. Enter scores in the playoff brackets
5. Click "Download data (CSV)" to export everything
6. Click "Clear all" to start fresh

## Data storage

- Data is stored **locally** in each person's browser
- If 5 people open the link, they each have their own separate signup sheet
- Data does NOT sync between devices
- To share a populated sheet: use the CSV export

## Need shared data collection?

If you want one central sheet where everyone's signups sync:
- Use Google Forms instead
- Or contact me to build a cloud-synced version

## Technical notes

- Pure HTML/CSS/JavaScript (no server needed)
- Works offline after first load
- Uses browser localStorage for persistence
- CSV export includes team rosters + match results

---

Created with Claude
