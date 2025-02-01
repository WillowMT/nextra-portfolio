---
title: 📚 Flashcards App
date: 2024-11-25
description: A simple flashcard app built with Next.js and Tailwind CSS. Great for learning and memorizing information in a fun and engaging way.
tag: flashcard
author: Wai Yan
---

# Modern Flashcard App

A powerful and intuitive flashcard application designed to help you learn and retain information effectively. This app combines the science of spaced repetition with engaging study modes to make your learning experience both efficient and enjoyable.

<div style="background: linear-gradient(135deg, #4F46E5 0%, #10B981 100%); padding: 1rem; border-radius: 12px; margin: 2rem 0; text-align: center; box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1); transition: transform 0.2s ease;">
  <a href="https://flashcards.waiyanmt.com" style="color: white; text-decoration: none; font-weight: 600; display: flex; align-items: center; justify-content: center; gap: 1rem;">
    <span style="font-size: 1.5rem;">✨</span>
    <span>Try the Flashcard App</span>
    <span style="background: rgba(255, 255, 255, 0.15); padding: 0.375rem 1rem; border-radius: 9999px; font-size: 0.875rem; display: flex; align-items: center; gap: 0.5rem;">
      <span style="width: 6px; height: 6px; background: #4ade80; border-radius: 50%; animation: pulse 1.5s ease-in-out infinite;"></span>
      Live
      <style jsx>{`
        @keyframes pulse {
          0% { opacity: 0.6; }
          50% { opacity: 1; }
          100% { opacity: 0.6; }
        }
      `}</style>
    </span>
  </a>
</div>

<Image
  src="/images/flashcard/flashcard-6.png"
  alt="Flashcard"
  width={1125}
  height={750}
  priority
  className="next-image"
/>

## 🌟 Key Features

### 📱 Mobile-Friendly Design
Access your flashcards from any device - whether you're on your phone, tablet, or computer. The app can be installed directly on your device for quick access, just like a native application. Study offline without an internet connection, and when you're back online, your progress automatically syncs across all your devices.

### 🎯 Smart Learning System
Our scientifically-proven spaced repetition system adapts to your learning pace. Cards you find challenging will appear more frequently in your reviews, while well-remembered cards show up less often. The system continuously adjusts based on your performance, and you can track your progress with clear mastery indicators that show how well you've learned each card.

### 📚 Study Modes

#### 1. Classic Review Mode
The classic review mode offers multiple ways to study. Focus on cards due for review today, go through your entire collection, or concentrate on cards you haven't mastered yet. You can also prioritize your least reviewed cards to ensure balanced learning. Rate your confidence with each card using a four-point scale: Again (1), Hard (2), Good (3), or Easy (4). Use the spacebar to flip cards, and enjoy smooth, beautiful animations that make studying more engaging.

<Image
  src="/images/flashcard/flashcard-2.png"
  alt="Flashcard"
  width={1125}
  height={750}
  priority
  className="next-image"
/>
<Image
  src="/images/flashcard/flashcard-5.png"
  alt="Flashcard"
  width={1125}
  height={750}
  priority
  className="next-image"
/>

#### 2. Speed Review Game
Challenge yourself with our speed review game mode. Select your preferred time limit from 30 seconds up to 2 minutes, and test how many cards you can review accurately. Enjoy engaging sound effects and visual feedback as you play. This mode is perfect for quick practice sessions and helps improve your recall speed while making learning fun.

<Image
  src="/images/flashcard/flashcard-3.png"
  alt="Flashcard"
  width={1125}
  height={750}
  priority
  className="next-image"
/>

#### 3. Gallery View
The gallery view gives you a comprehensive overview of your entire collection. Easily search through your cards, apply filters to find specific content, and make quick edits when needed. Sort your cards using various criteria to organize your study material effectively. This view provides quick access to all your content in one place.

<Image
  src="/images/flashcard/flashcard-4.png"
  alt="Flashcard"
  width={1125}
  height={750}
  priority
  className="next-image"
