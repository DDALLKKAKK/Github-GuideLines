# Github-GuideLines
## 새로운 프로젝트 폴더를 Github와 연결해봅시다.
<pre><code>mkdir 내프로젝트이름  
cd 내프로젝트이름  
echo "# 내프로젝트이름" >> README.md  
git init  
git add README.md  
git commit -m "작성하고 싶은 커밋 메세지"  
git branch -M main  
git remote add origin https://github.com/내githubusername/내프로젝트이름.git  
git push -u origin main</code></pre>
---
## 기존 프로젝트 폴더를 Github와 연결해봅시다.
<pre><code>cd 내프로젝트이름  
git init  
git add .  
git commit -m "작성하고 싶은 커밋 메세지"  
git branch -M main  
git remote add origin https://github.com/내githubusername/내프로젝트이름.git  
git push -u origin main</code></pre>
---
## Commit이라는 걸 해봅시다.
<pre><code>git add .  
git commit -m "작성하고 싶은 커밋 메세지"</code></pre>
---
## Push라는 걸 해봅시다.
<pre><code>git push</code></pre>
---
## Pull Request라는 걸 해봅시다.
1. PR을 보내려하는 repo를 ```fork```합니다.
2. ```git clone https://github.com/본인githubusername/레포이름.git``` 입력
3. ```clone```된 폴더에 들어간 후, 코드를 수정합니다.
4. 아래와 같이 입력하세요.
<pre><code>git switch -c 새로만들branch이름  
git add .  
git commit -m "작성하고 싶은 커밋 메세지"  
git push origin 아까만든branch이름
</code></pre>
6. Github에서 해당 레포에 접속 후, ```Compare & Pull Request``` 버튼을 클릭합니다.
7. 해당 페이지에서 점검사항 모두 확인 후, ```Create Pull Request``` 버튼을 클릭합니다.  
***
## Merge라는 걸 해봅시다.
1. PR 기록이 있어야 합니다.
2. Github에서 해당 레포의 ```Pull Requests``` 탭에 접속합니다.
3. 변동 사항 모두 확인 후, ```Merge``` 여부를 선택합니다.
