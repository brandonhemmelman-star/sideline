# Sideline

A roster, lineup and snap counter for youth football coaches.

I built it over a full season for my own team. I used it to plan games and on the sideline during them, and fixed it after each game based on what worked and what didn't.

It answers three questions:

- Is every position covered?
- Is every player getting a chance to develop?
- Is everyone reaching the snap minimum?

## What it does

- **Snaps:** Tap + after each play to count snaps for every player. Players under the minimum show in red. Undo covers a mis-tap.
- **Roster:** Add players one at a time or paste a list from a spreadsheet. Mark players IN or OUT for the day.
- **Positions (optional):** Choose which players are eligible for each position.
- **Lineup (optional):** Plan starters for each half or quarter. Auto-fill suggests lineups that give the most time to players with the fewest starts. Review shows positions with no backup, players who only know one spot, and who is not starting.
- **Settings:** Set your league's snap minimum, ball-carrier weight limit, position names and spot counts.

Positions and lineups are off by default. Turn them on in Settings.

## Try it

Open the live app: https://brandonhemmelman-star.github.io/sideline/

The app opens with a demo team of made-up players and a short tour. Clear the demo on the Roster tab when you are ready to enter your own team.

## Your data

Everything is stored in your browser on your device. There is no account and no server. Nothing is sent anywhere.

Because of that, back up your roster now and then. On the Roster tab, tap Copy backup and save the text somewhere. Paste it into Restore from backup to bring it back on a new phone. Backups include the roster, settings and lineups. They do not include snap counts.

Clearing your browser's site data erases your roster, so keep a backup.

## Run it

It is one file with no build step. Open `index.html` in a browser.

To put it online with GitHub Pages:

1. Push this folder to a GitHub repository.
2. Go to Settings, then Pages.
3. Under Build and deployment, choose Deploy from a branch, pick your branch, and save.
4. Wait a minute, then open the address GitHub shows you.

If the folder sits inside a larger repository, the app will be at `/sideline/` on that site. Pages publishes everything in the branch, so use a repository that only holds things you want to be public.

On a phone, use Add to Home Screen to open it like an app.

## Notes

- Fonts load from Google Fonts. If they can't load, the app falls back to system fonts.
- League rules vary. The defaults are a 12-snap minimum and a 150 lb ball-carrier limit. Change them in Settings, or clear the weight limit to turn it off.


## Notes

- Fonts load from Google Fonts. If they can't load, the app falls back to system fonts.
- League rules vary. The defaults are a 12-snap minimum and a 150 lb ball-carrier limit. Change them in Settings, or clear the weight limit to turn it off.
