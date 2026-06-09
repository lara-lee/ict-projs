# ict-projs

Archive of beginner projects from ICT 인재개발원 (2023).

## Projects

- [01addressBookProj](01addressBookProj/) — 주소록 프로젝트
- [02memberBbsProj](02memberBbsProj/) — 회원/게시판 프로젝트
- [03tripMaven_Team](03tripMaven_Team/) — Trip Maven (팀 프로젝트)
- [04textify](04textify/) — Textify

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
