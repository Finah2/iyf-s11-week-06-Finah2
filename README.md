# Finah Nyamwaya — Week 06: Asynchronous JavaScript

This week I learned how JavaScript handles things that take time. API calls, delays, waiting for responses — it all clicked once I understood promises and async/await.

## Live Demo

[View Live Site](https://Finah2.github.io/iyf-s11-week-06-Finah2)

> 🌤️ Main project: [Weather Dashboard](https://Finah2.github.io/iyf-s11-week-06-Finah2/weather.html)
> 👥 User Directory: [users.html](https://Finah2.github.io/iyf-s11-week-06-Finah2/users.html)

## Features

- ✅ Sync vs Async — understanding the event queue
- ✅ Callbacks and callback hell
- ✅ Promises — creating, chaining, Promise.all, Promise.race
- ✅ Async/Await with try/catch error handling
- ✅ Fetch API — GET and POST requests
- ✅ Display API data in the DOM
- ✅ Live search and filter on API data
- ✅ Weather Dashboard with OpenWeatherMap API
- ✅ localStorage for recent searches
- ✅ Celsius/Fahrenheit toggle
- ✅ All 5 daily challenges

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+) — Promises, Async/Await, Fetch API
- OpenWeatherMap API
- JSONPlaceholder API
- GitHub Pages

## Project Structure

```
iyf-s11-week-06-Finah2/
├── index.html
├── weather.html
├── users.html
├── about.html
├── projects.html
├── contact.html
├── styles.css
├── js/
│   └── async-practice.js
├── daily-challenges/
│   ├── day1-delayed-promise.html
│   ├── day2-promise-chain.html
│   ├── day3-error-handling.html
│   ├── day4-async-rewrite.html
│   └── day5-parallel-fetches.html
└── README.md
```

## What I Learned

The biggest shift this week was understanding that JavaScript doesn't wait. When you call an API, the rest of your code keeps running — and the response comes back later. Promises and async/await are just clean ways to say "when that's done, do this."

The weather dashboard was the most satisfying project so far because it uses real live data. Type a city, hit search, and actual weather information comes back from a real API. That felt like building something real.

## Challenges Faced

**Understanding Promise chaining:** At first I kept forgetting to return the next promise inside `.then()`. Without the return, the chain breaks and you get undefined.

**Error handling:** I learned the hard way that `fetch()` doesn't throw on 404 errors — you have to check `response.ok` yourself. The API returns a response either way, it's up to you to check the status.

## Contact

- Email: finahnyamwaya062@gmail.com
- GitHub: [@Finah2](https://github.com/Finah2)
