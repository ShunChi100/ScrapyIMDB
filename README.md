# ScrapyIMDB


Crawl IMDB user's review


All runnable scripts are in: [scripts link](scrapyIMDB/script)


1. [crawl_movie_list.sh](scrapyIMDB/script/crawl_movie_list.sh) : execute module [movies_spider](scrapyIMDB/spiders/movies_spider.py), crawl a list of movie(& its information) from the link      `http://www.imdb.com/search/title?year={year},{year}&title_type=feature&sort=num_votes,desc`
2. [crawl_reviews_list.py](scrapyIMDB/script/crawl_reviews_list.py) : read crawled data (from 1.) that is stored in `scrapyIMDB/data/movie_list.csv` and execute crawl_reviews.sh
