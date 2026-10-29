# FrameLab — Photography & Videography Masterclass PWA

A mobile-first, installable progressive web app starter for a 30-day beginner course.

## Included
- 30-day curriculum and lesson screens
- Daily checklist and progress bar
- Local lesson notes
- Local photo/video submission journal (best for smaller files)
- Mentor review log with 1–5 ratings
- Exportable journal JSON
- PWA manifest, icons, and service worker for offline shell caching

## Important limitations
This starter stores progress and uploaded media in the current browser/device only. It has no account, cloud backup, or cross-device sync. Browser storage can be limited, especially for video. Export your journal and keep original media in your device gallery. To receive ChatGPT critique, attach selected work to your ongoing ChatGPT conversation; this app does not automatically send files to ChatGPT.

## Run locally for a quick preview
Opening `index.html` directly lets you use the core UI, but installability and service-worker offline caching require HTTPS (or localhost).

## Host it for installation
1. Upload the contents of this folder to a static HTTPS host (for example, a GitHub Pages repository).
2. Ensure `index.html` is at the published site root and the manifest, `sw.js`, and `icons/` paths are preserved.
3. Open the published HTTPS URL in Chrome on Android.
4. Use Chrome's menu and choose **Install app** or **Add to Home screen**.

See MDN's PWA installation guide: https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps/Guides/Making_PWAs_installable
