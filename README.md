# Home Renovation Cost Tracker

A responsive web app for tracking renovation expenses, with dashboard, category chart, search/filter, add/delete expenses, budget tracking and JSON export.

## Current data
Budget: ₹471,000
Initial expenses: ₹111,100
Remaining: ₹359,900

## Multi-device family editing
The included `index.html` is a working demo and stores data in each browser's localStorage. To make edits shared across family members, connect the app to Firebase Firestore + Firebase Authentication (or Supabase) and replace the localStorage functions with cloud CRUD operations. Host the static app on Firebase Hosting, Vercel, Netlify, or GitHub Pages.

For a family-only app, use email/password or Google sign-in and Firestore security rules so only authenticated family members can read/write the renovation document.
