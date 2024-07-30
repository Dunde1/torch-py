# 환경 구성
- `python -m venv <dir_name(venv)>`
- activate : bash prefix 로 (venv) 붙음.
  - `win` : `.\<dir_name>\Script\activate`
  - `mac` : `<dir_name>\bin\activate`
- venv 환경 벗어나기 : `deactivate`
- 패키지 설치 : `pip install -r requirements.txt`
- pyCharm, intelliJ 경우 수동으로 환경구성

## 특이 사항

### window 환경
- [jupiter notebook 파일 실행 오류](https://github.com/zeromq/pyzmq/issues/1981) 이슈
  - `pyzmq` version `25.1.2`로 변경
