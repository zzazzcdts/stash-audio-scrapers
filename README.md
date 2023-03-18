# stash-audio-scrapers
Covering a very specific niche here - some Stash scrapers for audio sources.

## Why haven't you contributed these to the Community Scrapers?
Stash does not officially support audio as of March 2023. As such, it doesn't make much sense to contribute audio-only scrapers at this time.
As I understand it, audio support is on the roadmap for Stash at some point, but it'll be some time yet.

## So if audio isn't supported by Stash, what's the point of these scrapers?
Although not *officially* supported by Stash, there are ways of using Stash to manage audio files. If you add 'mp3', 'm4a', etc, to the 'Video extensions' section in the library settings, you can add audio files to your Stash, where they will come up as scenes.
These scrapers are to support people who use Stash in this manner, and also to give a 'running start' for when audio support is eventually added to Stash.

## OK, so what have you got so far, then?
My work on audio scrapers has been angled towards the hypnosis genre, and I have written two scrapers:
| Scraper name  | Status        |
| ------------- | ------------- |
| HypnoDB  | Search and URL works, some minor tweaks required.  |
| Mistress Stella  | URL works, search only works for exact matches.  |

## Wow, that's some dodgy code!
Not gonna lie, the code I've come up with is pretty shocking (if you want a good laugh, take a look at how I've handled dates for the HypnoDB scraper - there must be a better way than what I've done!), but the scrapers seem to largely do the job, and could serve as a jumping-off point for someone more...well...competent than me.

## License
Help yourself to the code, do whatever you like with it, no need to attribute or anything. I've only put it on here in case it helps anyone out.
