# TimeInKorea
[![Universal Platform](https://img.shields.io/badge/Platform-Universal-darkgreen?logo=windows&logoColor=white)](https://docs.microsoft.com/ko-kr/windows/uwp/get-started/universal-application-platform-guide) [![C#](https://img.shields.io/badge/C%23-Unity-222?logo=Unity)](https://unity.com/).

**2019 문화체육관광부 주최 문화데이터 활용 공모전 특별상 수상작**

Time In Korea는 대한민국 역사를 기반으로 한 빅데이터 기반 3D기능성 게임입니다.

# 1. 소개
[역사 게임의 효과]
- 역사 시뮬레이션 게임의 역사교육 적용 가능성에 대한 소고에 따르면 역사 시뮬레이션 게임은 학생들의 역사적 사고 발달에 기여합니다.<br>
- 역사 시뮬레이션 게임은 역사적 사건과 인물에 대한 추체험의 기회를 제공합니다.<br>
- 행복한 다람쥐단은 재미있는 역사 게임을 통해 대한민국 역사 게임을 통해 역사 인식을 높이고 역사 게임의 교육적 효과를 원하는 소비자들에게 포지셔닝 하였습니다.

[게임의 컨셉]
 역사 자료들이 해킹에 의해 조작됨을 반복하며 역사 자료를 신뢰할 수 없는 시대가 되었고, 미래공학기업에서 조상들의 기억을 엿볼 수 잇는 최첨단 기술을 개발하고 테스팅하기위해 과거로 돌아가서 탐험하는 컨셉입니다.
 
 # 2. 기술적 요소
 
 본 프로젝트는 다음과 같은 기술적 요소들을 사용하였습니다.
 
 ## 2.1. Unity
 ### 2.1.1 Terrain Compser의 활용
 앞서 World Composer를 통해 인천의 고도 정보를 담은 heightmap data를 Terrain Composer를 통해 편집 및 수정하여 게임 내 가상의 world를 구현하였습니다.
 * 지형을 자동으로 인식하여 이에 맞는 Splatmap을 적용할 수 있으며, 자동으로 적용된 Splatmap 위에 다시 자동으로 나무 object와 수풀 object를 생성한다. 물론 부족한 부분은 직접 수정할 수 있었습니다.
 
 
