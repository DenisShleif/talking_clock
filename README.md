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

## Contributers

 - Dimple Thomas
 - Denis Shleifman