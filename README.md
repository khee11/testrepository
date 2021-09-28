# testrepository
연습용 리퍼지토리 입니다.

## subtitle

  -  첫 번째 : first
  -  두 번째 : second
  -  세 번째: third

## 예제 연습
  > https://www.markdowntutorial.com/kr/lesson/1/


### 1. 이탤릭체와 볼드체

#### 1-1) 이탤릭체

마크다운으로 이탤릭체 를 사용하기 위해서 여러분은 글자의 바깥쪽에 밑줄(_)을 추가하면 됩니다. 
예를 들어, _이것_은 이탤릭체 가 됩니다.
다음 강의로 넘어가기 위해서, 아래 "not"란 단어를 이탤릭체로 만들어보세요.

    Writing in Markdown is _not_ that hard!


#### 1-2) 볼드체

비슷하게, 마크다운에서 볼드체를 사용하기 위해서, 여러분은 글자의 바깥쪽에 별표( ** )를 추가하면 됩니다. **정말** 이런식으로요.
아래 입력 창에서, "will"란 단어에 볼드체를 입혀보세요.

    I **will** complete these lessons!


#### 1-3) 이탤릭체 & 볼드체 한줄에

물론 여러분은 한 줄(line)에 _이탤릭체와 볼드체_를 사용할 수 있습니다. 다음과 같이 범위를 넓혀서 사용할 수 있구요. **여러 단어들이 가능하다!**.
아래 입력 창에서, "Of course"를 이탤릭체로, "a little moxie"를 볼드체로 만들어보세요.

    "_Of course_," she whispered. Then, she shouted: "All I need is **a little moxie**!"


#### 1-4) 이탤릭체 & 볼드체 모두 적용

이번 강의의 마지막 연습문제로 우리는 볼드체와 이탤릭체 를 모두 적용한 단어를 만들 것 입니다.
일반적으로 별표와 밑줄을 어느 순서로 배열하든지 상관없습니다. 아래 입력 창에서, "This is unbelievable"란 문장을 볼드체와 이탤릭체로 만들어보세요. 별표를 **_바깥쪽에_** 배치하여 좀 더 읽기 쉽게 만들어주세요.

    If you're thinking to yourself, **_This is unbelievable_**, you'd probably be right.


### 2. 헤더

마크다운에서 헤더를 만들기 위해, 여러분은 해쉬 마크(#)를 문단 앞에 사용하면 됩니다. 여러분은 여러분이 원하는 헤더 사이즈 크기만큼 해쉬 마크 갯수를 늘려 사용하면 됩니다. 예를 들어, 헤더 1을 사용하기 위해 해쉬 마크(# 헤더 1)를 한 개 사용할 수 있습니다. 헤더 3을 사용하기 위해 해쉬 마크(### 헤더 3)를 세 개를 사용할 수 있습니다.
다음 강의로 넘어가기 위해서, 각 헤더를 알맞은 사이즈로 만들어보세요.

    # Header one
    ## Header two
    ### Header three
    #### Header four
    ##### Header five
    ###### Header six


### 3. 링크
이제 우리는 www(world wide web)의 다른 웹사이트에 링크하는 방법을 배울 것입니다.
마크다운에는 두 가지 링크 유형이 있지만, 두 링크 유형 모두 정확히 같은 방식으로 렌더링됩니다. 

#### 3-1) 인라인 링크

첫 번째 링크 스타일은 인라인 링크라고 불립니다. 인라인 링크를 만들기 위해선, 여러분은 링크할 텍스트를 대괄호( [ ] )로 싼 다음, 링크할 주소를 소괄호로( ( ) )로 감싸면 됩니다. 예를 들어, Github 방문!이란 텍스트에 www.github.com로 링크되는 하이퍼링크를 만들고자 하면, 여러분은 마크다운으로 이렇게 작성하면 됩니다. [GitHub 방문!](www.github.com).

아래 입력 창에서, "Search for it."란 텍스트에 www.google.com로 링크되도록 링크를 만들어보세요.

    [Search for it.](www.google.com)


여러분이 원한다면 링크된 텍스트에 볼드체를 추가할 수 있습니다. 아래 입력 창에서, "really, really"를 볼드체로, 전체 문장이 www.dailykitten.com로 링크되도록 만들어보세요. 볼드체가 링크 대괄호 안에서 발생하는지 확인해보세요.

    [You're **really, really** going to want to see this.](www.dailykitten.com)


헤더에도 링크를 만들 수 있습니다.
다음 연습문제로 가기 위해, 아래 문장을 헤더 4로 만들고 "the BBC"를 www.bbc.com/news로 링크되도록 만들어보세요.

    #### The Latest News from [the BBC](www.bbc.com/news) 


#### 3-2) 참조링크

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


