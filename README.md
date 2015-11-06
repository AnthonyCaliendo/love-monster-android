# Love Monster Unleashed

## Overview

Love Monster Unleashed is an Android client to the Love Monster web
application. It makes it easy to see recent loves, send love, and view
activity data for individual users. It is a fast, convenient, and fun
way to show appreciation to your friends, family, or co-workers.

Time Spent: **0** hours.

## User Stories

The following **required** functionality is completed:

* [] Display a page of the most recent loves, including To, From,
  Reason, and the optional message.
* [] "Send Love" button that renders an activity that allows the user to
  select a receipient using a type-ahead dropdown, specify the reason
and optional longer message, then click Send to post the love to the API 
* [] Click on a user to render a user detail page, showing recently sent
  and received loves.
* [] Settings page to specify connection information that gets stored in
  User Preferences keystore
* [] Authentication with Okta
* [] The user can click an icon representing themselves to see a
  rendering of their own activity.

The following **optional** features are implemented:

* [] Infinite scrolling of loves, fetching more from the API
* [] Allow input and rendering of github emoticons like the main web app does
* [] Render users' profile pictures
* [] Render the "likes" functionality, showing what other users like a
  particular love.

## Notes

## Open-source libraries used

- [Android Async HTTP](https://github.com/loopj/android-async-http) - Simple asynchronous HTTP requests with JSON parsing
- [Picasso](http://square.github.io/picasso/) - Image loading and caching library for Android

## License

    Copyright 2015 Devin Breen, Anthony Caliendo, Ben Schmeckpeper

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
