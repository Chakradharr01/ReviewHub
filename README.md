# ReviewHub
🌍 ReviewHub
A Real-Time Location-Aware Exploration & Review Web Application
📌 Project Overview

ReviewHub is a smart, modern web application designed to help users explore and review nearby places using real-time GPS-based location detection.
The platform ensures 100% location accuracy, trusted reviews, and a visually immersive UI with smooth animations.

⚠️ Important:
ReviewHub does not use hardcoded, default, or random locations.
All results are fetched strictly based on the user’s live GPS coordinates.

🎯 Core Objective (Very Important)

To build a location-accurate web application that:

Detects the user’s real-time latitude & longitude

Displays only nearby places within a defined radius (2–5 km)

Ensures authentic reviews by allowing reviews only from visited places

🚀 Application Flow
1️⃣ Landing Screen
UI Design

Centered title: “ReviewHub”

Black theme UI

RGB neon-highlight animated buttons

Smooth UI transitions

Dense snowfall animation with tiny particles

Continuous animated snowfall background

Action

Start Button to proceed

2️⃣ Location Permission (CRITICAL STEP)

Before login, the application explicitly requests location access.

Implementation

Uses Browser Geolocation API

Fetches GPS-based real-time latitude & longitude

User Prompt

“Allow location access to show nearby places”

If Permission is Denied

Display warning message:

❗ “Location access is required to show nearby places accurately.”

3️⃣ Authentication

Accessible only after location permission is granted.

Login Options

Email & Password (with validation)

Google Sign-In

Display 2–3 Google accounts

Selecting one logs the user in

🔒 Access is granted only after successful authentication

4️⃣ Main Dashboard

After login, the user is presented with two modules:

Explorer

Reviewer

5️⃣ Explorer Module (STRICT LOCATION-BASED RESULTS)
🚨 Judge-Critical Rule

All places must be:

Fetched using live GPS coordinates

Within a 2–5 km radius

No hardcoded cities or random locations

Categories Available

Hotels

Restaurants

Malls

Salons

Parks

Nearby Famous Places

Temples

Traveling

Bus Stops

Auto Stands

Metro Stations

Railway Stations

Petrol Bunks

Emergency

Nearby Hospitals (Always Visible)

📍 Location Accuracy Features

For every category:

Uses latitude & longitude

Distance-based filtering

Displays:

Distance from user (e.g., 1.2 km away)

Google Maps navigation button (exact location)

✔️ Results must match Google Maps output from the user’s current location.

🚌 Traveling Module (Advanced Feature)

Shows nearby bus stops only.

Displays:

All active bus numbers

Live location of each bus

Estimated arrival time to the user’s stop

📄 Place Details (Each Listing)

Each category displays 15+ nearby places, showing:

Place name

Exact location

Distance from user

Contact number

Real images

Influencer video previews

Authentic user reviews

Fake review percentage indicator (analytical)

Google Maps navigation button

6️⃣ Reviewer Module (Trusted Review System)
🔐 Key Rule

❗ Reviews cannot be posted from Explorer.

Reviewer Access

Shows only previously visited places

Review Flow

Select category

Select visited place

Submit review

After Submission

Redirects back to Reviewer

Review appears instantly in Explorer

🛡️ Ensures review authenticity — a major evaluation criterion

7️⃣ Profile Section (Top-Right Corner)

Accessible in both Explorer and Reviewer.

Profile Features

Profile photo

Email

Recent visits

Favorites

Notifications

Settings & Privacy

Language preferences

Logout Rules

Logout available only in Reviewer

Explorer has a Back button (top-left)

8️⃣ Logout & End Screen

After logout:

THANK YOU
Visit us again

🎨 UI & Animation Enhancements

Black UI with RGB glow accents

Smooth hover & click animations

Extra-dense snowfall animation

Continuous animated background

Modern, clean, professional design

🔄 Start & End Definition

Start: Landing screen with snowfall animation

End: Thank You screen after logout

📝 Final Note (For AI / Judges)

ReviewHub prioritizes:

✅ Real-time GPS-based location accuracy

✅ No hardcoded or mismatched locations

✅ Trusted and verified review system

✅ Modern UI with advanced animations
