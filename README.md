# Puzzle Morocco

A beautiful puzzle game featuring 100 levels of Moroccan landmarks.

## Features

- 100 puzzle levels (3x3 to 6x6) featuring Moroccan landmarks
- Moroccan-themed UI with beautiful gradients
- Coin system with rewards and hint purchases
- Daily rewards with 7-day streak bonus
- Lucky Wheel mini-game (24h cooldown)
- Global leaderboard with Supabase backend
- Player profile with avatar customization
- 12 achievements to unlock
- GDPR consent modal
- Privacy policy page
- Language support: English, French, Arabic (RTL)
- Dark/Light theme with system mode
- Smooth animations with react-native-reanimated
- Sound effects and background music system
- Progress auto-saved with AsyncStorage

## Getting Started

```bash
npm install
npm run dev
```

## Building Android APK

```bash
npx eas-cli build --platform android --profile preview
```

## Building for Production

```bash
npx eas-cli build --platform android --profile production
```
