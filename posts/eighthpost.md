---
title: This is my eighth post.
description: This is a post on My Blog about code learning.
date: 2022-08-22
tags:
  - second tag
  - posts with two tags
layout: layouts/post.njk
---
::I had the idea to create old school design snippets and to learn markdown:: **I’m did 2 minutes of React** 🏝 how to open a file from the command line in VS Code is 
```bash
	code styles.css
```
to use the code command you have to first install the code command by pressing Shift Cmd P in VS code, and type « shell command » and select Install ‘code’ command in PATH. 

Idea: a database for oldschool internet styles

```py
	new_list = this_list.copy
	l = l[:]
```

```py
def bubblesort_once(l):
    if len(l) < 2: return l[:]
    
    lst, mx = [], l[0]
    for v in l[1:]:
        if mx<v: mx,v = v,mx
        lst.append(v)
    lst.append(mx)
    return lst
```

# day post
```javascript
	const billboard = (name, price = 30) => +(name.length / (1 / price))
```

Found this solution on codewars to a puzzle. I will collect solutions, I might look back at them and see if I get to understand them better. 🥑
