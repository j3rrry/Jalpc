---
layout: post
categories: [Blogging]
keywords: blog, blogging, disqus, github, jekyll
tags: [blogging, disqus, github, blog, jekyll]
title: github blog에 댓글 기능 세팅 (disqus)
desc: github blog에 댓글 기능 세팅 (disqus)
date: 2019-01-17
icon: fab fa-blogger-b
---

그동안 네이버, 티스토리 블로깅을 했지만 깃블로그? 깃헙 블로그?의 경우 댓글 기능이 따로 없더군요.  
그래서 disqus를 이용해 만들어봅니다.  
  
disqus는 게시물별로 댓글을 관리해주고 블로그 이전할 시 댓글도 가져올 수 있단다.  
좋은 듯.  
  
1. disqus.com에 회원 가입을 한다.
2. disqus.com 오른쪽 위에 프로필 사진(avatar) 클릭 -> Home 클릭
3. 오른쪽 위 'Settings' -> 'Add Disqus To Site'
4. 맨 아래 파란색 버튼 'GET STARTED'
5. 두 번째꺼 'I want to install Disqus on my site'
6. 'Website Name' 에 이름 짓기 (나중에 얼마든지 변경 가능)
   작은 글씨로 Your unique disqus URL will be: 'shortname'.disqus.com 에서 'shortname'이 계정 연결할 때 필요함 (변경 불가)
7. 'Jekyll' 선택 -> 다음 -> 다음 -> 성공
8. `_includes/comments.heml`, `_config.yml` 파일 수정
