# Defining the project
Personal project to enhance my daily activities, improve my coding and also give me some automation on my daily tasks

## This app should do the following: 
* Weather upates(today+upcoming 5 days)
* Traffic data for route to work
* News from a website(ideally journalist news to know whats going on)
* Upcoming events from my calandar
* Reddit thread updates
* Should be accessible from phone, tablet, PC

# Tech Stack

## Backend
- FastAPI --> Backend framework(to improve my FastAPI knowledge)
-  SQLite --> To store data
- Redis --> for caching


## Web Scraping

- Selenium 

## Frontend/UI

- React

# FastAPI File Structure

    project
    ├── backend/
    │   ├── app/
    │   │   ├── main.py
    │   │   ├── api/
    │   │   │   ├── weather.py
    │   │   │   ├── calendar.py
    │   │   │   └── ...
    │   │   ├── db/
    │   │   │   ├── models.py
    │   │   │   ├── database.py
    │   │   └── services/
    │   └── requirements.txt
    │   
    └── frontend/
        ├── public/
        ├── src/
        │   ├── components/
        │   ├── pages/
        │   └── App.tsx
        └── package.json



# Project components and steps

## 1. Gather API Access & Environment Setup 

- [ ] 1.1 Register on OpenWeatherMap, Google Maps API, RSS feeds from news site and IOS calendar API

- [ ] 1.2 Set up python main project document and also relevant sub-files according to project structure

- [ ] 1.3 install required libraries

## 2. Building core functionality of modules

- [ ] 2.1 Build weather module, fetch current data and upcoming forecast

- [ ] 2.2 Build traffic module, determine route information using Google maps API

- [ ] 2.3 Build News Module and fetch news either through RSS/API or scrape through Selenium

- [ ] 2.4 Build Calendar module through CalDav API

- [ ] 2.5 Build Reddit module

- [ ] 2.6 Test each component individually and also after building all of them for one final check

## 3. Set up DB with SQLAlchemy and SQLite 

- [ ] 3.1 Prepare to Store: 
- User settings/preferences
- Cached data(for example last fetched weather)
- Log history(sprinkles)

- [ ] 3.2 Use sqlite3 for simplicity

- [ ] 3.3 install required libraries


## 4. Set up frontend with React 

- [ ] 4.1 Fetch data from FastAPI endpoints

- [ ] 4.2 Build responsive UI components(Weather,Calendar etc)

- [ ] 4.3 install required libraries

## 5. API Integration

- [ ] 5.1 Weather: OpenWeatherMap

- [ ] 5.2 Calendar: sync calendar with CalDav API

- [ ] 5.3 Reddit API through PRAW? or requests? 

- [ ] 5.4 News RSS or Public API

- [ ] 5.5 Traffic: Google maps API

## 6. Deployment




| Backend | WebScraping | FrontEnd |  |
| -------- | -------- | -------- | -------- |
| FastAPI | Row 1, Col 2 |Row 1, Col 3 | 
| SQLite | Row 2, Col 2 |Row 2, Col 3 |''' 
