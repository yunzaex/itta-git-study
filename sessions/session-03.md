# Session 03 — Git Trouble Shooting

## Goal

Git 사용 중 발생하는 문제를 직접 재현하고 해결합니다.

## Mission

개인 Branch에서 다음 실습을 진행합니다.

1.  최신 `main`을 가져오고 개인 Branch 생성
2.  `starter` 파일을 본인의 `work` 폴더에 복사
3.  Merge Conflict 발생시키고 해결
4.  `restore`로 Staging 및 파일 변경사항 되돌리기
5.  `reset --soft`와 `revert` 실습
6.  `stash`로 작업 내용 보관하고 다시 가져오기
7.  잘못된 Branch의 Commit을 `cherry-pick`으로 옮기기
8.  실습 결과 보고서 작성
9.  Commit → Push → Pull Request 생성

## Branch

`week3/{github-id}`

예시: `week3/yunzaex`

## Files

- 실습 원본: `labs/session-03/starter/`
- 개인 작업 폴더: `labs/session-03/work/{github-id}/`
- 결과 보고서: `labs/session-03/submissions/{github-id}.md`

`starter` 폴더의 6개 파일을 개인 작업 폴더에 복사한 뒤, 먼저 Commit하여 실습 시작 상태를 기록해주세요.
이후 모든 실습은 개인 작업 폴더에서만 진행하며, 공용 `main`과 `starter` 파일은 직접 수정하지 않습니다.
실습 중에는 `git reset --hard`, `git push --force`를 사용하지 마세요.
결과 보고서는 `labs/session-03/report-template.md`를 복사해 `submissions/{github-id}.md`로 작성해주세요.

## Flow

최신 `main` 가져오기  
→ Branch 생성  
→ 파일 복사  
→ 오류 재현 및 해결  
→ 보고서 작성  
→ Commit  
→ Push  
→ Pull Request

## 제출

main을 대상으로 Pull Request를 생성하면 제출 완료입니다.

## Deadline

10/21(수) 23:59