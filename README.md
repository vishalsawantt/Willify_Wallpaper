# Wallpaper App

This Android application allows users to browse and search for high-quality wallpapers using the **Pexels API**. Users can download images, share them with others, 
and set them as wallpaper on their mobile devices.


## Features

- **Browse & Search**: Explore a variety of high-quality wallpapers from Pexels.
- **Download**: Save wallpapers to your device's local storage.
- **Set as Wallpaper**: Set any wallpaper directly from the app.
- **Share**: Share your favorite wallpapers with friends or on social media.
- **Full-Screen View**: Zoom in and out of images for a detailed view.


## Screenshots

1. **SplashScreenActivity**, **MainActivity**, and **FullScreenActivity**  
   <div style="display: flex; justify-content: space-between;">
      <img src="https://github.com/user-attachments/assets/db42f59a-97c7-410a-bb3a-6e3f1d032e51" alt="CreateAccount_activity" width="200" style="border: 1px solid #000;">
      <img src="https://github.com/user-attachments/assets/2c0e06bb-0d1d-4a13-b575-0a78a3cbdc4b" alt="Login_Activity" width="200" style="border: 1px solid #000;">
      <img src="https://github.com/user-attachments/assets/a62884ac-9e75-4f86-bf54-8bd89b8e8cbd" alt="Login_Activity" width="200" style="border: 1px solid #000;">
  </div>



## How it Works

1. **Fetching Images**: The app uses the Pexels API to retrieve high-quality images.
2. **Image Interaction**:
   - View the image in fullscreen with zoom-in/zoom-out functionality.
   - Download the image for offline viewing or to set it as your wallpaper.
   - Share the image via other apps or social media platforms.


## Tech Stack

- **Android Studio**: Development IDE
- **Java**: Primary programming language
- **Pexels API**: For fetching high-quality images
- **Picasso**: Image loading and caching library
- **ZoomageView**: For image zoom functionality
- **ConstraintLayout & RecyclerView**: For UI and layout management


## Pexels API Integration

The app integrates with the [Pexels API](https://www.pexels.com/api/) to fetch high-quality images. You need to get an API key from Pexels and add it to your project in order
to use the API.

- Sign up at [Pexels](https://www.pexels.com/api/) to obtain your API key.
- Replace the API key in your code at the appropriate places.


## Permissions

The app requests the following permissions to work properly:

- Internet Access: To fetch images from the Pexels API.
- Storage Access: To save downloaded images to your device.
- Set Wallpaper: To allow the app to set an image as your wallpaper.


# Download APK

You can download the latest release of the app directly from the following link:

[Download APK](app/release/app-release.apk)


## Contact

For any questions or feedback, please feel free to reach out at [sawantvishal2001@gmail.com].  


