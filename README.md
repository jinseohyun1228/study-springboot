# study-springboot

백엔드 개발자를 위한 스프링부트 스터디

## 스터디 참여 및 과제 제출 가이드라인

1. 저장소 Fork 하기
   원본 저장소를 자신의 GitHub 계정으로 Fork 하세요.

- 오른쪽 상단의 'Fork' 버튼을 클릭합니다.
- 자신의 계정을 선택하여 Fork를 완료합니다.

2. 자신의 컴퓨터에 클론하기
   Fork한 저장소를 자신의 컴퓨터로 클론합니다.

3. 원본 저장소를 Upstream으로 추가하기
   원본 저장소의 변경사항을 쉽게 가져오기 위해 Upstream을 설정합니다.

`git remote add upstream https://github.com/ApptiveDev/study-springboot.git` 4. 작업할 step 브랜치 생성하기
각 step별로 브랜치를 생성하여 작업합니다.
자신의 브랜치에 study-n 폴더를 만들고 내부에 과제물을 제출한다.

`git checkout -b step-1 origin/step-1`

5. 과제 작업하기
   지정된 폴더 내에서 과제를 수행합니다.

6. 변경사항 커밋하기
   과제가 완료되면 변경사항을 커밋합니다.

```
git add .
git commit -m "예시: step1 ERD 작성 완료"
```

7. 자신의 GitHub 저장소에 푸시하기
   변경사항을 자신의 GitHub 저장소에 푸시합니다.

`git push origin step-n`

8. 원본 저장소에 변경사항을 Pull Request 보내기

GitHub에서 자신의 저장소로 이동합니다.
'New pull request' 버튼을 클릭합니다.
Base repository는 원본 저장소의 해당 step 브랜치로 설정합니다.
내용을 작성하고 스터디를 진행하는 해당 기수의 스터디장에게 "Reviewers" 를 설정해주신 후에

'Create pull request' 버튼을 클릭합니다.

9. 다음 step을 위한 준비
   리뷰 후에 원본 저장소에 변경사항이 병합되면 다음 step을 위해 다음 과제를 확인하고 준비합니다.

이제 스터디를 진행하시면 됩니다!
