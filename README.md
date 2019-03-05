# wp-api
wordpress rest api

## CRUD
- GET root-url/wp-json/wp/v2/posts
- POST root-url/wp-json/wp/v2/posts

wp-json/wp/v2/query
  posts: 최근글 10개
  posts?per_page=num: 가져올 글 수 지정
  post?categories=3: 카테고리
  post?categories=3&per_page=1: 카테고리3의 글 1개
