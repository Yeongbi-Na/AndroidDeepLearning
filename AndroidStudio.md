### View와 View Group
1. View: 화면에 보이는 버튼, 텍스트 등 각각을 의미. control이나 위젯이라 불리는 UI구성요소
2. View Group:  여러개의 뷰들을 포함한 것. 뷰에서 상속해 뷰가 되며, 위의 뷰는 눈에 보이지 않는 영역도 포함 
3. 위젯: 뷰 중에서 일반적인 컨트롤 역할 하는 것(버튼 텍스트 등)
4. 레이아웃: 뷰 그룹 내부 뷰들을 포함하고 있고 그걸 배치하는 역할
 ![image](https://user-images.githubusercontent.com/61492320/213085079-be640b61-fab6-4b78-8ec0-b48ba606bdd5.png)

### 상속
- 부모 특성을 그대로 물려받아서 변수나 메소드 재사용
- 자바에서 extends 로 AppcompatActivity를 상속해서 MainActivity를 만들었음
```
  public class MainActivity extends AppCompatActivity
```
- 나 자신은 this, 부모는 super 

### XML 태그 
- 태그 + 속성값
- <TextView>, <android.support.contraint.~~>처럼 .은 패키지를 표현한 것
  

