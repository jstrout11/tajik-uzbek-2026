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

## TJ → UZ on Day 9: land vs fly — evaluated

The Day 9 trek-out → Samarkand transit can be done overland (current plan) or via one of two flight paths. We evaluated all three.

### Option A — Land via Sarazm/Jartepa border (CURRENT PLAN)
- Trek out → Penjikent (~5h) → border (45 min from Penjikent) → Samarkand (45 min from border)
- Total: ~7h door-to-door from the trailhead
- Cost: **~$20/person**
- Border 24/7, no flight booking
- Direction: continuous westward — no backtracking
- Risk: border closure (rare since 2018 reopening; was closed nearly a decade post-USSR)

### Option B — Fly via Khujand (LBD → TAS)
- Trek out → Penjikent (~5h) → Khujand over **Shahristan Pass 3380m** (~4h) → overnight Khujand → fly LBD → TAS (1h, **not daily** — most days require a layover) → train TAS → Samarkand (2h)
- Total: **2 days** (overnight in Khujand)
- Cost: **~$130–180/person** (flight + Khujand hotel + train)
- ⚠️ Shahristan Pass at 3380m — **same October snow concern as the trek**; if snow closes Alaudin, it'll likely close this too
- ⚠️ Khujand-Tashkent direct flights aren't every day (Somon Air ~11/week, Ural Airlines 69/week but mostly via TAS layover routes — verify exact day)
- Backtracks our westward direction (Khujand is north, Tashkent is north-northeast)

### Option C — Fly via Dushanbe (DYU → TAS)
- Trek out → Penjikent (~5h) → Dushanbe over Anzob Pass (~6h) → overnight Dushanbe → fly DYU → TAS (1h, Somon Air / Uzbekistan Airways / Centrum Air, $100–200) → train TAS → Samarkand (2h)
- Total: **2 days** (overnight in Dushanbe)
- Cost: **~$150–250/person** (flight + Dushanbe hotel + train)
- Worst direction-wise: backtrack 240km east, fly 280km west, train 260km east

### Verdict
| | Time | Cost | Hassle |
|---|---|---|---|
| **Land (A)** | 7h | $20 | low — one shared taxi day |
| Khujand (B) | 2 days | $150 | airport, snow risk on Shahristan |
| Dushanbe (C) | 2 days | $200 | airport, full backtrack, costs a Dushanbe hotel |

> [!tip] Recommendation
> Land crossing is unambiguously the right call. It's faster, cheaper, scenic, and goes in the direction we're already moving. Flying is a **fallback only**, not a Plan B to weigh.

### When to switch to flying
- **Sarazm/Jartepa border closes** (geopolitics, rare). Check [Caravanistan border crossings](https://caravanistan.com/border-crossings/uzbekistan/) 2 weeks before departure.
- **Trek runs long / one of us is incapacitated** — if Day 9 trek-out doesn't get us to Penjikent until evening, we miss border closing hours on rare bad days; sleep Penjikent, cross AM Day 10
- **Carrying critical gear / time pressure** — not applicable to us

> [!warning] Pre-trip check (~2 weeks before)
> Confirm Sarazm/Jartepa is open and running normal hours. If closed, **Option B (Khujand) beats Option C (Dushanbe)** because we don't backtrack as far and Khujand is on the way out of Fann anyway. But check Shahristan Pass conditions — early snow can close it.

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
