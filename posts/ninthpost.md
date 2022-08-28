---
title: This is my ninth post.
description: This is a post on My Blog about code learning.
date: 2022-08-28
tags:
  - second tag
  - posts with two tags
layout: layouts/post.njk
---
##day writing
I like that by the end of the day I woke up to continuing the q2 activities. I applied to a number of places for apprenticeships. The application process messes with my dopamine. I continued the Khan academy math courses. I am studying sporadically. It is fun.

I had the idea to create a gallery for my abstract paintings, and other paintings and drawings, perhaps with a shop, and a ship. 

```javascript
function MyCard() {
          const imageFlex = (num) => {
            let result = []
            for (let i = 0; i < num; i++) {
              result.push(<div className="image-div" />)
            }
          }
          return (
            <div className="one-card">
              {result.map(e => e)}  
            </div>
          );
        }
```

I have a bug in this code, I am learning how to display multiple elements inside the return statement. First I will simplify the code so that I can see what is displayed from the result variable. How to save stuff in React to a variable. Is it a string or an array, or the mapping of an array, how the HTML tags work with React and JSX. The following works:

```javascript
function MyCard() {
        let result = <p>🏄🏻</p>
          return (
            <div className="one-card">
              {result}
            </div>
          );
        }
```