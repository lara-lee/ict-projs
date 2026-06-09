# ict-projs

Archive of beginner projects from ICT 인재개발원 (2023).

## Projects

| # | Project | Period | Description |
| --- | --- | --- | --- |
| 1 | [001addressBookProj](001addressBookProj/) | 2024-10-21 ~ 2024-11-25 | 주소록 프로젝트 |
| 2 | [002memberBbsProj](002memberBbsProj/) | 2024-10-21 ~ 2024-11-25 | 회원/게시판 프로젝트 |
| 3 | [003tripMaven_Team](003tripMaven_Team/) | 2024-10-29 ~ 2024-11-25 | Trip Maven (팀 프로젝트) |
| 4 | [004textify](004textify/) | 2024-10-23 ~ 2025-12-08 | Textify |

> 기간은 각 레포의 첫/마지막 커밋 날짜 기준.

## Clone with submodules

```bash
git clone --recurse-submodules https://github.com/lara-lee/ict-projs.git
```

이미 clone 했다면:

```bash
git submodule update --init --recursive
```

## Update all submodules to latest

```bash
git submodule foreach 'git checkout master && git pull'
```

## Note (Windows long path)

이 레포는 long path를 사용하는 파일이 포함돼 있어요. Windows에서 clone 전에 다음 명령을 실행하세요:

```bash
git config --global core.longpaths true
```
