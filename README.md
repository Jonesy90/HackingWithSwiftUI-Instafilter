# Hacking With SwiftUI - Instafilter

## Overview/Description
The task of this project was to build an app that lets the user import photos from their library, then modify them using various image effects (using Core Image).

## What I Learned
1. Using the @Environment property wrapper with 'requestReview'. Using this provides an alert that allows the user to provide a review of the app and how to use it effectively.
2. More usage of the @AppStorage property wrapper. Again, this is used to hold very small amounts of data.
3. Introduction to PhotoPicker. This provides a view to the user so they can browse and select a photo.
4. Introduction to using ContentUnavailable. In this app it was used to show a custom unavailable message to the user if a Image was not displaying in the PhotoPicker.
5. Using Core Image is something I understand but can be quite confusing on how to actually use it. From what I understand because it hasn't fully integrated with SwiftUI (and Image). We are required to take the selected image (using PhotoPicker), convert it to a Data type, convert the Data type into a UIImage, then covert the UIImage into CIImage, apply the filters we required then convert the CIImage to Image. Then take that Image and display it in the PhotoPicker view.

## What it looks like
<img width="201" height="437" alt="Simulator Screenshot - iPhone 17 Pro - 2026-06-30 at 15 17 49" src="https://github.com/user-attachments/assets/2a67e340-07ac-4114-82f3-3e4a8ad71b6c" />
<img width="201" height="437" alt="Simulator Screenshot - iPhone 17 Pro - 2026-06-30 at 15 17 59" src="https://github.com/user-attachments/assets/c8a32ee5-71c3-48a4-b25a-c45d89fab7f4" />
<img width="201" height="437" alt="Simulator Screenshot - iPhone 17 Pro - 2026-06-30 at 15 18 06" src="https://github.com/user-attachments/assets/776788c7-0868-45fa-920a-befcf3b15f3e" />
<img width="201" height="437" alt="Simulator Screenshot - iPhone 17 Pro - 2026-06-30 at 15 18 14" src="https://github.com/user-attachments/assets/3a32012a-5b08-4029-857a-463444ad221f" />

## Personal Challenges
TBC
