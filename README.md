# Instagram-Like UI Layout

## Overview
This project contains an XML layout file for an Android application designed to mimic the Instagram interface. It utilizes `RelativeLayout`, `CardView`, `ImageView`, and `TextView` elements to create a UI with profile stories, posts, and interactive icons.

## Features
- **Instagram-Style Header:** Includes a title, messenger icon, heart icon, and more options.
- **Story Highlights:** Circular profile images using `CardView` and `ShapeableImageView`.
- **Main Post Section:** Displays a sample post with profile details and interactive buttons (like, comment, share, save).
- **Profile Sections:** Uses custom drawable resources for profile images and story borders.

## Dependencies
- AndroidX `CardView`
- Google Material Components for `ShapeableImageView`

## XML Components Breakdown
- **`RelativeLayout`**: Used as the main container for organizing UI elements.
- **`TextView`**: Displays text and icons (heart, comment, send, save).
- **`ImageView`**: Used for profile pictures, posts, and icons.
- **`CardView`**: Provides rounded profile and story images.

## Resources Used
- `@drawable/messenger` - Messenger icon
- `@drawable/heart` - Like button icon
- `@drawable/more` - More options icon
- `@drawable/stories_border` - Border around stories
- `@drawable/mine`, `@drawable/jisoo`, `@drawable/eunwoo`, `@drawable/moon`, `@drawable/hwang` - Profile pictures
- `@drawable/post` - Main Instagram-like post image
- `@drawable/mountain` - Background image for additional UI section

## Screenshot
Below is an image of the rendered layout representing this design.

![image alt](https://github.com/AilaArshad/Instagram/blob/7422282e0041847cab525b36e8b5e802016a8c18/Preview.png)
