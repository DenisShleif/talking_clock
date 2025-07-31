# talking_clock

## MVP

### Inputs via shortcuts
 - start time
 - interval
 - end time or duration
 - pick voice

### Basic Architecture:
 - Create inputs in shortcut
    - Set as variables at the top of the shortcut
 - Configure voice
 - Use these settings to create a for loop
    - We need a delay method
 - We need a determine time method

### Tech Stacks

 - Only shortcuts (Preferred)
 - Shortcuts linked to Github Actions
 - iOS App

## Progress

### 2025-07-29: Shortcut inputs created
 - Created inputs StartTime, Interval, EndTime, Duration, Voice, Message
 - if Duration is included EndTime is calculated (Need to review corner cases next session)
 - Goals for next session: create loop and basic voice actions
 - iCloud Link: https://www.icloud.com/shortcuts/6c00aef43d30441b80eed1e2428ecdd5

### 2025-07-30: Basic logic implemented

 - Goals for next session: Fix logic with starttime, determine and fix corner cases with longer test
 - iCloud Link: https://www.icloud.com/shortcuts/9573bbcd383241d0a774e8f9e07f809d

### 2025-07-31: More updates

 - Future features: Dynamic implementation of voice
 - Test EndTime and Duration
 - Goals for next session: Test on another iPhone
 - iCloud Link: https://www.icloud.com/shortcuts/5b7e5c122da243698aad5314d37c29e6

## Contributers

 - Dimple Thomas
 - Denis Shleifman