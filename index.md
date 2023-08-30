# Markdown Communication

# [0] - What is markdown?
`Markdown` is a lightweight markup language used to quickly format information in a prettified format: It uses a series of special characters and HTML-like tags to accomplish this goal.

# [1] - Headers
`Headers` are typically used to define the start of a new context of information. For example, headers are used for titles, category names, and important lists -- to name a few. Headers are defined using `#` hashtags, which can be used to change the size of the header font: decreasing the size as more are added -- up to 6 total (`######`):
* # Heading 1
* ## Heading 2
* ### Heading 3
* #### Heading 4
* ##### Heading 5
* ###### Heading 6

#### Note: **Bold print** is just smaller than Heading 3 (`###`)

# [2] - Images
### Images can be added to Markdown using the syntax:
### ![`brief image summary`](`image url`)
#### Note: `[brief image summary]` is used as an alternative to the actual picture if the intended image fails to load/initialize -- not as a caption.
#
### Practical example:
### `![Picture of Elevator](https://static.wikia.nocookie.net/callofduty/images/a/af/Hotel_Elevator_A.jpg/revision/latest/scale-to-width-down/1200?cb=20110612115210)`
![Picture of Elevator](https://static.wikia.nocookie.net/callofduty/images/a/af/Hotel_Elevator_A.jpg/revision/latest/scale-to-width-down/1200?cb=20110612115210)

# [3] Code
Markdown has powerful support for code snippets -- for both `block` and `in-line` formats. 

`In-line` snippets are defined using `` ` `` backticks. These snippets are mainly used to emphasize variable names, keybinds, and vocabulary -- as they do not support language-based syntax highlighting.
`` `System.out.println("Hello, World!")` `` 🠊 `System.out.println("Hello, World!")`

`Block` snippets are single- or multi-line sets of code that support explicit language definition with automatic syntax highlighting. Block statements use the following syntax:
```md
```languageName
textContent
textContent
textContent
```⠀
```

### Example:
```
```java
class Markdown {
    public static void main(String[] args)
    {
        System.out.println("Hello, World!");
    }
}
```⠀
```
### Translates to:
```java
class Markdown {
    public static void main(String[] args)
    {
        System.out.println("Hello, World!");
    }
}
```
