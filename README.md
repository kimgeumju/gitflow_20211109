# gitflow_20211109


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


 
 
