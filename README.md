# RaiGel Shooter 💕

A fun Valentine's Day shooter game!

## How to Deploy to GitHub Pages

### Step 1: Update package.json
1. Open `package.json`
2. Replace `YOUR-USERNAME` in the homepage field with your actual GitHub username:
   ```json
   "homepage": "https://your-actual-username.github.io/raigel-shooter"
   ```

### Step 2: Create GitHub Repository
1. Go to GitHub.com and create a new repository named `raigel-shooter`
2. Don't initialize it with a README

### Step 3: Upload and Deploy
Run these commands in your terminal:

```bash
cd raigel-shooter-game

# Initialize git
git init

# Add all files
git add .

# Make first commit
git commit -m "Initial commit"

# Add your GitHub repository as remote
git remote add origin https://github.com/YOUR-USERNAME/raigel-shooter.git

# Push to GitHub
git push -u origin main

# Install dependencies
npm install

# Deploy to GitHub Pages
npm run deploy
```

### Step 4: Access Your Game
After deployment completes (2-3 minutes), your game will be live at:
`https://YOUR-USERNAME.github.io/raigel-shooter`

## Alternative: Simple Deployment

If you don't want to use npm, you can use GitHub Pages directly:

1. Upload all files to your repository
2. Go to repository Settings → Pages
3. Select "Deploy from a branch"
4. Select "main" branch and "/root" folder
5. Save and wait a few minutes

However, this won't work since it's a React app. The npm method above is required.

## Local Development

To run locally:
```bash
npm install
npm start
```

The game will open at `http://localhost:3000`

## Game Controls
- **Move:** Arrow Keys or WASD
- **Shoot:** Spacebar
- **Pause:** ESC

Enjoy! 💕
