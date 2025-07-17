# 제지 공정 에너지 최적화를 위한 강화학습 기반 운전 전략 도출
(Project Title: Deriving Optimal Operational Strategies for Papermaking Processes Using Multi-Objective Functions and Reinforcement Learning)

## 프로젝트 개요 (Overview)
본 프로젝트는 제지 공정의 시계열적 변동성과 변수 간 복잡한 상호작용을 해결하고, **생산성, 품질, 에너지 효율**을 동시에 최적화하는 운전 전략을 도출하는 것을 목표로 합니다. 이를 위해 다음 두 가지 접근 방식을 적용하고 실제 공정 데이터를 기반으로 성능을 비교 분석합니다.
1.  **다중 목표 보상 함수 (Multi-Goal Reward Function)** 기반 시나리오 최적화
2.  **강화학습 (PPO 알고리즘)** 기반 동적 운전 전략 학습

## 핵심 기능 (Key Features)
- **데이터 기반 분석**: 실제 제지 공장의 공정 데이터(DCS)를 활용한 시계열 분석 및 전처리
- **다중 목표 최적화**: 생산량, 수분, 스팀 압력 등 여러 목표를 동시에 고려하는 보상 함수 설계
- **강화학습 모델**: PPO (Proximal Policy Optimization) 알고리즘을 적용하여 최적의 운전 제어 전략 학습
- **성능 비교**: 정적 최적화 방식과 동적 강화학습 방식의 결과를 비교하여 각 전략의 강점 분석

