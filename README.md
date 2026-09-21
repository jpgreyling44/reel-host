# reel-host

Public HTTPS host for Instagram Reels.

Meta fetches media itself (`video_url`) when publishing a Reel, so the mp4 must sit at a
publicly reachable URL for the duration of the publish attempt. Release assets in this repo
provide that URL. Nothing secret lives here - only finished video files.

Publishing is done by `D:\hermes\scripts\post_instagram.py` (Instagram API with Instagram
Login, `graph.instagram.com`).
