# FC Sidekick challenge feed

Upload one JSON file per challenge group to the public `realtrx9/fcsidekick-releases/challenges` directory. Players on app version 0.2.17 or newer click **Update app and challenges** to receive all current files without installing a new app version. A file can contain one or more challenges in `children`. The app validates each file before replacing its locally cached feed. Existing challenges remain available when a download fails. Group and child IDs must be unique; a file with the same group ID replaces that built-in group.

Use the **Copy JSON creation prompt** button in the app, then send the prompt and screenshots to an AI assistant. Check the formation, every rule, names, and expiry against the game before uploading. The app skips expired groups and children. An expiry for a Riyadh calendar day is `21:00:00Z` on that day, which is midnight at the start of the following day in Riyadh.

The included `marquee-matchups-27-36.json` is a valid example. The full shape and rule definitions are in the app prompt. Commit a corrected file with the same filename to update it for all users on their next click. Remove a file after its challenge ends if you want to clean the repository; the expiry also hides it automatically.
