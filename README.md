# ETL Project- Music
### Paige Breyfogle, J.A. Gorman, Andrew Stepanek

## Purpose
Merge several music files and make a comprehensive list of music by artist, genre, and scores based on different criteria

## Requirements
| Python Modules | Usage |
| ------ | ------ |
| requests | make a request to a web page |
| sqlalchemy | orm for databases |
| psycopg2 | access postgresql server |

* Postgresql

## Workflow

###  [CSV FILES](https://github.com/jagorman/music_etl/tree/main/Resources)

### [DATASETS](https://www.kaggle.com/yamaerenay/spotify-dataset-19212020-160k-tracks)

#### *extract* -Paige Breyfogle

1. download csv (manual step)
2. load csv

#### *transform* -Andrew Stepanek

1. isolated appropriate data
2. standardized relevant data information using pandas loop

#### *load* -J.A. Gorman

1. Loaded transformed data into Postgresql
2. Used WITH to check for errors on loading
