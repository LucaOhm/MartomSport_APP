# MARTOM App – MVP

## 📱 Web app (best on a phone)
**https://lucaohm.github.io/MartomSport_APP/**

## 🎬 Marketing trailer (video file, 57 s, Spanish)
**[video/martom-trailer-es.mp4](video/martom-trailer-es.mp4)**: 1920×1080 MP4 with music. To download it on GitHub, open the file and click **"Download raw file"**.

---

## What the web app shows

When the link opens, a **short interactive demo (12 steps)** starts. A hand shows where to tap, and the rest of the screen is dimmed. After that, the normal user view begins.
To skip the demo and go straight to the app, use https://lucaohm.github.io/MartomSport_APP/#app

| # | Area | Contents |
|---|---|---|
| 1 | **Monitoring dashboard** | Minutes, km, kcal and resting heart rate, a weekly chart, and a connection to Apple Health, Google Health Connect, Garmin, Strava, Polar, Fitbit and a Bluetooth heart-rate strap |
| 2 | **Individual training** | "Create my personal plan" (goal, level, days, time, limitations, equipment), weekly planner, live and on-demand classes, and a guided player with exercise animations and a live ranking |
| 3 | **Community & gamification** | Over 100 communities (by sport, region and age), clubs, a weekly league with promotion, challenges, ranking and a feed with kudos |
| 4 | **Profile & equipment** | Every MARTOM machine with a health score, usage, software version and updates, maintenance, warranty, and a digital manual (installation and technique) |
| 🔒 | **Coming soon** | Nutrition (nutritionists, MARTOM protein) and recovery (physiotherapists), each with a waitlist |

Also included: MARTOM+ (freemium with discounts and bonuses), smart upselling, and English / Spanish.

## The trailer's pitch structure
Hook → problem (the customer is alone after delivery) → solution → 4 customer benefits (individual plan, monitoring, community, equipment) → 5 benefits for MARTOM (loyalty, new products, community, trust, marketing) → "Fidelizar. Atraer. Convencer." → logo.

## Notes
- Prototype with no backend. Data stays in the viewer's browser. To start over, use **Profile → Reset demo**.
- Logo, products, prices and product photos come from [martomsport.com](https://martomsport.com). Mood photos are from Unsplash (free licence).
- Users, communities, figures, offers and subscription prices are **fictional demo content**.
- The trailer music is an original composition generated in code, so there are no licence costs.

## Files
- `index.html`: the web app (everything in one file)
- `video/martom-trailer-es.mp4`: the marketing trailer
- `video/trailer.html`: the source of the trailer (scenes, texts and music), used to create the video again

## Publish an update
```bash
git add index.html README.md video/
git commit -m "MVP v0.6 + trailer"
git push
```
GitHub Pages updates the link within 1–2 minutes.
