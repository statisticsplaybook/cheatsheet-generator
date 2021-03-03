
# [Statistics playbook](https://www.youtube.com/c/statisticsplaybook) Cheatsheet Generator

[슬기로운 통계생활](https://www.youtube.com/c/statisticsplaybook) 컨닝페이퍼 생성기


To use it, include the following in the YAML header of your Rmarkdown file. (문서 설정부분은 다음과 같이 해주시면 됩니다.)

```
---
output:
  bookdown::pdf_document2:
    latex_engine: xelatex
    toc: false
    template: "setting.tex"
mainfont: NanumMyeongjo
packagename: packagename
---
```

## Compact Result

* Use `\bcolorbox` and `\ecolorbox` indicating the begin and end of the box.

![](./example.jpg)
