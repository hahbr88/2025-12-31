#### venv 환경 설정
---

- requirements.txt 만들기

```powershell
pip freeze > requirements.txt
```

---

- 새 환경 세팅
``` powershell    
# 가상환경 설정

# WINDOWS
python -m venv .venv
# MAC
python3 -m venv .venv

#이후 .venv 폴더 생성 후 아래 디렉토리 입력해서 실행

# WINDOWS
.\.venv\Scripts\Activate.ps1
# MAC
source .venv/bin/activate


python -m venv .venv
.\.venv\Scripts\activate
python -m pip install -r requirements.txt

#아래 입력하여 실행
python .\app.py
```

---

### bbc-football-gossip-translator (v1.0)

오늘 BBC 축구 가십 기사를 크롤링한 후 한국어로 번역하고 설정해둔 슬랙 채널로 메세지를 보내는 앱 