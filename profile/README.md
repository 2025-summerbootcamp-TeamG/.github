<h2 align="center">2025 Summer Bootcamp Team G</h2>
<h3 align="center">
  🎟️ 티켓 리셀 방지 서비스
</h3>
</br>
<p align="center">
  <img width="1302" height="729" alt="스크린샷 2025-07-30 오후 2 56 22" src="https://github.com/user-attachments/assets/3fc7426c-a384-49a2-8ca2-39be7cc6cbc6" />
</p>

<br>

## 📌 Table of contents
* [Introduction](#-introduction)
* [Workflow](#-workflow)
* [Demo](#-demo)
* [System Architecture](#-system-architecture)
* [ERD](#-erd)
* [Monitoring](#-monitoring)
* [Tech Stack](#-tech-stack)
* [How to start](#-how-to-start)
* [Members](#-members)


## ✏️ Introduction
### Medium  
> 📄 [Medium 글 주소](https://medium.com/...)

티켓 리셀을 방지하기 위해 얼굴 인식 기능을 도입한 서비스입니다.
## 📈 Workflow
저희 서비스를 쉽게 이해할 수 있도록 돕는 워크플로우입니다.
</br>
<img width="958" height="463" alt="스크린샷 2025-07-30 오후 2 57 29" src="https://github.com/user-attachments/assets/6fecd9f9-f215-43ed-9360-3b8a86f45f40" />


## 🎥 Demo
<p align="center">
  <img src="https://github.com/user-attachments/assets/6ad1449c-74cd-4552-9aaf-39ff944916a7" alt="홈화면+인기티켓스크롤" />
</p>

> 홈화면과 인기 티켓 화면입니다.

사용자는 인기순으로 정렬된 행사 목록을 조회할 수 있습니다.
</br>
</br>
<p align="center">
  <img src="https://github.com/user-attachments/assets/af22e935-7fcc-4f56-ac2c-cd9d6bb1775b" alt="행사선택-좌석선택" />
</p>

> 티켓 구매 과정의 화면들입니다.

원하는 행사의 시간대와 좌석을 선택하고 결제하기 버튼을 누릅니다.
</br>
</br>
<p align="center">
  <img src="https://github.com/user-attachments/assets/e81705f6-0341-43c7-8b4d-bef7b739d151" alt="결제하는거" />
</p>

> 티켓 결제 화면입니다.

결제 수단을 설정하고 결제 정보를 입력하여 결제를 완료합니다.
</br>
</br>
<p align="center">
  <img src="https://github.com/user-attachments/assets/4ac0fc88-15dd-4789-b7f8-e0cbb5013e5f" alt="생체인식+얼굴등록" />
</p>

> 생체 인식 후 얼굴을 등록합니다.

생체 인식을 통해 본인임을 확인한 후 얼굴 등록을 실시합니다.</br>
등록된 얼굴의 사람만 이 티켓을 이용할 수 있습니다.
</br>
</br>
<p align="center">
  <img src="https://github.com/user-attachments/assets/b7a91944-900f-4f45-8ffa-9152dd888eea" alt="동행자등록" />
</p>

> 동행자 등록 화면입니다.

티켓을 여러 장 구매한 경우 앱 내 아이디를 통해 동행자에게 티켓을 공유할 수 있습니다.</br>
티켓을 공유 받은 사람 또한 얼굴을 등록해야 합니다.
</br>
</br>
<p align="center">
  <img src="https://github.com/user-attachments/assets/ce4c4c08-68cd-475d-a336-fd5c532561b1" alt="스푸핑감지" />
</p>

> 실제 얼굴인지 아닌지 판별합니다.

스푸핑 감지 AI를 통해서 화면에 나타난 얼굴이 실제 얼굴인지 확인합니다.</br>
사진이나 화면을 통한 위조된 이미지인지 판별합니다.
</br>
</br>
<p align="center">
  <img src="https://github.com/user-attachments/assets/65852b13-c44f-4f97-ad1f-5ded0368812f" alt="상세정보" />
</p>

> 내 티켓 화면입니다.

내가 소유하고 있는 티켓들의 상세정보를 확인 할 수 있습니다.
</br>
</br>
<p align="center">
  <img src="https://github.com/user-attachments/assets/d2ec04e8-d9ab-4e0f-a235-a9fa528c6e53" alt="얼굴인증" />
</p>

> 얼굴 인증 화면입니다.

입장하기 전 얼굴 인증을 통해 티켓을 활성화합니다.
</br>
</br>
<p align="center">
  <img src="https://github.com/user-attachments/assets/6e835f7a-f33c-4010-924d-eafbc5f9fd0c" alt="QR코드" />
</p>

> QR 코드 화면입니다.

해당 QR 코드는 행사 관계자가 최종 확인하여 입장할 수 있습니다.
</br>
</br>
## 📍 System Architecture

<img width="983" height="553" alt="아키텍처1" src="https://github.com/user-attachments/assets/423d7655-7a7d-4753-bcd3-2b51ea0c2ffe" />
</br>
</br>
<img width="1480" height="826" alt="아키텍처2" src="https://github.com/user-attachments/assets/95367dc2-7d78-43d2-8a83-20de7ab29b41" />



## 📊 ERD
<img width="2150" height="852" alt="ticket_erd (2)" src="https://github.com/user-attachments/assets/ef44dbdf-4fed-4cf8-b363-d5332f14d0d6" />

## 🖥️ Monitoring

### cAdvisor
<table>
  <tr>
    <td width="50%">
      <img src="https://github.com/user-attachments/assets/bdbce0e6-f247-4aa1-9c69-6851fd43647d" 
           alt="cAdvisor 1"
           style="width: 100%; height: auto;" />
    </td>
    <td width="50%">
      <img src="https://github.com/user-attachments/assets/2849fe91-5aad-41d3-8440-b5253693d802" 
           alt="cAdvisor 2"
           style="width: 100%; height: auto;" />
    </td>
  </tr>
</table>


### Django
<table>
  <tr>
    <td><img width="1909" height="768" alt="스크린샷 2025-07-31 오전 1 40 11" src="https://github.com/user-attachments/assets/e8601911-0006-43ca-a7a0-75d3d0b0b827" /></td>
  </tr>
</table>

### cAdvisor
<table>
  <tr>
    <td width="50%">
      <img 
        src="https://github.com/user-attachments/assets/694afdd0-c839-4cbb-9e4c-b0e3393ec3aa" 
        alt="node_exporter 1"
        style="width: 100%; height: auto;" />
    </td>
    <td width="50%">
      <img 
        src="https://github.com/user-attachments/assets/f8a840a4-f4c1-46b0-95a8-3b96e7bbb252" 
        alt="node_exporter 2"
        style="width: 100%; height: auto;" />
    </td>
  </tr>
</table>

### Sentry
<table>
  <tr>
    <td><img width="1422" height="769" alt="스크린샷 2025-07-31 오전 12 34 28" src="https://github.com/user-attachments/assets/4886631c-2214-4e29-b1b7-921ee893922f" /></td>
  </tr>
</table>

## 🛠 Tech Stack
<div align="center">
  <table>
    <tr>
      <th>Field</th>
      <th>Technology of use</th>
    </tr>
    <!-- Frontend -->
    <tr>
      <td><b>Frontend</b></td>
      <td>
        <img src="https://img.shields.io/badge/React Native-61DAFB?style=for-the-badge&logo=React&logoColor=black"/>
        <img src="https://img.shields.io/badge/Typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=black">
        <img src="https://img.shields.io/badge/Expo-000000?style=for-the-badge&logo=Expo&logoColor=white"/>
        <img src="https://img.shields.io/badge/axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white">
        <img src="https://img.shields.io/badge/eslint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white">
        <img src="https://img.shields.io/badge/prettier-F7B93E?style=for-the-badge&logo=prettier&logoColor=white">
        <img src="https://img.shields.io/badge/React%20Navigation-CA4245?style=for-the-badge&logo=react&logoColor=white">
      </td>
    </tr>
    <!-- Backend -->
    <tr>
      <td><b>Backend</b></td>
      <td>
        <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white">
        <img src="https://img.shields.io/badge/django-092E20?style=for-the-badge&logo=django&logoColor=white"/>
        <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white"/>
        <img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=Celery&logoColor=white">
        <img src="https://img.shields.io/badge/redis-DC382D?style=for-the-badge&logo=redis&logoColor=white">
        <img src="https://img.shields.io/badge/gunicorn-499848?style=for-the-badge&logo=gunicorn&logoColor=white">
        <img src="https://img.shields.io/badge/Flask-3BABC3?style=for-the-badge&logo=Flask&logoColor=white">
      </td>
    </tr>
    <!-- DevOps -->
    <tr>
      <td><b>DevOps</b></td>
      <td>
        <img src="https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=nginx&logoColor=black">
        <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
        <img src="https://img.shields.io/badge/github%20actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white">
        <img src="https://img.shields.io/badge/Amazon AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"/>
      </td>
    </tr>
    <td><b>DB</b></td>
      <td>
        <img src="https://img.shields.io/badge/Mysql-4479A1?&style=for-the-badge&logo=Mysql&logoColor=white" />
      </td>
    </tr>
    <tr>
      <td><b>Monitoring</b></td>
      <td>
        <img src="https://img.shields.io/badge/sentry-362D59?style=for-the-badge&logo=sentry&logoColor=white">
        <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=black">
        <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=black">
        <img src="https://img.shields.io/badge/cAdvisor-1478FF?style=for-the-badge&logo=cAdvisor&Color=black">
        <img src="https://img.shields.io/badge/Node_EXPORTER-0?style=for-the-badge&logo=cAdvisor&Color=black">
      </td>
    </tr>
    <tr>
      <td><b>AI</b></td>
      <td>
        <img src="https://img.shields.io/badge/AWS%20Rekognition-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white">
      </td>
    </tr>
    <tr>
      <td><b>etc</b></td>
      <td>
        <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
        <img src="https://img.shields.io/badge/slack-4A154B?style=for-the-badge&logo=slack&logoColor=white">
        <img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white">
        <img src="https://img.shields.io/badge/zoom-0B5CFF?style=for-the-badge&logo=zoom&logoColor=black">
        <img src="https://img.shields.io/badge/figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white">
        <img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black">
        <img src="https://img.shields.io/badge/postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white">
      </td>
    </tr>
  </table>
</div>


## 📖 How to start
1. 리포지토리 클론
   ```bash
   git clone https://github.com/2025-summerbootcamp-TeamG/Frontend.git

## 🧑‍💻 Members

<table>
  <tr>
    <th>Name</th>
    <th>김주하</th>
    <th>김재영</th>
    <th>김혜연</th>
    <th>류상진</th>
    <th>윤은석</th>
  </tr>
  <tr>
    <th>Profile</th>
      <td style="text-align:center; vertical-align:middle;"><img src="https://github.com/user-attachments/assets/5a246be9-5ccf-4f5b-be65-0255b06a7481" style="width:100px;height:100px;"></td>
      <td style="text-align:center; vertical-align:middle;"><img src="" style="width:100px;height:100px;"></td>
      <td style="text-align:center; vertical-align:middle;"><img src="" style="width:100px;height:100px;"></td>
      <td style="text-align:center; vertical-align:middle;"><img src="" style="width:100px;height:100px;"></td>
      <td style="text-align:center; vertical-align:middle;"><img src="" style="width:100px;height:100px;"></td>
  </tr>
  <tr>
    <th>Role</th>
    <td>Leader, Fullstack</td>
    <td>Fullstack</td>
    <td>Fullstack</td>
    <td>Fullstack</td>
    <td>Fullstack</td>
  </tr>
  <tr>
