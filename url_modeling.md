이름            URL             비고

메인 페이지      /               main
소개 페이지      /about          main
주소 페이지       /contact       main

로그인          /user/login        user
로그아웃        /user/logout        user
회원가입        /user/signup        user
프로필 보기     /user/profile       user

게시글 목록     /blog  
게시글 상세     /blog/<int:post_pk>
게시글 작성     /blog/write
게시글 수정     /blog/edit/<int:post_pk>
게시글 삭제     /blog/delete/<int:post_pk>

댓글 작성       /blog/<int:post_pk>/comment
댓글 수정       /blog/update_comment/<int:comment_pk>/
댓글 삭제       /blog/update_comment/<int:comment_pk>/
카테고리        /blog/category/<str:slug>/

태그            /blog/tag/<str:slug>/

댓글 like
게시글 like
프로필 설정
404 페이지
권한 없음 페이지

