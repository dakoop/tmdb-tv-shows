# TMDB TV Show Dataset

This repository contains TV show information gathered using [TMDB](https://www.themoviedb.org/)'s API on Feb. 12, 2026. The provider information comes from TMDB's partnership with [JustWatch](https://www.justwatch.com). This data is being made available for educational purposes.

### Files

Files are provided in both parquet and gzip-compressed json formats.

* **tv-details**: File containing most of the information about the TV shows. Most but not all fields in the [details endpoint](https://developer.themoviedb.org/reference/tv-series-details) are provided. The `id` column uniquely identifies a show.
* **tv-networks**: File containing information about which networks are associated with the TV shows. The `id` column links this information with the show details.
* **tv-proiders**: File containing information about watch providers for the TV shows. The `id` column links this information with the show details. This information comes from TMDB's partnership with [JustWatch](https://www.justwatch.com).
