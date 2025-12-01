```c
#include <stdio.h>

int main(){
  printf("hello\n");
}

```

|제목1|제목2|제목3|
|---|---|---|
|데이터1|데이터2|데이터3|
|데이터1|데이터1|데이터1|
|데이터1|데이터1|데이터1|
|데이터1|데이터1|데이터1|

# 1. 오픈소스 소프트웨어
- 오픈소스 라이선스 종류 : GPL, Aoache License, MIT, BSD, CC, MPL, AGPL
- 오픈소스 형태의 운영체제: 리눅스(Ubuntu, Rhel, CentOS, Fedora)
- 개발 시 활용되는 관리 시스템: Git/GitHub, GitLab
- 
# 2. 리눅스
> 아래의 내용은 **Ubuntu 기준**으로 작성 되었음
> _여러 줄_
> <b><i>여러 줄</i></b>
## 2.1. 명령어 종류
1. 파일 관리: `ls`, `cd`, `mksir`, `rmdir`, `touch`, `vi`, `cat`, `mv`, `rm`, `find`
2. 셸: `chsh`, `echo`, `export`, `alias`, `unalias`, `history`
3. 파일 액세스 관리: `chmod`, `umask`, `chown`
4. 패키지 관리: 
5. 아카이빙/압축: `tar`, `gzip`, `gunzip`, `bzip2`, `bunzip2`
6. 프로세스: `ps`, `pgrep`, `kill`, 
7. 시스템 사용자 관리  
   -사용자: - (1)  
   -그룹: -(1)
8. 파일 시스템 관리: 
9. 네트워크 관리:

# 3. GitHub
## 3.1. GitHub 활용법
### 3.1.1. 로컬 레포지토리에서 작업

```shell
git clone <remote-app>
```

```shell
git add .|<files>
```

```shell
git commit -m "<msg>"
```

```shell
git push <remote> <branch>
```

### 3.1.2. 원격 레포지토리의 변경사항 가져오기

```shell
git clone <remote-app>
```
### 3.1.3. 브랜치 및 로그 확인
