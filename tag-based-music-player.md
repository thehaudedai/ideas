# Tag Based Music Player

## Core Idea

A local music player focused on **music files, not streaming**, where songs are organized using **user-defined tags instead of playlists**.

Each song can have multiple tags, and each tag can belong to multiple songs.

When playing music, instead of selecting a playlist, the user **chooses tags that represent the mood or vibe they want**, and the app generates a queue of songs that match those tags.

Basically **mood → tags → music**, instead of **playlist → music**.

---

## Problem
Playlists are rigid and annoying to manage.

Some issues:

-   Songs fit **multiple moods**, but playlists force them into fixed groups.

-   Creating and maintaining playlists takes effort.

-   Hard to create a playlist for every possible vibe.

-   People who listen based on mood have to manually organize songs a lot.

-   Many users (like me) just dump songs in their library and never properly organize them.

Because of this, it's hard to quickly get **songs that match a certain vibe**.

---

## Solution

Use **tags instead of playlists**.

Users create their own tags based on how they think about music.

Songs can have **many tags**.

When listening, the user picks **one or multiple tags**, and the player automatically generates a queue of songs that match those tags.

Example idea:

Select tags like:

Romantic + Slow + Hindi

The app plays songs that match those tags.

So the user gets the **exact vibe they want** without needing a playlist.

---

## Why This Helps

-   No need to create many playlists.

-   Songs can belong to multiple moods naturally.

-   Easier to organize music mentally.

-   You can create **new vibes anytime by combining tags**.

-   Works better for people who listen based on **mood rather than specific playlists**.

Also helps rediscover songs because tags connect songs across different contexts.

---

## Tag System

-   Users create **custom tags**.
-   Songs can have **multiple tags**.
-   Tags can have **many songs**.

Tags could represent things like:

-   mood
-   energy
-   language
-   context
-   genre
-   personal vibes

But tags are **completely user defined**.

---

## Playback Idea

Instead of playlists:

1.  User selects tags
2.  App filters songs matching those tags
3.  Queue is generated dynamically
4.  Songs play normally (shuffle or something similar)

So playlists become **dynamic combinations of tags** instead of manually curated lists.

---

## Possible Additions

-  Saving current queue to playlist; sharable and recreatable for apps like spotify or others
-  Maybe just maybe, editing tags here means metadata of the song file aslo include that tags, so if device changed but songs transferred tags arent lost
