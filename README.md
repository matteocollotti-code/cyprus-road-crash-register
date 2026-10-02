# Cyprus Road Crash Register (2016–2026)

Press-reported road traffic collisions in the Republic of Cyprus, from 1 January 2016 to 1 October 2026: **8,210 news articles** describing **3,075 distinct crashes** (532 fatal).

- **Interactive register:** https://matteocollotti-code.github.io/cyprus-road-crash-register/
- **Excel:** [cyprus_road_crashes_2016_2026.xlsx](cyprus_road_crashes_2016_2026.xlsx)
- **CSV:** [comma-separated](cyprus_road_crashes_2016_2026.csv) · [semicolon-separated (EU Excel)](cyprus_road_crashes_2016_2026_semicolon.csv)

## Columns

| Column | Content |
|---|---|
| Year, Day, Month | Date of the crash (from the article text; otherwise the publication date) |
| Involved Users | Road users and vehicles involved |
| Accident Outcome | Deaths and injuries as reported |
| Road Type | Highway / Motorway, Urban Area, Rural Road, Mountain Road, Dirt Road / Off-road, Unknown |
| City / Location | Town or village and the specific spot when given |
| Crash Causes | Cause as reported, or "Under investigation" / "Not reported" |
| Severity | Fatal or Non-Fatal |
| Article Link | URL of the press report |
| Duplicate Flag | `*` when the article reports a crash already listed in an earlier row |

Each row is one article. To count crashes rather than articles, keep only rows with an empty Duplicate Flag.

## Scope and sources

Only press reports are used — no police or government statistics. Crashes in the north of the island outside the Republic's effective control are excluded; the British Sovereign Base Areas are included. Greek-language reports are summarised in English.

| Outlet | Language | Years | Coverage |
|---|---|---|---|
| Phileleftheros (philenews.com) | Greek | mid-2017–2026 | all crash reports |
| Cyprus Times (cyprustimes.com) | Greek | 2016–2026 | all crash reports to 2017, fatal crashes after |
| Omega Live (omegalive.com.cy) | Greek | 2016–2026 | fatal crashes |
| Cyprus Mail (cyprus-mail.com and its archive) | English | 2016–2026 | all crash reports |
| Alphanews (alphanews.live) | Greek | 2017–2026 | fatal crashes |
| Sigmalive English (en.sigmalive.com) | English | Nov 2024–2026 | all crash reports |
| Famagusta Gazette (famagusta-gazette.com) | English | 2024–2026 | all crash reports |
| Limassol Today (limassoltoday.com.cy) | Greek | 2020–2026 | fatal crashes |

## Method and limitations

- Articles were collected from each outlet's public archive, filtered by crash-related keywords, and read one by one; the fields summarise the opening of each article.
- Articles about the same crash share an event and only the first listed one is unflagged. Severity reflects the final outcome of the crash across all its articles.
- When a post-mortem found the only death was from a medical cause (for example a heart attack at the wheel), the crash is marked Non-Fatal and the outcome says so.
- A block of 41 Cyprus Times posts with a corrupted publication date (all stamped 2 June 2016) is left out.
- Non-fatal crashes are only as complete as the outlets' own coverage; minor crashes no outlet reported are missing. About half of the crashes have no reported cause.
- Facebook posts were not read (they require sign-in); the register cites the outlets' own articles instead.

The summaries are short paraphrases; the original reporting belongs to the outlets linked in each row.
