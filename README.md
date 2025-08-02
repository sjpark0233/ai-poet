# pip 설치 세팅
```bash
pip install -r requirements.txt
```

---

# streamlit 실행방법
### Path 환경변수 설정 필요
```
C:\Users\sjpar\AppData\Roaming\Python\Python313\Scripts
```

### 실행
```bash
streamlit run main.py
```

### 웹 접속
```
localhost:8501
```

---

# 배포
### streamlit cloud 사이트 접속
```
https://streamlit.io/cloud
```

### create app 통해 배포
```
https://ai-poet-sdkn9eejdey9cqmwy9weni.streamlit.app/
```

---
### LLaMA 2 경량화 버전
### 다운로드 : llama-2-7b-chat.ggmlv3.q2_K.bin
```
https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML
```

### pip 설치
```bash
pip install ctransformers
```

### 실행
```
streamlit run main_llama.py
```