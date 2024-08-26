# PI-Server
땅울림 24년도 여름 스터디 서버 파트원

## Project

> 땅울림 스터디 8주차
> 
> 
> **프로젝트 기간 : 2024.08.26~2024.08.26**
> 

---

<br>

## TEAM

| <img width="200" src="https://github.com/user-attachments/assets/26bf757f-d311-4b8a-9a3e-6defbf44950c"> | <img width="200" src="https://github.com/user-attachments/assets/c6dd9fe9-3b7a-44a7-8f33-e54ab5619dd7">|
| --- | --- |
| 인수빈 | 박지현 |
| [InSooBeen](https://github.com/InSooBeen) | [jlhyunii](https://github.com/jlhyunii) |

<br>

## Task

| 기능 | 담당자 |
| --- | --- |
| Issue 4 | 인수빈 |
| Issue 1, 3 | 박지현 |
| ⚙️ 프로젝트 셋팅 | 박지현 |
| ⚙️ 깃헙 세팅 | 인수빈 |

<br>



<br>

## Git Flow & Convention

```
1. Issue를 생성
2. feature Branch를 생성 (ex.feat/#이슈번호-상세기능설명) (feat/#2-get-user-api)
3. Add - Commit - Pull - Push - Pull Request
4. 작성자 이외의 다른 팀원이 Code Review
5. Code Review가 완료되면 main Branch로 merge
```

- 작은 기능 구현 했을 때마다 자주 커밋
- 작업 전, 반드시 **`develop 브랜치`를 pull 받기**
- **`main`, `develop` 에 직접적인 commit, push는 ✖️**
- 코드 포맷팅 : `ctrl + alt + l`(window), `command + option + l`(mac)
- 미사용 Import문 삭제 : `ctrl + alt + o`

<br>

## **Branch Convention**

[data:image/gif;base64,R0lGODlhAQABAIAAAP///wAAACH5BAEAAAAALAAAAAABAAEAAAICRAEAOw==](data:image/gif;base64,R0lGODlhAQABAIAAAP///wAAACH5BAEAAAAALAAAAAABAAEAAAICRAEAOw==)

[feat] : 기능 추가

[fix] : 에러 수정, 버그 수정

[refactor] : 코드 리펙토링 (기능 변경 없이 코드만 수정할 때)

[modify] : 코드 수정 (기능의 변화가 있을 때)

[chore] : gradle 세팅, 위의 것 이외에 거의 모든 것

[docs] : README, 문서

[deploy] : 배포 관련

## **Commit Convention**

feat - #이슈번호 상세작업내용설명
