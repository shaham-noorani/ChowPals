# Chow Pals
A React Native app for setting up lunches with friends! Connect with members of your workplace, school, organizations, and clubs and be randomly paired with one or more *chow pals* on a reoccuring cycle!

## Feature Set
### *V1*
- chow groups
    - a group of people (friends, coworkers, organization) that want to eat together on a set reoccurring basis (weekly, biweekly, daily) and with a set size (two or more people per session)
    - group info: name (can be randomly generated), brief bio, logo, group coordinator info, list of members
- chow groups list
- profile page
    - picture, bio, food and other interests, contact info
    - *me*: edit button to update information
    - *other*: lists mutual chow groups, *chow pals*, and friends. Add friend button

### *V2*
- group chats for *chow pals*
    - once group has been made, creates a chat with members and lets them talk to each other
    - allows members to propose and vote on a time and place to eat
- time and place recommendation for *chow pals* group
    - analyzes *chow pals* calendars (3rd party or manual input) and food preferences and provides reccomendations of times and places to eat

### *V3*
- friends list
    - add users in contact list automatically
    - ability to setup reoccurring lunch buddies within your friends list
    - calendar view of which friends are looking for chow pals
    - add friend button on profile
- invite friends to group via custom url

## User Stories
*Chow group* = group of people (eg. friend group, student organization, team at work, sports team/league)

*Chow pals* = group eating together during current cycle (eg. Aggie Coding Club Cycle 6, Google Calendar Product Team Cycle 18, Fred and the Bois Cycle 45)

### *Within a group:*

1. Group coordinator sets up *chow group* with reoccurring cycle length (ie. every week, every other week) and size of chow pals groups (just 2 people or groups of 4, 5, etc), and other info
2. Members install app from iOS App Store or Google Play Store
3. Setup profile (name, contact info, food and other interests, availability, connect contact list)
4. Everyone in the group joins the *chow group* with join code or custom url
5. At a preset day of the week, *chow pals* are automatically generated (notification sent)
6. A group chat is made with *chow pals*
7. Based on their schedules and food prefs, times and places are recommended
8. Users will propose and vote on times and places—options with most votes are set as “decided on”
9. Everyone gets to enjoy a delicious meal together!

### *With friends:*

1. User and friends install app from iOS App Store or Google Play Store
2. Setup profile (name, contact info, food and other interests, availability, connect contact list)
3. User adds all of friends from contact list
4. User is shown day by day who matches their lunch and dinner availability
5. User reaches out to friends and sets up lunch date!