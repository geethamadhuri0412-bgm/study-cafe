# Study Cafe

A cozy study-together website for friends. Pick a location, join a private room with a 7-letter code, and focus together with a shared timer, live chat and relaxing background sounds.

## Features

- Private study rooms: create a room and share the code, only people with the code can join
- Both friends' avatars appear together in the same scene
- Focus timer with custom focus and break lengths
- Break pop-up styled like a phone, and your character walks around during the break
- Room chat that refreshes when a focus session ends
- Study sounds: rain, ocean, brown noise, white noise, fan and fireplace
- XP, coins, levels, streaks, tasks and character customization

## How to use

1. Open the website and create an account (accounts are saved in your own browser).
2. The first time, you'll be asked for the **shared server link**. Ask the owner for it. Everyone in the same room must use the same link.
3. Pick a location, then copy the room code from the Home page and send it to a friend.
4. Your friend opens the site, goes to **Locations**, and joins with the code.

## Setting up your own server (free)

The rooms and chat are stored in [MockAPI](https://mockapi.io):

1. Create a project and add a resource named `rooms`.
2. Add two **String** fields: `code` and `data`.
3. Copy your endpoint and add `/rooms` at the end, for example `https://xxxx.mockapi.io/rooms`.
4. Paste that link when the website asks for it. You can change it later in **Settings → Change server link**.

## Notes

- Everything is one HTML file, so it works on GitHub Pages with no build step.
- The server link is not stored in this repository. Anyone you give it to can read and write rooms, so only share it with friends.
- Accounts, XP and coins are saved in each browser, not on the server.

## Credits

Built by two friends with the help of Claude.
