# Photo Gallery App

A modern Android photo gallery application built with Jetpack Compose that allows users to view, capture, and manage photos with a sleek user interface.

## Course Information

- **Course**: Mobile Programming, HCMUTE 2024-2025
- **Assignment**: Homework Week 06
- **Student**: Nguyen Nhat Quang
- **Student ID**: 22110065

## Features

- **Photo Grid View**: Browse photos in an aesthetically pleasing grid layout
- **Full Photo View**: View photos in full screen with gesture support
  - Pinch to zoom
  - Swipe navigation between photos
  - Double-tap to toggle zoom
- **Photo Management**:
  - Add photos from camera
  - Import from device gallery
  - Mark photos as favorites
  - Delete photos
- **Theme Support**: Toggle between light and dark themes
- **Gesture Controls**:
  - Intuitive gestures for navigation and interaction
  - Visual indicators for available actions

## Tech Stack

- **UI Framework**: Jetpack Compose
- **Architecture**: MVVM (Model-View-ViewModel)
- **Image Loading**: Coil
- **Navigation**: Jetpack Navigation Compose
- **Animation**: Compose Animation APIs
- **State Management**: Compose State and ViewModel

## Project Structure

- `data/`: Data models
- `ui/`: Compose UI components and screens
  - `theme/`: Material theme configuration
  - Screen components: `PhotoGridScreen`, `FullPhotoScreen`, `SettingsScreen`
- `viewmodel/`: ViewModels to manage UI state and business logic

## Requirements

- Android SDK 21+
- Kotlin 2.0.0+
- Gradle 8.9+

## Getting Started

1. Clone the repository
2. Open the project in Android Studio
3. Build and run on an emulator or physical device

## Permissions

The app requires the following permissions:
- Camera access (for taking photos)
- Storage access (for saving and loading photos)
- Internet access (for loading remote photos)

