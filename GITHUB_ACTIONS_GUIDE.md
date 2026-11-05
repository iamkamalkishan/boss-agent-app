# GitHub Actions se APK Build Karne Ka Guide

## Step 1: GitHub Repository Banao
1. GitHub.com pe login karo
2. New repository banao (e.g., "boss-agent-app")
3. Private ya Public - aapka choice

## Step 2: Code Push Karo
```bash
cd /root/leads/flutter_app
git init
git add .
git commit -m "Initial commit - Boss Agent app"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/boss-agent-app.git
git push -u origin main
```

## Step 3: APK Download Karo
1. GitHub repository pe jao
2. "Actions" tab click karo
3. Latest workflow run click karo
4. "Artifacts" section mein "app-release" download karo
5. ZIP extract karo → app-release.apk mil jayega

## Step 4: Phone pe Install Karo
1. APK file phone pe transfer karo
2. "Unknown sources" allow karo (Settings → Security)
3. APK install karo

## Important
- Pehle `lib/main.dart` mein API key replace karo
- GitHub Actions free tier: 2000 minutes/month (kaafi hai)
- Build time: ~5-10 minutes per build