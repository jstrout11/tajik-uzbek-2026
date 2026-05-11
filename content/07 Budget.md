---
type: reference
category: budget
country: both
trip_days: 14
travelers: 2
tags: [budget]
---

# Budget

USD per **person** unless noted. Two travelers; trek economics work better split (one tent, one horseman, shared driver fees).

## Pre-trip (per person)
| Item | Cost USD |
|---|---:|
| Flights (already booked, TK economy, est.) | [flights_per_person:: 1500] |
| TJ e-visa (no GBAO) | [tj_visa:: 30] |
| Travel insurance (3 wk, trekking-covered) | [insurance:: 175] |
| Gear gaps (microspikes if needed, etc) | [gear:: 150] |
| **Pre-trip subtotal** | **1855** |

## On-the-ground daily ballparks (per person)

| Day type | Range USD |
|---|---:|
| Dushanbe city | $50–90 |
| Penjikent (border-town) | $40–70 |
| Trek day (food + horseman share + camp) | $25–40 |
| Samarkand | $60–110 |
| Tashkent | $70–120 |

## Detailed line items

### Lodging (twin rooms, per night for two, divide by 2 for per-person)
| Place | Per person/night | Notes |
|---|---:|---|
| Dushanbe (Atlas/mid-range) | [dushanbe_lodging:: 25] | Twin, mid-range |
| Penjikent (Hotel Umariyon) | [penjikent_lodging:: 18] | Twin, w/ breakfast |
| Trek (camp share + alplager bed) | [trek_lodging:: 10] | Avg across 5 nights |
| Samarkand (boutique guesthouse) | [samarkand_lodging:: 30] | Twin |
| Tashkent (central mid-range) | [tashkent_lodging:: 40] | Twin |

### Meals (per person, per meal)
| Meal | Cost USD |
|---|---:|
| Bazaar samsa / street | [meal_street:: 2] |
| Choyxona lunch | [meal_lunch:: 5] |
| Mid-range dinner | [meal_dinner:: 10] |
| Big plov meal (Besh Qozon) | [meal_plov:: 5] |
| Hotel breakfast (often included) | 0 |

### Transport (one-time / per-segment)
| Leg | Cost (per person USD) | Notes |
|---|---:|---|
| Yandex Go DYU airport → hotel | [taxi_dyu:: 5] | $10 total split |
| Dushanbe → Penjikent (shared taxi) | [taxi_dyu_pjk:: 15] | 5–6h |
| Penjikent → Artuch (vehicle hire) | [taxi_artuch:: 18] | Splits between two |
| Trek out → Penjikent | [taxi_pjk_out:: 18] | |
| Penjikent → border → Samarkand | [taxi_pjk_sam:: 20] | Including border |
| **Afrosiyob train** Samarkand → Tashkent | [afrosiyob:: 25] | Econ class, book ahead |
| Tashkent hotel → TAS airport | [taxi_tas:: 5] | $10 total split |

### Trek-specific (split between two travelers)
| Item | Total cost USD | Per person |
|---|---:|---:|
| Horseman + 1 horse, 5 days (300 TJS/day × 5) | $160 | $80 |
| Food provisioning (Penjikent bazaar, for 2 + horseman 5 days) | $85 | $43 |
| Stove fuel (Dushanbe) | $11 | $6 |
| Horseman tip + small gift | $40 | $20 |
| **Trek total per person** | | **~$149** |

### Activities / entries
| Site | Cost USD |
|---|---:|
| Dushanbe National Museum | 3 |
| Hissar Fortress (optional) | 1 + $16 taxi share |
| Ancient Penjikent ruins | 2 |
| Shah-i-Zinda | 4 |
| Registan | 5.5 |
| Bibi-Khanym | 3 |
| Gur-e-Amir | 3 |
| Ulugh Beg Observatory | 3 |
| Afrosiyob Museum | 3 |
| Khast Imam | free (donations welcome) |
| Tashkent metro day pass | 1 |

## Daily totals — per person

### Tajikistan phase (Days 1–9)

| Day | Location | Day total USD |
|---:|---|---:|
| 1 | Dushanbe (arrival) | 45 |
| 2 | Dushanbe | 53 |
| 3 | Penjikent | 47 |
| 4 | Artuch | 38 |
| 5 | Trek (Kulikalon) | 55 |
| 6 | Trek (rest) | 50 |
| 7 | Trek (Alaudin) | 52 |
| 8 | Trek (rest) | 50 |
| 9 | Trek out + Samarkand transit | 83 |
| | **TJ phase subtotal** | **~473** |

### Uzbekistan phase (Days 10–14)

| Day | Location | Day total USD |
|---:|---|---:|
| 10 | Samarkand | 78 |
| 11 | Samarkand | 69 |
| 12 | SAM → Tashkent | 92 |
| 13 | Tashkent | 66 |
| 14 | Tashkent | 72 |
| | **UZ phase subtotal** | **~377** |

**14-day on-ground total per person: ~$850**

Day totals break down as lodging + food + transport + activities — see the line-item tables above for the components.

## Bottom line

| Bucket | Per person USD |
|---|---:|
| On-the-ground (14 days) | ~$850 |
| Pre-trip excluding flights | ~$355 |
| **Per person, excluding international flights** | **~$1,200** |
| International flights (already booked) | ~$1,500 |
| **All-in per person** | **~$2,700** |

## Sanity checks
- Trek days run **$50–55** — cheap on lodging, but the horseman share inflates it
- Samarkand and Tashkent are the daily-cost peaks (lodging + entries + nicer dinners)
- Dushanbe is cheaper than UZ cities — TJS is weak, fewer tourist-targeted prices
- **$1,500 is doable** for a backpacker style (hostels, no horseman, [[Seven Lakes (Haft Kul)|Haft Kul homestays]] instead of Kulikalon-Alaudin)
- **$2,000–2,500 per person on-the-ground** if going boutique on hotels and dining better

## Cash flow plan
- Start with $700 USD cash per person
- ATM in Dushanbe Day 1 or 2: withdraw 3000 TJS (~$320)
- Use cards in Samarkand + Tashkent hotels + better restaurants
- Bazaar moneychangers in UZ for any USD-to-UZS conversion (better rates than banks)

## Dataview rollup
The Daily Template logs `spend_usd` per day. The Index dashboard query rolls it up across the trip — keeps actuals visible.

## Cross-references
[[Money]] · [[Flights]] · [[Overview]]
