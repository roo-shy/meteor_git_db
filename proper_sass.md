## Styles structure - best practices

#### Optional
- two (2) spaces indents, no tabs
- ideally, 80-characters wide lines or less
- meaningful use of whitespace
- use comments to explain CSS operations

- [Methodologies](http://www.hongkiat.com/blog/css-writing-methodologies/)


### Indentation, Nesting and Looping:

#### Nesting: 

- Never go more than 3 levels deep
- Ensure the CSS output is clean and reusable
- Use nesting when it makes sense, not as a default option

```

body {
}
  .wrapper {
  }
    .content {
    }
      #top-story {
      }
        .title {
          a {
            /* STYLES HERE */
          }
        }
    .sidebar {
    }
      .widgets {
        hr {
        }
      }
    footer.main {
    }
  ```

#### Looping:

[CSS Modules](http://clubmate.fi/for-while-and-each-loops-in-sass/)

### ModuleEverything:

[CSS Modules](https://glenmaddern.com/articles/css-modules)
[The Pros and Cons of Modular Sass](http://blog.planetargon.com/entries/the-pros-and-cons-of-modular-sass)

### Mixins:



### Variables: 

- Grid
- Base Typography
- Breakpoints
- Colors

### Tools:

- grunt 
- gulp

- [ ] Add basic structure
- [ ] Add mixins usage
