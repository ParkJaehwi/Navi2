venv 설치 및 실행(가상환경 설정)

python -m venv venv
.\venv\Scripts\Activate.ps1

에러시 
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process
.\venv\Scripts\Activate.ps1

venv\Scripts\activate
pip install Flask
pip install flask-cors
python server.py

--------------------------------------------------------------------

cd ../navi-client
npm i
npm start