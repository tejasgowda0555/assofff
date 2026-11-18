# Daily Fitness Log

A simple, single-page tracker for diet, workouts, cardio and body measurements, with a live progress dashboard. Built with plain HTML, CSS and JavaScript. No sign-up, no backend, no install.

## Features

**Daily log**
- **Body:** weight (kg) and measurements (waist, chest, hips, arms in cm)
- **Meals:** food, calories and protein, with quick-add from your own food list
- **Workouts:** exercise, sets, reps and weight (kg)
- **Cardio:** activity, minutes, distance (km) and steps
- **Notes:** energy, sleep, how the session felt
- Day totals for calories, protein, cardio minutes and steps
- Move between days with arrows, a date picker, or the "Logged days" chips

**Daily targets**
- Set calorie and protein goals once
- Progress bars show how much is left, or how far over you are

**My foods (Karnataka food list)**
- Comes with about 50 local dishes already named, including idli, neer dosa, ragi mudde, bisi bele bath, jolada rotti, saaru, Maddur vade, Mysore pak and filter coffee
- Calories and protein are left blank so you can enter values for your own portion size
- Add, rename or remove foods at any time

**Live dashboard**
- 7, 30 or 90-day view
- Averages for calories and protein compared with your targets
- Weight change, total cardio, workout days, days logged and current streak
- Charts for calories, protein, weight, cardio minutes and workout volume
- Your most logged foods
- Updates instantly as you log, including across open browser tabs

## How to use

1. Open `index.html` in any browser, or visit your deployed link.
2. Go to **Daily targets** and enter your calorie and protein goals.
3. Open **My foods** and fill in calories and protein for the dishes you eat most often.
4. Each day, log your meals (search a food, set the servings, then tap **Add**), along with your workouts, cardio and weight.
5. Switch to the **Dashboard** tab to see your progress.

Everything saves automatically as you type.

## Deploy on Vercel

1. Create a new GitHub repository (for example, `fitness-log`).
2. Upload the tracker file and rename it to `index.html`. Add this `README.md` too.
3. In Vercel, click **Add New → Project**, import the repository, and deploy. No build settings are needed.
4. Open the link on your phone and choose **Add to Home Screen** so it opens like an app.

```
fitness-log/
├── index.html
└── README.md
```

## Where your data is stored

- All data is saved in your browser's local storage, on your own device.
- Nothing is sent to a server.
- Your phone and laptop keep separate logs, because data does not sync between devices.
- Clearing your browser data, or using private/incognito mode, will erase your log.

## Tech

- A single HTML file with inline CSS and JavaScript
- Charts are drawn with inline SVG, so there is no chart library
- Barlow and Barlow Condensed fonts load from Google Fonts. The page still works offline with system fonts.
- Supports light and dark mode automatically

## Ideas for later

- Export / import a backup file
- Water intake counter
- Saved workout routines
- Weekly summary view
