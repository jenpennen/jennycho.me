---
title: "Scootly"
description: "Lorem ipsum dolor sit amet"
pubDate: "December 2022"
heroImage: "https://storage.googleapis.com/jennyencho-website/landing-img/scootly-landing.png"
---

## Context

> Reimagining urban mobility by turning personal scooters into a shared resource for everyone.

### Background

Scootly is a mobile app that allows users to rent out their personal scooters across Los Angeles. Driven by the urgent need to combat climate change, Scootly targets one of the most significant contributors: transportation. By offering a rideshare platform exclusively for eco-friendly micromobility vehicles, Scootly is redefining how we travel, making it greener, smarter, and more connected than ever before.

### Team

This project started in September 2022 as part of UCLA's infamous CS course: CS35L (Software Construction Laboratory). I teamed up with a fellow dev-signer Jeff, and four developers — Dwight, John, Madhavi, and Aparna. Spending many nights coding to bring Scootly to life, we were united by the challenges and rigor of the CS35L course and nurtured memorable and lasting friendships throughout the process!

### Problem

#### LA lacks a structured transportation system.

Like many American cities, LA’s public transportation system falls short, leaving residents with little choice but to rely heavily on cars. This dependence fuels a cycle of greenhouse gas emissions, exacerbating environmental challenges.

#### The Purchase Dilemma

Budget-conscious people, especially college students, often face a tough choice: should they purchase their own scooter or keep paying for rentals? Neither option seems ideal—owning and maintaining a personal scooter is too time-consuming, while constantly paying for short-term rentals from companies like Bird and Uber quickly becomes expensive.

> How can we motivate LA residents to embrace scooters as a viable transportation option?

### Goals

#### Promote micro-electric mobility

As LA's traffic worsens and intensifies climate change, it's time to embrace a solution that tackles both challenges head-on. We aim to reshape perceptions of scooters, presenting them as a practical, accessible mode of transportation for all.

#### Cater to every scooter rider.

The hurdles of owning a personal scooter often deter many from making the investment. With this in mind, we set out to make scooter ownership more appealing and rewarding, while also offering a convenient option for those who want to ride but aren’t ready to commit to buying their own.

## Research

### Guiding Principles

Creating an app centered around scooter rentals was not our first choice. We brainstormed solutions to everyday challenges faced by Angelenos. Our decision-making process for Scootly were guided by four key principles.

### Proposal

At UCLA, one thing is clear: scooters are a campus staple and offer an unbeatable convenience for getting around. For many students, scooters even outshine other eco-friendly transportation options like buses and carpools.

This observation begged the question: what if the environmental benefits of personal scooters could merge with the convenience of ridesharing? With this concept in mind, we laid the groundwork for Scootly. We identified key features needed for an eco-friendly rideshare experience and initiated the design process.

## Design Process

### Style Guide

#### Light Theme

Drawing from our core principles, I crafted a style guide that embodied Scootly’s mission for a cleaner and greener transportation future. I used shades of green and white to emphasize our commitment to eco-friendly transportation.

#### Dark Theme

Jeff, our fellow dev-signer, created a style guide that he believed best captured our guiding principles.

Ultimately, our team unanimously agreed that Jeff’s design better aligned with our vision for Scootly — simple, chic, and urban, making it the ideal style to resonate with Los Angeles residents.

### Wireframes

#### Low-Fi Wireframes

Our first priority was to quickly create low-fidelity mockups of the core features. With just two months to develop a functional MVP, these wireframes were essential for laying a strong foundation for coding.

#### Mid-Fi Wireframes

Next, we honed in on the app’s overall design while integrating technical feedback. We developed multiple versions of the key features to ensure we were working with the best possible design.

## Tech Process

### Web or Mobile?

As the capstone project for the CS35L course, students were required to develop a full-stack web application using React as a recommended tech stack. However, my team and I aimed to extend the project's scope beyond the standard requirements. We wanted Scootly to be accessible on both iOS and Android platforms. To achieve this, we opted to use React Native, directing our efforts toward the development of a cross-platform mobile application.

### Backend

For our backend, we used Firebase to manage user authentication and securely store user data. We first configured Firebase into our project, created a Firebase project in the Firebase Console, and integrated the Firebase SDK into our app. We then enabled various authentication methods, such as Email/Password and Google Sign-In, through Firebase’s Authentication section. We managed user sign-up, login, and logout using the Authentication API.

Once users were authenticated, we stored their information in Firebase Firestore. We set up a Firestore database, creating a document for each user to record essential details like email, display name, user preferences (vendor or renter), and registration date. We also configured Firebase Security Rules, allowing only authenticated users to access their own information.

## Final Work

### Onboarding

New users are greeted with a login/signup portal that caters to all types of users. Designed for simplicity, our two-part form enables full profile customization.

### Renter Dashboard

To encourage exploration, users can search and filter for the perfect ride based on factors like proximity, price, availability, and more. We’ve included all the essential information renters need to get to their destination.

### Vehicle Management

Scooter owners can now earn some extra cash with their scooters in a simple step! They can complete a quick form to rent out their vehicle, manage bookings, and communicate with renters seamlessly.

### Messaging

Scootly's in-app messaging platform ensures secure transactions and communication. With a special notification badge for new messages, users stay updated at all times.

## Impact

### Outcome

In the beginning of the course, our professor noted to a room of over 300 students that no capstone project has ever achieved commercial success. This revelation ignited a drive in my team and me to become the first.

Even after the quarter ended and we earned a perfect score on our project, we continued to refine Scootly with the goal of publishing it on the iOS App Store. As we continue to put in the final touches, we’re excited to see how Scootly will resonate with users and contribute to a more convenient and sustainable future!
