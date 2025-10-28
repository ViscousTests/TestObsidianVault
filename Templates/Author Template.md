---
category: "[[People]]"
tags:
  - people
  - authors
---
## Books

```dataview
table without id
	file.link ass Title,
	year as Year,
	rating as Rating
where
	contains(category,[[Books]]) and
	contains(author,this.file.link)
sort rating desc
```