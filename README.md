# 🎮 Steam Market Analysis

> Steam 게임 플랫폼 데이터를 분석한 인터랙티브 대시보드 포트폴리오 프로젝트

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-blue?style=flat-square)](https://chihyuns0ng.github.io/steam/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](LICENSE)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat-square&logo=jupyter)](steam.ipynb)

---

## 📌 프로젝트 개요

Steam 플랫폼에 등록된 **122,611개 게임** 데이터를 분석하여 시장 트렌드, 장르 분포, 가격 전략, 사용자 평점 패턴을 시각화한 데이터 분석 포트폴리오입니다.

| 항목 | 내용 |
|------|------|
| 데이터셋 | Steam Games Dataset (Kaggle · fronkongames) |
| 분석 게임 수 | 122,611 titles |
| 분석 기간 | 2003 — 2026 |
| 평점 지표 | 긍정 리뷰 비율 (Steam Reviews) |

---

## 🔍 핵심 인사이트

**시장 성장**
2025년 역대 최다인 24,973개 게임이 출시되며 시장이 지속 성장 중. 2003년 단 3개에서 시작해 22년 만에 8,324배 폭증 — Steam 플랫폼의 진입 장벽 완화가 핵심 동인.

**가격-리뷰 상관**
$5~10 구간이 긍정 리뷰 비율 79.7%로 가장 높음. $40+ 고가 게임은 오히려 63.1%로 최저 — 높은 기대치가 평가에 부정적으로 작용하는 패턴 확인.

**장르 트렌드**
인디 장르가 80,630개로 전체의 65.8%를 차지해 압도적 1위. 2014년부터 매년 최다 출시 장르로 자리잡았고, 캐주얼·어드벤처가 빠르게 추격 중.

---

## 📊 분석 항목

- **연도별 시장 분석** — 게임 출시량 추이 및 유료 게임 중앙값 가격 변화 (2003–2026)
- **장르 분석** — 장르별 인기도 분포 및 플랫폼 점유율 랭킹
- **가격대 분석** — 가격대별 긍정 리뷰 비율, 게임 수 분포, 장르 구성 비율
- **장르 트렌드** — 주요 장르 출시량 연도별 변화 (Indie, Casual, Action, Adventure, Simulation)
- **리뷰 & 평점 분석** — 연도별/장르별 긍정 리뷰 비율 추이 및 분포

---

## 🗂️ 파일 구조

```
steam/
├── steam.ipynb           # 데이터 전처리 및 EDA 노트북
├── steam_analysis.ipynb  # 심화 분석 및 시각화 노트북
├── games.csv             # Steam 게임 원본 데이터셋
├── docs/                 # GitHub Pages 배포 파일 (인터랙티브 대시보드)
└── README.md
```

---

## 🛠️ 기술 스택

| 분류 | 사용 기술 |
|------|-----------|
| 데이터 분석 | Python, Pandas, NumPy |
| 시각화 (노트북) | Matplotlib, Seaborn |
| 인터랙티브 대시보드 | Chart.js v4, HTML/CSS/JavaScript |
| 배포 | GitHub Pages |

---

## 🚀 시작하기

### 인터랙티브 대시보드 바로 보기

👉 **[https://chihyuns0ng.github.io/steam/](https://chihyuns0ng.github.io/steam/)**

### 로컬에서 노트북 실행하기

```bash
# 레포지토리 클론
git clone https://github.com/chihyuns0ng/steam.git
cd steam

# 필요 패키지 설치
pip install pandas numpy matplotlib seaborn jupyter

# Jupyter 실행
jupyter notebook
```

`steam.ipynb` 또는 `steam_analysis.ipynb`를 순서대로 실행하면 됩니다.

---

## 📈 주요 통계

| 지표 | 값 |
|------|----|
| 총 분석 게임 수 | 122,611 |
| 최다 출시 연도 | 2025 (24,973개) |
| 평균 긍정 리뷰 비율 | 77% (리뷰 10개 이상 기준) |
| 유료 게임 중앙값 가격 | $3 (USD) |
| 최대 장르 | 인디 (80,630개 · 65.8%) |

---

## 📄 라이선스

이 프로젝트는 [MIT License](LICENSE) 하에 배포됩니다.

---

<p align="center">
  Steam Game Analytics Dashboard · Portfolio Project<br>
  Data: <a href="https://www.kaggle.com/datasets/fronkongames/steam-games-dataset">Steam Games Dataset</a> (Kaggle · fronkongames)
</p>

