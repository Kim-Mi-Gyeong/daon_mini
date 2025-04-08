<small>
  
# ■ 프로젝트명: Daon

<img src="https://github.com/Kim-Mi-Gyeong/Project_FinFit/raw/main/FinFit-Chrome2025-04-0213-57-31-ezgif.com-video-to-gif-converter.gif.gif" width="720"/>

# ■ Daon - 데이터 분석 도서 서비스 

Daon은 머신 러닝, python 등 데이터 분석 관련 전문 도서 서비스<br>
도서의 상세 설명을 통해, 학습에 필요한 원활한 정보 제공<br>

<table>
  <thead>
    <tr>
      <th>항목</th>
      <th>내용</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>개발 기간</td>
      <td>
        2024년 12월 5일(목) ~ 2024년 12월 20일(금)
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      </td>
    </tr>
    <tr>
      <td>프로젝트 목표</td>
      <td>
        - 
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      </td>
    </tr>
  </tbody>
</table>

## ■ 목차 
1. 소개
2. 프로젝트 진행 관리  
3. 담당업무  
4. Skill & Tools
5. 기능 구현  
6. ER Diagram
7. Use case Diagram  
8. How to Test  

<h2> ■ 소개 </h2>



## ■  프로젝트 진행 관리 

![image](https://github.com/user-attachments/assets/7a16587a-5eb2-4be4-bfa9-fa67d59f96f1)

## ■ Stacks 

### Language
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)

### Backend(server)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat&logo=mariadb&logoColor=white)

### Frontend
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat&logo=bootstrap&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)

### Dev Tools
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat&logo=visualstudiocode&logoColor=white)
![venv](https://img.shields.io/badge/venv-3C3C3C?style=flat&logo=python&logoColor=white)

## ■ 기능 구현 



## ■ Service Flow Diagram

<img src="사용자흐름도(최종).png" alt="FinFit 사용자 흐름도" width="700">

## ■ Architecture
<pre>
📂FINFIT/<br>
├── 📂models/                   # 학습된 머신러닝 모델 파일 (.pkl)
├── 📂static/                   # 정적 파일 (CSS, JS, 이미지, CSV 등)
├── 📂templates/                # HTML 템플릿 (Jinja2)
├── 📂views/                    # 주요 기능별 Flask 뷰 파일
│   ├── chatbot_views.py          # ✨ (옵션) Gemini 기반 챗봇 응답 처리
│   ├── company_views.py          # 소개/회사 관련 페이지
│   ├── customer_views.py         # 사용자 정보 입력/관리
│   ├── depression_views.py       # 우울증 예측 기능
│   ├── disease_views.py          # 질병 예측 기능
│   ├── exercise_views.py         # 체형 예측 및 운동 추천
│   ├── hospital_views.py         # 병원 추천 기능
│   ├── main_views.py             # 메인 페이지, 라우팅 허브
│   └── squat_views.py            # 실시간 운동 자세 분석 (스쿼트)
├──📂 __init__.py               # Flask 앱 초기화
</pre>


## ■ How to Test 

> 아래 테스트는 Flask 서버 실행 후 http://localhost:5000 접속 시 확인할 수 있습니다.

| 테스트 항목 | 경로 | 주요 확인 내용 |
|-------------|------|----------------|
| 메인 페이지 | / | 전체 기능 링크 및 UI 연결 확인 |
| 사용자 정보 입력 | /customer | 성별·나이·키·몸무게·도시·지역 입력 후 DB 저장 |
| 스쿼트 분석 | /squat | 웹캠 기반 실시간 자세 추적 + 반복 수·피드백 확인 |
| 체형 예측 & 운동 추천 | /exercise | BMI 기반 체형 분류 + 난이도별 운동 영상 추천 |
| 질병 예측 | /disease | 당뇨·고혈압·고지혈증 예측 그래프 + 암 위험도 시각화 |
| 우울증 예측 | /depression | PHQ-9 기반 우울 단계 분석 + 수면 차트, AI 코멘트 확인 |
| 병원 추천 | /hospital | 지역 내 질병별 내과 병원 자동 추천 (Naver 지도 연동) |

🧩 모든 테스트는 가상환경(venv)에서 Flask 실행 후, 브라우저 기반으로 진행합니다.


</small>
