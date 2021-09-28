# testrepository
연습용 리퍼지토리 입니다.


## subtitle

  -  첫 번째 : first
  -  두 번째 : second
  -  세 번째: third

![github](https://user-images.githubusercontent.com/87646049/135098737-39a5dc8e-2bc2-4cdb-bfe4-63169c1f718c.png)



## 예제 연습
  > https://www.markdowntutorial.com/kr/lesson/1/


## 1. 이탤릭체와 볼드체

### 1-1) 이탤릭체

마크다운으로 이탤릭체 를 사용하기 위해서 여러분은 글자의 바깥쪽에 밑줄(_)을 추가하면 됩니다. 
예를 들어, _이것_은 이탤릭체 가 됩니다.
다음 강의로 넘어가기 위해서, 아래 "not"란 단어를 이탤릭체로 만들어보세요.

    Writing in Markdown is _not_ that hard!


### 1-2) 볼드체

비슷하게, 마크다운에서 볼드체를 사용하기 위해서, 여러분은 글자의 바깥쪽에 별표( ** )를 추가하면 됩니다. **정말** 이런식으로요.
아래 입력 창에서, "will"란 단어에 볼드체를 입혀보세요.

    I **will** complete these lessons!


### 1-3) 이탤릭체 & 볼드체 한줄에

물론 여러분은 한 줄(line)에 _이탤릭체와 볼드체_를 사용할 수 있습니다. 다음과 같이 범위를 넓혀서 사용할 수 있구요. **여러 단어들이 가능하다!**.
아래 입력 창에서, "Of course"를 이탤릭체로, "a little moxie"를 볼드체로 만들어보세요.

    "_Of course_," she whispered. Then, she shouted: "All I need is **a little moxie**!"


### 1-4) 이탤릭체 & 볼드체 모두 적용

이번 강의의 마지막 연습문제로 우리는 볼드체와 이탤릭체 를 모두 적용한 단어를 만들 것 입니다.
일반적으로 별표와 밑줄을 어느 순서로 배열하든지 상관없습니다. 아래 입력 창에서, "This is unbelievable"란 문장을 볼드체와 이탤릭체로 만들어보세요. 별표를 **_바깥쪽에_** 배치하여 좀 더 읽기 쉽게 만들어주세요.

    If you're thinking to yourself, **_This is unbelievable_**, you'd probably be right.


## 2. 헤더

마크다운에서 헤더를 만들기 위해, 여러분은 해쉬 마크(#)를 문단 앞에 사용하면 됩니다. 여러분은 여러분이 원하는 헤더 사이즈 크기만큼 해쉬 마크 갯수를 늘려 사용하면 됩니다. 예를 들어, 헤더 1을 사용하기 위해 해쉬 마크(# 헤더 1)를 한 개 사용할 수 있습니다. 헤더 3을 사용하기 위해 해쉬 마크(### 헤더 3)를 세 개를 사용할 수 있습니다.
다음 강의로 넘어가기 위해서, 각 헤더를 알맞은 사이즈로 만들어보세요.

    # Header one
    ## Header two
    ### Header three
    #### Header four
    ##### Header five
    ###### Header six


## 3. 링크
이제 우리는 www(world wide web)의 다른 웹사이트에 링크하는 방법을 배울 것입니다.
마크다운에는 두 가지 링크 유형이 있지만, 두 링크 유형 모두 정확히 같은 방식으로 렌더링됩니다. 

### 3-1) 인라인 링크

첫 번째 링크 스타일은 인라인 링크라고 불립니다. 인라인 링크를 만들기 위해선, 여러분은 링크할 텍스트를 대괄호( [ ] )로 싼 다음, 링크할 주소를 소괄호로( ( ) )로 감싸면 됩니다. 예를 들어, Github 방문!이란 텍스트에 www.github.com로 링크되는 하이퍼링크를 만들고자 하면, 여러분은 마크다운으로 이렇게 작성하면 됩니다. [GitHub 방문!](www.github.com).

아래 입력 창에서, "Search for it."란 텍스트에 www.google.com로 링크되도록 링크를 만들어보세요.

    [Search for it.](www.google.com)


여러분이 원한다면 링크된 텍스트에 볼드체를 추가할 수 있습니다. 아래 입력 창에서, "really, really"를 볼드체로, 전체 문장이 www.dailykitten.com로 링크되도록 만들어보세요. 볼드체가 링크 대괄호 안에서 발생하는지 확인해보세요.

    [You're **really, really** going to want to see this.](www.dailykitten.com)


헤더에도 링크를 만들 수 있습니다.
다음 연습문제로 가기 위해, 아래 문장을 헤더 4로 만들고 "the BBC"를 www.bbc.com/news로 링크되도록 만들어보세요.

    #### The Latest News from [the BBC](www.bbc.com/news) 


### 3-2) 참조링크

다른 링크 타입은 참조 링크 입니다. 이름에서 알 수 있듯이, 참조 링크는 실제로 문서 내의 다른 위치에 대한 참조를 나타냅니다. 여기 예제가 있습니다:

     여기에 [태그 1][참조 링크1]가 있습니다.
     여기에 [태그 2][참조 링크2]가 있습니다.
     앗, [태그 3][참조 링크1]도 있었네요.

     [참조 링크1]: www.github.com
     [참조 링크2]: www.google.com
  
"참조"는 위에서 두번째로 나타나는 대괄호들을 의미합니다: [참조 링크1]와 [참조 링크2]. 이 대괄호들은 마크다운 문서 하단에 외부 웹 사이트에 대한 적절한 링크로 정의됩니다. 참조 링크 스타일의 장점은 같은 장소에 대한 다중 링크는 한 번만 업데이트하면 된다는 것입니다. 예를 들어 [참조 링크1] 링크를 모두 다른 사이트로 이동시키기로 했다면 우리는 하나의 참조 링크만 변경하면 됩니다.

렌더링된 마크다운에는 참조 링크가 나타나지 않습니다.

참조 링크를 정의하는 방법은 대괄호로 묶은 참조 태그를 작성하고 그 다음에 콜론, 그 다음에 링크할 주소를 작성하면 됩니다.

아래 입력 창에서, 우리는 몇몇 참조 링크들을 작성하려 합니다. 이것을 해결해야 다음 강의로 넘어가는 것 아시죠? 첫 번째 참조 태그를 "a fun place"로 정의하고, www.zombo.com에 연결하세요. 두 번째 참조 태그 "another fun place"를 www.stumbleupon.com로 링크되도록 만들어보세요.

    Do you want to [see something fun][a fun place]?
    Well, do I have [the website for you][another fun place]!

    [a fun place]: www.zombo.com
    [another fun place]: www.stumbleupon.com



## 4. 이미지

여러분이 마크다운에서 링크를 사용할 줄 안다면, 이미지도 사용할 수 있습니다. 두 문법이 거의 동일합니다.

이미지 또한 두 가지 타입이 존재합니다. 링크처럼 두 타입 모두 렌더링 되는 방식은 같습니다. 링크와 이미지의 차이는 이미지는 앞에 느낌표를 사용합니다. ( ! ).


### 4-1) 인라인 이미지 링크

첫번째 이미지 타입은 인라인 이미지 링크라 부릅니다. 인라인 이미지 링크를 사용하기 위해 느낌표를 입력하고 ( ! ), 대괄호로 ( [ ] ) 대체 텍스트(Alt Text)를 감싼 다음, 소괄호로 ( ( ) ) 링크를 감싸면 됩니다. (대체 텍스트는 시각 장애인들을 위한 문단 혹은 문장입니다.)

예를 들어, https://octodex.github.com/images/bannekat.png에 대한 이미지 링크와 Benjamin Bannekat란 대체 텍스트를 생성하려 할 때, 여러분은 마크다운에서 이렇게 사용하시면 됩니다: 

    ![Benjamin Bannekat](https://octodex.github.com/images/bannekat.png)


아래 입력 창에서, 이미지 링크로 바꾼 후, 대체 텍스트를 "A pretty tiger"로 바꿔보세요:

    ![A pretty tiger](https://upload.wikimedia.org/wikipedia/commons/5/56/Tiger.50.jpg)   
![A pretty tiger](https://upload.wikimedia.org/wikipedia/commons/5/56/Tiger.50.jpg)

비록 여러분이 대체 텍스트를 필요 로 하지 않아도, 시각 장애가 있거나, 스크린 리더를 사용하거나, 고속 인터넷 연결이 없는 사람들을 포함하여 여러분의 청중들이 여러분의 컨텐츠에 접근할 수 있게 할 것입니다.

### 4-2) 참조 이미지 링크

문장 앞에 느낌표를 사용 후 대체 텍스트에 대괄호를 사용하고 이미지 태그에 대괄호를 사용하면 됩니다, 이렇게요: 

    ![The founding father][Father] 
    
마크다운 페이지 맨 하단에 이미지 태그를 정의하면 됩니다, 이렇게요: 

    [Father]: http://octodex.github.com/images/founding-father.jpg.

아래 입력 창에서, 우리는 참조 이미지를 사용하고자 합니다. 지난 강의처럼 이것을 해결해야 다음 강의로 넘어가는 것 아시죠? "Black"이란 이미지 태그로 https://upload.wikimedia.org/wikipedia/commons/a/a3/81_INF_DIV_SSI.jpg 이미지 링크를 만들어주세요. 두번째 이미지 링크는 http://icons.iconarchive.com/icons/google/noto-emoji-animals-nature/256/22221-cat-icon.png 이미지 링크로 만들어주세요.

    ![Black cat][Black]
    ![Orange cat][Orange]

    [Black]: https://upload.wikimedia.org/wikipedia/commons/a/a3/81_INF_DIV_SSI.jpg
    [Orange]: http://icons.iconarchive.com/icons/google/noto-emoji-animals-nature/256/22221-cat-icon.png


## 5. 인용문

만일 여러분이 다른 출처의 인용문을 언급하거나 잡지 기사의 인용문을 디자인해야 한다면, 마크다운의 인용문 (blockquote) 구문이 유용할 것입니다. 인용문은 독자들의 주의를 끌기 위해 특별히 포맷된 문장 또는 단락입니다.


### 5-1) 인용문 기본

인용문을 사용하기 위해서, 여러분이 해야할 것은 문장 앞에 "~보다 큰" 의미를 가진 캐럿 기호 (>)만 붙여주면 됩니다. 예를 들면:

    > "잠시 후 그는 맨발로 양말을 주머니에 넣고 캔버스 신발이 어깨 위로 매듭지어져 있는 끈에 매달려 있었고 
     바위들 사이에서 제담에서 뾰족한 소금 먹은 막대기를 골라 방파제의 비탈을 기어내려갔다."
     
아래 입력창에서, 인용구에 인용문을 적용시켜보세요:

    I read this interesting quote the other day:

    > "Her eyes had called him and his soul had leaped at the call. To live, to err, to fall, to triumph, to recreate life out of life!"
    

### 5-2) 캐럿 기호

여러분은 인용문의 각 줄에 캐럿 기호를 배치할 수도 있습니다. 이것은 여러분의 인용구가 여러 단락에 이르는 경우에 특히 유용합니다. 
예를 들면:

    > 그의 말은 그 자신의 천성적으로 어떤 깊은 화음에 부딪친 것 같았다. 그는 자기 자신에 대해, 있는 그대로 또는 되고 싶은 대로 말하였는가? 
    스티븐은 잠시 동안 말없이 그의 얼굴을 지켜보았다. 차가운 슬픔이 그곳에 있었다. 그는 자신에 대해, 그가 두려워하는 외로움에 대해 이야기했다.
    >
    > —누구한테 말하는 거야? 스티븐이 길게 물었다.
    >
    > 크랜리는 대답하지 않았다.
    
result)
> 그의 말은 그 자신의 천성적으로 어떤 깊은 화음에 부딪친 것 같았다. 그는 자기 자신에 대해, 있는 그대로 또는 되고 싶은 대로 말하였는가? 
스티븐은 잠시 동안 말없이 그의 얼굴을 지켜보았다. 차가운 슬픔이 그곳에 있었다. 그는 자신에 대해, 그가 두려워하는 외로움에 대해 이야기했다.
>
> —누구한테 말하는 거야? 스티븐이 길게 물었다.
>
> 크랜리는 대답하지 않았다.


+ 인용문 내에서 이탤릭체, 이미지, 링크와 같은 다른 마크다운 요소도 사용할 수 있습니다.


## 6. 리스트

리스트 타입은 보통 2가지가 존재합니다. 순서가 매겨지지 않은 것(unordered)과 순서가 매겨진 것(ordered)입니다. 별표(*)로 된 리스트와 숫자로 된 리스트가 존재한다고 말씀드리는게 더 적절한거 같네요.

### 6-1) 별표(*)로 된 리스트

순서가 매겨지지 않은 리스트를 생성하기 위해 여러분은 리스트의 각 항목에 별표( * )를 앞에 붙여주면 됩니다. 또한 각 항목은 자신의 라인을 가지고 있어야 합니다. 예를 들어, 마크다운으로 작성된 식료품 리스트는 다음처럼 작성할 수 있습니다:

    * 우유
    * 계란
    * 연어
    * 버터

result)
* 우유
* 계란
* 연어
* 버터


### 6-2) 순서가 매겨진 리스트

순서가 매겨진 리스트는 별표(*)대신에 숫자를 붙이면 됩니다. 아래에 요리법을 보세요:

    1. 보울 위에 계란 세 개를 깨뜨린다
    2. 우유 3.7L를 보울에 붓는다
    3. 버터를 힘차게 연어에 문지른다
    4. 연어를 우유,계란을 쏟은 보울에 넣는다
    
result)
1. 보울 위에 계란 세 개를 깨뜨린다
2. 우유 3.7L를 보울에 붓는다
3. 버터를 힘차게 연어에 문지른다
4. 연어를 우유,계란을 쏟은 보울에 넣는다

### + 

예상했다시피, 여러분은 리스트 안에 이탤릭체, 볼드체, 링크를 추가할 수 있습니다. 아래 입력창에서, 식물의 라틴어 이름을 이탤릭체로 바꿔보세요.

    * Azalea (_Ericaceae Rhododendron_)
    * Chrysanthemum (_Anthemideae Chrysanthemum_)
    * Dahlia (_Coreopsideae Dahlia_)
    
result)
* Azalea (_Ericaceae Rhododendron_)
* Chrysanthemum (_Anthemideae Chrysanthemum_)
* Dahlia (_Coreopsideae Dahlia_)


### 6-3) 리스트 & 리스트

때로는 좀 더 깊이 있는 리스트를 만들거나, 리스트에 다른 리스트를 겹쳐서 만들 수도 있습니다. 겁먹지 마세요. 마크다운 구문은 거기서 거깁니다. 여러분이 해야할 것은 앞의 항목보다 공백 한 칸 을 별표(*) 앞에 더 들여놓으면 됩니다.

예를 들어, 하기 리스트에서 우리는 각 항목에 몇 개의 하위 항목을 추가할 것입니다. 인물에 대해 상세히 묘사해보자면:

    * 틴틴
     * 기자
     * 얼간이 같은 주황색 머리
     * 세상에서 제일 멋진 개와 친구들
    * 햅덕
     * 선장
     * 멋진 턱수염
     * 위스키 좋아함
       * 아마 스카치도?
       
result)
* 틴틴
 * 기자
 * 얼간이 같은 주황색 머리
 * 세상에서 제일 멋진 개와 친구들
* 햅덕
 * 선장
 * 멋진 턱수염
 * 위스키 좋아함
   * 아마 스카치도?

여러분이 무한적으로 하위 리스트를 추가할 수 있지만, 대개는 3단계까지만 사용하는 것이 좋습니다. 그렇지 않으면, 여러분의 텍스트는 엉망진창이 될 것입니다.


## 7. 단락

마크다운은 단락을 포맷하는 몇 가지 방법이 있습니다.  

몇 줄의 시로 예를 들어볼게요. 여러분이 이런 형태의 글을 쓰기 원한다고 해봅시다:

    나는 나 자신과 모순되는가?
    그렇다면 아주 잘되었다… 나는 나 자신과 모순이다,
    (나는 크다… 나는 다량의 것을 품고 있다.)

여러분은 각 구절마다 자신의 라인을 가지면 문제가 해결될거라 생각할지 모릅니다:  
아쉽게도 그 생각은 틀렸습니다! 마크다운은 단순히 하나의 직선으로 렌더링합니다:  

    나는 나 자신과 모순되는가? 그렇다면 아주 잘되었다… 나는 나 자신과 모순이다, (나는 크다… 나는 다량의 것을 품고 있다.)

### 7-1) 문단 나눔 : hard breaks

개행을 강제로 넣으면, 결합이 깨지게 됩니다:

    나는 나 자신과 모순되는가?

    그렇다면 아주 잘되었다… 나는 나 자신과 모순이다,

    (나는 크다… 나는 다량의 것을 품고 있다.)

### 7-2) 줄 나눔 : soft breaks

여러분은 각 줄의 끝에 2번의 공백을 넣음으로 줄 나눔을 할 수 있습니다. 공백은 눈에 보이지 않아 실제로 보기는 어렵지만, 이렇게 보여질 수 있습니다:

    나는 나 자신과 모순되는가?··
    그렇다면 아주 잘되었다… 나는 나 자신과 모순이다,··
    (나는 크다… 나는 다량의 것을 품고 있다.)


## Conclusion

여러분은 모든 레슨을 끝냈습니다!

믿으실지 모르겠지만, 우리는 이제 막 마크다운으로 이뤄낼 수 있는 것들에 대한 탐험을 시작한 셈입니다. 테이블, 정의된 리스트, 각주 등 마크다운의 “확장된” 구현들이 정말 많습니다. 그것들은 표준이 아니기 때문에, 우리가 여기에서 소개한 기본적인 개념을 배우는데 필수는 아니었습니다.

만약 여러분이 이같은 마크다운 구현에 대해 더 알고 싶으시면, 수 많은 마크다운 앱과 튜토리얼들을 보시면 됩니다. 여기에 몇 가지 링크를 소개합니다:

https://daringfireball.net/projects/markdown/

https://spec.commonmark.org/dingus/

https://johnmacfarlane.net/babelmark2/faq.html

https://www.markdownguide.org

https://dave.autonoma.ca/blog/2019/05/22/typesetting-markdown-part-1/

http://idratherbewriting.com/2013/06/04/exploring-markdown-in-collaborative-authoring-to-publishing-workflows/

https://en.wikipedia.org/wiki/Markdown#Example

https://docs.gitlab.com/ee/user/markdown.html

https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax



## 향후 계획

테이블 만드는 법 공부

Readme.md 파일의 텍스트 간격 조정 필요

