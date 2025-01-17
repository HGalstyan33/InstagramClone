# Project 3 - *InstaClone*

**InstaClone** is a photo sharing app similar to Instagram but using Parse as its backend.

---

## Part 2

Time spent: **15** hours spent in total

## User Stories

The following **required** functionality is completed:

- [X] User can view the last 20 posts submitted to "Instagram".
- [X] The user should switch between different tabs - viewing all posts (feed view), compose (capture photos form camera) and profile tabs (posts made) using fragments and a Bottom Navigation View.
- [X] User can pull to refresh the last 20 posts submitted to "Instagram".

The following **optional** features are implemented:

- [X] User sees app icon in home screen and styled bottom navigation view
- [X] Style the feed to look like the real Instagram feed.
- [X] User can load more posts once he or she reaches the bottom of the feed using infinite scrolling.
- [X] Show the username and creation time for each post.
- [ ] User can tap a post to view post details, including timestamp and caption.
- [ ] User Profiles 
    - [ ] Allow the logged in user to add a profile photo 
    - [X] Display the profile photo with each post 
    - [ ] Tapping on a post's username or profile photo goes to that user's profile page and shows a grid view of the user's posts 
- [ ] User can comment on a post and see all comments for each post in the post details screen.
- [ ] User can like a post and see number of likes for each post in the post details screen.

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src="InstaClone2.gif?raw=true" width="250px">

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

- Setting the time format
- Being able to save profile pictures
- Like, comment, direct, and save functionalities not loading

---

## Part 1

Time spent: **12** hours spent in total

## User Stories

The following **required** functionality is completed:

- [X] User can sign up to create a new account using Parse authentication.
- [X] User can log in and log out of his or her account.
- [X] The current signed in user is persisted across app restarts.
- [X] User can take a photo, add a caption, and post it to "Instagram".

The following **optional** features are implemented:

- [X] User sees app icon in home screen and styled bottom navigation view.
- [X] Style the feed to look like the real Instagram feed.
- [X] After the user submits a new post, show an indeterminate progress bar while the post is being uploaded to Parse.

The following **additional** features are implemented:

- [X] Splash screen when opening the app

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src="InstaClone.gif?raw=true" width="250px">

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

- How to setup the menu so it looked organized
- Setting up the bottom navigation
- Programming the logout button

## Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

## License

    Copyright [2020] [Hasmik Galstyan]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
