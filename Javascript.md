## 20220331

map함수 

```
var devi = [op_dnn_deviation.series[0].data.map(x => x.value)];
```

## 20220408

### 선택한 selectbox의 인덱스 값 알아내기

1. 자바스크립트를 이용한 방법 
```var x = document.getElementById("SelectBoxId").selectedIndex;

var y = document.getElementById("SelectBoxid").options;

var idx = y[x].index;

console.log("선택한 index : " + idx); 

```
2. 제이쿼리를 이용한 방법

```var idx = $("#SelectBoxId option").index( $("#SelectBoxId option:selected") );

console.log("선택한 index : " + idx);```



출처: https://freehoon.tistory.com/79 [훈잇 블로그]
