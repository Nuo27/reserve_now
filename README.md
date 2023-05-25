# 2023 iOS Dev Assignment3 repo

This repository is dedicated to 2023 Autumn Assignment 3 in the course 41889 & 42889 Application Development in the iOS Environment.

The assignment focuses on developing an online booking app for restaurants and **completed by Nuo Chen as a group of one.**

This app is designed to be used by both customers and restaurant staff. Customers can use the app to book and cancel a reservation at a restaurant, while restaurant staff can use the app to view and manage bookings. Please refer to Features and Usage section for more details.

The GitHub repository link for the project is: https://github.com/Nuo27/iOS_Assignment3

After submission, the project will be set to public for review and evaluation.

---

In this repo:

- [2023 iOS Dev Assignment3 repo](#2023-ios-dev-assignment3-repo)
  - [Introduction](#introduction)
  - [Plz notify that](#plz-notify-that)
  - [Basic Build info](#basic-build-info)
  - [Features and Usage](#features-and-usage)
      - [Customer](#customer)
      - [Staff](#staff)
      - [Functions](#functions)
  - [Iteration product design cycle](#iteration-product-design-cycle)
      - [Iteration 1: May 7th - May 14th](#iteration-1-may-7th---may-14th)
      - [Iteration 2: May 14th - May 16th](#iteration-2-may-14th---may-16th)
      - [Iteration 3: May 16th - May 23th](#iteration-3-may-16th---may-23th)
      - [Iteration 4: may 23th - May 26th](#iteration-4-may-23th---may-26th)
  - [Used external tools](#used-external-tools)
      - [Cocoapods:](#cocoapods)
      - [OHMySQL:](#ohmysql)
      - [db4free:](#db4free)
  - [Copyright](#copyright)

---

## Introduction

The purpose of this assignment is to create a user-friendly app that facilitates online booking system for restaurants. The app caters to both customers and restaurant staff, providing a seamless experience for both parties.

---

## Plz notify that

I used a free online database as the backend support, this app may not work properly after the database is closed. That is also to say, the app may be running slow due to the physical distance between the database and the app.

Assignment due date: 2023-05-26

---

## Basic Build info

Xcode 14.3(14E222b)

Deployment: iOS 16.4

Build system: Xcode Build System

Bundle Identifier: au.edu.uts.iOS-Assignment3

---

## Features and Usage

#### Customer

- Select Date and time Slot
- check time Slot availability
- Place booking with customer details
- Confirm details printed out
- view maded booking records
- cancel maded booking records

#### Staff

- Login with admin ID and password (admin/admin in default)
- Select Date and time Slot
- View all booking records
- Cancel any booking

#### Functions

- Settings -> view local stored Receipts ID
- Settings -> clear all local stored Receipts ID
- input validation null check
- Input validation for Name -> only accept letters and no space included
- Input validation for Phone -> 10-digit number only
- Input validation for Email -> email format only
- auto-adjust partySize according to the availability but limited to 10
- etc...

---

## Iteration product design cycle

Start with a defining all the features that the app should have, then design the UI and the flow of the app.

**Then enter the my iteration cycle from:**

- sum up bugs left or possible improvement from last iteration
- define new features that the app should have
- implement functions
- test and debug
- sum up bugs left or possible improvement from this iteration

**I have 4 iterations in total, and an approximate timeline in header of each iteration.**

where the overall length of project is about 20 days.

#### Iteration 1: May 7th - May 14th

- setup the project
- create views and UI
- create basic view crossing functions
- test and debug

#### Iteration 2: May 14th - May 16th

- create Model customer
- create Controllers
- implement local logic customer booking functions
- test and debug

#### Iteration 3: May 16th - May 23th

- implement cocoaPods and OHMySQL -> connect to database
- rewrite/create all local logic customer booking functions to database functions
- input validation
- restructure the project features and views
- test and debug

#### Iteration 4: may 23th - May 26th

- sum up bugs left or possible improvement from last iteration
- design UI visual
- implement UI visual
- test and debug
- submit

---

## Used external tools

In order to enhance the functionality of the app, the following external tools were utilized:

#### Cocoapods:

Cocoapods is a dependency manager for iOS projects. The official Cocoapods website can be found at https://cocoapods.org/.

#### OHMySQL:

OHMySQL is an open-source Objective-C library that allows developers to connect their iOS apps to MySQL databases. The OHMySQL library can be found on GitHub at https://github.com/oleghnidets/OHMySQL.

#### db4free:

db4free is a free MySQL database hosting service. The db4free website can be accessed at https://www.db4free.net/.

:heart: This is a special thanks from Nuo to the developers of these tools. :heart:

---

## Copyright

It is important to note that this app is created solely for educational purposes as part of an assignment. The records stored in the database used by the app are entirely fictional and do not represent any real-life individuals. The app and its contents are not intended for commercial use, copying for future assignments, or any other purposes beyond the scope of this assignment.
