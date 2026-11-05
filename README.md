<div align="center">
  <h1>🛰️ NewsOrbit</h1>
  <p><strong>News from Earth, pictures from space.</strong></p>

  ![Android](https://img.shields.io/badge/Android-6.0+-3DDC84?logo=android&logoColor=white)
  ![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)
  ![SQLite](https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white)
</div>

## About

An Android app I built in Java. Read the latest BBC headlines from the US & Canada, or look up NASA's picture of the day for any date.

## Features

**News**
- Browse the latest headlines
- Open a story to see its summary, date and link
- Save your favorites and long press to delete them

**NASA pictures**
- Pick a date and see that day's picture
- Get links to the normal and HD versions
- Save pictures in the app and long press to delete them

## Run it locally

1. Clone the repo:

   ```bash
   git clone https://github.com/PranavTiwari44/BBC-News-Reader.git
   ```

2. Open the project in Android Studio and let Gradle sync.
3. Set the Gradle JDK to Java 8 or 11, since this project uses Gradle 5.4.1.
4. Run it on an emulator or a phone with Android 6.0 or newer.

## Where the data comes from

- News: [BBC News RSS feed](https://www.bbc.co.uk/news/10628494)
- Pictures: [NASA APOD API](https://api.nasa.gov/)

This project isn't affiliated with the BBC or NASA.

## To do

- Add more news sections
