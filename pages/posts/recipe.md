---
title: 🥙 Recipe Generator
description: AI based recipe generator you can use to generate any kind of recipe for your next meal.
tag: recipe
date: 2025-01-30
author: Wai Yan
---

# AI Recipe Generator

A modern web application that generates custom recipes with images using AI. Built with Next.js 14, TypeScript, Trigger.dev, and Clerk Authentication.


<div style="background: linear-gradient(135deg, #4F46E5 0%, #10B981 100%); padding: 1rem; border-radius: 12px; margin: 2rem 0; text-align: center; box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1); transition: transform 0.2s ease;">
  <a href="https://recipe-generator-theta.vercel.app/browse" style="color: white; text-decoration: none; font-weight: 600; display: flex; align-items: center; justify-content: center; gap: 1rem;">
    <span style="font-size: 1.5rem;">✨</span>
    <span>Try the Recipe Generator</span>
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

<br/>

<Image
  src="/images/recipe/recipe-1.png"
  alt="Photo"
  width={1125}
  height={750}
  priority
  className="next-image"
/>

## Core Features

### User Authentication
Secure authentication powered by Clerk, providing a seamless sign-in experience. Users must be authenticated to generate recipes and manage their collection. The authentication system includes email/password and social login options.

### AI Recipe Generation
The application leverages AI technology to generate unique, customized recipes. Users can specify their preferences including the dish name, main ingredient, and cuisine type (with options for Italian, Mexican, Indian, Chinese, and American). The system also takes into account dietary preferences with a vegetarian option, allows customization of cooking time between 5-120 minutes, and offers three difficulty levels (Easy, Medium, Hard). Each generated recipe is accompanied by an AI-generated image that visually represents the final dish.

<Image
  src="/images/recipe/recipe-2.png"
  alt="Photo"
  width={1125}
  height={750}
  priority
  className="next-image"
/>

### Recipe Browser
The recipe browser presents a responsive grid layout showcasing all generated recipes. Each recipe card displays essential information in an elegant format, presenting the recipe name alongside its cuisine type and a generated image. Users can quickly assess cooking time and difficulty level, while getting a preview of ingredients and instructions. This intuitive layout makes it easy to browse and discover new recipes.

<Image
  src="/images/recipe/recipe-5.png"
  alt="Photo"
  width={1125}
  height={750}
  priority
  className="next-image"
/>

### Detailed Recipe View
When viewing individual recipes, users are presented with a comprehensive cooking guide. The page features a high-quality recipe image prominently displayed alongside detailed cooking instructions. Users can find a complete list of ingredients, step-by-step cooking instructions, and important details such as cooking time and difficulty level. Additional information about cuisine type and dietary considerations is also readily available.

<Image
  src="/images/recipe/recipe-3.png"
  alt="Photo"
  width={1125}
  height={750}
  priority
  className="next-image"
/>

### Credit System
The application implements a thoughtful credit-based system to manage recipe generation. Users start with a limited number of generation credits, which are consumed each time a new recipe is created. The current credit balance is conveniently displayed in the navigation bar, keeping users informed of their remaining generations. When credits are depleted, users are seamlessly guided to purchase more credits to continue generating recipes.

<Image
  src="/images/recipe/recipe-6.jpg"
  alt="Photo"
  width={1125}
  height={750}
  priority
  className="next-image"
/>

### Recipe Management
Users have complete control over their recipe collection through a personal management system. The interface allows users to view their entire collection of generated recipes and easily remove any unwanted entries. Users can access their complete recipe history and efficiently organize their culinary creations, making it simple to track and manage their favorite recipes.

<Image
  src="/images/recipe/recipe-4.png"
  alt="Photo"
  width={1125}
  height={750}
  priority
  className="next-image"
/>

## Technical Implementation
The application is built on a robust technical foundation using Next.js 14 App Router for optimal performance and TypeScript for type safety. Background job processing is handled by Trigger.dev, while Prisma manages database operations. The modern user interface is crafted using Tailwind CSS with Shadcn UI components. Authentication is securely managed through Clerk, and the application leverages server-side rendering for enhanced SEO and performance.
