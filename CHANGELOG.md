# Changelog

Every King for Windows release, newest first. Each version lists what changed in King itself; Windows-specific notes are marked **Windows**.

## 1.8.0 for Windows — first Windows release (16 October 2026)

**Windows**

- King now runs on Windows 10 and 11 (64-bit). Download `King-1.8.0-x64-Setup.exe` to install it, or `King-1.8.0-x64-Portable.exe` to run it without installing.
- The installer lets you choose the install folder and adds Start menu and desktop shortcuts. Uninstall it from Settings → Apps; your library, settings and API keys stay on the PC.
- King uses the standard Windows title bar, with minimise, maximise and close buttons. Press Alt to show the menu bar.
- The installed version checks this page for new Windows releases. To update the portable version, download the new file.
- This build isn't code-signed yet, so the first time you open it Windows shows "Windows protected your PC". Click **More info**, then **Run anyway**.

## 1.8.0 — Your consistency playbook, built in

King now follows the GenHQ character, product and shot methods from your course notes.

- Characters → Reference sheet: “Base character shot” (one clean front photo on white) and “360° turnaround” (5 views in one sheet).
- Products → Create reference sheet: “360° object sheet” (6 angles) and “Label sheet” (front and back label laid flat).
- The Director and scene director write every shot in your scene template, using the shot chart (ECU to EWS, eye level to over-the-shoulder).
- Video clip prompts follow the motion rules: if the camera holds still, the subject moves.

## 1.7.2 — Photodump shot lists and photo history

AI-written Photodump shots, and replaced character photos you can bring back.

- Photodump: “Write shots with AI” (about 1 cent, asks first) writes a fresh shot list from your vibe and theme; Shuffle stays free.
- Photodump shows the identity chip, so you can see whether the pack or photos are sent.
- Characters keep the photos you replace; edit a character to put an old one back.

## 1.7.1 — See which identity you’re sending

Every selected person now shows whether their identity pack or their photos are sent.

- Image references, the Director cast and UGC Ad presenter show “identity pack ✓”, “original photos”, “photos (no pack)” or “pack out of date”.
- Build or rebuild a pack right there (about 1 cent), without leaving the page.
- Switch a person to their original photos when you want their exact studio pose or outfit, and back again.

## 1.7.0 — The same person, every time

Identity packs keep your characters looking exactly like themselves in every feature.

- Build an identity pack on any character (⋯ menu, about 1 cent): an exact identity card plus face crops at several angles and the full body.
- Image, Director, UGC Ad, Photodump, AI Influencer and Ask King all send the pack, with a separate lock for each person.
- Every new image (and Director clip) of a person with a pack is checked automatically and flagged if the face drifted.
- Check identity and Fix face on any image, and character references for Veo 3.1 and Seedance 2.0 video clips.

## 1.6.0 — Director clips and saved influencer weeks

Turn storyboard stills into video clips, and never lose an influencer week again.

- Director: Make clips turns each shot’s still into a video, starting with the cheapest draft model.
- Pick the still and clip models per ad, keep several clips per shot, and continue a shot from the last frame of the one before.
- Open in Video Editor now uses your clips where you have them.
- AI Influencer: “Create this week” keeps running when you leave, and every week is saved under the influencer with links to its photos and reels.

## 1.5.0 — Meet the Director

Chat an ad idea into scenes and shots, and see a still of every shot before any video.

- Director (Ad studio): pick your cast, product and location, then describe the ad.
- It writes the story as scenes and shots, with camera, action and voiceover for each.
- Make a still per shot, take new takes, edit any shot, and open the storyboard in the Video Editor.
- Products that aren’t clothing are now held or placed, never worn, with sharper packaging text.

## 1.4.0 — People belong in your worlds

Characters placed in an environment now look photographed there, not pasted in.

- Location view: King cuts your world sheet into its views and sends only the one you pick (or Auto).
- AI scene director (about 1 cent, asks first): plans the camera, pose, light and shadows, and picks the view.
- With the director on, only each person’s face is sent, so the model draws their body in the scene.
- Lens flares only appear from real light sources, and the location’s light always wins.
- The Environments row now shows on every window size.

## 1.3.4 — UGC ads keep going when you leave

You can leave the UGC Ad page while an ad is being made.

