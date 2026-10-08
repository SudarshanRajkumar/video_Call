# Sudarshan ♥ Taniya

A private video call for two. One static page, no server to run.

## How it works
Video goes directly between your two browsers (WebRTC). The free public PeerJS cloud server only helps you find each other.
Both of you open the site, type the same secret word, and tap your own name.

## Deploy on Vercel
1. Put `index.html` and `README.md` in a GitHub repo.
2. On vercel.com choose Add New > Project, import the repo, keep the defaults (Framework: Other), and Deploy.
3. Open your `https://...vercel.app` address on both devices. HTTPS is required for the camera.

## If it will not connect on mobile data
Some mobile networks block direct connections. Add a TURN server to the `TURN` list near the top of the script in `index.html`.
