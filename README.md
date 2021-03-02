# Section 2 project - 영화평점예측 모델
---
# # About Data Sets
### - 데이터 출처
- kaggle : [The movies data set](https://www.kaggle.com/rounakbanik/the-movies-dataset)
    - Metadata on over 45,000 movies. 26 million ratings from over 270,000 users.
- MovieLens: [GroupLens Movie data set](https://grouplens.org/datasets/movielens/)
    - 최신의 rating data와 user의 수가 더 많기 때문에 rating 정보는 movie len 데이터를 사용하였음.
- Web Crawling
    1) tmdb api에서 budset, gross 정보가 누락된 영화들의 imdb page를 crawling 하였음
    2) 주연배우 3명까지 배우들의 Wiki page crawling 해서 각종 수상 & 노미네이트 횟수를 Count 하였음

