
# Level 3 Questions

## Which stages of an activity lifecycle exists?

 - onCreate
 - onStart
 - onResume
 - onPause
 - onStop
 - onDestroy

## Which are the two kind of intents, and what is the difference?  
- There are two types of intents. The explicit **intent**, this means you specify the component to start by name. the **implicit** intent means that you do not specify the action: **Intent intent = new Intent(this, Target)** 

## What is the difference between Parcelables and Serializables?
- **Parcel able** is faster than **serializable**. **Parcel able** is going to convert object to byte stream and pass the data **between** two activities. It doesn't create more temp objects while passing the data **between** two activities

## What is the purpose of the analyzer?
- **Android** Studio includes an APK **Analyzer** that provides immediate insight into the composition of your APK after the build process completes. Using the APK **Analyzer** can reduce the time you spend debugging issues with DEX files and resources within your app, and help reduce your APK size.
