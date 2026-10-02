# Custom character art for OOC.ai

This folder hosts emotion artwork for custom OOC.ai characters. GitHub serves
every file in a public repo at a direct image link, so the character's
description can point the AI at a different image for each emotion.

## How it works

1. Each character gets a folder: `characters/<name>/emotions/`.
2. Each emotion is one image named after the emotion: `happy.png`, `sad.png`,
   `angry.png`, and so on. Use lowercase names with no spaces.
3. The direct link to an image looks like this:

   ```
   https://raw.githubusercontent.com/zackbedrosian/Bedrosian-Project/master/characters/<name>/emotions/happy.png
   ```

   Open the link in your phone's browser. If you see only the picture, the link
   works.
4. Paste the filled-in block from `<name>/character.md` into the character's
   description or definition on OOC.ai. The block tells the AI which image to
   show for each emotion.

## Adding images from your phone (GitHub mobile website)

The GitHub app can't upload files. Use the website in your phone's browser,
and switch to desktop view if the "Add file" button doesn't appear.

1. Go to https://github.com/zackbedrosian/Bedrosian-Project and make sure the
   branch dropdown says **master**. The links above only work for files on
   `master`.
2. Open `characters/`, then tap **Add file → Upload files**.
3. To create a new character folder, use **Add file → Create new file** and
   type `characters/<name>/emotions/README.md`. The `/` characters create the
   folders. Commit it, then upload the images into the new `emotions` folder.
4. Rename your images *before* you upload them (`happy.png`, `sad.png`, …).
   You can do this in the iOS Files app or an Android file manager.
5. Tap **Commit changes**. The new link can take a minute or two to start
   working.

## Making the art

You need several images of the *same* character with different expressions.
Some options:

- OOC.ai's own image generation: save the images you like.
- An AI character tool with a "character reference" feature. Upload one base
  image and ask for the same character with a different expression.
- Hand-drawn or commissioned expression sheets, cropped into one image per
  emotion.

Tips: keep the framing (bust shot, same pose and background) the same in every
image so switching between them looks natural. Square or portrait images under
about 1 MB load fastest on mobile.

## If the images don't appear on OOC.ai

Whether OOC.ai shows image links inside chat messages hasn't been confirmed.
Test with one image before you make a full set:

- Start a chat with your character and send:
  `(OOC: please reply with exactly this: ![test](YOUR_LINK_HERE))`
- If a picture appears, the full method works.
- If you see the raw text, OOC.ai doesn't display images inside messages. Then
  use the images as the character's uploaded avatar and gallery images
  instead. The GitHub folder still keeps your expression set in one place, and
  you can download each image from its link when you need it.
