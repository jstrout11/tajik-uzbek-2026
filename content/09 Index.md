---
type: index
trip: tajikistan-uzbekistan-2026
start_date: 2026-10-03
end_date: 2026-10-18
duration_days: 16
travelers: 2
direction: TJ-first
status: booked
tags: [index]
---

# Tajikistan + Uzbekistan 2026

> [!info] Trip shape
> **Oct 3 → Oct 18, 2026.** Two travelers. Tajikistan first (trek), Uzbekistan second (cities). Open-jaw on Turkish Airlines via IST: arrive DYU 01:00 Oct 3, depart TAS 09:35 Oct 18.

`route:: Dushanbe → Penjikent → Fann Mountains → Penjikent → Samarkand → Tashkent`
`booking_status:: confirmed`
`vault_owner:: trip-planning`

---

## Decisions made
- **Direction:** TJ-first → UZ-second. Trek at peak fitness, descend into easier cultural half.
- **Trek:** [[Kulikalon-Alaudin Loop]] — 5 days, max pass 3860m. October-viable.
- **Cities cut:** Bukhara and Khiva parked for a future trip. Samarkand is the non-negotiable UZ stop.
- **Border:** Sarazm/Jartepa overland (Penjikent → Samarkand). 24/7 crossing.
- **Flights:** Turkish Airlines, IST hub. No domestic Dushanbe→Tashkent — we exit overland.
- **GBAO permit:** **NOT needed** — Pamir is not on the itinerary.
- **Travelers:** Both fit and capable. No softer route, no soft itinerary.

---

## Live dashboard

### Places (by country, priority)
```dataview
TABLE country, days_needed, priority, elevation_m
FROM "Tajikistan + Uzbekistan 2026/03 Places"
WHERE type = "place"
SORT country ASC, priority DESC
```

### Open logistics
```dataview
TABLE category, country, status
FROM "Tajikistan + Uzbekistan 2026/01 Logistics"
WHERE status = "open"
```

### All open todos
```dataview
TASK
FROM "Tajikistan + Uzbekistan 2026"
WHERE !completed
```

### Trek options
```dataview
TABLE days, max_elevation_m, october_viability, difficulty
FROM "Tajikistan + Uzbekistan 2026/04 Treks"
WHERE type = "trek_route"
SORT max_elevation_m DESC
```

### Daily spend rollup (fills in as the trip progresses)
```dataview
TABLE date, location, spend_usd, country
FROM "Tajikistan + Uzbekistan 2026/02 Itinerary"
WHERE type = "day"
SORT date ASC
```

---

## Quick navigation

### Logistics
- [[Visas]] · [[Flights]] · [[Money]] · [[SIM & Connectivity]] · [[Packing]] · [[Health]]

### Trip
- [[Overview|Itinerary Overview]] · [[Daily Template]] · [[Budget]]

### Places
- TJ: [[Dushanbe]] · [[Penjikent]] · [[Artush and Pasrud]] · [[Iskanderkul]]
- UZ: [[Samarkand]] · [[Tashkent]]

### Treks
- [[Kulikalon-Alaudin Loop]] (the plan) · [[Seven Lakes (Haft Kul)]] (backup) · [[Chimtarga Base Camp]] (parked)

### Reference
- [[05 Food & Culture]] · [[06 Phrases]] · [[08 Resources]]

---

## Open questions
- [ ] Confirm Penjikent border (Sarazm/Jartepa) is operating normally — check 2 weeks before departure via [Caravanistan forum](https://caravanistan.com/forum/)
- [ ] Apply for TJ e-visa via [evisa.tj](https://www.evisa.tj/) by August 2026 (allow 3–5 days, **no GBAO**)
- [ ] Book Afrosiyob Samarkand → Tashkent on [railway.uz](https://railway.uz/) 1–2 weeks before
- [ ] Email 3+ operators using templated message in [[Kulikalon-Alaudin Loop#Specific people to email — start here|trek note]] (Saidbek, Saidali, Paramount Journey, Hiking Tajikistan, ZTDA)
- [ ] Decide: independent trek with hired horseman vs. supported guided trek (~$50–80/day extra for guide)
- [ ] Reserve [Hotel Umariyon](https://www.booking.com/hotel/tj/umarion.html) in Penjikent for Day 3 and Day 9
- [ ] Decide: shared taxi vs. private hire Dushanbe → Penjikent (Anzob Pass)
- [ ] Confirm travel insurance covers trekking to 4000m
- [ ] Buy/borrow microspikes — only needed if shoulder-season snow hits passes
- [ ] Identify whether to do Hissar Fortress half-day from Dushanbe (extra Day 2 option)

## Surfaceable later
- [ ] Pre-trip language: download Memrise/Anki Russian phrasebook
- [ ] Photo plan: Shah-i-Zinda sunrise, Registan blue hour, metro stations
- [ ] Bring USD cash in small clean bills — see [[Money]]

---

## Parked (future trips)
- **Bukhara + Khiva** — would require dropping the trek or another stop. Not this trip.
- **Pamir Highway / Wakhan / GBAO** — needs Kyrgyz exit (Osh) to make sense. Pair with Lenin Peak next time.
- **Khujand + Panjshanbe Bazaar** — northern detour, doesn't fit.
