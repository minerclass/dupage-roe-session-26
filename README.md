# What AI Makes Easy Might Be What Students Need to Struggle With

Interactive keynote presentation prepared for DuPage ROE.

The presentation examines how frictionless generative AI can improve visible
student work while bypassing the cognitive, rhetorical, and existential
struggles through which learning develops. It connects learning science, media
ecology, AI governance, and practical instructional design.

## View the presentation

Open `index.html` in a modern browser, or publish the repository with GitHub
Pages.

For presentation use, a desktop or laptop display in landscape orientation is
recommended. Phone portrait mode fits the slides to the viewport but makes
dense slide text difficult to read.

## Interaction

- Use the previous, next, and reset controls to move through the 26 full-screen scenes.
- The public presentation intentionally hides the editor-style thumbnail rail.
- Scroll vertically or use the browser URL hash to move between slides.
- Click cards and controls to reveal examples and explore concepts.
- Use the built-in activities for audience participation and discussion.
- External resource links open in a new browser tab.

## Publish with GitHub Pages

1. Create a new public GitHub repository.
2. Add the files in this folder to the repository root.
3. In the repository, open **Settings > Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder, then save.

GitHub will display the presentation at:

`https://<github-username>.github.io/<repository-name>/`

## Repository structure

- `index.html` — self-contained presentation and embedded visual assets
- `dupage-session-qr.png` — opening-slide QR code for the session short link
- `.nojekyll` — tells GitHub Pages to serve the files directly
- `.gitignore` — excludes common local and editor files

## Public links

The presentation links to these public resources:

- <https://bit.ly/4eIqti4>
- <https://minerclass.github.io/friction-game/>
- <https://minerclass.github.io/orality_game/>
- <https://micahminer.com/projects/>

## Privacy and maintenance

The reviewed presentation contains no credentials, local file paths, private
participant data, or obvious personally identifiable student information.
Keep private district information, participant data, research notes, and
credentials out of this public repository.

`index.html` is a generated standalone bundle. It is reliable for presenting
and publishing, but direct editing is difficult. Keep the original editable
presentation source in a private working location and regenerate `index.html`
when substantive revisions are needed.

The generated bundle uses the in-browser Babel transformer and emits a
non-failing production-use warning in the browser console. Removing that
warning would require rebuilding from the editable source with precompiled
scripts.
