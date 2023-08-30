# Markdown Communication

# [0] - What is markdown?
`Markdown` is a lightweight markup language used to quickly format information in a prettified format: It uses a series of special characters and HTML-like tags to accomplish this goal.

# [1] - Headers
`Headers` are typically used to define the start of a new context of information. For example, headers are used for titles, category names, and important lists -- to name a few. Headers are defined using `#` hashtags, which can be used to change the size of the header font: decreasing the size as more are added -- up to 6 total (`######`). If a line only contains a single `#`, it will be turned into a divisor line:
#
* # # Heading 1
* ## ## Heading 2
* ### ### Heading 3
* #### #### Heading 4
* ##### ##### Heading 5
* ###### ###### Heading 6

#### Note: `**bold print**` is a bit smaller than `### Heading 3` and a bit larger than `#### Heading 4`

# [2] - Images
### Images can be added to Markdown using the syntax:
```md
![imageSummary](imageUrl)
```
#### Note: `[imageSummary]` is used as an alternative to the actual picture if the intended image fails to load/initialize -- not as a caption (serves as an HTML `alt` attribute)
#
### Practical example:
```md
![Picture of Elevator](https://static.wikia.nocookie.net/callofduty/images/a/af/Hotel_Elevator_A.jpg/revision/latest/scale-to-width-down/1200?cb=20110612115210)
```
![Picture of Elevator](https://static.wikia.nocookie.net/callofduty/images/a/af/Hotel_Elevator_A.jpg/revision/latest/scale-to-width-down/1200?cb=20110612115210)

# [3] - Code
Markdown has powerful support for code snippets -- for both `block` and `in-line` formats. 

`In-line` snippets are defined using `` ` `` backticks. These snippets are mainly used to emphasize variable names, keybinds, and vocabulary -- as they do not support language-based syntax highlighting. In-line snippets use the following syntax:
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

# [4] - Task Lists
`Task lists` are checkbox-based lists that can be used to track the completion of various tasks. Task lists use the following syntax:
```md
- [ ] Incomplete Task
- [x] Completed Task
```

The `[]` brackets are used to track the state of our list. An empty pair `[ ]` means the task is incomplete -- **note that empty pairs MUST contain a space between them to be properly evaluated**. A pair of brackets containing an x `[x]` indicates that the task has been completed.

### Example:
```md
- [x] Start learning Markdown!
- [x] Take a weirdly-structured course!
- [ ] Retain the information!
```
### Translates to:
- [x] Start learning Markdown!
- [x] Take a weirdly-structured course!
- [ ] Retain the information!
