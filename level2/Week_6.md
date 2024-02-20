2. *안건 list*
-96점 나오는 실험 (은성)
	- data set, augmentation(horizontal)해서 2배로 늘려서 실험
	- resize가 중요한듯 514 -> 1024
		- 작은 객체를 탐지하지 못하기 때문에 늘려봄
	- 기본 모델 (res50)
	- resize하면 터졌기 때문에 batch size를 변경해줌
	- step이 조금 이상하다는 의견?
  - Unet으로 실험중
	output 채널이 5개, 평균을 내서 역전파
- Super Resolution을 해보자.
- pkl파일 생성, res50, unet에서 구동하는 코드 업로드 완료
	- 실행시간이 많이 단축 적극 활용할 것
	- make_pkl
	- pkl파일 생성은 CPU만 사용해서 실험과 동시에 수행이 가능하다.
	
- 19번 실험
	- ReduceLR… 스케쥴러
	
- mmSegmentation을 적용해보는 방안
	
3. *마무리 및 다음 단계*
- pkl파일 활용 도입하기
- 19번 실험내용(기법들, 옵티마이저, 스케쥴러…) 활용하기
- mmSegmentation
- super Resolution 사용해보기
