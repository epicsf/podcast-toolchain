# Podcast Toolchain

## Dependencies

- LAME MP3 encoder
- Feeder 3 (macOS podcast management app)

## Assumptions

- Feeder installed and set up to manage/publish/upload podcast feed
- Will be executed on the same day that we want to name the file with (we rename to YYYY-MM-DD.mp3)
- Will be executed on the same day as the new Feeder entry is created
- We can store files at `/Users/video/Podcast`

## Setup

Configure a Final Cut Pro X share destination that exports as audio-only and calls this toolchain (as an Automator Workflow) after completion.

## Usage

1. Create a new feed item in Feeder and pre-fill all relevant metadata. Save the entry (to the feed, not as a draft).
2. Share from FCPX using the share destination created above.
