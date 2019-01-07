# playGround
Lots of things to play

## git tutorial for kr
https://backlog.com/git-tutorial/kr/stepup/stepup1_4.html

git _hub_ **Hi there**

## 깃 간단 설명서
1. Git 에서 **password** 저장하는 방법  
git config --global credential.helper cache 
2. Git 에서 **유저네임** 설정하는 방법
>
>>git config --global user.name "이름"  
>>git config --global user.email "이메일"
>
>프로젝트 하나에서만 변경하고 싶으시면
>
>>git config --local user.name "이름"  
>>git config --local user.email "이메일"
>

3. Git 에서 **이미지** 넣기  
    <img src="http://octodex.github.com/images/octdrey-catburn.jpg" width="300">
4. Git 에서 **Hypertext** 넣기  
    [A representation of Octdrey Catburn](http://octodex.github.com/)
5. 계정이 바꼈을 때  
[블로그 Link](http://recoveryman.tistory.com/392)
6. git status가 꼬였을 때  
    * git status
    * gcam "commit 내용"
    - **error**: Pulling is not possible because you have unmerged files.
7. git ignore 파일 추가하기  
[git ignore](http://rapapa.net/?p=85)  
```bash
    git add .
    git commit -m "add ignore file config"
```
 8. Git Branch 만들기
    1. git branch <branchname>
    2. git checkout <branchname>
    *  위 두작업을 동시에 하기  
    git checkout -b <branch>  
    3. $ git add myfile.txt
    4. $ git commit -m "add 설명을 추가"
    5. git push origin <branchname>
        Revisit your forked repository, then there is Compare & pull request Button.
        >back to master
    6. git merge <branchname>


> $ git branch
> issue1
> * master




***
### 라인 넣기

* list 1
    - 리스트 2
    - 리스트 3
* list 2
    * 리스트 1
    * 리스트 2

> 코드블럭 생성하기
```python
>    a = 50
>    b = 100
>    abs(1-b)
>    print("hi")
```

### 깃 **기본 커밋** 사용법
>1. repo 생성
>2. git clone **https~~~**
>3. 작업
>4. add
>5. commit
>6. push

### 깃 **기본 커밋** 사용법2
>1. vi README.md
>2. git add --all [gaa]
>3. git commit -am "Instructoction" [gcam]
>4. git push (-f) [gp]
>5. git pull [gl]
>6. git clone [gcl]
>7. git rm -r —cached .
