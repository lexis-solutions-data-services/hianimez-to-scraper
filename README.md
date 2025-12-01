# 📺 HiAnimez Scraper

![banner](https://i.ibb.co/pjTTWQLd/hianimez-cover.png)

An actor that scrapes anime data from [HiAnimez.to](https://hianimez.to/), a platform that streams a wide variety of anime shows and movies. The actor allows you to programmatically search and filter anime listings by title, genre, season, language, rating, and more.

<p align="center">
  <img src="https://apify-image-uploads-prod.s3.us-east-1.amazonaws.com/DevbkY3adMTBuoECt-actor-vXPR3Xr9ngzXxiccT-qeouYclYzM-images-2.jpeg" alt="Hianimez To Scraper" style="height: 60px; margin-right: 15px;" /><a href="https://apify.com/lexis-solutions/hianimez-to-scraper" target="_blank">
    <img src="https://img.shields.io/badge/Try%20it%20on-Apify-0066FF?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNDA4IiBoZWlnaHQ9IjQwOCIgdmlld0JveD0iMCAwIDQwOCA0MDgiIGZpbGw9Im5vbmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+CjxnIGNsaXAtcGF0aD0idXJsKCNjbGlwMF8zNDFfNDE1NykiPgo8cGF0aCBkPSJNMjE4LjY5NSAxMDRIMzAwLjk3QzMwMi42NDMgMTA0IDMwNCAxMDUuMzU3IDMwNCAxMDcuMDNWMjMyLjc2NkMzMDQgMjM1Ljc3OCAzMDAuMDgzIDIzNi45NDUgMjk4LjQzNCAyMzQuNDI1TDIxNi4xNTkgMTA4LjY5QzIxNC44NDEgMTA2LjY3NCAyMTYuMjg3IDEwNCAyMTguNjk1IDEwNFoiIGZpbGw9IndoaXRlIi8+CjxwYXRoIGQ9Ik0xODkuMzA1IDEwNEgxMDcuMDNDMTA1LjM1NyAxMDQgMTA0IDEwNS4zNTcgMTA0IDEwNy4wM1YyMzIuNzY2QzEwNCAyMzUuNzc4IDEwNy45MTcgMjM2Ljk0NSAxMDkuNTY2IDIzNC40MjVMMTkxLjg0IDEwOC42OUMxOTMuMTU5IDEwNi42NzQgMTkxLjcxMyAxMDQgMTg5LjMwNSAxMDRaIiBmaWxsPSJ3aGl0ZSIvPgo8cGF0aCBkPSJNMjAyLjU5MSAyMDQuNjY4TDEwOS4xMjcgMjk4LjgzNUMxMDcuMjI5IDMwMC43NDcgMTA4LjU4MyAzMDQgMTExLjI3OCAzMDRIMjk2LjhDMjk5LjQ4MyAzMDQgMzAwLjg0MiAzMDAuNzcgMjk4Ljk2NyAyOTguODUyTDIwNi45MDggMjA0LjY4NUMyMDUuNzI2IDIwMy40NzUgMjAzLjc4MiAyMDMuNDY4IDIwMi41OTEgMjA0LjY2OFoiIGZpbGw9IndoaXRlIi8+CjwvZz4KPGRlZnM+CjxjbGlwUGF0aCBpZD0iY2xpcDBfMzQxXzQxNTciPgo8cmVjdCB3aWR0aD0iMjAwIiBoZWlnaHQ9IjIwMCIgZmlsbD0id2hpdGUiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEwNCAxMDQpIi8+CjwvY2xpcFBhdGg+CjwvZGVmcz4KPC9zdmc+Cg==&logoColor=white" alt="Try it on Apify" style="border-radius: 12px; height: 60px;" />
  </a>
</p>


---


## 📊 Actor Stats

| Stat | Value |
|------|-------|
| **Version** | `0.0.3` |
| **Last Update** | Dec 1, 2025 |

---



## 💻 Integration Examples

This repository includes example code showing how to integrate the `hianimez-to-scraper` actor into your projects.

You can find example implementations in the [`examples/`](./examples) folder:
- **TypeScript/JavaScript**: See [`examples/typescript/`](./examples/typescript) for a complete TypeScript example
- **Python**: See [`examples/python/`](./examples/python) for a complete Python example

Each example includes:
- Ready-to-use code templates
- Setup instructions
- Documentation links

---


## 🧰 Key Features

- 🔍 Search anime by title query
- 🎯 Filter results by genre, type, language, release season, and score
- 🗓 Filter by release date range
- 🎞 Get metadata like MAL score, type, genres, language, and more
- 📈 Control maximum number of results

---

## 👤 Who Is This Actor For?

This actor is ideal for:

- **Anime content aggregators** who need up-to-date anime metadata
- **Data scientists / analysts** building anime recommendation engines
- **Media platforms** looking to enrich anime listings
- **Otaku developers** building search tools, dashboards, or apps

---

## 🎛 Enums Schema

Below are the accepted enum values for filtering your anime search (use the IDs as your values):

### 🎞 Type

| ID  | Type    |
| --- | ------- |
| 1   | Movie   |
| 2   | TV      |
| 3   | OVA     |
| 4   | ONA     |
| 5   | Special |
| 6   | Music   |

### 📡 Status

| ID  | Status           |
| --- | ---------------- |
| 1   | Finished Airing  |
| 2   | Currently Airing |
| 3   | Not yet aired    |

### 🔞 Rate

| ID  | Rating |
| --- | ------ |
| 1   | G      |
| 2   | PG     |
| 3   | PG-13  |
| 4   | R      |
| 5   | R+     |
| 6   | Rx     |

### ⭐ Score

| ID  | Score Label      |
| --- | ---------------- |
| 1   | (1) Appalling    |
| 2   | (2) Horrible     |
| 3   | (3) Very Bad     |
| 4   | (4) Bad          |
| 5   | (5) Average      |
| 6   | (6) Fine         |
| 7   | (7) Good         |
| 8   | (8) Very Good    |
| 9   | (9) Great        |
| 10  | (10) Masterpiece |

### 🍂 Season

| ID  | Season |
| --- | ------ |
| 1   | Spring |
| 2   | Summer |
| 3   | Fall   |
| 4   | Winter |

### 🗣 Language

| ID  | Language  |
| --- | --------- |
| 1   | SUB       |
| 2   | DUB       |
| 3   | SUB & DUB |

### 🏷 Genres

| ID  | Genre        | ID  | Genre         |
| --- | ------------ | --- | ------------- |
| 1   | Action       | 19  | Music         |
| 2   | Adventure    | 7   | Mystery       |
| 3   | Cars         | 20  | Parody        |
| 4   | Comedy       | 39  | Police        |
| 5   | Dementia     | 40  | Psychological |
| 6   | Demons       | 22  | Romance       |
| 8   | Drama        | 21  | Samurai       |
| 9   | Ecchi        | 23  | School        |
| 10  | Fantasy      | 24  | Sci-Fi        |
| 11  | Game         | 42  | Seinen        |
| 35  | Harem        | 25  | Shoujo        |
| 13  | Historical   | 26  | Shoujo Ai     |
| 14  | Horror       | 27  | Shounen       |
| 44  | Isekai       | 28  | Shounen Ai    |
| 43  | Josei        | 36  | Slice of Life |
| 15  | Kids         | 29  | Space         |
| 16  | Magic        | 30  | Sports        |
| 17  | Martial Arts | 31  | Super Power   |
| 18  | Mecha        | 37  | Supernatural  |
| 38  | Military     | 41  | Thriller      |
| 32  | Vampire      |     |               |

> ℹ️ Use the `genres` field as an array of genre IDs, e.g., `"genres": ["1", "2", "4"]` for Action, Adventure, Comedy.

---

## 🧮 Input Schema

The actor accepts the following input fields:

```json
{
  "query": "one piece", // Search keyword for anime title
  "type": "1", // Enum ID for anime type (e.g., Movie, TV)
  "status": "2", // Enum ID for airing status (e.g., Ongoing, Completed)
  "rate": "2", // Enum ID for rating (e.g., PG, R+)
  "score": "5", // Enum ID for score (e.g., Appalling, Masterpiece)
  "season": "2", // Enum ID for release season (e.g., Spring, Summer)
  "language": "1", // Enum ID for language (e.g., SUB, DUB)
  "genres": ["1", "2", "4"], // Array of genre enum IDs (e.g., Action, Comedy)
  "startDate": "2024-01-01", // ISO date string, e.g., "2024-01-01"
  "endDate": "2025-02-01", // ISO date string, e.g., "2025-02-01"
  "maxItems": 100 // Maximum number of results to fetch
}
```

## 📤 Output Schema

Each result (anime) will contain the following fields:

```json
{
  "title": "Watch My Instant Death Ability is So Overpowered, No One in This Other World Stands a Chance Against Me! English Sub/Dub online Free on HiAnime.to",
  "description": "Best site to watch My Instant Death Ability is So Overpowered, No One in This Other World Stands a Chance Against Me! English Sub/Dub online Free and download My Instant Death Ability is So Overpowered, No One in This Other World Stands a Chance Against Me! English Sub/Dub anime.",
  "descriptionHTML": "\n                                <div class=\"text\">\n                                    Awaking to absolute chaos and carnage while on a school trip, Yogiri Takatou discovers that everyone in his class has been transported to another world! He had somehow managed to sleep through the entire ordeal himself, missing out on the Gift &#x2014; powers bestowed upon the others by a mysterious Sage who appeared to transport them. Even worse, he and another classmate were ruthlessly abandoned by their friends, left as bait to distract a nearby dragon. Although not terribly bothered by the thought of dying, he reluctantly decides to protect his lone companion. After all, a lowly Level 1000 monster doesn&apos;t stand a chance against his secret power to invoke Instant Death with a single thought! If he can stay awake long enough to bother using it, that is...\n                                </div>\n                            ",
  "searchKeywords": [
    "My Instant Death Ability is So Overpowered",
    "No One in This Other World Stands a Chance Against Me! English Sub/Dub",
    "free My Instant Death Ability is So Overpowered",
    "No One in This Other World Stands a Chance Against Me! online",
    "watch My Instant Death Ability is So Overpowered"
  ],
  "url": "https://hianimez.to/my-instant-death-ability-is-so-overpowered-no-one-in-this-other-world-stands-a-chance-against-me-18847?ref=search",
  "primaryImageUrl": "https://cdn.noitatnemucod.net/thumbnail/300x400/100/e670bd9fd14f8659450e9be3d87f517b.jpg",
  "parentalGuidance": "PG-13",
  "quality": "HD",
  "sub": "12",
  "type": "TV",
  "length": "23m",
  "japanese": "即死チートが最強すぎて、異世界のやつらがまるで相手にならないんですが。",
  "synonyms": "The other world doesn't stand a chance against the power of instant death, My Instant Death Ability is Overpowered",
  "aired": "Jan 5, 2024 to Mar 22, 2024",
  "premiered": "Winter 2024",
  "duration": "23m",
  "status": "Finished Airing",
  "malScore": "6.43",
  "genres": [
    "https://hianimez.to/genre/action",
    "https://hianimez.to/genre/adventure"
  ],
  "studios": ["https://hianimez.to/producer/okuruto-noboru"],
  "producers": [
    "https://hianimez.to/producer/aqua-aris",
    "https://hianimez.to/producer/mainichi-broadcasting-system",
    "https://hianimez.to/producer/klockworx"
  ]
}
```

👀 p.s.

Got feedback or need an extension?

Lexis Solutions is a [certified Apify Partner](https://apify.com/partners/find). We can help you with custom solutions or data extraction projects.

Contact us over [Email](mailto:scraping@lexis.solutions) or [LinkedIn](https://www.linkedin.com/company/lexis-solutions)

## Support Our Work 💝

If you're happy with our work and scrapers, you're welcome to leave us a company review [here](https://apify.com/partners/find/lexis-solutions/review) and leave a review for the scrapers you're subscribed to. It will take you less than a minute but it will mean a lot to us!

Image Credit: https://hianimez.to/
