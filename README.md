# Fiton Project

[![Repository](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/2zm00/Fiton_Project)  
[![ERD 다이어그램](https://img.shields.io/badge/ERD-2496ED?style=for-the-badge&logo=database&logoColor=white)](https://www.erdcloud.com/d/298fbiaFf2XZf4Etd)  
[![요구사항정의서](https://img.shields.io/badge/요구사항정의서-FF4154?style=for-the-badge&logo=googledocs&logoColor=white)](https://docs.google.com/spreadsheets/d/1z0MNgjmX_-icLs5omh3fUv9CrDgwp_VYDUaUMc3BOqk/edit?usp=sharing)


  ## 프로젝트 역할
- 프로젝트 매니저 & 팀 리더
- 문서화 담당자
- 프론트엔드 리더
- 백엔드 개발자

  ## 주요 기능 구현


### 결제 시스템 통합
**회원권 결제 시스템**
<div align=center>
  
![회원권 결제](https://github.com/user-attachments/assets/d60e656d-8e80-4fcf-90ef-a1a8c318fbd0)
</div>
   
- Toss Payments를 이용하여 안전한 결제 시스템 구축했습니다.  
- 센터운영자가 설정한 회원권의 정보들을 토대로 결제 정보가 전송됩니다.  
- 결제 성공/실패에 따른 페이지를 렌더링합니다.

  
**수강권 결제**
<div align=center>
  
![수강권 결제](https://github.com/user-attachments/assets/ae90da81-db48-4ed5-907a-1e93dd8b3fc0)
</div>

- 동일한 토스 페이먼츠를 사용하였고  
- 강사의 설정을 기반으로 가격 시스템을 구현합니다.
- 동일하게 결제 성공/실패에 따른 페이지를 랜더링합니다.
  
  
### 디바운싱을 활용한 실시간 검색 기능
**메인 검색 기능**
<div align=center>
  
![메인 검색](https://github.com/user-attachments/assets/38398ae6-4f42-4c4e-aeaf-d4ce190812c9)
</div>

- 메인페이지에 검색창을 구현하였고, 키워드에 따른 페이지를 전송해줍니다.
- 디바운싱 기술을 활용하여 성능 최적화하였습니다.
- 다중 키워드 검색 지원:
  - 피트니스 센터
  - 강사
  - 운동 종목
- 검색 키워드에 기반하여 동적 페이지 라우팅을 구현하였습니다.

**전용 검색 페이지**
<div align=center>
  
  ![페이지 검색](https://github.com/user-attachments/assets/e5c6c373-e962-4ff0-94e7-f315c8087a19)
</div>

- '/search'경로의 통합 검색 인터페이스입니다.
- 기본적으로 센터 정보를 표시합니다.
- 실시간 결과를 통해 사용자의 경험을 개선했습니다.
  
### 센터 관리 시스템
**센터 생성 및 관리**
<div align=center>
  
![센터장, 센터 생성](https://github.com/user-attachments/assets/5149dce4-3e5b-48be-b6fe-339e67948f28)
</div>

- 센터장 계정 전용 권한을 설정하였습니다.
- 포괄적인 센터 정보들을 관리할 수 있습니다.
- 상세 정보 또한 수정이 가능합니다.

  **강사 인증 시스템**
<div align=center>
  
![센터 상세, 오류 시 알림](https://github.com/user-attachments/assets/952d4ce8-cea9-4b81-b98d-e1a803bef744)
</div>

- 센터 등록은 양방향 인증 프로세스입니다. 강사는 센터에 인증을 신청할 수 있습니다.
- 센터장은 강사를 승인/거절 할 수 있습니다.  
- 강사의 활성 수업 일정을 자동 검증하고, 우측 상단 알림께 강사 해지에 대한 결과를 받을 수 있습니다.  
- 센터장은 회원권을 발급할 수 있고, 또한 수업을 개설 할 수 있습니다.


### 프론트엔드 리더십 기여
**디자인 및 인터페이스**
<div align=center>

![인트로 애니메이션](https://github.com/user-attachments/assets/da346bb6-6e4c-43c9-8867-a5aa6953fdf3)

</div>

- 전체 프로젝트의 디자인 및 컨셉을 주도하였습니다.
- 인트로 애니메이션을 구현하였습니다.
- 일관된 UI/UX 패턴을 수립하였습니다.

  ### 기술 문서화
- 프로젝트에 대한 문서화 총괄했습니다.
- ERD 다이어그램 작성 및 관리하였습니다.
- WBS 일정을 수립하였습니다.
- 팀 커뮤니케이션 및 진행 상황 추적했습니다.

## 프로젝트 관리
- 일일 스탠드업 및 팀 미팅 주도적으로 이끌었습니다.
- 프로젝트 일정 및 산출물을 관리하였습니다.


본 프로젝트는 안정적인 결제 시스템, 실시간 검색 기능, 그리고 정교한 사용자 역할 관리를 갖춘 종합적인 피트니스 센터 관리 시스템입니다. 프로젝트 매니저이자 기술 리더로서 코드 품질과 사용자 경험의 높은 수준을 유지하면서 다양한 컴포넌트 간의 원활한 통합을 보장했습니다.
