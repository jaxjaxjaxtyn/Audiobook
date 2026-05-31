The read-along audiobook is ready in this folder.

Open this file:
index.html

For the phone-first version:
iphone.html

What is included:
- gatsby.m4a: the packaged audiobook audio
- subtitles.vtt: subtitle cues
- readalong.json: sync data between subtitle cues and book positions
- data.js: player data loaded by the HTML page

Notes:
- The player highlights the current subtitle and follows the matching paragraph in the book text.
- `iphone.html` uses a more iPhone-friendly, Apple Podcasts-style subtitle layout with larger live captions.
- Most subtitle cues are matched directly to the EPUB text. The spoken intro and spoken outro remain unmatched on purpose.
- There is also one noisy stretch in the middle of chapter 3 where the subtitle text did not align cleanly enough to trust a highlight, so the player leaves that section unmatched rather than pointing to the wrong place.
