#### venv 환경 설정
---

- requirements.txt 만들기

```powershell
pip freeze > requirements.txt
```

---

- 새 환경 세팅
``` powershell    
# python -m venv [venv 폴더명] 이 프로젝트에서는 폴더명 .venv로 설정
python -m venv .venv

#이후 .venv 폴더 생성 후 아래 디렉토리 입력해서 실행
.\.venv\Scripts\Activate.ps1

python -m venv .venv
.\.venv\Scripts\activate
python -m pip install -r requirements.txt

#아래 입력하여 실행
python .\app.py
```