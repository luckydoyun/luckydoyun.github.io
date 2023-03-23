# 이력서

# 로컬 서버 구동

1. Ruby and the gems for Jekyll installed locally. [here](https://jekyllrb.com/docs/installation/)
2. ```cd [your-repository-name]```
3. ```bundle install```
4. bundle exec jekyll serve
  4-1. 에러 발생 시 :  ```GitHub Metadata: No GitHub API authentication could be found. Some fields may be missing or have incorrect data.``
  
       해결방법 : bundle add webrick
      
5. Open your browser to ```http://localhost:4000```

Note: You will need to re-run ```bundle exec jekyll serve``` to see changes made in ```_config.yml```.
    
