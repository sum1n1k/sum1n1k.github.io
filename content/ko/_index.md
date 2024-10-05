---
# Leave the homepage title empty to use the site title
title:
date: 2024-03-25
type: landing

sections:

  - block: about.avatar
    content:
      title: ''
      username: admin
      text: <br><span style="font-size:110%">**안녕하세요, 전북대학교 컴퓨터공학부 22학번 김수민입니다.** <br><span style="font-size:70%">현재 컴퓨터공학을 주전공하고 있으며 통계학을 추가로 공부하기 위해 빅데이터AI를 연계전공하고 있습니다. 진로를 확실하게 정하지 못해 여러가지 분야를 경험해보고자 활동하고 있으며, 가장 최근에는 AI에 대한 심화 학습을 진행하고 있습니다.</span> <br> **[⭐더 자세히 알아보기⭐](/ko/author/김수민/)**<br><br>
    design:
      backgroung:
        image:
          filename: tiago-ferreira-Yw35FMpMAtE-unsplash.jpg

  - block: features
    content:
      title: <span style="font-size:75%">Academic Interests</span><br><br>
      items:
        - name: 천문학(Astronomy)
          icon: moon
          icon_pack: fas
          style: "margin-right: 10px;"
          # description: <span style="font-size:90%">여행을 다니는 걸 좋아합니다. 국내여행, 해외여행 모두 좋아하며 앞으로도 꾸준히 여행 다닐 예정입니다.</span><br><br>
        - name: 통계학(Statistics)
          icon: chart-pie
          icon_pack: fas
          style: "margin-right: 10px;"
          # description:  <span style="font-size:90%">동물을 좋아합니다. 고양이를 특히 좋아합니다. 고래 같은 해양생물을 좋아해 아쿠아리움 가기를 즐깁니다.</span><br><br>
        - name: 컴퓨터공학(Computer Engineering)
          icon: computer
          icon_pack: fas
          style: "margin-right: 10px;"
          # description: <span style="font-size:90%">여행을 다니는 걸 좋아합니다. 국내여행, 해외여행 모두 좋아하며 앞으로도 꾸준히 여행 다닐 예정입니다.</span><br><br>
    design:
      class: "custom-icon-spacing"


  - block: features
    content:
      title: <span style="font-size:75%">Personal Favorite</span><br><br>
      items:
        - name: 여행(Travel)
          icon: plane
          icon_pack: fas
          style: "margin-right: 10px;"
          # description: <span style="font-size:90%">여행을 다니는 걸 좋아합니다. 국내여행, 해외여행 모두 좋아하며 앞으로도 꾸준히 여행 다닐 예정입니다.</span><br><br>
        - name: 동물(Animal)
          icon: cat
          icon_pack: fas
          style: "margin-right: 10px;"
          # description:  <span style="font-size:90%">동물을 좋아합니다. 고양이를 특히 좋아합니다. 고래 같은 해양생물을 좋아해 아쿠아리움 가기를 즐깁니다.</span><br><br>
        - name: 음악(Music)
          icon: headphones
          icon_pack: fas
          style: "margin-right: 10px;"
          # description:  <span style="font-size:90%">음악 듣는 걸 좋아합니다. 장르, 나라 상관없이 듣습니다. 하지만 다 좋아하진 않습니다.</span><br><br>
        - name: 영화(Movie)
          icon: film
          icon_pack: fas
          style: "margin-right: 10px;"
          # description:  <span style="font-size:90%">영화 보는 것을 좋아합니다. .</span><br><br>
    design:
      class: "features-container"


  - block: slider
    content:
      slides:

      - title: <span style="font-size:70%">천문학</span>
        content: <span style="font-size:70%; line-height:0.3;">우주, 지구 관련 과학과 이슈들에 대한 관심<br>관심 있으시다면 아래 링크에 방문해보세요!</span>
        align: center
        background:
          image:
            filename: recruitment.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          icon: moon
          icon_pack: fas
          text: <span style="font-size:60%">SPACE WEATHER</span>
          text-color: '#000'
          url: 'https://spaceweather.com/'

      - title: <span style="font-size:70%">통계학</span>
        content: <span style="font-size:70%">통계와 컴퓨터과학의 연관성, 빅데이터에 대한 관심</span>
        align: center
        background:
          image:
            filename: Ai.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">컴퓨터공학</span>
        content: <span style="font-size:70%; line-height:0.3;">하드웨어와 소프트웨어 모두에 대한 관심<br>정보 보안에 대한 관심</span>
        align: center
        background:
          image:
            filename: healthcare.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">여행</span>
        content: <span style="font-size:70%">국내여행, 해외여행 상관없이 좋아함</span>
        align: center
        background:
          image:
            filename: mathematics.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">동물</span>
        content: <span style="font-size:70%">육상동물 중에는 고양이,해양동물 중에는 고래 특히 좋아함</span>
        align: center
        background:
          image:
            filename: development.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">음악</span>
        content: <span style="font-size:70%">장르, 나라 상관없이 노래 듣는 거 좋아함</span>
        align: center
        background:
          image:
            filename: development.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">영화</span>
        content: <span style="font-size:70%">비오는 날에 집에서 혼자 맛있는 거 챙겨서 영화 보는 거 좋아함</span>
        align: center
        background:
          image:
            filename: development.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '350px'
      slide_width: '100px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000


  - block: portfolio
    content:
      title: <br><br><span style="font-size:80%">Projects</span><br><br>
      page_type: project
      filter_default: 0
      filter_button:
        - name: All
          tag: '*'
        - name: C++
          tag: 'Tree'
        - name: JAVA
          tag: 'RG'
        - name: AI
          tag: 'AI'
    
    design:
      columns: '1'
      view: masonry
      flip_alt_rows: true
      background: {}
      spacing: {padding: [0, 0, 0, 0]}

  # - block: collection
  #   content:
  #     id: section-1
  #     title: Notifications & News
  #     subtitle:
  #     text:
  #     count: 3
  #     offset: 0
  #     order: desc
  #     filters:
  #       folders:
  #         - notification
  #         - post
  #         - event
  #   design:
  #     view: community/custom_card
  #     columns: '2'

  # - block: collection
  #   content:
  #     title: Latest Publications
  #     subtitle:
  #     text:
  #     count: 3
  #     filters:
  #       author: ''
  #       category: ''
  #       exclude_featured: false
  #       publication_type: ''
  #       tag: ''
  #     offset: 0
  #     order: desc
  #     page_type: publication
  #   design:
  #     view: community/custom_card
  #     columns: '2'
  #   advanced:
  #     css_style: "text-align: center;"

---