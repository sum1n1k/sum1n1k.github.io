---
# Leave the homepage title empty to use the site title
title:
date: 2024-03-25
type: landing

sections:

  - block: features
    content:
      title: <span style="font-size:70%">Medical AI & Computational Science (Macs) Lab </span>
      text: <br><span style="font-size:125%">�쟾遺곷���븰援� �쓽猷� AI 諛� 怨꾩궛 怨쇳븰 �뿰援ъ떎 �솃�럹�씠吏��뿉 �삤�떊 寃껋쓣 �솚�쁺�빀�땲�떎.</span> <br><br>
        {{% cta cta_link="./field/" cta_text="See Research Field �넂" %}}


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
        content: <span style="font-size:70%">�쓽猷�/�빆怨듭슦二�/而⑦뀗痢� �벑 �듅�꽦�솕 遺꾩빞�뿉 �쟻�슜 媛��뒫�븳 AI 湲곗닠 媛쒕컻<span style="font-size:70%">
        align: center
        background:
          image:
            filename: Ai.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Healthcare</span>
        content: <span style="font-size:70%">�쓽猷� 諛� �뿬�뒪耳��뼱 遺꾩빞�뿉 �쟻�슜 媛��뒫�븳 AI 湲곗닠 媛쒕컻</span>
        align: center
        background:
          image:
            filename: healthcare.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Mathematics</span>
        content: <span style="font-size:70%">AI��� 愿��젴�맂 �닔�븰 諛� 理쒖쟻�솕 �씠濡� �뿰援�</span>
        align: center
        background:
          image:
            filename: mathematics.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Development</span>
        content: <span style="font-size:70%">湲곕컲 湲곗닠�쓣 �솢�슜�븳 Full-Stack �뼱�뵆由ъ���씠�뀡 媛쒕컻</span>
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
      text: ����씗 �뿰援ъ떎�뿉�꽌�뒗 �떎�쓬怨� 媛숈�� �뿰援�/媛쒕컻 遺꾩빞�뿉 愿��떖�쓣 �룦怨� �엳�뒿�땲�떎.<br><br><br><br>
      items:
        - name: �씤怨듭���뒫(AI)
          icon: code-branch
          icon_pack: fas
          description: <span style="font-size:90%">�쓽猷� (Medical), �빆怨듭슦二� (Aerospace), 而⑦뀗痢� (Contents) �벑 �떎�뼇�븳 �듅�꽦�솕 遺꾩빞�뿉 �쟻�쓳�삎 AI 湲곗닠 �쟻�슜.</span><br><br>
        - name: 硫��떚紐⑤떖(Multi-modality)
          icon: globe
          icon_pack: fas
          description:  <span style="font-size:90%">Vision & Language 遺꾩빞�쓽 湲곕컲 AI 湲곗닠 媛쒕컻 諛� 愿��젴 �쓳�슜 �뼱�뵆由ъ���씠�뀡�뿉 湲곗닠 �쟻�슜.</span><br><br>
        - name: �쓽猷뚯닔�븰(Medical Math)
          icon: calculator
          icon_pack: fas
          description:  <span style="font-size:90%">�쓽猷� 遺꾩빞�뿉 ����븳 �넻怨� 遺꾩꽍 �닔�뻾 諛� �쓽猷� 吏덈퀝�뿉 ����븳 �닔�븰�쟻�씤 紐⑤뜽留� 愿��젴 �뿰援� �닔�뻾.</span><br><br>
        - name: 而⑦뀗痢� (Contents)
          icon: comment-dots
          icon_pack: fas
          description:  <span style="font-size:90%">�쎒�댆 諛� 誘몃뵒�뼱 而⑦뀗痢좎�� 愿��젴�맂 AI 湲곕컲 湲곗닠 媛쒕컻 諛� 怨좊룄�솕.</span><br><br>
        - name: 媛쒕컻 (Development)
          icon: laptop
          icon_pack: fas
          description:  <span style="font-size:90%">Full-Stack 湲곕컲�쓽 �쓳�슜 �뼱�뵆由ъ���씠�뀡 媛쒕컻.</span><br><br>
        - name: �넄猷⑥뀡 (Solution)
          icon: app-store-ios
          icon_pack: fab
          description:  <span style="font-size:90%">AI 湲곕컲湲곗닠 諛� 愿��젴 �뼱�뵆由ъ���씠�뀡�뿉 �쟻�슜�쓣 �넻�븳 �넻�빀 �넄猷⑥뀡 媛쒕컻!</span><br><br>


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
        {{% cta cta_link="./contact/" cta_text="Join team �넂" %}}
    design:
      columns: '1'
---