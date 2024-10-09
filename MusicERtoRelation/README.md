# Music Database Management System

## Project Overview
This project is a Music Database Management System that organizes and manages data related to artists, songs, instruments, genres, and user ratings. The database schema is designed to facilitate the retrieval and management of music-related information.

## Entity-Relationship Diagram (ERD)
An ER diagram illustrates the relationships between various entities in the database. It includes tables such as `Artist`, `Instrument`, `Song`, `Genre`, and `User`.

## Database Tables
The following tables are included in the project:

1. **Instrument Table**
   - Stores information about musical instruments.
   - Columns: `I_id`, `family`, `name`.

2. **Artist Table**
   - Contains details about music artists.
   - Columns: `A_id`, `Name`, `email`, `Instrument_id`.

3. **Song Table**
   - Holds details about songs.
   - Columns: `S_id`, `Title`, `duration`, `Artist_Id`, `Genre_Id`.

4. **Genre Table**
   - Contains information about music genres.
   - Columns: `G_id`, `name`, `Starting_year`.

5. **User Table**
   - Merges user information and song preferences.
   - Columns: `U_id`, `userName`, `Rating`, `S_id`.

## Getting Started

### Prerequisites
- SQL database system (MySQL)
- Database management tools (MySQL Workbench)

