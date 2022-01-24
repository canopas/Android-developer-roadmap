<h1 align="center">Android Developer Roadmap 2022</h1>

![alt text](https://github.com/cp-radhika-s/Android-Roadmap/blob/main/image/og_image.png)


 Android Developer Roadmap 2022 is learning paths to understanding Android development.
 
## How to Learn Android?

In Android, programming is done in two languages JAVA or Kotlin and Jetpack Compose(Declarative UI) or XML(Extension Markup Language). The XML file deals with the design, presentation, layouts, blueprint, etc (as a front-end) while the JAVA or KOTLIN deals with working of buttons, variables, storing, etc (as a back-end). And the biggest confusion for an Android beginner is which language to choose between Java and Kotlin? So let me try to overcome the confusion first. 
### Java or Kotlin?

Java is the official language for Android App Development and consequently, it is the most used language as well. Kotlin has also been introduced as a “official” Java language in 2017. Kotlin is much simpler for beginners to try as compared to Java and it can also be used as an “entry point” for Android App Development. So my recommendation for a beginner is to go with Java first, then jump to Kotlin.

# Table of contents
* [Sprint 1](https://github.com/canopas/Canopas-Android-Roadmap#sprint-1)
* [Sprint 2](https://github.com/canopas/Canopas-Android-Roadmap#sprint-2)
* [Sprint 3](https://github.com/canopas/Canopas-Android-Roadmap#sprint-3)
* [Sprint 4](https://github.com/canopas/Canopas-Android-Roadmap#sprint-4)
* [Sprint 5](https://github.com/canopas/Canopas-Android-Roadmap#sprint-5)
* [Sprint 6](https://github.com/canopas/Canopas-Android-Roadmap#sprint-6)

#### Let's start with basic learning

## Sprint 1

### Java basics

* Introduction to [Java Programming](https://www.udacity.com/course/java-programming-basics--ud282)
* [Object Oriented Programming (OOPs)](https://www.geeksforgeeks.org/object-oriented-programming-oops-concept-in-java/) Concept in Java
* Java difference between [primitive type and class types](https://stackoverflow.com/questions/5199359/why-do-people-still-use-primitive-types-in-java)

### Android basics

* [7 Key Android Concepts](https://www.macadamian.com/learn/7-key-android-concepts/)
* Android [best practices](https://github.com/futurice/android-best-practices)
* Introduction to [Activities](https://developer.android.com/guide/components/activities/intro-activities)
* Understand The [Activity Lifecycle](https://developer.android.com/guide/components/activities/activity-lifecycle)
* Understand The [Fragments](https://developer.android.com/guide/fragments)

#### Practicle 1.1
* Button click counter application
    - Write an application which counts the number of button clicks and shows the click count  on  the app screen.
    
### Delightful user experience     
*  [User Interface](https://www.udacity.com/course/android-basics-user-interface--ud834)
*  Basic knowledge of 
      - [Material designs](https://material.io/design/introduction)
      - [Drawables](https://developer.android.com/reference/android/graphics/drawable/Drawable) 
      - [Styles and theme](https://developer.android.com/guide/topics/ui/look-and-feel/themes)

#### Practicle 1.2 
Create the [scorekeeper](https://developer.android.com/codelabs/android-training-drawables-styles-and-themes#1) application.

### Code Style

A quick look on [Java](https://source.android.com/setup/contribute/code-style) and [Android](https://blog.mindorks.com/android-code-style-and-guidelines-d5f80453d5c7) code style

### Json
* Introduction of [Json](https://www.softwaretestinghelp.com/json-tutorial/)
* [What is JSON and why would I use it?](https://stackoverflow.com/questions/383692/what-is-json-and-what-is-it-used-for)
* [Json vs XML](https://beginnersbook.com/2015/04/json-tutorial/)    

### Version control system
* Introduction to version control: [What Is Version Control?](http://guides.beanstalkapp.com/version-control/intro-to-version-control.html)
* How to use git
    -  [Version control with git](https://www.udacity.com/course/version-control-with-git--ud123)
    -  [Git: The Beginner's Guide to Understanding Core Version Control Concepts](https://www.freecodecamp.org/news/git-the-laymans-guide-to-understanding-the-core-concepts/)
    -  [When to commit in version control](https://softwareengineering.stackexchange.com/questions/74764/how-often-should-i-do-you-make-commits)

### Android Permission
#### Practicle 1.3
* Write an application to request read and write storage permission on button click and Show result on the screen. 
#### References
* [Permissions overview](https://developer.android.com/guide/topics/permissions/overview)
* [Storage updates in Android 11](https://developer.android.com/about/versions/11/privacy/storage)

###  User interaction 
#### Practicle 1.4
* Write an application that has two edit texts for user name and user phone number, button and recycler view, shows user inputs in recycler view on button click. 
#### References
* Android From Scratch: [Understanding Views And View Groups](https://code.tutsplus.com/tutorials/android-from-scratch-understanding-views-and-view-groups--cms-26043)
* Build a Responsive UI with [ConstraintLayout](https://developer.android.com/training/constraint-layout)
* Recyclerview
      - Recyclerview [component](https://medium.com/android-news/understanding-recyclerview-components-part-2-1fd43001a98f)
      - Recyclerview [Pro Tip](https://proandroiddev.com/recyclerview-pro-tips-part-1-8a291594bafc)

## Sprint 2

### Kotin for android development
> Kotlin is a great fit for developing Android applications, bringing all of the advantages of a   modern language to the Android platform.

* [Java vs kotlin](https://www.moveoapps.com/blog/java-vs-kotlin/)
* [Kotlin basic](https://kotlinlang.org/docs/basic-syntax.html)
* [Setup kotlin](https://kotlinlang.org/docs/android-overview.html) in android studio
* [Android App Development Masterclass using Kotlin](https://www.udemy.com/course/android-oreo-kotlin-app-masterclass/) 

### Working in background

#### Practicle 2.1
* Write an application that lets the user trigger, update and cancel a notification using three buttons.
#### Practicle 2.2
* Create a broadcast receiver which listens to telephone state changes. If the phone receives a phone call, then the receiver will be notified and log a message.
#### Practicle 2.3
* Create a music player which play music in background 
#### References
* Guide to [background processing](https://developer.android.com/guide/background)
* [Broadcasts](https://developer.android.com/guide/components/broadcasts)    
* [Services](https://developer.android.com/guide/components/services) 

### Saving user data
#### Practicle 2.4
* Imaplement Todo task reminder application.     
#### References
* Introduction of database:[Udemy section 10](https://www.udemy.com/course/android-oreo-kotlin-app-masterclass/) : lecture 177 - 178 
* [Data and file storage](https://developer.android.com/training/data-storage) overview
* [Shared preferences](https://developer.android.com/training/data-storage/shared-preferences)

#####  Save data in local database
* Introduction of database:[Udemy section 10](https://www.udemy.com/course/android-oreo-kotlin-app-masterclass/) : lecture 189 to 191  
* Save data using [SQLite](https://developer.android.com/training/data-storage/sqlite) 
* Storing data with [Room](https://developer.android.com/training/data-storage/room)

# Advance Learning

## Sprint 3
> Now it’s time to dive into the real development with 50% work and 50% training daily

### Jetpack compose
#### Practical 3.1
* Create a Login registration form using Compose UI.
* Create a UI like [this](https://github.com/cp-radhika-s/Android-Roadmap/blob/main/image/screenshot_2.png) 
#### References
* [Setup](https://developer.android.com/jetpack/compose/setup)
* [Jetpack compose basics](https://developer.android.com/jetpack/compose/tutorial?gclid=Cj0KCQjwktKFBhCkARIsAJeDT0ild-qffsVE98m2uwRTmjnj5LRAH2yAm9GCFKzPvYZfw-RbHKFsZUsaArEgEALw_wcB&gclsrc=aw.ds) 

### Android Networking
#### Practicle 3.2
* Retrieve and display a simple users list from web API to Android recyclerview using the retrofit library. Display Name, email, and city in Recyclerview and delete the user on a long item click.
  -  **GET Api Url**: http://jsonplaceholder.typicode.com/users
#### References
* [OkHttp](https://square.github.io/okhttp/)
* Typesafe HTTP client for android: [Retrofit](https://square.github.io/retrofit/)

## Sprint 4

### App Architecture
* [Guide to app architecture](https://developer.android.com/jetpack/guide)
* Android [Application Architecture](https://medium.com/oceanize-geeks/android-application-architecture-189b4721c7c5)
  - Android [MVP Architecture](https://androidwave.com/android-mvp-architecture-for-beginners-demo-app/)
  - Android Architecture Patterns: [Model-View-ViewModel](https://medium.com/upday-devs/android-architecture-patterns-part-3-model-view-viewmodel-e7eeee76b73b) 
  - Android [MVVM Design Pattern](https://www.journaldev.com/20292/android-mvvm-design-pattern)

### ViewModel and LiveData
#### Practicle 4.1
* Use liveData and viewModel  in practical 3.2
#### References
* [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel)
* [LiveData](https://developer.android.com/topic/libraries/architecture/livedata) 
* [Udemy section 11](https://www.udemy.com/course/android-oreo-kotlin-app-masterclass/)

## Sprint 5

### RxJava and RxAndroid
#### Practical 5.1
* Create an android application to show a list of movies in recycler view using rxjava and retrofit using MVP architecture, use coil to display images.
   - **GET API Url**  : https://api.androidhive.info/json/movies.json
* Self exercise: Write an open-source project to cover operators of rxjava such as map, flat map, combine, zip  etc...

#### References
* [Rxjava](https://github.com/ReactiveX/RxJava) and [RxAndroid](https://github.com/ReactiveX/RxAndroid)
    - Part 1:  [The Basics](https://blog.danlew.net/2014/09/15/grokking-rxjava-part-1/)
    - Part 2:  [Operator, Operator](https://blog.danlew.net/2014/09/22/grokking-rxjava-part-2/)
    - Part 3:  [Reactive with Benefits](https://blog.danlew.net/2014/09/30/grokking-rxjava-part-3/)
    - Part 4:  [Reactive Android](https://blog.danlew.net/2014/10/08/grokking-rxjava-part-4/)
* **Example:** [Rxjava with retrofit](https://www.freecodecamp.org/news/how-to-set-up-networking-in-your-android-app-with-retrofit-rxjava-mvp-108e7153521a/) 

### Hilt
#### Practical 5.2
* Retrieve and display a simple users list from web API to Android recycler view using retrofit. Display name, email and city in recyclerView. Store users in database. **GET Api Url** : http://jsonplaceholder.typicode.com/users
* On user item click display all albums of selected user  on next screen. **GET Api Url**  : https://jsonplaceholder.typicode.com/albums?userId=1
* On the Album item click show all photos of the selected album on the next screen.**GET Api Url** : http://jsonplaceholder.typicode.com/photos?albumId=2


#### References
* [Dependency injection](https://developer.android.com/training/dependency-injection)
* [Dependency injection with Hilt](https://developer.android.com/training/dependency-injection/hilt-android)
* [Hilt](https://dagger.dev/hilt/)

## Sprint 6

### Kotlin coroutines
* [Coroutines Overview](https://kotlinlang.org/docs/coroutines-overview.html)
* [Thread vs. Coroutines](https://www.youtube.com/watch?v=C38lG2wraoo&list=PLlxmoA0rQ-LwgK1JsnMsakYNACYGa1cjR)
* [Kotlin coroutines on Android](https://developer.android.com/kotlin/coroutines)
* Background processing using coroutines- [Udemy section 12: lecture 276](https://www.udemy.com/course/android-oreo-kotlin-app-masterclass/)

### Kotlin Flow
#### Practicle 6.1
* Make a calculator application. Save calculation history in the database. Users can view history and clear history.
#### Practicle 6.2
* Implament Makeup application. Retrive makeup list from api, also show full detail on item click
* **API** http://makeup-api.herokuapp.com/api/v1/products.json?brand=maybelline
#### References
* [Kotlin flow](https://developer.android.com/kotlin/flow) on android
* [Learn advance coroutine with kotlin flow and LiveData](https://developer.android.com/codelabs/advanced-kotlin-coroutines#0)

#### StateFlow and SharedFlow 
* [StateFlow and SharedFlow](https://developer.android.com/kotlin/flow/stateflow-and-sharedflow)
* [Reactive Streams on Kotlin: SharedFlow and StateFlow](https://www.raywenderlich.com/22030171-reactive-streams-on-kotlin-sharedflow-and-stateflow)


## Extra
#### Useful libraries
* [Glide](https://github.com/bumptech/glide) for loading and caching images
* [Timber](https://github.com/JakeWharton/timber) : Very useful library for logging
* [EventBus](https://github.com/greenrobot/EventBus) - Android optimized event bus that simplifies communication between Activities, Fragments, Threads, Services, etc. Less code, better quality.
* [Coil](https://coil-kt.github.io/coil/) An image loading library for Android backed by Kotlin Coroutines.




