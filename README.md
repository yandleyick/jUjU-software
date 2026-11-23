# jUjU software

I'm Julian 'candlestick' McLendon (yandleyick), founder of jUjU software. I make tools for the work I do for myself, such as AI agents that automatically edit music visuals and gaming montages or comb through hundreds of hours of footage to find highlights.

## Archive provenance and ownership

My digital archive goes back to my first PC, which I got at age 10, and to the creation of my Google account. I consider that history part of jUjU software. The company treats the archive, its indexes, the intellectual property I own or create going forward, and all data I collect going forward as proprietary company assets. That includes the records I keep of where files came from and how I used them. When I save someone else’s video or screenshot, the original creator’s rights and any license terms still apply.

### Archive size

On November 23, 2026, I inventoried Google Drive, including its computer backup, and the personal and project folders on my two SSDs. These are rounded estimates of distinct files.

| Media | Estimate | What was counted |
| --- | ---: | --- |
| Photos | About 750 | About 250 files had camera metadata, a camera-format filename, or a camera file type. A sample of other images in personal and download folders suggested about 500 more photos. Untagged photos elsewhere may be missing. |
| Videos | About 4,900 | Video files across the scanned locations. About 810 were in download or attachment folders or had a recorded web origin. |
| Screenshots in downloads and attachments | About 320 | A sample of images in those folders plus files explicitly labeled as screenshots. This includes likely game and app captures. |

I counted local copies using file sizes and content fingerprints and matched Drive files by name and size. Re-encoded or edited copies can count separately. The download figures include material I saved from other people. A download location alone can’t tell me who made it, so the third-party share is unknown.

### Google Photos and my second Drive

On November 23, 2026, Google Dashboard showed **366 photos** in my primary Google Photos account and **152 photos** in my second account. That adds up to **518 photos across the two account counts**. The same photo can appear in both accounts or already be on Drive or an SSD, so the number of unique photos across the whole archive is still unknown.

Google Dashboard showed **220 files** in my second Drive. Searching that account for files I own returned **80 image files** and **20 video files**. Of the 80 images, **44** had screenshot filenames. These are account-level counts. The earlier estimate of about 750 photos covers my primary Drive and the two SSDs.

I estimate that my Discord index covers roughly twice as many media items as the Drive and SSD archive. That’s my own estimate. The inventory above didn’t measure Discord or how much the collections overlap.

## Candlestick Creator Toolkit

I’ve built many tools and workflows. Seven of them are published in the Candlestick Creator Toolkit. I also curated a catalog of 88 third-party tools and resources, with links to the people and projects behind them. [Toolkit on GitHub](https://github.com/yandleyick/candlestick-creator-toolkit) · [Creator guide](https://yandleyick.com/guides/toolkit)

| What I made | How I use it |
| --- | --- |
| [Konr Wings](https://github.com/yandleyick/candlestick-creator-toolkit/tree/main/tools/konr-wings) | I built a wing-shaped Windows crosshair for Overwatch. It stays centered when I move the game between monitors, and I can switch between Rainbow and Deep Black with a hotkey. |
| [ILYFFMPEG](https://ilyffmpeg.yandleyick.com/) | I turn a YouTube link into a video file for my timeline, or save just the audio when a song was uploaded with a still image. |
| [ILYMFFMPEG](https://ilymffmpeg.yandleyick.com/) | When a clip is embedded in a webpage, I paste the page link into this tool. It finds the main video player and saves the source video for editing. |
| [Freestyle editor](https://github.com/yandleyick/candlestick-creator-toolkit/blob/main/docs/FREESTYLE.md) | I use a timestamped transcript to find a passage, watch it back, and set the cut from the setup through the payoff. I can then export the clip with editable captions. |
| [Rate Freestyle](https://github.com/yandleyick/candlestick-creator-toolkit/blob/main/docs/RATE-FREESTYLE.md) | I built a Codex plugin to find standout writing in long practice transcripts and compare verses head to head. It gives me timestamps and explains where a rhyme, callback, or later bar develops an earlier idea. |
| [Overwatch scanner](https://github.com/yandleyick/candlestick-creator-toolkit/blob/main/docs/OVERWATCH.md) | I built a kill-feed scanner to flag stretches where Tracer may have landed several final blows in one life. I jump to those timestamps, watch the whole fight, and pick the montage clips. |
| [Restoration workflow](https://github.com/yandleyick/candlestick-creator-toolkit/blob/main/docs/RESTORATION.md) | I wrote the frame-recovery step for my Natural v3 workflow. I use it to bring back fine brightness detail, compare the result with the original footage, and decide which older Overwatch clips to denoise or upscale for a montage. |

## Game in development

I’m developing a story-driven, single-player first-person shooter that doubles as an aim trainer. Aim practice is part of playing through the story.

## Project notes

Keep each project in its own folder under `projects/`. In its README, record what’s being built, where the source files live, and the next step. Link to the shared original for large recordings, videos, and design files.

Use a separate ChatGPT Project chat for each topic and copy decisions that affect the work into the project README. For code changes, open a pull request with a summary and how the change was checked.
