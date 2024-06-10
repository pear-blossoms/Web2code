---
layout: default
---
Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

#Overview

Overview. Our Web2Code instruction tuning dataset construction and instruction generation process87
involves four key components: (1) Creation of new webpage image-code pair data: We generated88
high-quality HTML webpage-code pairs following the CodeAlpaca prompt [6] using GPT-3.5 and89
convert them into instruction-following data. (2) Refinement of existing webpage code generation90
data: We transform existing datasets including WebSight [ 22 ] and Pix2Code [ 4] into an instruction-91
following data format similar to LLaVA data [33 ], so they can be used as instruction-following data92
to train MLLMs. (3) Creation of a new text question-answer pair data: We generated a new question-93
answer pair dataset utilizing our new GPT-3.5 generated data from (1) for webpage understanding.94
(4) Refinement of existing webpage understanding data: We refine the WebSRC [ 10] question-answer95
data to improve its quality using the GPT-4. Each component is elaborated in detail as follows

# Data

<table>
    <tr>
        <th>Stage</th> <th>Dataset</th> <th>Number</th> <th>Download</th>
    </tr>
</table>

# Performance

# Examples
<table>
    <tr>
        <td><img src="./sample1.png" width = "1000" alt="sample1"></td>
    </tr>
    <tr>
        <td><img src="./sample2.png" width = "1000" alt="sample2"></td>
    </tr>
    <tr>
        <td><img src="./sample3.png" width = "1000" alt="sample3"></td>
    </tr>
</table>

# Bibtext

# Acknowledgement


## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```

