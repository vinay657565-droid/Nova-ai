NOVA AI phone project

Files:
- index.html: app interface and demo chat
- manifest.webmanifest: installable web app metadata
- sw.js: basic offline caching

To use:
1. Upload these files to a static web host using HTTPS.
2. Open the hosted URL in Chrome on Android.
3. Use Chrome menu > Add to Home screen / Install app.

Important:
- This is a prototype. Replies are scripted demo replies, not a connected AI model.
- Microphone input depends on browser support and HTTPS.
- Male/female voice selection uses voices installed on the phone; availability varies.
- Do not put secret AI API keys in index.html. A secure server-side backend is needed for real AI.
