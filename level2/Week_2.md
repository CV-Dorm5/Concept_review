- 잘한 점 : mmdetection의 process 완벽이해, 깃 컨벤션에 익숙해짐, 깃과 wandb로 협업과 자료 공유에 익숙해짐

- 못한 점 : 건강관리와 수면 관리, EDA자료를 모델 훈련 시 적절히 녹이지 못한 점
    
- 도전할 것 : 적절한 augmentation을 찾아내기, 앙상블 조합찾기

- 키워드 : 여러 실험 데이터 축적!

- 이번주 내가 했던 행동, 작업, 계획, 일정, 소통, 활동에 대한 회고

안종진 : mmdetection이나 detectron2같은 라이브러리를 운용하는데 어려움을 느꼈습니다. 기초적인 튜토리얼부터 따라가야 두 라이브러리를 제대로 활용할 수 있을 것 같았습니다. NoisyAnchor라는 논문을보고 이번 프로젝트에 적용해보려고 시도하였습니다.

최현영 : mmdetection을 알아봤고 objdetection의 task cycle을 이해해서 좋았따

고은성 : YOLO를 기준으로 실험을 한주간 계속했습니다. 남은 한주는 점수를 향상시킬 수 있는 augmentation과 데이터처리, 앙상블을 적용시키고 복습하는 한주를 가지겠습니다.

이유민 : mmdetection을 다 이해한 것 같다 생각했는데, 데이터셋을 잘 이해 못 해서 정확도가 낮게나온 다는 점이 되려 새로웠다. 언제나 기교를 갈고닦는 데 시간을 쓰기보다 기초부터 밟아나가야함을 느낀다


## 월

---

- 종진 : 강의 듣고, 특강에서 pickle부분 들어봄 
- 현영 : 디텍트론 이용해서 학습하고 있고 이전에 mAP가 0으로만 나왔는데 이제 0.0014로 나왔음 성능 향상 시킬 여지가 많음
- 태민 : valid set으로 overfitting 잡아내고 싶어요 어떻게 해요?, 그냥 split만하면 안되겠지요~?
- 유민 : yolo inference EDA해봄, Yolo5,7,8 다 학습해서 infer하는 방법 연구중
- 은성 : YoLo로 infer해보는중 mAP가 0이라서 좀 의아함 이름이 다른 문제가있어서 해결 해볼예정
- 진하 : 백그라운드 실행 관련으로 찾아보는중 screen도 좋나? config에서 이것저것 수정하는중

- 피어세션 내용 공유
    우리 프로젝트 3에서의 예상되는 어려움
    1. 형태가 자연스럽게 무너지는 경우 어떻게 할것인가
        - 움직일 수 있는 후보들을 미리 지정해놓는다 (ex, 눈썹, 볼, 입술등 )
    2. static한 이미지 먼저 -> dynamic한 이미지 생성으로 전화
    3. 일단 모델 찾아보고 돌려보자 (toy로 찾아보자구~)

### 화

---

- 종진 : git말썽 리셋할거임
- 현영 : 이력서작성, detectron2 official tutorial보고 다시할거야
- 태민 : 서버 정리중 mmdetectron 최신버전을 쓰고 싶어
- 유민 : cascade로 detection해봤음 근데 0.5는 못넘는중, loss 바꿔서 해보는중
- 은성 : yolov8도전
- 진하 : detection task에 대한 이해를 위해 노력중 강의 열심히 들을게요!

- 피어세션 내용 공유
    멘토링 


### 수

---

- 종진 : 강의 다 듣고 실전 들어가자!!
- 현영 : mmdetectron으로 회귀
- 태민 : efficientDet공부하는 중
- 유민 : cascade로 detection해봤음 근데 0.5는 못넘는중, loss 바꿔서 해보는중
- 은성 : ap가 진짜 좋은 metric인가에 대한 질문
- 진하 : detection task에 대한 이해를 위해 노력중 강의 열심히 들을게요!

- 피어세션 내용 공유

### 목

---

- 종진 : 공결
- 현영 : mmdetection 공부
- 태민 : efficientDet공부하는 중
- 유민 : cascade로 detection해봤음 근데 0.5는 못넘는중, loss 바꿔서 해보는중
- 은성 : YOLOV8 실험 V7과 비교
- 진하 : detection task에 대한 이해를 위해 노력중 강의 열심히 들을게요!

- 피어세션 내용 공유

### 금

---

- 종진 : NoisyAnchor 적용 시도, detectron2 구조 이해
- 현영 : mmdetection 공부
- 태민 : efficientDet공부하는 중
- 유민 : cascade로 detection해봤음 근데 0.5는 못넘는중, loss 바꿔서 해보는중
- 은성 : 증강 목록 체크 및 파라미터 조정
- 진하 : detection task에 대한 이해를 위해 노력중 강의 열심히 들을게요!

- 피어세션 내용 공유
