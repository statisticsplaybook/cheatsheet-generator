
# [Statistics playbook](https://www.youtube.com/c/statisticsplaybook) Cheatsheet Generator

[슬기로운 통계생활](https://www.youtube.com/c/statisticsplaybook) 컨닝페이퍼 생성기


To use it, include the following in the YAML header of your Rmarkdown file.

```
---
output:
  bookdown::pdf_document2:
    latex_engine: xelatex
    toc: false
    template: "setting.tex"
mainfont: NanumMyeongjo
packagename: 패키지명
---
```