# Vector Siege

An arena shooter that runs in any modern browser, including Safari on iPhone and iPad.
No accounts and no app store needed.

- **Team Battle 5v5:** everyone who opens the site joins the same match. AI bots fill every empty slot.
- **Drone Siege:** solo survival against waves of drones.
- **Private match:** add a code to the link, like `.../vector-siege/#friday`. Only people with that exact link play together.

Online play connects players directly to each other (WebRTC through the free PeerJS service). On some strict networks, such as certain cellular or school Wi-Fi networks, two players may not be able to connect. When that happens, each player still gets a full match against bots.

## Hosting on GitHub Pages
1. Create a new public repository named `vector-siege`.
2. Upload every file in this folder to it.
3. Open Settings, then Pages. Under "Build and deployment", choose **Deploy from a branch**, then `main` and `/ (root)`, and save.
4. After about a minute the game is live at `https://<your-username>.github.io/vector-siege/`.
