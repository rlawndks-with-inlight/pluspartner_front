📦src
 ┣ 📂assets             //이미지 및 폰트 등 정적인 파일 위치입니다.
 ┃ ┗ 📂images
 ┃ ┃ ┣ 📂icon
 ┃ ┃ ┣ 📂test
 ┣ 📂common             //공통으로 존재하는 컴포넌트 입니다.
 ┃ ┣ 📂manager          //관리자 페이지에 공통으로 존재하는 컴포넌트입니다.
 ┃ ┃ ┣ 📜Breadcrumb.js  //위에 헤드부분 입니다.
 ┃ ┃ ┣ 📜DataTable.js   //관리자 리스트 페이지에 사용되는 컴포넌트입니다.
 ┃ ┃ ┣ 📜DataTr.js 
 ┃ ┃ ┣ 📜Pagination.js
 ┃ ┃ ┗ 📜SideBar.js     //관리자 페이지에 사용되는 사이드바 컴포넌트 입니다.
 ┃ ┣ 📜BottomMenu.js
 ┃ ┣ 📜Footer.js        // 푸터 입니다.
 ┃ ┗ 📜Headers.js       // 헤더 입니다.
 ┣ 📂components         // 기능 및 스타일이 들어간 컴포넌트 입니다 📂components 바로 안에 있는 파일들은 기능에 사용되는 컴포넌트, 📂elements 안에 있는 파일들은 스타일 위주의 컴포넌트 입니다.
 ┃ ┣ 📂elements         // 스타일 위주의 컴포넌트 입니다.
 ┃ ┃ ┣ 📂button
 ┃ ┃ ┃ ┣ 📜AddButton.js
 ┃ ┃ ┃ ┣ 📜ButtonContainer.js 
 ┃ ┃ ┃ ┗ 📜CancelButton.js
 ┃ ┃ ┣ 📂pagination
 ┃ ┃ ┃ ┣ 📜PageButton.js
 ┃ ┃ ┃ ┗ 📜PageContainer.js
 ┃ ┃ ┣ 📜AuthContentTemplete.js
 ┃ ┃ ┣ 📜Content.js
 ┃ ┃ ┣ 📜ContentMenu.js
 ┃ ┃ ┣ 📜ContentMenuContainer.js
 ┃ ┃ ┣ 📜ContentTitle.js
 ┃ ┃ ┣ 📜ContentWrappers.js
 ┃ ┃ ┣ 📜LeftContent.js
 ┃ ┃ ┣ 📜ManagerContentWrappers.js
 ┃ ┃ ┣ 📜ManagerTemplete.js
 ┃ ┃ ┣ 📜ManagerWrappers.js
 ┃ ┃ ┣ 📜MBottomContent.js
 ┃ ┃ ┣ 📜SelectSubType.js
 ┃ ┃ ┣ 📜SubType.js
 ┃ ┃ ┣ 📜UserContentTemplete.js
 ┃ ┃ ┗ 📜Wrappers.js
 ┃ ┣ 📜Chart.js
 ┃ ┣ 📜CommentComponent.js
 ┃ ┣ 📜ContentHeader.js
 ┃ ┣ 📜ContentTitle.js
 ┃ ┣ 📜EditMyInfoCard.js
 ┃ ┣ 📜FindMyInfoCard.js
 ┃ ┣ 📜IssueContent.js
 ┃ ┣ 📜LeftImgCard.js
 ┃ ┣ 📜LetterByDateContent.js
 ┃ ┣ 📜LetterByThemeContent.js
 ┃ ┣ 📜Loading.js
 ┃ ┣ 📜LoginCard.js
 ┃ ┣ 📜MetaTag.js
 ┃ ┣ 📜MLoginCard.js
 ┃ ┣ 📜Modal.js
 ┃ ┣ 📜NewsContent.js
 ┃ ┣ 📜ResignCard.js
 ┃ ┣ 📜RightImgCard.js
 ┃ ┣ 📜ScrollToTop.js
 ┃ ┣ 📜ScrollToTopButton.js
 ┃ ┣ 📜SignUpCard.js
 ┃ ┣ 📜ThemeCard.js
 ┃ ┣ 📜TopImgCard.js
 ┃ ┣ 📜UpsetContent.js
 ┃ ┣ 📜useNetwork.js
 ┃ ┣ 📜VideoCard.js
 ┃ ┗ 📜ZoomButton.js
 ┣ 📂data
 ┃ ┣ 📜Data.js                      //고정값 또는 기본 세팅 데이터 입니다. 그리고 관리자 리스트 페이지에 사용되는 데이터 입니다.
 ┃ ┗ 📜TestData.js
 ┣ 📂functions
 ┃ ┗ 📜utils.js                     // 자주 쓰이는 함수가 모여있는 파일 입니다.
 ┣ 📂pages
 ┃ ┣ 📂Manager
 ┃ ┃ ┣ 📜MAlarmEdit.js              // 푸시알림 추가 및 수정 페이지 입니다.
 ┃ ┃ ┣ 📜MChannelEdit.js            // 채널 추가 및 수정 페이지 입니다.
 ┃ ┃ ┣ 📜MFeatureCategoryEdit.js    // 특징주 카테고리 추가 및 수정 페이지 입니다.
 ┃ ┃ ┣ 📜MIssueCategoryEdit.js      // 핵심이슈 카테고리 추가 및 수정 페이지 입니다.
 ┃ ┃ ┣ 📜MItemEdit.js               // 핵심이슈, 특징주 등 게시물 추가 및 수정 페이지 입니다.
 ┃ ┃ ┣ 📜MItemList.js               // 관리자 리스트 페이지 추가 및 수정 페이지 입니다.
 ┃ ┃ ┣ 📜MLogin.js                  // 관리자 로그인 페이지 입니다.
 ┃ ┃ ┣ 📜MMasterEdit.js             // 강사 추가 및 수정 페이지 입니다.
 ┃ ┃ ┣ 📜MNoticeEdit.js             // 공지사항 추가 및 수정 페이지 입니다.
 ┃ ┃ ┣ 📜MPopupEdit.js              // 팝업 추가 및 수정 페이지 입니다.
 ┃ ┃ ┣ 📜MProhibitCommentEdit.js    // 금지 댓글 추가 및 수정 페이지 입니다.
 ┃ ┃ ┣ 📜MSettingEdit.js            // 배너 등 기본 사이트 세팅 페이지 입니다.
 ┃ ┃ ┣ 📜MUserEdit.js               // 유저 추가 및 수정 페이지 입니다.
 ┃ ┃ ┗ 📜MVideoEdit.js              // 핵심비디오 추가 및 수정 페이지 입니다.
 ┃ ┣ 📂User
 ┃ ┃ ┣ 📂Auth
 ┃ ┃ ┃ ┣ 📜AddInquiry.js
 ┃ ┃ ┃ ┣ 📜BlockUserSetting.js
 ┃ ┃ ┃ ┣ 📜EditMyInfo.js
 ┃ ┃ ┃ ┣ 📜FindMyInfo.js
 ┃ ┃ ┃ ┣ 📜KakaoRedirectHandler.js
 ┃ ┃ ┃ ┣ 📜Login.js
 ┃ ┃ ┃ ┣ 📜MyInquiry.js
 ┃ ┃ ┃ ┣ 📜MyPage.js
 ┃ ┃ ┃ ┣ 📜NaverLogin.js
 ┃ ┃ ┃ ┣ 📜Resign.js
 ┃ ┃ ┃ ┗ 📜SignUp.js
 ┃ ┃ ┣ 📂Feature
 ┃ ┃ ┃ ┗ 📜FeatureList.js
 ┃ ┃ ┣ 📂Issues
 ┃ ┃ ┃ ┗ 📜IssueList.js
 ┃ ┃ ┣ 📂Master
 ┃ ┃ ┃ ┗ 📜Master.js
 ┃ ┃ ┣ 📂Notice
 ┃ ┃ ┃ ┣ 📜Notice.js
 ┃ ┃ ┃ ┗ 📜NoticeList.js
 ┃ ┃ ┣ 📂OneEvent
 ┃ ┃ ┃ ┗ 📜OneEventList.js
 ┃ ┃ ┣ 📂OneWord
 ┃ ┃ ┃ ┗ 📜OneWordList.js
 ┃ ┃ ┣ 📂Policy
 ┃ ┃ ┃ ┗ 📜Policy.js
 ┃ ┃ ┣ 📂Posts
 ┃ ┃ ┃ ┣ 📜asd
 ┃ ┃ ┃ ┣ 📜post.css
 ┃ ┃ ┃ ┣ 📜Post.js
 ┃ ┃ ┃ ┗ 📜Video.js
 ┃ ┃ ┣ 📜AppSetting.js
 ┃ ┃ ┣ 📜Home.js
 ┃ ┃ ┣ 📜MasterList.js
 ┃ ┃ ┣ 📜Search.js
 ┃ ┃ ┣ 📜SelectFeatureCategory.js
 ┃ ┃ ┣ 📜SelectIssueCategory.js
 ┃ ┃ ┣ 📜ThemeList.js
 ┃ ┃ ┗ 📜VideoList.js
 ┃ ┣ 📜App.js
 ┃ ┗ 📜Page404.js
 ┣ 📂routes
 ┃ ┗ 📜route.js                 // 페이지 파일 및 해당 페이지에 맞는 uri가 담겨있는 파일입니다. (가장 먼저 분석해야 할 파일)
 ┣ 📂styles
 ┃ ┣ 📜fonts.css                
 ┃ ┣ 📜style.css                // 리액트 라이브러리 사용시 css 변경이 필요할 때가 있는데, 거기에 사용되는 css 파일입니다.
 ┃ ┗ 📜theme.js                 // 자주 쓰이는 스타일을 저장하는 파일입니다.
 ┣ 📜index.js
 ┣ 📜reportWebVitals.js
 ┣ 📜setupProxy.js              // 백엔드 프록시 파일입니다.
 ┗ 📜setupTests.js