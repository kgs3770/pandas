pip -m venv venv : 가상환경 생성
source venv/Scripts/activate : 가상환경 활성화
pip <module_name> : 모듈설치
pip freeze >> requirement.txt : 현재 설치된 모듈 리스트 저장
pip install -r requirements.txt : requirements.txt 기준으로 모듈 설치