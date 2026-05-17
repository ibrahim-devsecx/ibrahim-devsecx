<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6f7f88,50:8a9aa3,100:a7b6be&height=230&section=header&text=Ibrahim%20Awad&fontSize=72&fontColor=ffffff&fontAlignY=42&desc=Android%20Developer%20%7C%20Kotlin%20and%20Java%20%7C%20Clean%20Mobile%20Architecture&descSize=16&descColor=ffffff&animation=fadeIn" width="100%" />

<br/>

### Hello, World! I'm **Ibrahim Awad**

**Android Developer · Gaza City, Palestine**

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-ibrahim--awad--devsecx-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ibrahim-awad-devsecx/)
[![Email](https://img.shields.io/badge/Email-ibrahim.devsecx%40outlook.com-0078D4?style=for-the-badge&logo=microsoftoutlook&logoColor=white)](mailto:ibrahim.devsecx@outlook.com)
[![GitHub](https://img.shields.io/badge/GitHub-ibrahim--devsecx-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ibrahim-devsecx)

</div>

<br/>

---

## About Me

Android Developer with practical experience in building clean, reliable, and maintainable mobile applications using **Kotlin** and **Java**.

I work with **Android SDK**, **MVVM architecture**, **Firebase**, **Room Database**, **Retrofit**, **Coroutines**, **Flow**, **Media3**, **FFmpegKit**, and **Google Maps**.

I also have a **Cybersecurity Engineering** background, which helps me build more security-aware and reliable Android solutions.

Interested in building real-world Android applications, improving app architecture, and contributing to clean and scalable mobile projects.

<br/>

> **My engineering philosophy:** _Good Android apps are not just screens — they are reliable and secure systems._  
> As an Android developer with a cybersecurity mindset, I focus on building mobile applications with clean architecture, readable code, secure data handling, smooth performance, and real-world reliability.

<br/>

---

## What I Work With

<div align="center">

| Area | Technologies and Concepts |
| :--: | :-- |
| **Native Android** | Kotlin, Java, Android SDK, XML |
| **Architecture** | MVVM, Clean Architecture, Clean Code, Maintainable App Structure |
| **Android Jetpack** | ViewModel, LiveData, Navigation Component |
| **Android Components** | Services, Broadcast Receivers, Content Providers |
| **Networking** | REST APIs, Retrofit, OkHttp |
| **Local Storage** | Room Database, SQLite, Offline Storage |
| **Async Programming** | Kotlin Coroutines, Flow, StateFlow |
| **Firebase** | Authentication, Realtime Database, Firestore, FCM |
| **Storage and Files** | Internal Storage, External Storage, Media Access, Content URIs |
| **Maps and Location** | Google Maps, GPS, Location Services |
| **Media Tools** | FFmpeg, FFmpegKit, Media3 ExoPlayer, Video Processing, Playback |
| **Debugging** | Logcat, Android Debugger, Problem Solving |

</div>

<br/>

---
## How I Structure Android Apps

```mermaid
flowchart LR
    UI["UI Layer\nActivity / Fragment / XML"] --> VM["ViewModel\nUI State / StateFlow"]
    VM --> UC["Use Cases\nBusiness Logic"]
    UC --> REPO["Repository\nData Gateway"]
    REPO --> API["Remote Data Source\nRetrofit / OkHttp"]
    REPO --> DB["Local Data Source\nRoom / SQLite"]

    API -. "Fetch / Sync" .-> REPO
    DB -. "Cache / Offline Data" .-> REPO

    style UI fill:#3DDC84,color:#073042,stroke:#3DDC84,stroke-width:2px
    style VM fill:#4285F4,color:#ffffff,stroke:#4285F4,stroke-width:2px
    style UC fill:#7F52FF,color:#ffffff,stroke:#7F52FF,stroke-width:2px
    style REPO fill:#073042,color:#E6EDF3,stroke:#3DDC84,stroke-width:2px
    style API fill:#0B1F33,color:#3DDC84,stroke:#3DDC84,stroke-width:2px
    style DB fill:#0B1F33,color:#4285F4,stroke:#4285F4,stroke-width:2px

```

<br/>

---

## Tech Stack

<div align="center">

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=kotlin,java,androidstudio,gradle,firebase,sqlite,git,github,postman" height="120" />
</a>

<br/><br/>

![Android SDK](https://img.shields.io/badge/Android_SDK-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![MVVM](https://img.shields.io/badge/MVVM-0f2027?style=for-the-badge)
![Clean Architecture](https://img.shields.io/badge/Clean_Architecture-203a43?style=for-the-badge)
![Room](https://img.shields.io/badge/Room_Database-2c5364?style=for-the-badge)
![Retrofit](https://img.shields.io/badge/Retrofit-48B983?style=for-the-badge)
![Coroutines](https://img.shields.io/badge/Coroutines-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Flow](https://img.shields.io/badge/Flow-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Media3](https://img.shields.io/badge/Media3_ExoPlayer-FF6F00?style=for-the-badge)
![FFmpegKit](https://img.shields.io/badge/FFmpegKit-007808?style=for-the-badge)
![Google Maps](https://img.shields.io/badge/Google_Maps-4285F4?style=for-the-badge&logo=googlemaps&logoColor=white)

</div>

<br/>

---

## Featured Projects

<div align="center">

<table>
<tr>
<td width="33%" align="center" valign="top">

### 🎬 MediaToolKit App

**A native Android media processing app focused on video selection, preview, trimming, and local history tracking.**

Built with a clean and maintainable Android structure, using modern media handling, playback, background processing, and local data persistence.

<br/>

[![Repo](https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ibrahim-devsecx/MediaToolKitApp)

<br/><br/>

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![MVVM](https://img.shields.io/badge/MVVM-2C5364?style=flat-square)
![FFmpegKit](https://img.shields.io/badge/FFmpegKit-007808?style=flat-square)
![Media3](https://img.shields.io/badge/Media3-FF6F00?style=flat-square)
![Room](https://img.shields.io/badge/Room-2C5364?style=flat-square)

</td>
<td width="33%" align="center" valign="top">

### 🚚 Gas Delivery User App

**A customer-side Android application for requesting gas delivery services and tracking delivery-related interactions.**

The app focuses on service requests, customer experience, location-based features, Firebase integration, and real-world ordering flow.

<br/>

[![Repo](https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ibrahim-devsecx/GasDelivery-User-App)

<br/><br/>

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Google Maps](https://img.shields.io/badge/Google_Maps-4285F4?style=flat-square&logo=googlemaps&logoColor=white)
![FCM](https://img.shields.io/badge/FCM-FFCA28?style=flat-square&logo=firebase&logoColor=black)

</td>
<td width="33%" align="center" valign="top">

### 🛠️ Gas Delivery Manager App

**A manager-side Android application for handling gas delivery requests and managing service operations.**

Designed to support order review, request management, delivery workflow control, Firebase-based data handling, and communication between customers and service providers.

<br/>

[![Repo](https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ibrahim-devsecx/GasDelivery-Manager-App)

<br/><br/>

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Orders](https://img.shields.io/badge/Order_Management-203A43?style=flat-square)
![Location](https://img.shields.io/badge/Location_Services-34A853?style=flat-square)

</td>
</tr>
</table>

</div>

<br/>

---

---

## Education

<div align="center">

| Degree | Institution | Date |
| :--: | :-- | :--: |
| **Bachelor’s Degree in Cybersecurity Engineering** | University College of Applied Sciences | Expected Dec 2026 |
| **Diploma in Mobile Development** | University College of Applied Sciences | Jun 2021 |

</div>

<br/>

---

## GitHub Stats

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=ibrahim-devsecx&theme=tokyonight&hide_border=false&border_radius=6&stroke=ffffff&ring=70a5fd&fire=70a5fd&currStreakNum=c792ea&sideNums=70a5fd&currStreakLabel=c792ea&sideLabels=70a5fd&dates=40e0d0" width="70%" alt="Ibrahim's GitHub Streak" />

</div>

<br/>

---

## Let's Connect

I'm open to **Android Developer opportunities**, **freelance projects**, and **technical collaboration**.

**LinkedIn:** [Ibrahim Awad](https://www.linkedin.com/in/ibrahim-awad-devsecx/)  
**Email:** [ibrahim.devsecx@outlook.com](mailto:ibrahim.devsecx@outlook.com)

---

<p align="center">
  <em>"First, solve the problem. Then, write the code." — John Johnson</em>
</p>
