# gitflow_20211109

## 머리말 (Header)
  * # H1 입니다.

  * ## H2 입니다.

  * ### H3 입니다.

  * #### H4 입니다.

  * ##### H5 입니다.

  * ###### H6 입니다.

## 수평선 (Horizon)
  
***

## 개행(New line)

강제개행 문법입니다.  
문장끝의 공백을 통해 개행이 적용됩니다.

단락바꿈 문법입니다.

Enter키를 통해 개행이 적용됩니다.

## 인용구 (BlockQuote)

> 인용구입니다.

>> 인용구안에 인용구를 사용할 수 있습니다.

## 목록 (List)

* 순서가 없는 리스트입니다.
  * 리스트1
  * 리스트2
  * 리스트3

+=* +
+ 순서없음
    - 홍길동
      * 중대장
        + 프로실망러


* 순서가 있는 리스트입니다.
  1. 리스트1
  2. 리스트2
  3. 리스트3

* 상위 리스트1
  * 하위 리스트1
  * 하위 리스트2
    * 하위의 하위 리스트1
    * 하위의 하위 리스트2

* 리스트('*')
+ 리스트('+')
- 리스트('-')


1. 첫번째
1. 두번째
1. 세번째
  


## 코드 (Code)

* 문장속 코드 `example code inline` 삽입 예시입니다.

* 박스형 코드 삽입예시입니다.
```
example code box
```

## 링크

* <https://www.github.com>
* [Github](https://www.github.com)

## 강조

* 강조 문법 **강조된 부분** 예시입니다.

## 이미지

![예시 이미지](https://raw.githubusercontent.com/ByungJun25/Wiki/master/Markdown/example_image.jpg)


 


```
 #!/bin/bash

## 도움말 출력하는 함수
help() {
        echo "splt [OPTIONS] FILE"
                echo "    -h         도움말 출력."
                echo "    -a ARG     인자를 받는 opt."
                echo "    -b ARG     인자를 받는 opt2."
                exit 0
}
while getopts "a:b:h" opt
do
case $opt in
a) arg_a=$OPTARG
echo "Arg A: $arg_a"
;;
b) arg_b=$OPTARG
echo "Arg B: $arg_b"
echo "$arg_b"
;;
h) help ;;
?) help ;;
esac
done



출처: https://systemdesigner.tistory.com/17 [System Designer]
```

|제목|내용|설명|
|-----|---|---|
|테스트1|테스트2|테스트3|
|테스트1|테스트2|테스트3|
|테스트1|테스트2|테스트3|



![고양이](https://user-images.githubusercontent.com/94296757/142394490-4152f9c0-8d93-48b1-b79d-ec05a55b92f6.jpg)

!<img src="https://user-images.githubusercontent.com/94296757/142394490-4152f9c0-8d93-48b1-b79d-ec05a55b92f6.jpg" width="30%" height = "30%">



[Chosun] (http://www.chosun.ac.kr)

[Chosun](http://www.chosun.ac.kr "Chosun University")


*기울임*
**굵게**
***굵고 기울임***

* fruit
  * Banana
  * Apple
  * Mango
  * Watermelon
    * Water

```c
 #include <stdio.h>
 
 int main(void)
 {
  printf("Hello World\n");
  return 0;
 }
 ```
```python

import numpy as np
ar = np.zeros([3,255,255])
print(ar.shape)

```

 
