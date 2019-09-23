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

### Minimum Viable Product (MVP)
The following *required* functionality is completed:
- [ ] User can filter the list of articles by Top 10, Top 20, Top 50%, All
- [ ] User can read the news articles and comments offline (background refresh)
- [ ] User can switch between light/dark mode
- [ ] User can catch up to missed days of articles/news
- [ ] User can view/read webpages without leaving the app

### Phase 2
The following *optional* functionality is completed:
- [ ] User can read text summary of article
- [ ] User can search HackerNews from the search tab
- [ ] User can customize the following settings
		- Appearance (font, text size, reader mode)
		- Theme
		- Profile (posts, comments)
		- App Icon
		- Connect their YCombinator account
		- Ability to provide feedback/feature requests
		- Ability to donate to cover development costs
- [ ] User can engage on HackerNews similar to [Apollo](https://apolloapp.io/) or [Reddit](https://apps.apple.com/us/app/reddit/id1064216828) official apps
		- Comments
		- Upvote/downvote on comments and articles
		- Writing Editor to comment
		- Tap to collapse/hide a comment thread
- [ ] User can download iOS/Android app from the App Store or Play Store

### Future Work
The following *optional* features are implemented:
- [ ] User can view the top comments
- [ ] User can download desktop app from a public AWS S3 bucket
- [ ] User can post an article or write a comment using anonymous/ephemeral account
- [ ] User can explore top writers on HackerNews using the explore tab

## Technology Stack

- Built on [Firebase platform by Google](https://firebase.google.com/)
- Hosted on AWS Lambda or Google App Engine
- Hosted databases such as mLab or RDS
- Hosted exception tracking with sentry.io
- Cloud-native 12-factor backend application

## Detailed Requirements

### Design

*Spec (Design responsible)*

Prototype: Screen mockups of the Refined HckerNews app
<p align="center">
    <img src="ScreenMockups.jpg" alt="Screens of the Refined HckerNews app" />
</p>

Design:
	- Post an ad on Fiverr to get a polished design of the app

Other:
	- Post an ad on Fiverr to get custom app icons for the app

### Development

*Technical Spec: Front End and Back End*

Technical Approach Description
	-

Todo (Technical Tasks & Assignees)
	-

###	Testing

User Acceptance Testing
	- Collect feedback from product managers
	- Collect feedback from beta users

### Deployment
	...

###	Other
	...

###	Out of Scope
	...

## Philosophy

- No advertising on the apps whatsoever
- Minimal and privacy focused analytics on the apps (https://github.com/electerious/Ackee as an alternative for Google Analytics)
- Sign-in with Apple functionality and keep user emails private
- Allow user donations through PayPal to cover cloud hosting costs.
