# `imdb.csv` — column reference

149,531 rows x 32 columns. Converted from the original
`description.txt` (UTF-16, CRLF); dtypes and non-null counts are read off the file itself.

| Column                      | dtype   | Non-null | Description                                                                                    |
|-----------------------------|---------|----------|------------------------------------------------------------------------------------------------|
| originalTitle               | string  | 149,531  | Original title, in the original language.                                                      |
| rating                      | string  | 149,531  | IMDB title rating class.                                                                       |
| startYear                   | int64   | 149,531  | Represents the release year of a title. In the case of TV Series, it is the series start year. |
| endYear                     | string  | 149,531  | TV Series end year.                                                                            |
| runtimeMinutes              | string  | 149,531  | Primary runtime of the title, in minutes.                                                      |
| awardWins                   | int64   | 149,531  | Number of awards the title won.                                                                |
| numVotes                    | int64   | 149,531  | Number of votes the title has received.                                                        |
| worstRating                 | int64   | 149,531  | Worst title rating.                                                                            |
| bestRating                  | int64   | 149,531  | Best title rating.                                                                             |
| totalImages                 | int64   | 149,531  | Total Number of Images for the title within the IMDb title page.                               |
| totalVideos                 | int64   | 149,531  | Total Number of Videos for the title within the IMDb title page.                               |
| totalCredits                | int64   | 149,531  | Total Number of Credits for the title.                                                         |
| criticReviewsTotal          | int64   | 149,531  | Total Number of Critic Reviews.                                                                |
| titleType                   | string  | 149,531  | The type/format of the title (e.g. movie, short, tvseries, tvepisode, video, etc).             |
| awardNominationsExcludeWins | int64   | 149,531  | Number of award nominations excluding wins.                                                    |
| canHaveEpisodes             | bool    | 149,531  | Whether or not the title can have episodes.                                                    |
| isRatable                   | bool    | 149,531  | Whether or not the title can be rated by users.                                                |
| isAdult                     | int64   | 149,531  | Whether or not the title is for adult. 0: non-adult title; 1: adult title.                     |
| numRegions                  | int64   | 149,531  | The regions number for this version of the title.                                              |
| userReviewsTotal            | int64   | 149,531  | Total Number of Users Reviews.                                                                 |
| ratingCount                 | int64   | 149,531  | The total number of user ratings submitted for the title.                                      |
| countryOfOrigin             | string  | 109,544  | The country where the title was primarily produced.                                            |
| genres                      | string  | 149,531  | The genre(s) associated with the title (e.g., drama, comedy, action).                          |
| castNumber                  | int64   | 149,531  | Total Number of Cast individuals present within the IMDb title page.                           |
| companiesNumber             | int64   | 149,531  | Total Number of companies that worked for the title.                                           |
| averageRating               | float64 | 149,531  | Weighted average of all the individual user ratings.                                           |
| regions                     | string  | 149,531  | The regions for this version of the title.                                                     |
| externalLinks               | int64   | 149,531  | Total Number of External Links the title has within the IMDb page.                             |
| writerCredits               | int64   | 149,531  | Total number of writer credits of the title.                                                   |
| directorsCredits            | int64   | 149,531  | Total number of director credits of the title.                                                 |
| soundMixes                  | string  | 149,531  | Technical specification of the sound mixes available for the title.                            |
| quotesTotal                 | int64   | 149,531  | Total Number of quotes the title has within the IMDb page.                                     |

## Notes

- `rating` holds **interval strings**, not numbers: `(0, 1]` … `(9, 10]`. It is a
  perfect binning of `averageRating` — every row's `averageRating` falls inside its own
  `rating` interval, so the two carry the same information and using both leaks the target.
- `runtimeMinutes` is read as a string because missing values are encoded as `\N`;
  26.88% of rows (40,195) are missing and are model-imputed in
  `notebooks/00_preprocessing_and_outlier_detection.ipynb`.
- `numVotes` and `ratingCount` are identical in 89.65% of rows.
- `worstRating`, `bestRating` and `isRatable` are constant (1, 10 and `True`) and carry no
  signal; `endYear` is `\N` in 96.2% of rows. All four are dropped in the first
  preprocessing cell.
- `countryOfOrigin`, `genres`, `regions` and `soundMixes` hold Python-list literals as strings.
