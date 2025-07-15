# 🔬 HyperKAN: Kolmogorov–Arnold Network 기반 HSI 분류 연구

이 저장소는 **HyperKAN** 및 **실험용 KAN 구조**를 기반으로 한 논문 및 구현 코드에 대한 정보를 담고 있습니다.

## 📌 소개

- **HyperKAN (ICLR 2024)**  
  최근 제안된 Kolmogorov–Arnold Network 기반 구조로, spline-based 함수로 low-SNR 조건에서도 복잡한 비선형 함수를 효과적으로 모델링할 수 있음.  
  > 논문: [HyperKAN: Kolmogorov–Arnold Networks make hyperspectral image classifiers smarter (ICLR 2024)](https://arxiv.org/abs/2403.09876)

- **실험용 KAN 모델 (ICLR)**  
  본 프로젝트에서는 HyperKAN의 구조를 참고하여 실험용 KAN 기반 HSI 분류 네트워크를 구성하고, 실제 MWIR-HSI 환경에서의 성능을 검증합니다.

## 📂 구성

| 파일/폴더 | 설명 |
|-----------|------|
| `models/` | KAN 기반 분류기 구현 |
| `data/` | MWIR-HSI 샘플 데이터셋 |
| `train.py` | 학습 루프 |
| `README.md` | 현재 문서 |
| `requirements.txt` | 의존 패키지 목록 |

## 🧪 주요 기술

- Kolmogorov–Arnold Network (KAN)
- Spline-based Adaptive Activation
- Hyperspectral Image (HSI) Classification
- Mid-Wave Infrared (MWIR)
- Dual-path Spectral-Spatial Fusion

## 📜 인용
