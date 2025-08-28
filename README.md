# 소설 생성기 (Qwen + llama.cpp)

Hugging Face에서 공개된 **Qwen2.5 Instruct GGUF 모델**을  
`llama-cpp-python`을 통해 로컬에서 불러와, 간단한 **자동 소설 이어쓰기**를 실험한 코드입니다.  

---

## ✨ 기능
- 첫 문장을 입력하면 모델이 소설을 이어서 한 문단씩 작성
- `JSON`, `TXT` 파일로 저장하여 기록 유지
- 매번 실행해도 이전 이야기를 불러와 이어서 계속 작성 가능
- 파라미터(`temperature`, `top_p`, `repeat_penalty`)를 조절해 글 스타일 변화 관찰
- 글을 바꾸고 싶다면 저장된 파일을 삭제하거나 이동
---

## ⚙️ 환경
- Python 3.12 (Anaconda 가상환경 권장)
- 주요 라이브러리
  - [llama-cpp-python](https://github.com/abetlen/llama-cpp-python)
  - [huggingface_hub](https://github.com/huggingface/huggingface_hub)

---

## 📥 만들어진 txt파일로 입력과 출력 확인
```
![화면 캡처 2025-08-28 162904](https://github.com/user-attachments/assets/f9d97c28-77d2-4911-bd3d-038598723d86)



