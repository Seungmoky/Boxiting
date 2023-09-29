# Github

## 로컬 디렉토리 Git으로 관리하기

`git init` 을 사용해서 해당 디렉토리에서 Git을 시작한다

## 원격 저장소 GitHub에 커밋 푸쉬(commit, push)

`git remote add origin [https://github.com/Seungmoky/Project_name.git](https://github.com/Seungmoky/Project_name.git)` Github 주소 추가

`git push origin master`

## 원격 저장소 받아오기 클론(clone)

원격 저장소에서 받을 로컬 디렉토리를 만들고

`git clone [https://github.com/Seungmoky/Project_name.git](https://github.com/Seungmoky/Project_name.git) .` 받아온다.

## 다른 Github의 내용 복제해 오기 포크(fork)

해당 github에서 fork를 클릭해서 본인 깃헙에 올리고, `clone` 해주면 된다.

### amend 어멘드

같은 커밋의 작업을 실수로 따로 커밋하게 될때 커밋 옵션 중 **최근 커밋 정정**

### stash 스태시

커밋하기 애매할 정도의 진행을 두고 다른 커밋 작업을 하러갈 때 **stash**로 임시 저장

### reset 초기화

진행을 되돌리고 싶을 때 돌아갈 시점을 우클릭해서 “이 커밋까지 현재 브렌치 초기화” 클릭

<aside>
💡 hard reset의 경우에 원격 저장소는 수정되지 않아서 git옵션에서 강제 푸쉬를 허용해서 강제 푸쉬를 해야한다.

</aside>

### revert 리버트

reset은 커밋이  남지 않지만 revert는 커밋을 되돌렸다는 커밋이 남는다.

### cherry-pick 체리픽

다른 브렌치의 특정 작업만(특정 작업 이후는 빼고) 현재 브렌치에 적용할 때 사용