# Requirements Document

## Introduction

A gamified health routine tracking application that encourages users to maintain basic daily wellness habits through positive reinforcement and point-based rewards. The system focuses on morning light exposure, nutrition tracking based on MyPlate.gov guidelines, mindful breathing exercises, movement activities, and sleep quality monitoring, with an emphasis on encouraging messaging regardless of user performance. All tracked activities represent "health investment bills" that users pay to themselves before attending to other responsibilities.

## Glossary

- **Health_Tracker_App**: The mobile/web application system for tracking daily health routines
- **User**: An individual using the application to track their health habits
- **Point_System**: The gamification mechanism that awards points for completed activities
- **Morning_Light_Activity**: The daily outdoor exposure routine (a few minutes, focusing on consistency)
- **Streak_Bonus**: Additional points awarded for consecutive days of activity completion
- **MyPlate_Tracking**: Nutrition logging based on USDA MyPlate.gov portion guidelines
- **Breathing_Exercise**: 5-minute mindful breathing sessions with extended exhales
- **Sleep_Log**: User-reported sleep duration and quality assessment
- **Daily_Summary**: End-of-day analysis and encouragement based on completed activities
- **Awareness_Point**: Partial point awarded for acknowledging less optimal choices
- **Movement_Exercise**: Physical activity including walking, dancing, weight lifting, or other movement
- **Body_Awareness_Check**: User self-assessment of physical readiness and energy levels
- **Health_Investment_Bills**: Daily wellness activities that users complete for themselves before attending to other responsibilities
- **Step_Count**: Daily step tracking input from User

## Requirements

### Requirement 1

**User Story:** As a health-conscious individual, I want to track my morning light exposure, so that I can establish a consistent circadian rhythm routine.

#### Acceptance Criteria

1. WHEN the User opens the Health_Tracker_App in the morning, THE Health_Tracker_App SHALL display a prompt to step outdoors for a few minutes
2. WHEN the User completes the morning light exposure for one day, THE Health_Tracker_App SHALL award one point to the User
3. WHEN the User completes morning light exposure for seven consecutive days, THE Health_Tracker_App SHALL award a bonus of three points
4. THE Health_Tracker_App SHALL provide guidance that outdoor light is much brighter than indoor lighting and works through light hitting the eyes, not skin exposure like vitamin D
5. THE Health_Tracker_App SHALL explain that the User can sit or stand comfortably outdoors, and that cloudy or rainy days still provide adequate outdoor light brightness

### Requirement 2

**User Story:** As a user focused on nutrition, I want to track my food portions according to MyPlate guidelines, so that I can maintain balanced eating habits.

#### Acceptance Criteria

1. THE Health_Tracker_App SHALL provide input fields for tracking daily portions of fruits, vegetables, whole grains, dairy, and nuts based on MyPlate.gov guidelines
2. WHEN the User logs one serving of fruits, vegetables, or whole grains, THE Health_Tracker_App SHALL award one point per serving
3. THE Health_Tracker_App SHALL calculate cumulative daily nutrition points from all logged servings
4. WHEN the User achieves three full nutrition days within a seven-day period, THE Health_Tracker_App SHALL double all nutrition points for that week
5. THE Health_Tracker_App SHALL recognize that full nutrition days do not need to be consecutive and can include different combinations of food categories to acknowledge that healthy diet changes are difficult
6. WHEN the User logs less optimal food choices, THE Health_Tracker_App SHALL award awareness points for self-recognition
7. THE Health_Tracker_App SHALL display encouraging messages that reward lifestyle changes rather than perfection

### Requirement 3

**User Story:** As someone seeking stress relief, I want to practice mindful breathing exercises, so that I can take regular mental health breaks throughout my day.

#### Acceptance Criteria

1. WHEN the User completes five focused breaths with extended exhales, THE Health_Tracker_App SHALL award one point
2. WHEN the User spends five minutes outdoors, THE Health_Tracker_App SHALL award one point
3. WHEN the User combines five focused breaths with five minutes outdoors, THE Health_Tracker_App SHALL award four points
4. THE Health_Tracker_App SHALL provide guidance for exhale-focused breathing with exhales twice as long as inhales
5. THE Health_Tracker_App SHALL track multiple breathing and outdoor sessions per day

### Requirement 4

**User Story:** As a user wanting better sleep, I want to log my sleep quality and duration, so that I can monitor my rest patterns.

#### Acceptance Criteria

1. THE Health_Tracker_App SHALL provide input fields for sleep duration and quality rating
2. THE Health_Tracker_App SHALL allow the User to log sleep information at any time
3. THE Health_Tracker_App SHALL store historical sleep data for pattern analysis
4. THE Health_Tracker_App SHALL display encouraging messages about sleep logging regardless of reported quality
5. THE Health_Tracker_App SHALL connect sleep quality feedback to other daily activities when appropriate

### Requirement 5

**User Story:** As a motivated user, I want to see my daily progress summary, so that I can feel encouraged about my health journey regardless of performance.

#### Acceptance Criteria

1. THE Health_Tracker_App SHALL calculate total daily points from all completed activities
2. THE Health_Tracker_App SHALL generate a daily summary with encouraging statements based on User's activities
3. WHEN the User has low activity completion, THE Health_Tracker_App SHALL provide supportive and understanding messages
4. THE Health_Tracker_App SHALL display explanations for why certain activities benefit health
5. THE Health_Tracker_App SHALL maintain a positive and encouraging tone in all messaging

### Requirement 6

**User Story:** As someone who values physical activity, I want to track my movement and exercise, so that I can maintain an active lifestyle appropriate for my current physical state.

#### Acceptance Criteria

1. THE Health_Tracker_App SHALL accept various forms of Movement_Exercise including 10-minute walks, slow dancing, 5-minute weight lifting, or equivalent activities
2. WHEN the User completes 10 minutes of Movement_Exercise, THE Health_Tracker_App SHALL award one point
3. WHEN the User logs a Body_Awareness_Check about their readiness for movement, THE Health_Tracker_App SHALL award one point
4. THE Health_Tracker_App SHALL allow the User to input daily Step_Count manually
5. THE Health_Tracker_App SHALL offer exercise suggestions based on User's reported physical readiness and recovery needs

### Requirement 7

**User Story:** As a user recovering from illness or injury, I want to assess my body's readiness for exercise, so that I can make informed decisions about my activity level.

#### Acceptance Criteria

1. THE Health_Tracker_App SHALL provide options for the User to report feeling ready for more exercise, same amount, or less exercise
2. THE Health_Tracker_App SHALL analyze movement patterns and body awareness inputs to provide personalized suggestions
3. WHEN the User indicates need for recovery, THE Health_Tracker_App SHALL emphasize that rest is valuable and necessary
4. THE Health_Tracker_App SHALL educate Users that more exercise is not always better, especially during viral infections or injury recovery
5. THE Health_Tracker_App SHALL reward body awareness and self-care decisions with encouraging messages

### Requirement 8

### Requirement 8

**User Story:** As a user learning about my habits, I want to receive awareness points for acknowledging less optimal choices, so that I can build self-awareness without judgment.

#### Acceptance Criteria

1. WHEN the User logs less optimal choices, THE Health_Tracker_App SHALL award partial awareness points
2. THE Health_Tracker_App SHALL provide educational explanations for why certain choices might occur
3. THE Health_Tracker_App SHALL connect awareness logging to potential underlying needs or circumstances
4. THE Health_Tracker_App SHALL maintain encouraging messaging even for awareness-only activities
5. THE Health_Tracker_App SHALL treat all user input as valuable self-reflection regardless of the activity type