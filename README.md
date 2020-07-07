# subject_ko

## 42 과제 리스트
| 과제명            | 번역상태                                                                   | 번역자   |
|------------------|----------------------------------------------------------------------------|--------|
| libft            | <ul><li>- [ ] 작업중</li><li>- [x] 검토중</li><li>- [ ] 완료</li></ul> |  gipark  |
| get_next_line    | <ul><li>- [ ] 작업중</li><li>- [x] 검토중</li><li>- [ ] 완료</li></ul> |  gipark  |
| ft_printf        | <ul><li>- [ ] 작업중</li><li>- [x] 검토중</li><li>- [ ] 완료</li></ul> |  gipark  |
| netwhat          | <ul><li>- [ ] 작업중</li><li>- [x] 검토중</li><li>- [ ] 완료</li></ul> |  gipark  |
| ft_server        | <ul><li>- [ ] 작업중</li><li>- [x] 검토중</li><li>- [ ] 완료</li></ul> |  gipark  |
| cub3d            | <ul><li>- [ ] 작업중</li><li>- [x] 검토중</li><li>- [ ] 완료</li></ul> |  gipark  |
| miniRT           | <ul><li>- [ ] 작업중</li><li>- [ ] 검토중</li><li>- [ ] 완료</li></ul> |         |
| libasm           | <ul><li>- [x] 작업중</li><li>- [ ] 검토중</li><li>- [ ] 완료</li></ul> |  yopark |
| minishell        | <ul><li>- [x] 작업중</li><li>- [ ] 검토중</li><li>- [ ] 완료</li></ul> |  yechoi |
| ft_services      | <ul><li>- [ ] 작업중</li><li>- [ ] 검토중</li><li>- [ ] 완료</li></ul> |         |
| philosophers     | <ul><li>- [ ] 작업중</li><li>- [ ] 검토중</li><li>- [ ] 완료</li></ul> |         |
| cpp module 00    | <ul><li>- [ ] 작업중</li><li>- [ ] 검토중</li><li>- [ ] 완료</li></ul> |         |
| cpp module 01    | <ul><li>- [ ] 작업중</li><li>- [ ] 검토중</li><li>- [ ] 완료</li></ul> |         |
| cpp module 02    | <ul><li>- [ ] 작업중</li><li>- [ ] 검토중</li><li>- [ ] 완료</li></ul> |         |
| cpp module 03    | <ul><li>- [ ] 작업중</li><li>- [ ] 검토중</li><li>- [ ] 완료</li></ul> |         |
| cpp module 04    | <ul><li>- [ ] 작업중</li><li>- [ ] 검토중</li><li>- [ ] 완료</li></ul> |         |
| cpp module 05    | <ul><li>- [ ] 작업중</li><li>- [ ] 검토중</li><li>- [ ] 완료</li></ul> |         |
| cpp module 06    | <ul><li>- [ ] 작업중</li><li>- [ ] 검토중</li><li>- [ ] 완료</li></ul> |         |
| cpp module 07    | <ul><li>- [ ] 작업중</li><li>- [ ] 검토중</li><li>- [ ] 완료</li></ul> |         |
| cpp module 08    | <ul><li>- [ ] 작업중</li><li>- [ ] 검토중</li><li>- [ ] 완료</li></ul> |         |
| ft_containers    | <ul><li>- [ ] 작업중</li><li>- [X] 검토중</li><li>- [ ] 완료</li></ul> |  wpark  |
| webserv          | <ul><li>- [ ] 작업중</li><li>- [X] 검토중</li><li>- [ ] 완료</li></ul> |  wpark  |
| ft_irc           | <ul><li>- [ ] 작업중</li><li>- [ ] 검토중</li><li>- [ ] 완료</li></ul> |         |
| ft_transcendence | <ul><li>- [X] 작업중</li><li>- [ ] 검토중</li><li>- [ ] 완료</li></ul> |  wpark  |

## 번역할 과제 찜하기
작업중/검토중/완료가 체크되지 않은 과제 중에서 본인이 하고 싶은 과제를 골라주세요.
현재 default 브랜치로 설정된 checklist 브렌치 read.md 를 직접 수정하시면 됩니다.

## 번역을 시작하기
```
git@github.com:42seoul-translation/subject_ko.git
git checkout dev
git branch [작업할 프로젝트명]
git checkout [작업할 프로젝트명]
```
1. 작업을 시작하기전에 dev branch로 이동합니다. `git checkout dev`
2. 본인이 작업할 프로젝트명으로 branch 를 만듭니다. ex) `git branch get_next_line`
3. 만든 branch 로 이동합니다. ex) `git checkout get_next_line`
4. 프로젝트명과 동일한 폴더를 만듭니다.
5. 해당 폴더 안에 번역에 참고한 원문pdf 파일을 같이 추가해주세요.
5. 해당 폴더 안에 본인이 번역할 내용이 담길 파일을 만들어 주세요. 마크다운, 워드프로세서, 한글 등 본인이 편한 방식으로 진행주시면 됩니다.

## 번역이 완료되면
1. push 하고 dev branch 로 병합하기 위해 pull request 를 합니다.
2. 다른 분들의 리뷰를 받고 개선할 것이 있는지 확인합니다.
3. 개선할 것이 확인되면 해당 pull request 를 닫고 수정한 뒤 다시 push합니다.
4. 개선할 것이 없으면 dev branch 에 merge 합니다.
5. <b>2명 이상의 승인</b>을 받아야만 dev branch 에 merge 할 수 있습니다.

## 다른 사람 번역을 첨삭할 때
다른 사람의 번역을 첨삭할 때는 두 가지 방법이 있습니다.
해당 번역의 pull request 에서 리뷰를 남기거나, 다른 사람의 번역 위에 커밋을 쌓을 수 있습니다.

* 멤버의 경우 (review 를 통해 진행)
  1. 다른 번역자가 올린 pull request 에 들어갑니다.
  2. 해당 번역중 고쳐야할 부분이 있으면 해당 부분을 표시하고 댓글을 남깁니다.
  3. 만약 해당 번역이 괜찮다고 생각하면 approval을 눌러주세요. 2명 이상의 승인이 있으면 dev 브랜치에 merge 됩니다.
* 비멤버의 경우 (fork & push & Pull Request 를 통해 진행)
  1. 해당 repo 를 fork 합니다.
  2. 수정을 제안하고 싶은 번역의 브랜치로 이동합니다. (git checkout [브랜치명])
  3. 수정을 완료하고 커밋 후 본인의 repo 로 push
  4. organization 프로젝트 브랜치로 Pull Request(PR) 를 합니다. 이때 같은 브랜치로 PR을 했는지 확인해주세요. 예를들어 본인이 libft브랜치에서 libft 를 수정했다면 PR시 [본인id]/libft -> subject_ko/libft 로 PR을 해야합니다. 
  5. 그 후 해당 프로젝트 번역자가 확인 후 수정안을 합치면 됩니다. 

## 주의사항
1. 번역을 할 때는 원문을 최대한 해치지 않도록 번역해주세요.
2. 본인이 dev 브렌치에서 프로젝트명으로 브렌치를 제대로 만들었는지 확인해주세요.
3. 번역을 하기 전에 반드시 번역자란에 체크하는 것을 잊지 말아주세요.
4. dev 브랜치는 번역작업을 위한 브랜치입니다. 프로젝트 번역이 완료되면 merge 하는 용도입니다.
6. chcklist 브랜치는 현재 default 브랜치로 설정되었으며 번역자 체크를 위한 용도입니다.
7. master 브랜치는 최종 번역이 완료되면 사용합니다.
