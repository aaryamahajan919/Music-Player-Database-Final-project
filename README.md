# Music Player Database

## Overview

This project is a backend design for a music player database, simulating the functionality of real-world music streaming platforms like Spotify or Apple Music. The database supports efficient management of users, songs, playlists, artists, and albums.

## Features

- User account creation and management.
- Storage of songs with metadata such as title, duration, genre, and release year.
- Creation and management of playlists by users.
- Linking songs to artists and albums.
- Capturing playback history for personalized recommendations.

## Key Concepts

- **Entities:** Users, Artists, Albums, Tracks, Playlists, PlayHistory.
- **Relationships:**
  - Each User can have multiple Playlists.
  - Tracks are linked to Playlists through a many-to-many relationship.
  - Artists create Albums containing Tracks.
- **Optimizations:**
  - Database normalized to 3NF.
  - Indexing for performance improvement.

## Video Overview
For a detailed walkthrough, watch the [project overview video](https://www.youtube.com/watch?v=uPtnxC5UU2I).

---

## Contact

For questions or feedback, please contact:
- **Name:** Aarya Mahajan
- **Email:** [aaryamahajan919@gmail.com](mailto:aaryamahajan919@gmail.com)
