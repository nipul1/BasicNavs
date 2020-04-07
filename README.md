# BasicNavs
Step by step guide on how to create Navigation drawer app using fragments
1) create a basic android app with empty activity 
2) we need some essential files to be created first these files are as follows  
  a) menu file (drawer_menu) // android resource file in res folder 
  b) drawer_header  // design it accordingly give it a fixed width 
  c) drawer_toolbar // make Toolbar view(make sure it is AppCompatWidgetToolbar) with height attribute for this as attr/actionBarSize
  d) add a frame layout to contain fragments 
3) come to activity_main 
4) change constraint layout to drawer_layout 
5) <include
      set height, width, id, and layout reference as drawer_toolbar  
    >
6) <include
      contain_view layout 
    >
7) add NavigationView
        set app:menu as drawer_menu
        set app:header as drawer_header
        set layout_gravity as start
        set fitsSystemWindows as true
        
  
