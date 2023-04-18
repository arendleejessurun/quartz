---
tags: 
created: 2021-10-04, 22:25
modified: 2022-04-29, 12:24
---

# Dataview
- [Github](https://blacksmithgu.github.io/obsidian-dataview/)
- [Dataview Plugin: How To Use This Powerful Obsidian Plugin (With Examples)](https://www.youtube.com/watch?v=7kFEl7Ovsr8)
- [An Introduction to Dataview - Part 1](https://www.youtube.com/watch?v=sEgzrRNkgsE&t=1328s)

I figured out how to solve my [[How to Sit]] page range issue by using a `number(string)` function, particularly `number([page])`.

I figured out how to list the notes I've made on a given day thanks to [this thread](https://forum.obsidian.md/t/query-files-of-the-same-day-in-other-years-with-dataview-plugin/23198). Here is the code:

`LIST
WHERE file.cday.month = date({{date}}).month
AND file.cday.day = date({{date}}).day
AND file.path != this.file.path SORT file.cday desc
SORT file.ctime asc`
