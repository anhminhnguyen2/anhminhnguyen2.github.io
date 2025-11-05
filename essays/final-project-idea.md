---
layout: essay
type: essay
title: "Final Project Idea"
date: 2025-11-04
labels:
  - Software Engineering
  - Nextjs
---

Group member: Anh Minh Nguyen, Kyla Kanemoto, Kincade Morimoto

## Project: UH Class Planner
## Overview
The problem: Navigating the UHM campus can be challenging for everyone, including students, faculty, and visitors. When there are sudden problems, such as a full parking lot, blocked road, or amenities (broken elevator, toilet, on-site construction, etc), students are usually informed by their friends or scattered departmental announcements, making it difficult to plan their route. This lack of real-time announcements can lead to frustration and lost time while navigating through the campus.

The solution: ManoaMap+ is a real-time campus web application, presenting the conditions around campus. Users can see live reports about campus conditions when inputting the location they want to check in real time (“Lot 20 full,” “Elevator in Kuykendall out of order”, etc). 

## Approach
The application will fetch information from reliable sources, such as the campus’ and departments’ social media, or from reporters (UH staff members or verified students) who can verify or update location reports.

Users can log in to save their information and preferences (favorite locations, view history, or notifications)

Some possible mockup pages:
Landing Page – Introduces ManoaMap+ and provides login options.
User Home Page – Displays personalized map view, favorite locations, and current alerts.
Reporter Dashboard – Allows users with permissions to verify, edit, or remove reports.
Admin Home Page – Enables management of users, permissions, and master campus data.
Add Report Page – Form to submit a new live report (location and categories: parking, barrier, accessibility issue, other).
User Profile Page – Lets users manage preferences, notification settings, and favorites.
Live Map Page – Main interactive map with filter options.

## Use case ideas
New users need to sign up with either personal or school email address.
A school email address is needed to sign up to be a “reporter”.

New user goes to landing page, logs in, user home page appears, sets up profile
Admin user goes to landing page, logs in, user home page appears, can edit the web app.
User goes to landing page, logs in, user home page appears
User favorites Lot 20, logs out, logs back in, user home page appears (updates are highlighted)

## Beyond the basics
Notify students via email or SMS for new reports or that status has changed
AI Recommendations based on past user behavior (updates about similar locations; “You visit Hamilton Library often, new barrier reported nearby”)
