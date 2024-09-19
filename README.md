# PhotoGallery

PhotoGallery is an Android application designed for publication on the Google Play Store. The app fetches and displays thumbnail images from Flickr, providing users with a seamless browsing experience.

## Features

- **Image Fetching:** Utilizes Retrofit and Moshi for efficient network requests and JSON parsing, allowing for smooth retrieval of images from Flickr.

- **Dynamic Image Loading:** Implements Coil for dynamic image loading in a RecyclerView, ensuring smooth caching and management of placeholder images.

- **Asynchronous Operations:** Integrates Kotlin Coroutines to handle asynchronous image searches.

- **Full-Sized Image Viewing:** Includes a WebView for displaying full-sized images with a progress bar to enhance user experience.

- **Background Updates:** Utilizes WorkManager to implement a toggleable polling feature, enabling background updates and Notifications to alert users of new images.

## Technologies Used

- **Programming Languages:** Java, Kotlin
- **Development Tools:** Android Studio
- **Libraries:** Retrofit, Moshi, Coil, WorkManager
