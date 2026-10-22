# Incense to Ask

A working prototype for a thesis project on how older adults living alone ask for help.

Lighting incense is asking for help. On one phone, Grandma Chen chooses a task (a meal, cleaning, a hospital visit) and a person, and a stick is lit in her burner. On the other phone, that person receives the request and can answer. When they do, the incense glows steady.

## Use it

Open the site on two phones:

- Burner (the elder's side): `https://YOUR-SITE.netlify.app/#burner`
- Helper (the person asked): `https://YOUR-SITE.netlify.app/#helper`
- Both on one screen: `https://YOUR-SITE.netlify.app/#both`

Tap the burner to wipe the stick away and start again.

The two phones stay in sync through a public relay (ntfy.sh). To give your demo its own private channel, add the same `?room=` name on both phones, e.g. `https://YOUR-SITE.netlify.app/?room=sophie-demo#burner` and `https://YOUR-SITE.netlify.app/?room=sophie-demo#helper`.

## Deploy

This is a single static file (`index.html`), so no build step is needed. On Netlify, set the publish directory to the repository root and leave the build command empty.

Cat photos are placeholders for real helpers.
