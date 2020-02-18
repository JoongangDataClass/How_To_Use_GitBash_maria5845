--------------깃허브 간단 사용법(git bash 명령어)--------------------

1장 {깃허브 마스터 브랜치에 기본 업로드 하는 법} 

1. 업로드하고자 하는 작업 공간을 오른쪽 클릭하여 'Git Bash'를 누른다

2.  콘솔 창이 뜨면 깃초기화 명령어 'git init'을 입력한다 

3. 초기화 이후에 'git status'로 올리고자하는 파일을 확인한다 

4. 깃 배쉬 스테이지에 업로드 하고자 하는 파일을 add한다 
  
    명령어 : git add 파일명 
   
    전체 파일을 업로드 하고자 한다면
    
    명령어 : git add .(점누르시면 됨)

5. 스테이지에 add된 파일을 커밋시킨다. 
    
    명령어 : git commit -m "커밋 설명" 
    
    커밋설명 : 올리는 파일에 대한 간단한 설명 혹은 이름 

6. 커밋을 한 이후 올리고자 하는 저장소를 연결한다. 
    
    명령어 : git remote add origin 저장소 주소 

7. 저장소와 연결시키고자 하는 작업공간이 잘 연결되었는지 확인하다. 
    
    명령어 : git remote -v  

8. 연결이 잘 되어있다면 마스터 브렌치에 푸쉬한다. 
    
    명령어 : git push origin master 
