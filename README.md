# Refined HackerNews 

## Goal

To build a refined, privacy-focused, lightweight and elegant app for reading [Hackernews](https://news.ycombinator.com/), improves on [hckrnews.com](https://hckrnews.com) website

## Motivation

Catching up on hackernews is a painful experience with many websites and apps that fragment the experience instead of streamlining it.  

## Why now?

Most mobile clients lack dark mode functionality and aren't designed so that you can catch up when you missed a few days of news

## Folder structure

- `backend`: folder for backend API server files
- `frontend`: folder for frontend clients in React Native
- `desktop`: folder for desktop clients (in Electron, React or a similar framework)

## User Stories

The following *required* functionality is completed:
- [ ] User can switch between light/dark mode 
- [ ] User can read the news articles and comments offline (background refresh)
- [ ] User can filter the list of articles by Top 10, Top 20, Top 50%, All 
- [ ] User can catch up to missed days of articles/news
- [ ] User can download iOS/Android app from the App Store or Play Store


The following *optional* features are implemented:
- [ ] User can download desktop app from a public AWS S3 bucket
- [ ] User can engage on HackerNews similar to [Apollo](https://apolloapp.io/) or [Reddit](https://apps.apple.com/us/app/reddit/id1064216828) official apps