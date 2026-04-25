## Dataset

This project uses the publicly available Goodreads dataset.

Note: All listed files are required for the pipeline to run successfully.

Download from:
https://cseweb.ucsd.edu/~jmcauley/datasets/goodreads.html

Required files:

* `goodreads_books_*.json.gz`
* `goodreads_interactions_*.json.gz`
* `goodreads_book_genres_initial.json`
* `goodreads_book_authors.json`
* `goodreads_book_series.json`
* `goodreads_book_works.json`

An alternative automated download method is available here:
https://github.com/MengtingWan/goodreads/blob/master/download.ipynb

After downloading, place all files inside:

```
data/raw/
```

Note: The dataset is not included in this repository due to its large size,. Users are expected to download it from the original source.
