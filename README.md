# Android RecyclerView & Glide Example (Java)

An Android reference application demonstrating dynamic list rendering using `RecyclerView` and image loading via **Glide** in Java.

## Overview
This project serves as a practical reference implementation for building performant UI lists in Android using Java. It showcases how to construct a custom adapter, handle model binding with a contact list example, and integrate asynchronous image loading and caching using the Glide library.

## Key Features
* **RecyclerView Adapter Pattern:** Implementation of custom `RecViewAdapter` for view recycling and list management.
* **Model Binding:** Data mapping using a dedicated `Contact` model class.
* **Image Loading & Caching:** Integration of **Glide v4.12.0** for asynchronous image fetching, caching, and rendering inside list items.

## Tech Stack
* **Language:** Java 8
* **UI Components:** `androidx.recyclerview`, `ConstraintLayout`, Material Components
* **Image Loading:** `com.github.bumptech.glide:glide:4.12.0`
* **Min SDK:** 16 (Android 4.1)
* **Target SDK:** 30

## Quick Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/m-lomba/recyclerview-example.git
   ```
2. Open the project in **Android Studio**.
3. Build and run on an emulator or physical device running API 16 or higher.
