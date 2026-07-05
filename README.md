<div align="center">

# DeepLearning_lecture

**Keras 기반 딥러닝 강의·과제 실습 노트북 모음**

![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white) ![Deep Learning](https://img.shields.io/badge/Deep_Learning-7C3AED?style=flat-square)

[English](./README.en.md)

</div>

---

## 소개

이 저장소는 딥러닝 강의와 과제에서 사용한 notebook, 샘플 데이터, 이미지, 모델 파일을 모아 둔 저장소입니다. Dense layer, sigmoid/tanh/ReLU, Keras 모델 구성, 붓꽃/와인/주택 데이터 실습이 포함되어 있습니다.

패키지형 프로젝트가 아니라 강의 실습 아카이브이므로, README는 어떤 notebook이 어떤 학습 목표를 갖는지 빠르게 파악하도록 돕습니다.

각 notebook은 완성된 라이브러리 API보다 학습 과정 자체를 보여주는 데 초점이 있습니다. 활성화 함수, 단순 신경망 구성, 분류 데이터셋 적용, 저장된 모델 파일 확인을 순서대로 따라가면 강의에서 다룬 개념의 연결을 확인할 수 있습니다.

## 주요 기능

| 기능 | 설명 |
|---|---|
| 기초 신경망 실습 | `1강 코드.ipynb`에서 Keras Dense 모델과 sigmoid 출력층을 다룹니다. |
| 직접 구현 과제 | `과제 1 코드.ipynb`에서 sigmoid/tanh 기반 신경망과 활성화 함수 실험을 다룹니다. |
| 분류 실습 | `과제2 코드.ipynb`와 `와인 종류 예측하기.ipynb`에서 붓꽃·와인 데이터 분류를 다룹니다. |
| 샘플 데이터 | `data-master/`에 CSV, 이미지, hdf5 모델 파일이 들어 있습니다. |
| 실습 아카이브 | 강의별 notebook, 과제 코드, 데이터 자산을 한 저장소에서 다시 열람할 수 있습니다. |

## 저장소 구조

| 경로 | 역할 |
|---|---|
| *.ipynb | Lecture and assignment notebooks |
| data-master/ | CSV datasets, sample images, and model artifacts |

## 학습 순서

1. `1강 코드.ipynb`에서 Keras 모델의 기본 구성과 Dense layer 사용법을 확인합니다.
2. `과제 1 코드.ipynb`에서 sigmoid와 tanh 같은 활성화 함수가 계산에 어떻게 들어가는지 봅니다.
3. `과제2 코드.ipynb`와 `와인 종류 예측하기.ipynb`에서 분류 데이터셋을 모델에 적용합니다.
4. `data-master/` 안의 CSV, 이미지, 모델 파일을 보며 notebook 입력 자산을 확인합니다.

노트북이 작성된 시점의 TensorFlow/Keras 버전과 현재 설치 버전이 다를 수 있습니다. 재실행 전에는 가상환경을 만들고, 필요한 패키지를 고정한 뒤 셀을 순서대로 실행하는 편이 안전합니다.

## 빠른 시작

### Jupyter 실행

```bash
jupyter lab
```

### 노트북 목록 확인

```bash
find . -name "*.ipynb" | sort
```

### 권장 순서

1강 코드.ipynb -> 과제 1 코드.ipynb -> 과제2 코드.ipynb -> 와인 종류 예측하기.ipynb

## 검증

| 항목 | 명령 |
|---|---|
| Notebook count | `find . -name "*.ipynb" | wc -l` |

## 운영 메모

- 일부 notebook은 오래된 환경이나 로컬 경로를 전제로 할 수 있습니다.
- Keras/TensorFlow 버전에 따라 실행 결과가 달라질 수 있으니 환경을 별도로 기록하는 것이 좋습니다.
- 후속 정리를 한다면 `requirements.txt` 또는 `environment.yml`을 추가해 강의 실행 환경을 고정하는 것이 가장 먼저 할 일입니다.

## 문서 작성 근거

이 README는 저장소 안의 다음 파일과 문서를 기준으로 작성했습니다.

- `1강 코드.ipynb`
- `과제 1 코드.ipynb`
- `과제2 코드.ipynb`
- `와인 종류 예측하기.ipynb`
- `data-master/`
