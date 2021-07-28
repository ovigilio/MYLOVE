#1 블로그 작성가이드

1. 경어체로 작성한다. ex) ~ 한다 → ~ 합니다.
2. 긴 영문 문장 사용을 피하고 짧은 영문은 인용구로 처리한다.
3. 제목은 H1, 본문의 중주제,소주제는 각각 H2, H3을 사용한다.
4. 박스는 되도록 코드에만 사용한다. (* code 작성시 사용)
5. 블로그 마지막은 요약 문장을 작성하여 마무리 한다.
6. 이미지를 가지고 온 경우 출처를 표기한다.
7. 마지막에 참고문서가 있다면 목록을 작성하여 표기한다.
8. 뉴스기사를 가지고 온 경우 출처를 표기한다.


#2 포스트 등록방법

1.  _posts 디렉터리 하위에 YYYY-MM-DD-title.md 구문으로 md 파일생성합니다.
2.  아래 내용을 필수로 입력 후 다음 라인부터 내용을 작성하시면 됩니다.

```
---
layout: post
title:  "제목"  # 제목
subtitle: "설명" # 부제목
date: 2021-07-28 10:53:24 +0900 # 등록일자 입력
categories: Interview # 생성한 카테고리 title을 입력하세요.(카테고리는 반드시 1개만 입력)
tags: [HR, CTO] # 태그는 복수 입력 가능
---


본문 서두에는 "작성자 : 이름" #작성자명을 입력하시고 다음 문단부터 글을 작성합니다

내용....
```

github에 commit 후 잠시 기다리면 적용된 모습을 확인할 수 있습니다.

#3 본문에 이미지 삽입하는 방법

루트디렉토리에서 assets 디렉토리로 들어가서 아래와 같은 방법으로 본문에 임베딩할 수 있습니다.

![ImageName](/assets/images/postimg/20210728_cto.확장자) # 디렉토리에서 불러오는 경우

![ImageName](https://source.unsplash.com/random/1500x1000(랜덤 또는 파일 이름)"  # 웹사이트에서 가져오는 경우


