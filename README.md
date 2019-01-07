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
[Blog: Link](http://recoveryman.tistory.com/392)
6. git status가 꼬였을 때  
    * git status
    * gcam "commit 내용"
    - **error**: Pulling is not possible because you have unmerged files.
7. git ignore 파일 추가하기  
[Blog: git ignore](http://rapapa.net/?p=85)  
```bash
    git add .
    git commit -m "add ignore file config"
```
 8. Git Branch 만들기
    1. $ git branch (branchname)  : branch 생성
    2. $ git checkout (branchname) : 브랜치로 로그인
    >위 두작업을 동시에 하기    
    >git checkout -b (branchname)  
    3. $ git **add** myfile.txt // git add --all
    4. $ git **commit** -m "add 설명을 추가"
    5. $ git push **origin** (branchname)  
    6. Revisit your forked repository, then there is Compare & pull request Button.
        >back to master
        >git brahcn -v : 현재 위치 확인
        >git checkout master
    7. $ git merge (branchname)
    8. $ git push
    >번외 : 브랜치 지우기  
    9. git branch -d (branchname)
    
    #### Error: The file will have its original line endings in your working directory.
    >그러므로 윈도우 사용자의 경우 이러한 변환이 항상 실행되도록 다음과 같은 명령어를 입력한다. 물론 시스템 전체가 아닌 해당 프로젝트에만 적용하고 싶다면 —global 을 빼주면 된다.
    >git config --global core.autocrlf true
    >리눅스나 맥을 사용하고 있는 경우, 조회할 때 LF를 CRLF를 변환하는 것은 원하지 않을 것이다. 따라서 뒤에 input이라는 명령어를 추가해줌으로써 단방향으로만 변환이 이루어지도록 설정한다.
    >git config --global core.autocrlf true input
    >혹은 이러한 변환 기능을 원하지 않고, 그냥 에러 메시지 끄고 알아서 작업하고 싶은 경우에는 아래 명령어로 경고메시지 기능인 core.safecrlf를 꺼주면 된다.
    >git config --global core.safecrlf false

### 브랜치 확인 명령어
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
>3. git commit -am "Instructoction" [gcam "설명"]
>4. git push (-f) [gp] : force[강제로]
>5. git pull [gl]
>6. git clone [gcl]
>7. git rm -r —cached .
