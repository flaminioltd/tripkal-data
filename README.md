# tripkal-data

Public data for the tripkal app (Israel edition of triphandy).

- `travel-warnings.json`: Israeli National Security Council travel-warning levels (1–4) per destination, with the Hebrew summary. Source: the data.gov.il "travelwarnings" open dataset. Updated daily by an automated job; do not edit by hand.

The app reads `https://raw.githubusercontent.com/flaminioltd/tripkal-data/main/travel-warnings.json`.
