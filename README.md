# 📚 Machine Learning Study Repository

머신러닝 학습을 위한 레포지토리입니다.

## 📂 폴더 구조
```
machine_learning_repo/
├── models/            # 머신러닝 모델 구현
│   └── 01_LinearRegression.ipynb
├── notes/             # 학습 노트 및 정리
│   ├── 01_tensor.ipynb
│   ├── 02_operations.ipynb
│   ├── 03_manipulation.ipynb
│   └── 04_autograd.ipynb
├── quiz/              # 연습 문제 및 퀴즈
│   ├── quiz1.ipynb
│   ├── quiz2.ipynb
│   ├── quiz3.ipynb
│   └── quiz4.ipynb
├── .gitignore
├── CLAUDE.md          # Claude Code 설정 파일
└── README.md          # 프로젝트 개요
```

## 📂 학습 내용

### 🔥 PyTorch
#### 텐서 기초
- **Tensor 기초**: 텐서 초기화, 속성, 데이터 타입 변환
- **다차원 텐서**: 0D~5D 텐서의 구조와 활용 사례

<br/>

#### 텐서 연산
- **산술 연산**: 기본 사칙연산 및 바꿔치기 연산
- **각종 연산**: 수학 연산, 통계 연산, 내적 및 행렬 곱셈

<br/>

#### 텐서 조작
- **인덱싱/슬라이싱**: NumPy 스타일의 인덱싱 및 값 변경
- **모양 변경**: view를 통한 텐서 크기 및 모양 변경
- **차원 조작**: squeeze/unsqueeze를 통한 차원 축소 및 증가
- **텐서 결합/분할**: stack/cat을 통한 결합, chunk/split을 통한 분할

<br/>

#### 자동미분
- **Autograd 기초**: requires_grad를 통한 자동미분 설정
- **역전파**: backward()를 통한 미분값 계산 및 grad 속성 활용
- **미분 제어**: torch.no_grad()를 통한 연산 그래프 차단

<br/>

### 🤖 머신러닝 모델
#### 선형 회귀
- **단일 선형회귀**: nn.Linear를 사용한 기본 선형회귀 구현
- **신경망 선형회귀**: 은닉층과 활성화 함수를 추가한 비선형 모델
- **손실함수**: MSELoss와 SGD 옵티마이저를 활용한 학습

<br/>

---
*마지막 업데이트: 2025-09-22*