---
# Display name (이름 표시)
title: 강경태

# Full Name (SEO용)
first_name: Gyeongtae
last_name: Kang

# Username (이것은 폴더 이름과 일치해야 합니다)
authors:
  - admin

# Is this the primary user of the site? (이것이 사이트의 주 사용자입니까?)
superuser: true

# Role/position (역할/직위)
role: 대학생

# Organizations/Affiliations (소속 조직/협회)
organizations:
  - name: '<span style="color: initial; transition: color 0.3s;">경태의 개발연습</span>'
    url: 'https://gyeongta1101.netlify.app'

# Short bio (짧은 소개)
bio: 전북대학교 컴퓨터공학부 학생으로, 의류학과에서 전과해 AI와 데이터 분석에 열정을 쏟고 있습니다. 전북대 아이디어 해커톤 최우수상, 창업 아이디어 메이커톤 베스트 피칭상 등 다양한 수상을 했으며, 현재는 이경수 교수님의 의료 인공지능 연구실에서 활동 중입니다. 서비스직 경험과 학업 성과를 바탕으로 기술과 혁신을 통해 사회에 기여하고자 합니다.

# Interests (관심 분야)
interests:
  - 인공지능 및 딥러닝
  - 데이터 분석 및 빅데이터
  - 소프트웨어 개발 및 프로그래밍
  - 창업 및 아이디어 구현
  - 사회 문제 해결 및 지속가능성
  - 서비스 경험 및 소통

# Education (학력)
education:
  courses:
    - course: 컴퓨터공학부
      institution: 전북대학교(JBNU)
      year: 2020 - 2025
    - course: 일반계(이공계열)
      institution: 전주고등학교
      year: 2016 - 2019

# Social/Academic Networking (소셜/학술 네트워킹)
social:
  - icon: instagram
    icon_pack: fab
    link: https://www.instagram.com/gyeongtae1101/
  - icon: github
    icon_pack: fab
    link: https://github.com/gyeongtaekang
  - icon: cv
    icon_pack: ai
    link: 'https://gyeongtaekang.github.io/publication/0020-fine-grained-binary-object-segmentation-in-remote-sensing-imagery-via-path-selective-test-time-adaptation/자기소개.pdf'

# Email (이메일)
email: 'namwon420@naver.com'

# Highlight the author in author lists? (이름 강조 여부)
highlight_name: true

# User groups (사용자 그룹)
user_groups:
  - human

sections:

  - block: features
    content:
      title: <span style="font-size:70%">Medical AI & Computational Science (Macs) Lab </span>
      text: <br><span style="font-size:125%">전북대학교 의료 AI 및 계산 과학 연구실 홈페이지에 오신 것을 환영합니다.</span> <br><br>
        {{% cta cta_link="./field/" cta_text="See Research Field →" %}}


  - block: slider
    content:
      slides:

      - title: <span style="font-size:70%">Recruit</span>
        content: <span style="font-size:70%">Interested in MacsLAB?</span>
        align: center
        background:
          image:
            filename: recruitment.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          icon: user
          icon_pack: fas
          text: <span style="font-size:60%">Join Us</span>
          text-color: '#000'
          url: contact

      - title: <span style="font-size:70%">AI</span>
        content: <span style="font-size:70%">의료/항공우주/컨텐츠 등 특성화 분야에 적용 가능한 AI 기술 개발<span style="font-size:70%">
        align: center
        background:
          image:
            filename: Ai.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Healthcare</span>
        content: <span style="font-size:70%">의료 및 헬스케어 분야에 적용 가능한 AI 기술 개발</span>
        align: center
        background:
          image:
            filename: healthcare.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Mathematics</span>
        content: <span style="font-size:70%">AI와 관련된 수학 및 최적화 이론 연구</span>
        align: center
        background:
          image:
            filename: mathematics.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Development</span>
        content: <span style="font-size:70%">기반 기술을 활용한 Full-Stack 어플리케이션 개발</span>
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


  - block: features
    id: features
    content:
      title: <span style="font-size:75%">Lab's Interests</span>
      text: 저희 연구실에서는 다음과 같은 연구/개발 분야에 관심을 쏟고 있습니다.<br><br><br><br>
      items:
        - name: 인공지능(AI)
          icon: code-branch
          icon_pack: fas
          description: <span style="font-size:90%">의료 (Medical), 항공우주 (Aerospace), 컨텐츠 (Contents) 등 다양한 특성화 분야에 적응형 AI 기술 적용.</span><br><br>
        - name: 멀티모달(Multi-modality)
          icon: globe
          icon_pack: fas
          description:  <span style="font-size:90%">Vision & Language 분야의 기반 AI 기술 개발 및 관련 응용 어플리케이션에 기술 적용.</span><br><br>
        - name: 의료수학(Medical Math)
          icon: calculator
          icon_pack: fas
          description:  <span style="font-size:90%">의료 분야에 대한 통계 분석 수행 및 의료 질병에 대한 수학적인 모델링 관련 연구 수행.</span><br><br>
        - name: 컨텐츠 (Contents)
          icon: comment-dots
          icon_pack: fas
          description:  <span style="font-size:90%">웹툰 및 미디어 컨텐츠와 관련된 AI 기반 기술 개발 및 고도화.</span><br><br>
        - name: 개발 (Development)
          icon: laptop
          icon_pack: fas
          description:  <span style="font-size:90%">Full-Stack 기반의 응용 어플리케이션 개발.</span><br><br>
        - name: 솔루션 (Solution)
          icon: app-store-ios
          icon_pack: fab
          description:  <span style="font-size:90%">AI 기반기술 및 관련 어플리케이션에 적용을 통한 통합 솔루션 개발!</span><br><br>


  - block: collection
    content:
      id: section-1
      title: Notifications & News
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - notification
          - post
          - event
    design:
      view: community/custom_card
      columns: '2'

  - block: collection
    content:
      title: Latest Publications
      subtitle:
      text:
      count: 3
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: publication
    design:
      view: community/custom_card
      columns: '2'
    advanced:
      css_style: "text-align: center;"

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./contact/" cta_text="Join team →" %}}
    design:
      columns: '1'
---