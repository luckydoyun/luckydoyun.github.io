# 이력서

- lyout은 content 안에서 중복으로 사용 불가능

1. 이력을 2개 이상 기입 : [- title] 사용하여 추가

# 로컬 서버 구동

1. Ruby and the gems for Jekyll installed locally. [here](https://jekyllrb.com/docs/installation/)
2. ```cd [your-repository-name]```
3. ```bundle install```
4. bundle exec jekyll serve
  4-1. 에러 발생 시 :  ```GitHub Metadata: No GitHub API authentication could be found. Some fields may be missing or have incorrect data.```
       
       해결방법 : ```bundle add webrick``` 
