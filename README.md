# ⭐️git-practice⭐️
Git과 GitHub 공부하기 

![GitHub last commit](https://img.shields.io/github/last-commit/AshtonSW/git-practice)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/AshtonSW/git-practice)

⌨️ Git과 GitHub를 공부하기 위한 공간입니다.

🏃‍♀️ 프로젝트의 버전 관리 및 협업시 사용할 Git에 대해 공부하고자 만들었습니다. 

🏃‍♀️ 추후에 다시 내용을 확인할 수 있도록 각 내용들을 블로그에 기록했습니다.

# Section(0x01-)

### 🌱 Section 0x01. Git 시작하기
| Section | Contents | Keywords |
| :--: | :--: | :--: |
| 1-1 | [Git을 배워야 하는 이유](https://ashtonsw.tistory.com/13) | |
| 1-2 | [CLI vs GUI](https://ashtonsw.tistory.com/13) | |
| 1-3 | [Git 최초설정 및 관리 시작하기](https://ashtonsw.tistory.com/15) | 이름과 주소 설정, init |
| 1-4 | [.gitignore 사용 방법](https://ashtonsw.tistory.com/16) | |


### 🌱 Section 0x02. Git 시간 여행
| Section | Contents | Keywords |
| :--: | :--: | :--: |
| 2-1 | [프로젝트 변경사항을 버전에 담기](https://ashtonsw.tistory.com/17) | git status, add, commit(-m, -am), log, diff |
| 2-2 | [버전 되돌리기](https://ashtonsw.tistory.com/18) | reset --hard, revert |

🔍 git revert --no-commit (되돌릴  커밋 해시) -> 커밋하지 않고 revert하기

### 🌱 Section 0x03. 차원 넘나들기
| Section | Contents | Keywords |
| :--: | :--: | :--: |
| 3-1 | [여러 branch 만들기](https://ashtonsw.tistory.com/19) | branch, switch, branch rename |
| 3-2 | [branch 합치기](https://ashtonsw.tistory.com/20) | merge, rebase |
| 3-3 | [branch 충돌 문제 해결하기](https://ashtonsw.tistory.com/21) | |

🔍 git config --global init.defaultBranch main -> 기본 브랜치명을 main

🔍 git log --all --decorate --oneline --graph -> CLI에서도 이 명령어를 통해서 트리 확인 가능


### Section 0x04. GitHub 사용하기
| Section | Contents | Keywords |
| :--: | :--: | :--: |
| 4-1 | [GitHub란 무엇인가?](https://ashtonsw.tistory.com/22) | token |
| 4-2 | [GitHub 원격저장소 사용](https://ashtonsw.tistory.com/23) | git remote, push, clone |



### Section 0x05. Git을 보다 깊게 이해하기
| Section | Contents | Keywords |
| :--: | :--: | :--: |
| 5-1 | [Git의 원리(3가지 공간)](https://ashtonsw.tistory.com/22) | Working directory, Staging area, Repository 개념 |
| 5-2 | [Git 파일의 삭제와 이동](https://ashtonsw.tistory.com/23) | git rm, mv, restore --staged |
