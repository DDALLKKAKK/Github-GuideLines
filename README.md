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
