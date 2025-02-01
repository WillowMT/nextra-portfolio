---
title: 🚌 Singapore Bus Tracker
date: 2024-08-12
description: Singapore Bus Tracking service that allows you to track bus arrivals and nearby bus stops in real-time.
tag: sbs
author: Wai Yan
---

# SBS Tracker V2

## Introduction
SBS Tracker V2 is a modern web application designed to enhance your daily commute experience in Singapore. This application helps you track SBS bus services and nearby bus stops in real-time, making your journey planning more efficient and convenient.

<div style="background: linear-gradient(135deg, #4F46E5 0%, #10B981 100%); padding: 1rem; border-radius: 12px; margin: 2rem 0; text-align: center; box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1); transition: transform 0.2s ease;">
  <a href="https://sbs.waiyanmt.com/service/search/q" style="color: white; text-decoration: none; font-weight: 600; display: flex; align-items: center; justify-content: center; gap: 1rem;">
    <span style="font-size: 1.5rem;">✨</span>
    <span>Try SBS Tracker V2</span>
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
  src="/images/sbs/sbs-1.png"
  alt="Flashcard"
  width={1125}
  height={750}
  priority
  className="next-image"
/>

## Key Features

### Real-Time Bus Tracking
The service tracking feature provides up-to-the-minute information about bus arrivals. Simply enter your bus service number, and you'll get detailed information about the next arriving buses, including their estimated arrival times and current location.



### Nearby Bus Stops
Finding the closest bus stop has never been easier. The application uses your current location to show all nearby bus stops on an interactive map. Each bus stop displays relevant information such as its name, code, and the bus services that stop there.

<Image
  src="/images/sbs/sbs-3.png"
  alt="Flashcard"
  width={1125}
  height={750}
  priority
  className="next-image"
/>

### Save Bus Stops
Save bus stops for quick access by clicking the 'Saves' button to open the drawer. At the bottom of the drawer, click the green 'Save Current' button to add your current bus stop to your favorites list.

<Image
  src="/images/sbs/sbs-2.png"
  alt="Flashcard"
  width={1125}
  height={750}
  priority
  className="next-image"
/>

### Mobile-Friendly Design
SBS Tracker V2 is designed to work seamlessly on your mobile device. The interface automatically adjusts to your screen size, ensuring a comfortable viewing experience whether you're using a smartphone or tablet.

### Progressive Web App
The application can be installed on your mobile device like a native app. Once installed, you can access it directly from your home screen without opening a web browser. This feature provides quick access and a more app-like experience.

## How to Use

### Finding Bus Arrivals
1. Open the service search page
2. Enter your bus service number
3. View real-time arrival information for both directions

### Locating Nearby Bus Stops
1. Allow location access when prompted
2. View the map showing bus stops in your vicinity
3. Tap on any bus stop to see detailed information

### Installing the App
1. Visit the website on your mobile device
2. Tap the "Add to Home Screen" option in your browser
3. Access the app directly from your device's home screen

## Privacy and Permissions
The application requires location access only when you use the nearby bus stops feature. This information is used solely for finding bus stops in your vicinity and is not stored or shared with third parties.

## Offline Support
Basic features of the application work even without an internet connection, though real-time updates require an active internet connection for the most accurate information.
