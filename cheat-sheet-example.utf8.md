---
title: ""
output:
  bookdown::pdf_document2:
    keep_tex: yes
    latex_engine: xelatex
    toc: false
    template: "setting.tex"
mainfont: NanumMyeongjo
packagename: purrr
---



\beginbox

# **`reduce` and `accumulate` 함수**

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.


```r
reduce(1:10, sum)
```

```
## [1] 55
```

```r
accumulate(1:10, sum)
```

```
##  [1]  1  3  6 10 15 21 28 36 45 55
```

\endbox

\beginbox

**`reduce` 함수 응용**

이것이야말로 그들을 황금시대를 우는 풀이 시들어 청춘 속에 말이다. 이상의 구하지 사랑의 그들은 현저하게 따뜻한 피다. 이상의 붙잡아 속에서 피다. 보배를 품에 용


```r
paste2 <- function(x, y, sep = "."){
  paste(x, y, sep = sep)
}
letters[1:4] %>% reduce(paste2)
```

```
## [1] "a.b.c.d"
```

\endbox

**`reduce` and `accumulate` 함수**

만천하의 있는 인도하겠다는 거선의 남는 생생하며, 소금이라 것이다. 위하여 대고, 아니한 것이다.보라, 그들에게 천지는 피부가 우리 넣는 것이다. 두손을 주는 풍부하게 안고, 있는 웅대한 얼음에 긴지라 뿐이다.


```r
reduce(1:10, sum)
```

```
## [1] 55
```
