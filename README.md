# Kotlin Multiplatform Project Example

This project is a minimum mpp project.  

This application has Android, iOS, Web and Server modules.  
The server returns a simple JSON object and clients show it on each view.

## Example for

I made this repository for explaining my presentation and book.  
I'm sorry both are in Japanese.

* Kotlin Fest 2019発表時のサンプルは[こちら](https://github.com/AAkira/mpp-example/tree/KotlinFest2019)  
Tag: KotlinFest2019   
Slide link: [Speaker deck](https://speakerdeck.com/aakira/introduction-kotlin-mpp)

* みんなのKotlin執筆時のサンプルは[こちら](https://github.com/AAkira/mpp-example/tree/KotlinForEveryone)  
Tag: KotlinForEveryone   
Book link: [Amazon](https://amzn.to/2FZRLiZ)

## Run on each platform 

### Android

It works on Android Studio.

![preview-android][preview-android]

### iOS

It works on XCode.

![preview-ios][preview-ios]

### Web

It works on Web browsers.

![preview-web][preview-web]

* Build command

`./gradlew :web:browserWebpack`

* Open this file on your browser after building.

`/web/src/main/resources/index.html`

### Server

It works on localhost:8080.

![preview-server][preview-server]

* Run

`./gradlew :server:run`

[preview-android]: /arts/mpp-android.jpg
[preview-ios]: /arts/mpp-ios.jpg
[preview-web]: /arts/mpp-web.jpg
[preview-server]: /arts/mpp-server.jpg
