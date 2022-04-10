# Commit Rules
### 커밋 메시지의 구조
기본적으로 커밋 메시지는 제목/본문/꼬리말로 구성됩니다.
여기서 제목은 필수, 본문과 꼬리말은 선택사항입니다. 

	<type> : <subject>			-제목
	<BLANK LINE>				
	<body>						-본문
	<BLANK LINE>
	<footer>					-꼬리말

##### &lt;type&gt; (필수)
이 &lt;type&gt;가 의아하신 분들이 있을 것 같아서 잠시 설명을 드리자면, 간단하게 말해서 커밋의 내용을 설명합니다. 아래 중 하나여야 하며, 이는 필수입니다. 

	# feat		: 새로운 기능에 대한 커밋
	# fix		: 버그 해결에 대한 커밋
	# build		: 빌드 관련 파일 수정에 대한 커밋
	# docs		: 문서 생성, 변경에 대한 커밋
	# chore		: 그 외 자잘한 수정에 대한 커밋
	# post		: 신규 포스트 작성 및 수정에 대한 커밋
	# style		: formatting, 코드 스타일에 대한 커밋 (코드에 변경은 없음)
	# refactor	: 코드 리팩토링에 대한 커밋
	# test		: 테스트 - 테스트 코드 추가, 수정, 삭제에 대한 커밋


##### 제목 (필수)
제목을 작성할 때 지켜야 할 규칙들이 있습니다.
- 제목은 50자를 넘기지 않을 것(영문 기준)
- 제목 첫 글자는 반드시 대문자로
- 제목 끝에 `.` 금지
- 제목은 `명령조` 로 지을 것 (과거시제 금지)
- 제목과 본문은 한 줄 띄워 분리
- 제목 또는 본문에 이슈 번호가 있다면 붙일 것

##### 본문 (선택)
본문은 선택사항이기에 모든 커밋에 본문을 작성할 필요는 없습니다.
- 한 줄에 72자를 넘기지 말 것
- `HOW(어떻게)` 보다 `WHAT(무엇을)`, `WHY(왜)`에 초점을 두고 작성할 것
- 설명 또는 커밋의 이유를 담고 있음


### Reference

- [Chris Beams : How to Write a Git Commit Message](https://cbea.ms/git-commit/)
- [김은호 : 좋은 git 커밋 메시지를 작성하기 위한 7가지 약속](https://meetup.toast.com/posts/106)
- [GitHub : Linking a pull request to an issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue)
- [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)
