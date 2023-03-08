# readme.md
**OVERVIEW:
              Physical activity trackers help measure personal metrics involved in fitness, such as number of steps walked, heart rate, quality of sleep, etc. They come predominantly in the form of wristbands (e.g., Fitbit, Mio) and smartwatches (e.g., Apple Watch, Samsung Gear, Garmin).
**DATABASE:
              I'm designing a database for a workout tracker app. Each user should be able to track multiple workouts (routines). A workout can have multiple exercises an exercise can be used in many workouts. Each exercise will have a specific track type (weight and reps, distance and time, only reps).
              My tables so far:

**| User |       |
|------|-------|
| id   | name  |
| 1    | Ilka  |
| 2    | James |

**| Exercise |                     |               |
|----------|---------------------|---------------|
| id       | name                | track_type_id |
| 1        | Barbell Bench Press | 1             |
| 2        | Squats              | 1             |
| 3        | Deadlifts           | 1             |
| 4        | Rowing Machine      | 3             |

**| Workout |         |                 |
|---------|---------|-----------------|
| id      | user_id | name            |
| 1       | 1       | Chest & Triceps |
| 2       | 1       | Legs            |
