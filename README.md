# NavigationDrawer-with-TabBar
NavigationDrawer와 TabBar 백업파일

##다른 코드 들어가서 보기 어지럽기전에 코드 백업 및 설명서.
    
    1)  원하는 항목들을 고쳐줍니다.
            navigation drawer menu - res/menu/nav-item-main
            navigation drawer header - res/layout/nav-header-main
            toolbar - res/layout/toolbar
        
    2)  setItems() 에서 수정된 xml view들의 id 등록.
    
    3)  setViewPager()에서 원하는 Fragments들의 개수만큼 add.
    
    4)  setNavItemListener() 에서 navigationItems들의 OnClickAction 지정.