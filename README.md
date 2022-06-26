# kokojong_TIL

- 22.06.19(sun) : 블로그 글 작성 [RxMoya(Moya) ErrorHandling 해보기(feat. Repository Pattern)](https://kokojong.tistory.com/22)
- 22.06.21(tue) : 블로그 글 작성 [CollectionView, TableView 내의 UIView에 TapGesture 추가하기](https://kokojong.tistory.com/23)
- 22.06.26(sun) : 블로그 글 작성 [[iOS/Swift] catchError로 error 처리하기](https://kokojong.tistory.com/24)


# 새싹 귀환

### Push / Modal 방식의 생명주기 차이
- A -> B로 이동한다고 가정하면 Push는 A의 viewWillDisappear, viewDidDisappear가 호출된다. 그러나 Modal방식은 새로운 뷰를 덮는 방식이기 때문에 A의 viewWillDisappear, viewDidDisappear가 호출되지 않는다.

[TabBarController와 NavigationController의 생명주기 차이](https://github.com/kokojong/kokojong_TIL/issues/1)  