- Progress stays when you switch pages and come back.
- A small progress note follows you around the app.
- When it’s done, King saves the ad and shows an Open button instead of jumping pages.
- A second run can’t start by accident while one is going.

## 1.3.3 — Relight keeps your scene

Relight now has two modes, and the default no longer changes your background.

- Keep the scene (default): changes only the light. Background, product and text stay the same.
- New background: the earlier IC-Light behaviour, now clearly labelled.
- Flow Canvas relight steps use Keep the scene.

## 1.3.2 — Clearer, easier to read

Contrast fixes so text stays readable on King’s dark look.

- A cleaner “What’s new” card with readable text and a clear close button.
- Image prompts shown on hover are now white and sit above the rating buttons.
- The remove-key button on the APIs page stays visible when you hover it.

## 1.3.1 — Video generation fixes

Fixes for AI video clips that failed or went missing.

- Kling 3.0 Pro and Kling O3 Pro on fal now accept the clip length (they rejected every request before).
- KIE video jobs no longer give up after a brief network drop while the video is still being made.
- UGC Ad keeps the still image when a clip fails, and tells you which clips failed and why.

## 1.3.0 — Editors, round three

More power in the Video Editor, Ad Canvas and photo editor.

- Video Editor: shapes and stickers as clips, Option-drag to ripple trim, and a ? list of every shortcut.
- Export just the audio of a video as WAV or M4A.
- Auto clips can follow the speaker instead of cropping the centre.
- Ad Canvas carousels: several pages in one design, exported as numbered images.
- Photo editor: magic select by colour, and Upscale 2x or 4x (paid, asks first).

## 1.2.0 — King becomes an ad studio

A big update: ad design, testing, video and photo editing, social posting and an assistant, all in one app.

- Ad Canvas with brand kits, templates, 60 elements, QR codes, arrange tools and variants for testing.
- Video Editor with a multi-track timeline, captions, smart cuts, crop, masks, green screen and auto clips.
- Photo editor: crop, filters, text and stickers, healing, resizing and background removal.
- Social page for Facebook, Instagram and TikTok drafts with a scheduler, plus easier Meta connection.
- Ask King (Cmd+J), a 14-item sidebar, a spending tracker and confirmations before every paid action.

## 1.1.24 — Worlds → Environments rename

All user-facing labels now say "Environment" instead of "World" for brand environment references.

- Renamed toasts, buttons, empty states, subtitles, and aria-labels from "World" to "Environment" across the Image and Environments pages.
- Internal API entity types and code identifiers remain unchanged to preserve existing data.

## 1.1.23 — Sales velocity renderer bridge

The renderer can now use the sales velocity bridge for polling status, trend data, and polling controls.

- Added preload access for sales velocity status and trend requests.
- Added preload polling controls so future sales velocity screens can start and stop background polling safely.
- Shared renderer types now cover all sales velocity bridge return objects.

## 1.1.22 — Sales velocity and workspace image fixes

Products now show all linked images in the workspace, and the app degrades gracefully when opened outside Electron.

- Product workspaces now load all saved images instead of only the first page, so every linked image appears correctly.
- Opening King in a browser tab no longer crashes — a clear toast explains that the Electron window is required.
- Added sales velocity services with platform polling, cache staleness tracking, and exponential backoff.
- Added sales velocity IPC handlers for status, trends, and polling control.

## 1.1.21 — Navigation hierarchy cleanup

The main navigation is now grouped into clearer creation, tools, and library/business sections.

- Core creation groups Products, Image, Video, and Create Campaign together.
- Tools groups Marketing Templates, Reverse Engineer, Clone, and Music together.
- Library/Business groups Brand Environments, Characters, Starred, Ads, and Store while keeping every page accessible.

## 1.1.20 — Product campaign workspace upgrades

Product workspaces now guide first-run setup and make product-linked campaign assets easier to package and reuse.

- Empty Products now shows a focused 5-step setup path with one Add first product action.
- Product workspaces can create and save labeled product reference sheet assets for reuse in Image, Video, and Create Campaign.
- Image and Video detail views now support product linking, winner marking, campaign handoff, variations, and opening the linked product workspace.
- Create Campaign can export a product campaign bundle with launch brief, copy, manifest, winner status, and selected source assets.

## 1.1.19 — Workspace image placement fixes

Saved images are easier to place on product workspaces, with safer repeat actions and fuller image-library access.

