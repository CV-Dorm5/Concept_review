월
대부분  DocVQA로 pre-trained 되어있음. [https://www.kaggle.com/code/tusharcode/training-layoutlm-docvqa/notebook] layoutLM 훈련법
목표 - infographics VQA 훈련, huggingface demo 업로드
2월 19일 - 2월 23일 기업연계 상견례 진행 -> 별도의 상견례 없이 진행
이미지 학습 <-> 언어 학습
언어 학습은 pretrained 된 모델 그대로 들고옴, 이미지만 CE로 학습.

화
최종 프로젝트
1단계 : 도넛, LayoutLM을 구현 해보자.
도넛은 text위주, 우리는 infographic이라 최종적으로 맞지 않다.
PaLI3
코드와 Paper가 모두 존재.
현재 우리가 사용하기에 가장 좋아보인다.
SOTA 일수록 복잡한 모델이고, 훈련이 한번 꼬이면 많이 복잡해질 수 있을 것 같다.
아직 미완성 코드로 보인다.
Gemini - 코드가 없다.
멘토링 시간에 질문

수
현재 코드가 제공되어 있는 sota 모델은 PaLI3 -> ToDo가 아직 남아있다->완성 안된 것...?
LayoutLM, Donut -> 텍스트 기반 multi modal 경험 해볼 것인가, InfographicVQA를 먼저 시작할 것인가
Donut 보다는 Sota로 가자,,?-> Donut은 Document에 집중하고 있음-> 그대로 가져와서 사용하기는 어려움(but 구조 자체는 차용할 수 있을 듯.)
일단 구현해보자
고은성, 안종진 -> LayoutLM
이유민 -> Donut
전진하 -> PaLI
최현영 -> infographicVQA 리뷰

목
최종 프로젝트 멘토링
pixtoinstruction
google에서 나온 infographic VQA에 적용가능한 모델
Gemma
QA가 가능, keras를 사용해야 될 수 있다.
뜯어서 사용하긴 어렵고 사용해보는 정도 가능
영어만 가능
새로운 모델 개발, Document VQA 모델을 적용하는건 어려운 수준
월요일에 기업에 문의 후 멘토님과 논의
업스테이지와 논의 후 요구사항을 듣고 그 방향으로 진행하는게 가장 좋음
