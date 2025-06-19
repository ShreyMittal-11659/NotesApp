# PocketPages 📝

PocketPages is a modern, offline-first, and feature-rich note-taking application for Android, inspired by the versatility of Notion. It provides a clean, block-based editor designed for everything from quick notes and to-do lists to structured databases and long-form writing, all while ensuring your data is always available, even without an internet connection.

![home](https://github.com/user-attachments/assets/267fd7d0-ae92-43a2-ac4f-51b0e00a431d)
![bin](https://github.com/user-attachments/assets/6a869f8b-df67-423f-8a9f-75ee81b8da11)
![login](https://github.com/user-attachments/assets/01e7bb8d-7180-4597-803c-f83600e9caa5)
![settings](https://github.com/user-attachments/assets/da1d15b5-389e-4e8f-b9d2-62670cc883d2)




## ✨ Features

- **✍️ Block-Based Editor**: Structure your notes with a variety of content blocks, including:
  - Rich Text (with more formatting options to come)
  - Headings
  - To-Do Lists with checkboxes
  - Bulleted Lists
  - Quote blocks for emphasis

- **💯 Offline-First Architecture**: Create, read, edit, and delete pages with zero latency, even without an internet connection. Your data is always available on your device.

- **♻️ Bin & Recovery**: Deleted pages are moved to a bin, where they can be restored or permanently deleted.

- **💾 Robust Local Storage**: Utilizes a **Room Database** to provide a fast, reliable, and queryable local cache for all your pages.

- **🚀 Modern Android Tech Stack**: Built with the latest recommended Android technologies for a scalable and maintainable codebase.

- **☁️ Cloud Sync Ready**: The architecture is designed to seamlessly integrate with a cloud backend (like Firebase or a custom REST API) for data backup and multi-device synchronization.

## 🛠️ Tech Stack & Architecture

PocketPages is built using a modern, scalable architecture that separates concerns and promotes best practices.

- **Language**: **Kotlin** (100% Kotlin codebase)
- **Architecture**: **MVVM (Model-View-ViewModel)** - A clean and testable architecture pattern
  - **View**: Activities and XML Layouts for the UI
  - **ViewModel**: Manages UI-related data and state, surviving configuration changes
  - **Model**: The Repository pattern, which acts as the single source of truth for all app data
- **Asynchronous Programming**: **Kotlin Coroutines** for managing background threads and asynchronous operations like database access
- **Database**: **Room Persistence Library** - A powerful SQLite object mapping library for robust local data storage and caching
- **UI**: 
  - Android XML Layouts with Material Design 3 components
  - RecyclerView for displaying dynamic lists of pages and blocks efficiently
- **Dependency Management**: **Gradle** with Kotlin DSL (.kts)

## 📱 Usage

1. **Creating Pages**: Tap the "+" button to create a new page
2. **Adding Content**: Use the block-based editor to add different types of content
3. **Organizing**: Pages are automatically saved and can be organized in your preferred structure
4. **Offline Access**: All your data is stored locally and accessible without an internet connection

## 🚀 Future Roadmap

PocketPages is an evolving project with many exciting features planned:

### Planned Features

- **[#4] Add More Items**: A "+" button at the end of lists to quickly add new items
- **[#6] Multimedia Blocks**: Support for adding and viewing Images, Videos, and Audio files
- **[#7] Book Feature**: A dedicated view to group pages into a "book" with a page-turning UI
- **[#9] Text Customization**: A rich text formatting toolbar for bold, italics, color, font size, etc.
- **Cloud Synchronization**: Full implementation of Firebase or a custom backend for data backup and sync
- **Search**: A powerful search functionality to find content across all pages
- **Reminders & Scheduling**: Integration with the system calendar for reminders
