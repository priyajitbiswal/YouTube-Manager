# YouTube Manager

A simple command-line application to manage your YouTube video collection with multiple storage options.

## Features

- **Add Videos**: Store video name and duration
- **List Videos**: View all saved videos
- **Update Videos**: Modify video details
- **Delete Videos**: Remove videos from collection
- **Multiple Storage Options**: Choose between JSON file, SQLite, or MongoDB

## Files

- `youtubemanager.py` - JSON file-based storage (simple and lightweight)
- `youtube_manager_sqlite.py` - SQLite database storage (structured data)
- `youtube_manager_mongodb.py` - MongoDB storage (cloud/local database)
- `youtube.txt` - JSON data file for storing video information

## Quick Start

### Option 1: JSON File Storage (Recommended for beginners)

```bash
python youtubemanager.py
```

### Option 2: SQLite Database

```bash
python youtube_manager_sqlite.py
```

### Option 3: MongoDB

```bash
# For local MongoDB
python youtube_manager_mongodb.py

# For cloud MongoDB, set environment variable first:
set MONGODB_URI=your_mongodb_connection_string
python youtube_manager_mongodb.py
```

## Sample Data

The project includes sample video data in `youtube.txt` with programming tutorials covering:

- Python, JavaScript, React.js
- Node.js, MongoDB, HTML/CSS
- Git, Docker, SQL, REST APIs

## Usage

1. Run your preferred version
2. Choose from the menu options:
   - 1: List all videos
   - 2: Add a new video
   - 3: Update video details
   - 4: Delete a video
   - 5: Exit

## Requirements

- Python 3.x
- For MongoDB version: `pip install pymongo`
- For SQLite version: No additional packages (built-in)
- For JSON version: No additional packages (built-in)

## Notes

- JSON version is the simplest to get started
- SQLite version provides structured data with SQL queries
- MongoDB version supports both local and cloud databases
- All versions maintain the same core functionality

Enjoy managing your YouTube video collection! 🎥
