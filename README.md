# Blaise McGill — Football Highlights

A simple personal football highlights website written in Blaise's voice. Ready for GitHub Pages.

## Publish

1. Create a public GitHub repository, for example `blaise-football`.
2. Upload `index.html` and `videos.js` **to the root of the repository** (not inside a subfolder).
3. Go to **Settings → Pages → Build and deployment**. Select **Deploy from a branch**, then **main** and **/(root)**, and save.
4. Visit `https://YOUR-USERNAME.github.io/blaise-football/`.

## Trinity JV videos

All four supplied YouTube URLs are already configured in `videos.js`. The site shows a click-to-play panel rather than requesting YouTube thumbnails, avoiding missing-thumbnail errors. Clicking loads YouTube's official embed player. If YouTube restricts embedding for a particular video, the **Open video** link below the player opens the original YouTube page.

YouTube videos must allow embedding and must be Public or Unlisted (not Private). Some browser privacy settings or extensions also block embedded players.

## Add individual varsity and JV videos

The Hudl profile is linked prominently throughout the site. Its public page did not expose a reliable list of individual video URLs, so no individual Hudl clips were invented. If you have shareable video URLs, add objects in the `videos` array in `videos.js` with `level: 'varsity'` or `level: 'jv'`. For Hudl share links use `kind: 'link'`; the card will open the link rather than attempting an unsupported embed. For YouTube use `kind: 'youtube'`.

## Notes

The text is drafted in first person for Blaise to review and personalize. Confirm his academic and athletic details and obtain his approval before publishing a public profile. No contact information is exposed.


All four parent-recorded Trinity JV videos have been added to `videos.js` as YouTube embeds.


## Hudl highlights

Three individual Hudl highlight URLs are listed in `videos.js` and appear as direct links in the Varsity and JV sections. They are **not** embedded: a normal Hudl watch URL is not necessarily an iframe URL. To embed them, sign in to Hudl, open the highlight, choose Share > Embed if available, and use the official embed snippet. The four Trinity YouTube videos use click-to-load YouTube players.

## MaxPreps game report

The Stats & Media section links to the October 14, 2025 MaxPreps report for the Blue Ridge varsity game. The page paraphrases the reported statistics and links to the original article.

## Player photo
The home page hero now displays `assets/blaise-football.jpg` (the supplied original photo). Upload the entire `assets` folder alongside `index.html` and `videos.js`. The site references the relative path `assets/blaise-football.jpg`.

## Hudl embedded players
The three Hudl highlight cards use the official iframe embed URLs supplied by the account holder. They require an internet connection and may be subject to Hudl playback settings.
