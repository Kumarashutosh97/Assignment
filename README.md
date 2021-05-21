# Assignment
A assignment project in which have all new coding structured follows
<h3>Building using Android Studio...</h3>

1. Open Android Studio and launch the Android SDK manager from it (Tools | Android | SDK Manager)
1. Ensure the following components are installed and updated to the latest version.
   1. *Android SDK Platform-Tools*
   1. *Android Support Repository*
   1. *Google Repository*
   
   
**IMPORTANT** Ensure you have set the ANDROID_HOME environment variable.

    SDk location
    sdk.dir=/home/ashutosh/Android/Sdk
    ./gradlew build
    
  ## Steps for run Code
  1. Clone the https://github.com/Kumarashutosh97/Assignment
  2. Sync the gradle
  3. Connect the device/ Emulator
  4. Run the project
  *Note* - Please create a project on NY times for API_Key and use own key for run the application/
  
  ## Architecture 🗼
This app uses [***MVVM (Model View View-Model)***](https://developer.android.com/jetpack/docs/guide#recommended-app-arch) architecture.

  
  ## Built With 🛠
- [Kotlin](https://kotlinlang.org/) - First class and official programming language for Android development.
- [Coroutines](https://kotlinlang.org/docs/reference/coroutines-overview.html) - For asynchronous and more..
- [Android Architecture Components](https://developer.android.com/topic/libraries/architecture) - Collection of libraries that help you design robust, testable, and maintainable apps.
  - [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel) - Stores UI-related data that isn't destroyed on UI changes. 
- [Material Components for Android](https://github.com/material-components/material-components-android) - Modular and customizable Material Design UI components for Android.
 - [NY times API] - API for fetching most popular data within 7 days.
 - [Kotlin delegate]- The Delegation pattern has proven to be a good alternative to implementation inheritance, and Kotlin supports it natively requiring zero boilerplate code.
 - [Data binding] -The Data Binding Library is a support library that allows you to bind UI components in your layouts to data sources in your app using a declarative format rather than programmatically.
 - [Dagger 2] -agger 2 is dependency injection framework. It is based on the Java Specification Request (JSR) 330. It uses code generation and is based on annotations.
<br />

## Package Structure 📦
    
    com.assigmnent.cleararchitecture # Root Package
    ├── data                         # Model class
    ├── DI                           # Dagger 2 packages.
    |
    ├── ktx                          # Kotlin Delegat method for Data binding
    |
    |___network                      # Retrofit provides and service API
    |
    ├── UI                           # Activity/Fragment View layer
    │   ├── Adapter                  # Adapter class
    │   ├── master                   # Master Activity
    │   ├── ViewModel                # Add ViewModel
    │   ├── Webview                  # Details Activity
    ├── utils                        # All Utils classes


<br />



