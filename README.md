# Section 2 project - 영화평점예측 모델
## # About Data Sets
### - 데이터 출처
- kaggle : [The movies data set](https://www.kaggle.com/rounakbanik/the-movies-dataset)
    - Metadata on over 45,000 movies. 26 million ratings from over 270,000 users.
- MovieLens: [GroupLens Movie data set](https://grouplens.org/datasets/movielens/)
    - 최신의 rating data와 user의 수가 더 많기 때문에 rating 정보는 movie len 데이터를 사용하였음.
- Awards by Directors : [220k_awards_by_directors](https://www.kaggle.com/stephanerappeneau/350-000-movies-from-themoviedborg)
    - tmdb api를 기본으로 감독의 수상 & 노미네이트 정보를 담고 있음
- Web Crawling
    1) tmdb api에서 budset, gross 정보가 누락된 영화들의 imdb page를 crawling 하였음
    2) 주연배우 3명까지 배우들의 Wiki page crawling 해서 각종 수상 & 노미네이트 횟수를 Count 하였음

## # Code
- 1_Preprocessing : data cleaning & preprocessing & merge crawoling 결과
- 2_actor_wiki_crawling & 3_imdb_crawling : request, beautifulSoup으로 크롤링
- 4_FeatureEngineer_model : Feature Engineering과 model을 만들고 튜닝 & test
- 5_shap_on_colab : shap 패키지가 로컬에 설치되지 않기 때문에 dpd, shap은 코랩에서 따로 작성하였음
