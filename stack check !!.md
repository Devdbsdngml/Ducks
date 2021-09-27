<h2>stack check !!



- Kotlin + MVVM (100%)
- ViewModel
  뷰모델은 단순히 데이터만 저장하는 것이 아니다
  LifeCycle에 따른 UI 관련 데이터를 저장하고 관리하기 위한 목적으로 나온 것이기 때문에 UI 갱신과 관련된 업데이트 동적이 들어가면 된다(api 호출 등등)
- Repository
  ViewModel에 로직이 많아져서 복잡한 코드를 작성하는 것을 세분화 시키려고 Repository 패턴을 적용할 수 있고 네트워크 처리하는 로직과 db 로직을 또 분리시킬 수 있다
- Retrofit2 + Okhttp3
- LiveData + Data Biding + View Binding + AAC ViewModel + Coroutine
- 
- Glide
- UI
  - ConstraintLayout
  - CoordinatorLayout
  - NestedScrollView
  - RecyclerView(+ Nesting RecyclerView)
  - TapLayout + ViewPager2
- ETC
  - Social Login(kakao, naver, facebook, google)
  - Firebase(FCM, DynamicLink)