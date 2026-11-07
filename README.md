# MARTOM App – MVP

## 📱 Web app (best on a phone)
**https://lucaohm.github.io/MartomSport_APP/**

## 🎬 Pitch video for management (57 s, Spanish)
**[video/martom-trailer-es.mp4](video/martom-trailer-es.mp4)**: 1920×1080 MP4 with music. To download it on GitHub, open the file and click **"Download raw file"**.

---

## Two perspectives
- **Pitch video → business view.** Why the app pays off for MARTOM: recurring revenue, customer loyalty, marketing, cross-selling, data and go-to-market for new countries. Peloton, Tonal and Strava serve as proof of the model.
- **Web app → customer view.** What a MARTOM owner gets: their plan, their progress, their community, their machine.

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

Also included: MARTOM+ (freemium with discounts and bonuses), offers for accessories and upgrades, and English / Spanish.

## The pitch structure (video)
1. Hook: "Today we sell machines. What if we sold a relationship?"
2. Problem: one sale, one time – after delivery we lose the customer
3. Proof: Peloton, Tonal and Strava sell a relationship that renews every month
4. The MARTOM app: the same formula
5. What the customer gets: plan, progress, community, machine always up to date
6. The model: from a one-off sale to recurring revenue (MARTOM+, accessories, nutrition & recovery)
7. Five reasons the app is a business: loyalty · marketing · cross-selling · data · go-to-market
8. "Fidelizar. Facturar. Escalar." → logo

The video shows no concrete figures; Peloton, Tonal and Strava are named only as market references.

## Notes
- Prototype with no backend. Data stays in the viewer's browser. To start over, use **Profile → Reset demo**.
- Logo, products, prices and product photos come from [martomsport.com](https://martomsport.com). Mood photos are from Unsplash (free licence).
- Users, communities, figures, offers and subscription prices are **fictional demo content**.
- The trailer music is an original composition generated in code, so there are no licence costs.

## Files
- `index.html`: the web app (everything in one file)
- `video/martom-trailer-es.mp4`: the pitch video
- `video/trailer.html`: the source of the pitch video (scenes, texts and music), used to create the video again

## Publish an update
```bash
git add index.html README.md video/
git commit -m "MVP update"
git push
```
GitHub Pages updates the link within 1–2 minutes.
