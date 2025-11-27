# ⚽ Football Results App

A clean and simple Android app for managing football match results,
viewing team statistics, and browsing match reports --- all stored
locally with SQLite.

------------------------------------------------------------------------

## 🚀 Features

-   📝 **Add & Edit Matches**\
    Choose teams, enter score, date & city --- with validation.

-   📊 **Automatic Team Statistics**\
    Wins, draws, losses, goals, points --- calculated instantly.

-   🔍 **Search Matches by Team**\
    Pick a team and view all games played.

-   📑 **Match Reports**\
    Clean list of all recorded matches.

-   📈 **League Table View**\
    Sortable by points (ascending/descending).

-   💾 **Local & Offline**\
    No internet needed --- all data stored in SQLite.

------------------------------------------------------------------------

## 🧱 Tech Stack

-   **Java**\
-   **Android Studio**\
-   **SQLite (custom DAO layer)**\
-   **RecyclerView + Adapters**\
-   **Material Design Components**

------------------------------------------------------------------------

## 🧱 Tech Stack

- **Java**  
- **Android Studio**  
- **SQLite (custom DAO layer)**  
- **RecyclerView + Adapters**  
- **Material Design Components**

------------------------------------------------------------------------


## 📂 Project Structure

    app/
     ├─ activities/     # Screens (Match Entry, Reports, Stats, Search)
     ├─ adapters/       # RecyclerView adapters
     ├─ database/       # SQLite helper + DAOs + seeding
     ├─ models/         # Match, TeamStats
     └─ utils/          # Date formatting & statistics calculator

------------------------------------------------------------------------

## ▶️ Getting Started

1.  Clone the repo:

    ``` bash
    git clone https://github.com/<your-username>/football-results-app.git
    ```

2.  Open in Android Studio\

3.  Run on emulator or device --- the app seeds sample teams & matches
    automatically on first launch.

------------------------------------------------------------------------
👨‍💻 **Author:** 
Yuval Boker  
Full-Stack & Software Developer ⚽💙
