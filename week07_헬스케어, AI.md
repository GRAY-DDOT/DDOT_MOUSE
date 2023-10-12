# 회사 소개
MOA 데이터 : 
SAIZYE : 반려견 산책 IOT, 사진, 백내장
메디에이지: 생체 나이

## 모아 데이터 기술

- 데이터 센터
- 스마트 공장
- 헬스케어
- 펫라이프

- 이상탐지/예측 서비스
	1.  MST-VAE
		1. 시계열 데이터
		2.  VAE
		3.  CNN(MST
		4. 
	2.  TranSentLo
		1. log data 이상 탐지
		2. sentiment analysis
		3. Transformer 구조 적용
		4. log data 긍/부정 감지


- 노화지수(인공신경망 기반 회귀분석)
- Multi-nDeep
	- 인공신경망 기반 생존분석 모델
	- 세브란스 바이오뱅크 데이터
	- etc

# AI
## AI 발전사
1. rule based programing
	1. (in=>hand designed=>out)
2. hand designed feature based ML
	1. (in=>hand designed features => mapping from features=>out)
3. deep learning
	1. (in=> deep&wide(features=>mapping from features) => out)
4. pre-trained & fine-tuning
	1. in => pre-trained model => fine-tuned model=>out
5. Large Model & zero/few shot
	1. in => large model => zero/few shot =>out


# Data
1. EDA(탐색적 data 분석)
	1. raw의 ㅋcolumn, row 분석
	2. 결측치, 데이터 필터링
	3. 시각화
2. 데이터 간 관계
	1. 단변량/다변량
	2. correlation 분석
	3. Outlier 처리
	4. feature engineering
3. Synthetic Data(합성데이터)
	1. 의미 : 인위적으로 제조되는 정보로 알고리즘적으로 생성되거나 컴퓨터 시뮬레이션에 의해 생성된 데이터
	2. 훈련데이터 증각으로 모델의 일반화(Bias)와 정확도 개선
	3. 개개인의 기밀성 유지함녀서 자유롭게 활용가능
	4. 예시
		1. tabular synthetic data(사용자 행동, 재무로그 등 모방)
		2. synthetic img ans video
		3. synthetic text
		4. 오디오 합성(AudioLDM)
		5. ko 알파카
4. Manifold learnig
	1. 고차원 데이터를 해석하기위해 저차원 공간으로 변환
	2. t-SNE
	3. Glo Ve 단어 임베딩
5. 

# LLMs
1. prompt Enginnering
	1. 짧고 간결하고 확실하게, 아웃풋도 확실하게
	2. 길어지고 복잡하면 구역지정
	3. 예시(zero-shot, one-shot, few-shot)
	4. 목표 순서별로 정리
	5. 수정, 테스트: playground
	6. 팁
		1. 중요한건 마지막에 
	7. 유용한 것들
		1. playground
		2. chatGPT API
		3. Chrome adds
			1. chatGPT for google
			2. 프롬포트 지니: chat gpt자동 번역기
			3. ArXiveGPT: arXive 요약
2. LangChain & AutoGPT
	1. LLM 개발을 쉽게하기위한 프레임워크
	2. 
3. Naver cue