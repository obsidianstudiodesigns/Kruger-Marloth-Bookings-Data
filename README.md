# Kruger Marloth Bookings — data

Written by the owner dashboard of [Kruger-Marloth-Services-Bookings](https://github.com/obsidianstudiodesigns/Kruger-Marloth-Services-Bookings). Don't edit these files by hand.

| File | Contents |
|---|---|
| `availability.json` | Booked and on-hold date ranges per property. No guest details. Read by the public website. |
| `bookings.vault.json` | All bookings and guest details, encrypted (AES-256-GCM, key from the owner's password via PBKDF2). Created at first-time setup. |
| `access.json` | The dashboard's GitHub access token, encrypted with the owner's password, so the owner signs in with a password only. Created at first-time setup. |

The dashboard's access token only has access to this repository, not to the website.
