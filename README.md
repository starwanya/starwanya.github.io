# starwanya.github.io

## 소개
- 닉네임 : wanya
- 현재 관심 분야 : 컴퓨터그래픽스, AI
- Github 링크 : https://github.com/starwanya
## 대표 프로젝트 소개
### Wi-Finder: Wi-Fi CSI를 활용한 유니티 기반 실내 신원 식별 시스템
- WiFi, Wireless AI 분야 졸업과제 수행

#### 1. 문제 정의
- 기존 카메라 기반 실내 식별 시스템의 사생활 침해 및 사각지대 문제 해결
- 기존 Wi-Fi CSI 연구의 단일 사용자 중심 식별 한계 극복
- 저비용 하드웨어를 활용한 비접촉 다중 사용자 식별 및 실시간 모니터링 시스템 구축

#### 2. 역할
- 수집한 Wi-Fi CSI 데이터의 전처리
- CNN 기반 학습 수행, 결과 검증
- 데이터 합성, 분리 방안 탐색

#### 3. 사용 기술

| 분야 | 기술 |
| --- | --- |
| 하드웨어 및 데이터 수집 | ESP32-C6, ESP-IDF, Wi-Fi CSI, UDP |
| 데이터 처리 | Python, NumPy, Pandas |
| 머신러닝 | Scikit-learn, PCA, KNN |
| 딥러닝 | PyTorch, CNN, Dual Network, Cycle Consistency |
| 서버 및 통신 | FastAPI, WebSocket |
| 3D 시각화 | Unity, C# |


#### 4. 주요 결과
- 송신기 1대와 수신기 4대를 활용한 CSI 데이터 수집 및 전처리 파이프라인 구축
- KNN 기반 다중 사용자 인물 식별 정확도 98.89%, 위치 식별 정확도 99.25% 달성
- CNN 기반 미수집 사용자 조합의 CSI 데이터 합성 및 분리 모델 연구
- 실제 실험 공간을 1:1 비율로 구현한 3D 디지털 트윈 구축
- WebSocket 기반 실시간 식별 결과 전송 및 시각화 구현

#### 5. 소스 코드
- 전체 프로젝트: https://github.com/pnucse-capstone2026/capstone-2026-team-26
- Unity 클라이언트: https://github.com/Nuna30/indoor-identification-system 
