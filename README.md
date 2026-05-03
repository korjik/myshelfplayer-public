# My Shelf Player

My Shelf Player is a native iPhone, iPad, Apple Watch, and CarPlay audiobook client for self-hosted Audiobookshelf libraries. It is designed for people who manage their own audiobook server and want a polished mobile listening experience with streaming, offline downloads, playback progress, bookmarks, history, and watch-based remote control.

## What The App Does

My Shelf Player connects to an Audiobookshelf server and lets you browse and play your audiobook library from Apple devices.

Core functionality includes:

- Connect to an Audiobookshelf server with a server URL, username, and password.
- Browse the selected Audiobookshelf library.
- View books, series, collections, playlists, authors, and narrators.
- Search books, authors, and narrators.
- Continue listening from saved playback progress.
- View recently added books.
- Stream audiobooks from your server.
- Download audiobooks for offline listening after the optional downloads unlock.
- Track audiobook progress locally and sync progress back to Audiobookshelf.
- Start, pause, resume, seek, and skip forward or backward.
- Configure skip interval, playback rate, progress display, sleep timer defaults, and auto rewind behavior.
- Add and remove bookmarks while listening.
- View play history and resume from history timestamps.
- Use a mini player throughout the app.
- Use a full player with progress, chapter-aware playback, bookmarks, and playback controls.
- Manage download behavior, including Wi-Fi preference and automatic cleanup options.
- Restore the optional downloads in-app purchase through Apple.

## iPhone And iPad

The iOS app provides the main library and playback experience:

- Home view with library counts, search, continue listening, recently added books, and downloads.
- Continue view for unfinished books.
- Series, books, downloads, history, bookmarks, authors, narrators, collections, and playlists.
- Book detail pages with metadata, progress, history, bookmarks, and play actions.
- Settings for library selection, app appearance, playback, downloads, Apple Watch sync, and server account.

## Apple Watch

The Apple Watch app can control playback on the iPhone and display a compact library experience.

Watch functionality includes:

- Now Playing screen with play/pause, skip forward, skip backward, and seek controls.
- Continue, Series, History, Bookmarks, Playlists, Books, Narrators, Authors, and Collections menu sections.
- Open a book from the watch and jump directly to the player.
- Browse history by book, then choose a playback timestamp.
- Browse bookmarks by book, then choose a bookmark timestamp.
- Sync selected library data from the iPhone.
- Configure from the iPhone whether History and Bookmarks sync to Apple Watch.
- Configure the maximum number of books synced to Apple Watch.

## CarPlay

CarPlay support provides a safer listening interface in the car:

- Continue Listening section.
- Downloaded books section.
- Now playing integration.
- Playback commands through the CarPlay interface.

## Downloads Unlock

My Shelf Player may offer an optional non-consumable in-app purchase for offline downloads.

The expected App Store Connect product ID is:

```text
com.kozhokaru.myshelfplayer.downloads
```

This purchase is intended as a one-time unlock. It should be configured in App Store Connect as a **Non-Consumable** in-app purchase so it can be restored through the user’s Apple Account.

## Privacy

My Shelf Player is designed for self-hosted libraries. The app communicates with the Audiobookshelf server chosen by the user and with Apple services used by iOS, watchOS, CarPlay, StoreKit, and App Store purchases.

Privacy documents:

- [Privacy Policy](docs/privacy-policy.html)
- [User Privacy Choices](docs/privacy-choices.html)

If this repository is hosted with GitHub Pages from the `docs/` folder, the public URLs are expected to be:

- `https://korjik.github.io/shelfrepo-public/privacy-policy.html`
- `https://korjik.github.io/shelfrepo-public/privacy-choices.html`

## Support

For support, use the App Store support link for My Shelf Player or open an issue in the public repository if issues are enabled.

## Legal

My Shelf Player is an independent client for Audiobookshelf. Audiobookshelf is a separate open source project. Apple, iPhone, iPad, Apple Watch, CarPlay, StoreKit, and App Store are trademarks of Apple Inc.
