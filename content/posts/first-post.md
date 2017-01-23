---
title: 'First Post, no hero.'
date: 2016-01-22T00:00:00.000Z
layout: Post
---

This is the first post

dsfdsafsdfasdfasdf

Code is highlighted by default.

    const StatelessComponent = (props) => {
      return (
        <div>
          I‘m a stateless component that accepts children
          { props.children }
        </div>
      )
    }
    
    // ...
    
      return (
        <StatelessComponent>
          Example of child
        </StatelessComponent>
      )