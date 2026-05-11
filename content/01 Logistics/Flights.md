---
type: logistics
category: flights
country: both
status: resolved
carrier: Turkish Airlines
tags: [logistics]
---

# Flights

## Booked — Turkish Airlines, open-jaw via IST

### Outbound: DEN → DYU
- Thursday, **October 1, 2026**, depart DEN 20:25
- Connection: Istanbul (IST)
- Arrive DYU **01:00 Saturday October 3** (+2 days)
- Total: 17h 35m, Economy V-V
- `outbound_arrival_local:: 2026-10-03 01:00`

### Return: TAS → DEN
- Sunday, **October 18, 2026**, depart TAS 09:35
- Connection: Istanbul (IST)
- Arrive DEN 18:25 same day
- Total: 19h 50m, Economy V-V
- `return_departure_local:: 2026-10-18 09:35`

> [!info] Why this routing works
> Open-jaw lets us go TJ-first → UZ-second with no backtracking. Saves a domestic flight Dushanbe↔Tashkent ($100–200, ~1h) — we exit overland via the Sarazm border instead.

## IST ↔ DYU sector (Turkish Airlines)
- TK flies IST ↔ DYU **4× per week** (as of mid-2025); Somon Air also serves the route
- Flight time ~4h 35m
- Earliest IST departure ~10:45 (arrives DYU 17:20), latest ~19:10 (arrives DYU 01:55)
- Our segment is the late IST flight, arriving DYU at 01:00 local

## Implications

### Arrival logistics (Day 1, Oct 3, 01:00 DYU)
- Book Dushanbe accommodation **with confirmed late check-in**
- Pre-arrange airport pickup (most guesthouses do this for ~$10–20)
- First "day" is really a sleep-in; plan Day 1 light

### Departure logistics (Day 14/16, Oct 18, 09:35 TAS)
- Need to be at TAS by ~07:00 → leave hotel by 06:00–06:30
- Pre-book taxi the night before (Yandex Go works in Tashkent) or hotel arranges
- Pack the night before; nothing critical scheduled morning of departure

## Fallback / no-go scenarios

> [!warning] If the Sarazm/Jartepa border closes (Day 9)
> Fallback plan: shared taxi or fly Khujand → Tashkent. Somon Air and Uzbekistan Airways both run Dushanbe ↔ Tashkent (~1h, $100–200, several days/week). Centrum Air also operates this route. Last-resort budget: $400 unplanned flights for two.

## Internal transport (planned)
| Leg | Mode | Cost (per person, USD) | Duration | Status |
|---|---|---:|---|---|
| Dushanbe → Penjikent | Shared taxi, Anzob Pass | [tax_share_dyu_pjk_usd:: 15] | 5–6h | book day-of |
| Penjikent → Samarkand | Shared taxi via Sarazm border | [tax_share_pjk_sam_usd:: 20] | 2–3h incl. border | book day-of |
| Samarkand → Tashkent | **Afrosiyob** high-speed | [afrosiyob_sam_tas_usd:: 25] econ | 2h 10m | book 1–2 weeks ahead at [railway.uz](https://railway.uz/) |

## Cross-references
[[Visas]] · [[Money]] · [[Overview]]

## Sources
- [Direct flights IST → DYU schedules](https://www.flightsfrom.com/IST-DYU)
- [Turkish Airlines IST-Dushanbe](https://www.turkishairlines.com/en/flights-from-istanbul-to-dushanbe)
- [Caravanistan: Dushanbe transport](https://caravanistan.com/tajikistan/center/dushanbe/transport/)
