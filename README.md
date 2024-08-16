# W9D1
> Day 1 of LINUX

## 명령어
> <b> adduser / useradd </b> : 계정 생성 <br>
> <b> deluser / userdel </b> : 계정 삭제 (--remove-all-files 해당 계정에서 생성한 파일모두 삭제) <br>
> <b> whoami </b> : 현 계정 이름 확인 <br>
> <b> groups </b> : 현 계정의 권한 확인 (users, sudo 등) <br>
> <b> usermod </b> : 현 계정의 설정 변경 (-aG sudo : 권한변경(sudo)로 || -p : 비밀번호 변경 || -l : 이름 변경)<br>
> <b> chown </b> : 파일이나 폴더의 소유주 변경 <br>
> <b> chmod </b> : 파일이나 폴더의 설정 (-R: 권한변경(777:RWXRWXRWX) 변경 <br>
> <b> which </b> : 설치 위치 확인 <br>
> <b> apt-get </b> : 파일 혹은 라이브러리 설치 (remove --purge: 특정 파일 및 라이브러리 삭제 || autoremove: 불필요한 파일 및 라이브러리 삭제 || autoclean || --fix-missing, --fix-broken: 없거나 오류난 파일은 수정하여 설치를 진행) <br>
> <b> rm </b> : 파일 혹은 폴더 삭제 (-rf: 내부의 폴더 및 파일 여부에 상관없이 삭제 ) <br>



## 추가설명
> drwxr-xr-- 2 root   root   4096 temp : <br>
> > drwxr-xr-- : 
> > > d : 파일 유형 (d: 디렉터리 / -: 파일)<br>
> > > rwxr-xr-- : 파일권한<br>
> > root : 소유자<br>
> > root : 그룹<br>
> > 4096 : 용량<br>
> > Aug 16 03:29 : (마지막)수정일시<br>
> > temp : 파일 및 폴더명
<br>

# RWXR-XR-- : 
> RWX : 소유자의 권한
> > R(읽기): 4 || W(쓰기): 2 || X(실행): 1 <br>

> R-X : 소유그룹 권한
> > R(4) + X(1) = 5 <br>

> R-- : 게스트 권한
> > R(4) = 4

# 톰켓 기본 위치
> HOME : /usr/share/tomcat10 <br>
> CONF : /etc/tomcat10 <br>
> LOG : /var/log/tomcat10 <br>
> ROOT : /var/lib/tomcat10/webapps/ROOT <br>
