FROM python:3.10-slim

# 작업 디렉토리 설정
WORKDIR /app

# client 디렉토리 내 파일 복사
COPY client/requirements.txt ./requirements.txt
COPY client/run_client.py ./run_client.py

# 의존성 설치
RUN pip install --no-cache-dir -r requirements.txt

# 실행 명령 설정
CMD ["python run_client.py"]