- The image library picker now loads all saved images so workspace placement is not limited to the first page.
- Selected images from Image can be added directly to product workspaces, including from the image detail view.
- Adding saved images to a product workspace is now idempotent, so already-linked images are skipped safely while failed items stay retryable.

## 1.1.18 — Product workspace image linking

Products now act as the commerce workspace for product-aware image, video, and campaign creation.

- Product workspaces show a centered product brief panel with launch actions and recent linked image/video assets.
- Images created from Product Workspace, product references, or Create Campaign are saved back to the selected product workspace.
- Previously created saved images can now be placed onto any product workspace from the product board.
- Image and Video still keep direct freeform paths, including clear product/text-only escape options.

## 1.1.17 — Campaign creation and video polish

Create Campaign now guides offer-first ad creation more clearly and makes campaign-result video generation easier to recover.

- Create Campaign now walks through product, offer, audience, platform, reference style, output, results, export, and animation steps.
- Campaign video generation defaults to a general product reveal, explains when Shirt unwrap is chosen, and recovers saved videos for the selected source image.
- Marketing prompt templates and campaign export copy now better support offer-led promotional materials.

## 1.1.16 — Video and music creation updates

King now has a clearer Videos workflow, saved video/audio libraries, and broader generation routing.

- Videos has a top prompt box, source-image dropdown with preview, and clearer image-to-video/text-to-video model labels.
- Generated videos and audio are saved locally so they stay available after restart.
- fal.ai and KIE.ai video routes handle local image uploads more reliably before provider submission.

## 1.1.15 — Demo mode help

The dev-only demo toggle now explains exactly what sample data mode changes.

- Hover or focus the new ? beside Demo to see which dashboards switch to sample data.
- Demo help explains that ON skips real API calls and fills supported dashboards with fixtures.
- Demo help explains that OFF clears fixtures and returns those pages to real IPC/API data.

## 1.1.14 — Provider balance checks

Settings can now check provider-backed balances and quotas beside your current API usage.

- Check fal.ai, KIE.ai, OpenRouter, Firecrawl, and ElevenLabs balances or remaining quota directly from Settings > API keys.
- Compare provider-reported balance with this month’s saved fal.ai and KIE image usage on the same API key card.
- Replicate clearly reports that its public API does not expose a read-only balance or quota endpoint.

## 1.1.13 — Compare Create Ads results

Create Ads comparison now opens a real side-by-side review, and Reverse Prompt restart handling is clearer.

- Select two generated Create Ads results to open a focused comparison modal automatically.
- Close the comparison and reopen the same pair without losing your selected results.
- Use the side-by-side view to choose a winning creative before creating another ad or animating it.
- Reverse Prompt now explains when King must restart to load the latest desktop service fix and gives you a Restart King action.

## 1.1.12 — Reverse engineer any image

King now has a dedicated flow for turning uploads and image URLs into prompts.

- Open Reverse Engineer from the menu to upload, drag in, or paste any image URL for prompt reconstruction.
- Preview the source image, run the analysis, copy the final prompt, or send it back to image generation.
- Saved app images are normalized before analysis so Image Details reverse prompt works more reliably.

## 1.1.11 — Reverse prompt for saved images

King can now analyze a saved image and draft a generator-ready reconstruction prompt.

- Use Reverse prompt from the saved image detail view to infer the subject, style, lighting, colors, and scene structure.
- Copy the reconstructed prompt or send it straight back into Recreate for a faster refine loop.
- Results clearly explain that hidden prompts, seeds, LoRAs, sampler settings, and private generation metadata cannot be recovered from pixels.

## 1.1.10 — Image feedback for saved generations

King now lets you mark whether a saved generated image followed your instructions.

- Rate saved generated images as followed or missed instructions from the image detail view.
- See existing feedback directly on image cards so prompt-fit notes are easy to scan later.
- Feedback is stored cleanly on the saved image record without changing prompt generation behavior.

## 1.1.9 — Starred media landed ⭐

King now has a focused favorites flow for the saved images you want to come back to fast.

- Star and unstar saved images directly from the gallery or detail view.
- Jump into the new Starred section to see only your favorite saved media.
- Older saved images migrate safely and start unstarred until you choose otherwise.
- Image prompts can now include multiple product/character references, with products using only their primary image to avoid duplicate angles.
- Update handling is clearer when a restart is needed for new app wiring.
