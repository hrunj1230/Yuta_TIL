#파이썬 기초 및 응용

###
파이썬에서 조건문과 반복문을 활용하는 실용적인 예제와 함께 동작 방식을 설명하시오. 
[https://colab.research.google.com/drive/1ew79QjB38YytXMU2UXiEiZ0EXLxSsNRW?usp=sharing](https://colab.research.google.com/drive/1ew79QjB38YytXMU2UXiEiZ0EXLxSsNRW?usp=sharing)


 ###
 Fetch API를 사용해 서버에 모델 추론 요청을 보낼 때, 브라우저 CORS 정책이 어떤 제약을 주는지 설명하고, 이를 해결하기 위한 서버/클라이언트 측 전략을 서술하시오.

fetch api를 사용해 서버에 모델 추론 요청을 보낼 때 fetchapi의 브라우저 프론트 origin(출처)와 모델의 origin(출처)가 다르기 때문에 , 브라우저 cors정책이 적용이 되고 preflight요청 (사전요청)을 강제하고,응답 데이터를 차단해버린다. 그리고 스트리밍을 차단하게 된다.
그러면 서버/클라이언트는 이를 해결하려면 모델에 cors허용 설정을 해주는 방법이 있는데
OLLAMA_ORIGINS=* ollama serve 
OLLAMA_ORIGINS=https://~~~.com ollama serve
이런 방식으로 특정 origin 만 허용해줄수 있습니다.
하지만 이 방식은 내부테스트 단계에서는 괜찮지만 실서비스 단계에서는 보안적으로 모델에 제어나 보안을 추가하기 힘들기 때문에 중간에 프록시서버를 경유하는 방법을 선택할 수 있습니다.
브라우저 -> 모델에서
브라우저 -> 프록시 서버 -> 모델 방식으로 가게 되고
이 방식에서 프록시 서버를 fastapi를 사용하게 된다면 CORSMiddleware 를 사용해서 미들웨어가 들어오는 요청을 가로채 적절한 cors헤어와 함께 정보 제공 목적으로 200 or 400응답을 반환해준다.

출처
https://fastapi.tiangolo.com/ko/tutorial/cors/#use-corsmiddleware
중간에 
 OLLAMA_ORIGINS=* ollama serve
 
 브라우저 → 내 백엔드 서버(같은 origin) → Ollama









