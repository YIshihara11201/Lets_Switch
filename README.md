# Let's Switch

`GCD` / `MVVM` / `UserNotifications` / `PostgreSQL` / `Structured Concurrency` / `SwiftUI` / `Vapor` / `WebSockets`

## Release
I published the app to the App Store!🎉  [App Store Link](https://apps.apple.com/us/app/lets-switch/id1662123590)  

![App Store screenshots](https://user-images.githubusercontent.com/98417271/218228757-01e623f4-418a-4884-903f-4f5dd93bff9d.png)

## Introduction

### Backgorund
Switching tasks is always hard, especially you are studying, learning new things on your own. Once you finish studying math, you must feel unwilling to start reading history textbook. Without some kind of pressure, switching tasks is painstaking. I always feel guilty after realizing how valuable the time I was procrastinating was.

### Solution
This application takes advantage of peer pressure that you gain when you declare to do something in front of others. You will register your task in advance for some time slots in a day to match other user’s task. When the time comes, you are invited to matching room, there, you can send and receive ale to and from your partner, which will boost your motivation.

### Features
- PushNotifications
- WebSockets
- Database management for task scheduling with Vapor

### Requirements
- Swift: version 5.6
- iOS: 16.1 or later
- Vapor: version 4.0

## Usage

1. You will register a task. According to registration state, you will see different messages.


![slots{700:194/100}](https://user-images.githubusercontent.com/98417271/217910252-30dd857f-5a7b-4ea6-b293-41a8927171fe.png)

2. One minute before the registered time, you will receive push notification and can enter the matching room.

3. In the matching room, you and your partner can send ale to cheer up each other.

![demo{250:100/216}](https://user-images.githubusercontent.com/98417271/218219662-45b462de-f01c-4d3a-9c21-6249fc50ba26.gif)

4. You made a commitment, and will have no way to procrastinate switching tasks.


## Server-side
[Server-side implementation](https://github.com/YIshihara11201/Lets_Switch_server-side)