/>

### 💾 Data Management
Take control of your study material with flexible data management options. Import existing cards from CSV files, create backups by exporting your collection, and use batch import for adding multiple cards at once. All your data is stored securely on your device, ensuring your study materials are always accessible.

<Image
  src="/images/flashcard/flashcard-1.png"
  alt="Flashcard"
  width={1125}
  height={750}
  priority
  className="next-image"
/>

### ⌨️ Keyboard Shortcuts
Study efficiently with intuitive keyboard shortcuts. Use the spacebar to flip cards, numbers 1-4 to rate cards during review, and arrow keys to navigate between cards. These shortcuts make your study sessions faster and more productive, allowing you to focus on learning rather than navigation.

### 🎨 Customization
Personalize your learning experience with our customization options. Switch between dark and light modes to suit your preference and reduce eye strain. The modern interface features smooth animations and adapts perfectly to any screen size, ensuring a comfortable study experience across all devices.

## 📊 Progress Tracking
Monitor your learning journey with comprehensive progress tracking. View your complete review history, see which cards you've mastered, and keep track of your study streaks. These insights help you understand your learning patterns and maintain consistent study habits.

## 🔄 Smart Scheduling
Our intelligent scheduling system optimizes your learning by considering multiple factors. It takes into account how well you know each card, the time since your last review, your overall performance history, and scientifically-proven spacing intervals for long-term retention. This ensures you review cards at the optimal time for maximum learning efficiency.

## 💡 Tips for Best Results
Make the most of your study sessions by reviewing your due cards daily. Use the speed review game when you want quick, focused practice. Always rate your cards honestly based on how well you remember them - this helps the system adapt to your needs. Save time by importing existing cards from CSV files, and use the gallery view to keep your collection organized. Take advantage of offline mode to study anywhere, even without an internet connection.

## 🎮 Getting Started
Begin your learning journey by adding your first cards in the "Add Card" tab. Move on to the "Review" tab to start studying, and try the speed review game when you're ready for a challenge. Use the gallery to manage your growing collection, and don't forget to import any existing cards you may have.

The app is designed to make learning enjoyable and effective. Whether you're studying for an exam, learning a language, or just expanding your knowledge, this flashcard app adapts to your needs and helps you achieve your learning goals.

## Features

- 📱 **Progressive Web App (PWA)**
  - Works offline
  - Installable on mobile devices
  - Background sync support

- 🎯 **Spaced Repetition System (SRS)**
  - Smart scheduling based on performance
  - Four difficulty levels (Again, Hard, Good, Easy)
  - Mastery tracking for well-learned cards

- 💾 **Data Management**
  - Local storage persistence
  - CSV import/export functionality
  - Offline-first architecture

- 🎨 **Modern UI/UX**
  - Dark/Light mode support
  - Responsive design
  - Beautiful gradients and animations
  - Card flip animations
  - Keyboard shortcuts

## Core Technologies

- **Framework**: Next.js 14 (App Router)
- **Styling**: Tailwind CSS + Shadcn UI
- **State Management**: React Hooks + Local Storage
- **PWA Support**: next-pwa
- **UI Components**: 
  - Radix UI (base components)
  - Lucide Icons
  - Framer Motion (animations)

## Key Features Explained

### Spaced Repetition System
- Cards are scheduled using a modified SuperMemo 2 algorithm
- Review intervals increase based on performance
- Cards are marked as "mastered" after consistent good performance

### Study Modes
- **Due Cards**: Review cards scheduled for today
- **All Cards**: Review all cards in random order
- **Non-Mastered**: Focus on cards that need more practice
- **Gallery View**: Browse and manage cards with search and filters

### Card Management
- Create new flashcards with front/back content
- Import/Export cards via CSV
- Search functionality across card content
- Filter cards by status (Due, Mastered)
- Pagination for large card sets

### Offline Support
- Full functionality without internet connection
- Automatic sync when connection is restored
- Local data persistence
- Install as standalone app
