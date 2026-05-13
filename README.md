# 🧭 그리GO (GRI-GO)
> **당신이 꿈꾸는 여행을 그리다. 스마트 여행 코스 추천 및 쇼핑 플랫폼**

![Main Banner](https://images.unsplash.com/photo-1527631746610-bca00a040d60?auto=format&fit=crop&q=80&w=1200)

## 📖 프로젝트 소개
**그리GO**는 사용자 기반의 위치 정보를 활용하여 최적의 여행 경로를 추천하고, 숙박, 체험, 교통 등 다양한 여행 상품을 쇼핑할 수 있는 통합 여행 플랫폼입니다. 

## ✨ 주요 기능
### 1. 🚀 스마트 경로 최적화 (Dijkstra Algorithm)
- **다익스트라 알고리즘**을 활용하여 여러 여행지를 방문할 때 가장 효율적인 경로를 계산합니다.
- 이동 거리와 소요 시간을 최소화하여 여행의 피로도를 낮춰줍니다.

### 2. 🗺️ 실시간 위치 기반 서비스
- **카카오맵 API** 연동을 통한 정밀한 위치 확인.
- 현재 내 위치에서 목적지까지의 직선 거리 및 예상 소요 시간(도보/차량) 제공.
- 카카오맵 길찾기 기능을 통한 즉각적인 이동 지원.

### 3. 🛍️ 여행 상품 쇼핑몰
- **카테고리별 상품**: 숙박, 체험, 교통, 관광지 등 다양한 상품 구성.
- **실시간 데이터**: MongoDB를 통한 실시간 상품 정보 관리 및 검색 기능.
- **다이나믹 UI**: 프리미엄 디자인이 적용된 카드 뷰와 슬라이더.

### 4. 🤖 AI 컨시어지 (준비 중)
- AI가 사용자의 취향과 예산을 분석하여 맞춤형 여행 일정을 자동으로 생성합니다.

## 🛠 기술 스택
### Frontend
- **React Native (Expo)**: Cross-platform 모바일 앱 개발.
- **Lucide-native**: 세련된 아이콘 시스템.
- **React Navigation**: 매끄러운 화면 전환.

### Backend
- **Node.js (Express)**: RESTful API 서버 구축.
- **MongoDB**: 유저 및 상품 데이터 관리 (이중 커넥션 아키텍처).
- **Mongoose**: 데이터 모델링 및 스키마 관리.

## 🚀 시작하기
### Prerequisites
- Node.js & npm
- MongoDB (Local)
- Expo Go (Mobile App)

### Installation
1. Repository 클론
   ```bash
   git clone https://github.com/kmc4334/-GO.git
   ```

2. Backend 설정 및 실행
   ```bash
   cd travel-shopping-backend
   npm install
   # .env 파일 설정 필요 (MONGO_URI, PRODUCT_MONGO_URI 등)
   npm start
   ```

3. Frontend 설정 및 실행
   ```bash
   cd travel-shopping-app
   npm install
   npx expo start
   ```

## 📂 폴더 구조
- `travel-shopping-app`: React Native 프론트엔드 코드
- `travel-shopping-backend`: Express 서버 및 데이터베이스 로직

---
© 2026 그리GO Team. All rights reserved.
