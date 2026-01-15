# Health Routine Gamification App - Build Summary

## Core Concept
Build a mobile-first wellness app that gamifies daily health habits as "health investment bills" users pay themselves before other responsibilities. Emphasize positive reinforcement, consistency over perfection, and encouraging messaging for all outcomes.

## Key Features & Point System

**Morning Light (1 pt + 3 bonus for 7-day streak)**
- Track outdoor exposure (any duration, cloudy days count)
- Educational messaging about circadian rhythm benefits

**Nutrition Tracking (1 pt per serving + weekly doubling)**
- MyPlate.gov-based portions: fruits, vegetables, whole grains, dairy, nuts
- Weekly bonus: 3 full nutrition days = double all nutrition points
- Awareness points for logging less optimal choices

**Breathing & Outdoor Time**
- 5 focused breaths = 1 point
- 5 minutes outdoors = 1 point  
- Both combined = 4 points (quadrupled)

**Movement (1 pt per 10 min + 1 pt for body awareness)**
- Accept various exercises: walking, dancing, weight lifting
- Body readiness check-in (more/same/less exercise capacity)
- Manual step count input

**Sleep Logging**
- Duration and quality tracking with encouraging feedback regardless of results

## Technical Architecture
- **Frontend**: React Native (cross-platform)
- **Backend**: Node.js/Express
- **Database**: SQLite local-first with optional cloud sync
- **Key Components**: Daily Dashboard, Activity Trackers, Point Engine, Encouragement System

## Core Philosophy
- Treat all activities as valuable self-investments
- Reward awareness and effort, not just perfect execution
- Provide educational context for health benefits
- Maintain encouraging tone even for "missed" activities
- Focus on building sustainable habits through consistency

## Data Models
- User profiles with streak tracking
- Daily activity logs with flexible input
- Point calculation with bonuses and multipliers
- Encouragement message system with educational content

## User Experience Priorities
- Simple one-tap activity logging
- Real-time point calculations with visual feedback
- Streak visualization and bonus celebrations
- Offline functionality with sync capabilities
- Accessibility compliance and privacy-first design

Build as a compassionate wellness companion that celebrates every step toward better health.