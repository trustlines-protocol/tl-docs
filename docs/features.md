---
title: Trustlines Docs Features
---

## Basic

!!! quote ""
    ## Bold

    For **bold text**, the text is enclosed in two asterisks `**...**`.

    ```
    **Lorem ipsum dolor sit amet**, consectetur adipiscing elit.
    ```

    !!! success "Result"

        **Lorem ipsum dolor sit amet**, consectetur adipiscing elit.

!!! quote ""
    ## Italic

    For _italic text_, the text is enclosed in underlines `_..._`.

    ```
    _Lorem ipsum dolor sit amet_, consectetur adipiscing elit.
    ```

    !!! success "Result"

        _Lorem ipsum dolor sit amet_, consectetur adipiscing elit.

!!! quote ""
    ## Underlined

    For ^^underlined text^^, the text is enclosed in two carets `^^...^^`.

    ```
    ^^Lorem ipsum dolor sit amet^^, consectetur adipiscing elit.
    ```

    !!! success "Result"

        ^^Lorem ipsum dolor sit amet^^, consectetur adipiscing elit.

!!! quote ""
    ## Strikethtough

    For ~~strikethtough text~~ the text is enclosed in two tildes `~~...~~`.

    ```
    ~~Lorem ipsum dolor sit amet~~, consectetur adipiscing elit.
    ```

    !!! success "Result"

        ~~Lorem ipsum dolor sit amet~~, consectetur adipiscing elit.

!!! quote ""
    ## Headings

    Headings use the `# hash` sign

    One `# hash` sets the page title

    The 2nd level heading, `##` is the first level of heading in the body.

    !!! example "Example"
        ```
        ## Headings
        ### The 3rd level
        #### The 4th level
        ##### The 5th level
        ###### The 6th level
        ```

        ### The 3rd level

        #### The 4th level

        ##### The 5th level

        ###### The 6th level

    ## Headings <small>with secondary text</small>

    !!! example "Example"
        ```
        ## Headings <small>with secondary text</small>
        ### The 3rd level <small>with secondary text</small>
        #### The 4th level <small>with secondary text</small>
        ##### The 5th level <small>with secondary text</small>
        ###### The 6th level <small>with secondary text</small>
        ```

        ### The 3rd level <small>with secondary text</small>

        #### The 4th level <small>with secondary text</small>

        ##### The 5th level <small>with secondary text</small>

        ###### The 6th level <small>with secondary text</small>

!!! quote ""
    ## Blockquotes

    Use a single `>` in the beginning of the line/paragraph to enclose it in a blockquote

    ```
    > Morbi eget dapibus felis. Vivamus venenatis porttitor tortor sit amet rutrum.

    > Morbi eget dapibus felis. Vivamus venenatis porttitor tortor sit amet rutrum.
      Pellentesque aliquet quam enim, eu volutpat urna rutrum a. Nam vehicula nunc
      mauris, a ultricies libero efficitur sed.
    ```

    !!! success "Result"

        > Morbi eget dapibus felis. Vivamus venenatis porttitor tortor sit amet rutrum.

        > Morbi eget dapibus felis. Vivamus venenatis porttitor tortor sit amet rutrum.
          Pellentesque aliquet quam enim, eu volutpat urna rutrum a. Nam vehicula nunc
          mauris, a ultricies libero efficitur sed.

    ### Blockquote nesting

    Blockquotes can also be nested by using additional `> greater than` symbol.

    Example:
    ```
    > **Sed aliquet**, neque at rutrum mollis, neque nisi tincidunt nibh, vitae
      faucibus lacus nunc at lacus.

    > > Mauris dictum mi lacus, sit amet pellentesque urna vehicula fringilla.

    > > > `Suspendisse rutrum facilisis risus`, eu posuere neque commodo a.
    ```

    !!! success "Result"
        > **Sed aliquet**, neque at rutrum mollis, neque nisi tincidunt nibh, vitae
          faucibus lacus nunc at lacus.

        > > Mauris dictum mi lacus, sit amet pellentesque urna vehicula fringilla.

        > > > `Suspendisse rutrum facilisis risus`, eu posuere neque commodo a.

    ### Other content blocks

    > Vestibulum vitae orci quis ante viverra ultricies ut eget turpis.
    ``` js hl_lines="8"
      var _extends = function(target) {
        for (var i = 1; i < arguments.length; i++) {
          var source = arguments[i];
          for (var key in source) {
            target[key] = source[key];
          }
        }
        return target;
      };
    ```

      > > Praesent at `:::js return target`, sodales nibh vel, tempor felis.

!!! quote ""
    ## Lists

    ### Unordered lists

    Unordered lists are created by simply using `- hyphen` for listing the items along with indentation.

    ```
    - Sed sagittis eleifend rutrum. Donec vitae suscipit est.

        - Duis mollis est eget nibh volutpat, fermentum aliquet dui mollis.
        - Nam vulputate tincidunt fringilla.
            - Nullam dignissim ultrices urna non auctor.

    - Aliquam metus eros, pretium sed nulla venenatis, faucibus auctor ex.

    - Nulla et rhoncus turpis. Mauris ultricies elementum leo.
    ```

    !!! success "Result"

        - Sed sagittis eleifend rutrum. Donec vitae suscipit est.

            - Duis mollis est eget nibh volutpat, fermentum aliquet dui mollis.
            - Nam vulputate tincidunt fringilla.
                - Nullam dignissim ultrices urna non auctor.

        - Aliquam metus eros, pretium sed nulla venenatis, faucibus auctor ex.

        - Nulla et rhoncus turpis. Mauris ultricies elementum leo.

    ### Ordered lists

    Ordered lists are created by using numbers following a dot, ie. `1.` for listing the items along with indentation.

    ``` markdown
    1. Integer vehicula feugiat magna, a mollis tellus.

    2. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur
      ridiculus mus.

        1. Vivamus venenatis porttitor tortor sit amet rutrum.

            1. Mauris dictum mi lacus
            2. Ut sit amet placerat ante

        2. Morbi eget dapibus felis. Vivamus venenatis porttitor tortor sit amet
          rutrum.

        3. Pellentesque eget `:::js var _extends` ornare tellus, ut gravida mi.
        ``` js hl_lines="1"
        var _extends = function(target) {
          for (var i = 1; i < arguments.length; i++) {
            var source = arguments[i];
            for (var key in source) {
              target[key] = source[key];
            }
          }
          return target;
        };
        ```

    3. Vivamus id mi enim. Integer id turpis sapien.
    ```

!!! success "Result"

    1. Integer vehicula feugiat magna, a mollis tellus.

    2. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur
      ridiculus mus.

        1. Vivamus venenatis porttitor tortor sit amet rutrum.

            1. Mauris dictum mi lacus
            2. Ut sit amet placerat ante

        2. Morbi eget dapibus felis. Vivamus venenatis porttitor tortor sit amet
          rutrum.

        3. Pellentesque eget `:::js var _extends` ornare tellus, ut gravida mi.
        ``` js hl_lines="1"
        var _extends = function(target) {
          for (var i = 1; i < arguments.length; i++) {
            var source = arguments[i];
            for (var key in source) {
              target[key] = source[key];
            }
          }
          return target;
        };
        ```

    3. Vivamus id mi enim. Integer id turpis sapien.

!!! quote ""
    ## Code blocks

    ### Inline

    Morbi eget `dapibus felis`. Vivamus *`venenatis porttitor`* tortor sit amet
    rutrum.

    Nam vehicula nunc `:::js return target` mauris, a ultricies libero efficitur
    sed. Sed molestie imperdiet consectetur. Vivamus a pharetra leo. Pellentesque
    eget ornare tellus, ut gravida mi. Fusce vel lacinia lacus.

    ### Listing

    ``` js hl_lines="8"
        var _extends = function(target) {
          for (var i = 1; i < arguments.length; i++) {
            var source = arguments[i];
            for (var key in source) {
              target[key] = source[key];
            }
          }
          return target;
        };
    ```

!!! quote ""
    ## Horizontal rules

    A horizontal rules/lines can be added by using three underlines `___`

    Example

    ```
    ___
    ```

    Result:

___

!!! quote ""
    ## Tables

    Example:
    ```
    | Sollicitudo / Pellentesi | consectetur | adipiscing | elit    | arcu | sed |
    | ------------------------ | ----------- | ---------- | ------- | ---- | --- |
    | Vivamus a pharetra       | yes         | yes        | yes     | yes  | yes |
    | Ornare viverra ex        | yes         | yes        | yes     | yes  | yes |
    | Mauris a ullamcorper     | yes         | yes        | partial | yes  | yes |
    | Nullam urna elit         | yes         | yes        | yes     | yes  | yes |
    | Malesuada eget finibus   | yes         | yes        | yes     | yes  | yes |
    ```

    Result:

    | Sollicitudo / Pellentesi | consectetur | adipiscing | elit    | arcu | sed |
    | ------------------------ | ----------- | ---------- | ------- | ---- | --- |
    | Vivamus a pharetra       | yes         | yes        | yes     | yes  | yes |
    | Ornare viverra ex        | yes         | yes        | yes     | yes  | yes |
    | Mauris a ullamcorper     | yes         | yes        | partial | yes  | yes |
    | Nullam urna elit         | yes         | yes        | yes     | yes  | yes |
    | Malesuada eget finibus   | yes         | yes        | yes     | yes  | yes |

    ### Aligning table contents

    Example:
    ```
    | Left       | Center   | Right   |
    | :--------- | :------: | ------: |
    | Lorem      | _dolor_  | `amet`  |
    | [ipsum](#) | **sit**  |         |
    ```

    Result:

    | Left       | Center   | Right   |
    | :--------- | :------: | ------: |
    | Lorem      | _dolor_  | `amet`  |
    | [ipsum](#) | **sit**  |         |

## Symbols

MarkDown | Symbol |
:--:|:--:|
`(tm)`|	™|
`(c)`|	©|
`(r)`|	®|
`c/o`|	℅|
`+/-`|	±|
`-->`|	→|
`<--`|	←|
`<-->`|	↔|
`=/=`|	≠|
`1/4, etc.`|	¼, etc.|
`1st 2nd etc.`|	1st 2nd etc.|

## Advanced

## Feature blocks

Feature blocks follow a simple syntax: every block is started with `!!!`,
followed by a single keyword which is used as the type qualifier of the
block. The content of the block then follows on the next line, indented by
four spaces.

Example:

``` markdown
!!! note
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.
```

Result:

!!! note

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

### Types

#### Note

Example:

``` markdown
!!! note
    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
```

Result:

!!! note

    Lorem ipsum dolor sit amet, consectetur adipiscing elit.

#### Abstract

Example:

``` markdown
!!! abstract / summary / tldr
    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
```

Result:

!!! abstract

    Lorem ipsum dolor sit amet, consectetur adipiscing elit.

#### Info

Example:

``` markdown
!!! info / todo
    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
```

Result:

!!! info

    Lorem ipsum dolor sit amet, consectetur adipiscing elit.

#### Tip

Example:

``` markdown
!!! tip / hint
    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
```

Result:

!!! tip

    Lorem ipsum dolor sit amet, consectetur adipiscing elit.

#### Success

Example:

``` markdown
!!! success / check / done
    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
```

Result:

!!! success

    Lorem ipsum dolor sit amet, consectetur adipiscing elit.

#### Question

Example:

``` markdown
!!! question / help / faq
    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
```

Result:

!!! question

    Lorem ipsum dolor sit amet, consectetur adipiscing elit.

#### Warning

Example:

``` markdown
!!! warning / caution / attention
    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
```

Result:

!!! warning

    Lorem ipsum dolor sit amet, consectetur adipiscing elit.

#### Failure

Example:

``` markdown
!!! failure / fail / missing
    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
```

Result:

!!! failure

    Lorem ipsum dolor sit amet, consectetur adipiscing elit.

#### Danger

Example:

``` markdown
!!! danger / error
    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
```

Result:

!!! danger

    Lorem ipsum dolor sit amet, consectetur adipiscing elit.

#### Bug

Example:

``` markdown
!!! bug
    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
```

Result:

!!! bug

    Lorem ipsum dolor sit amet, consectetur adipiscing elit.

#### Example

Example:

``` markdown
!!! example / snippet
    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
```

Result:

!!! example

    Lorem ipsum dolor sit amet, consectetur adipiscing elit.

#### Quote

Example:

``` markdown
!!! quote / cite
    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
```

Result:

!!! quote

    Lorem ipsum dolor sit amet, consectetur adipiscing elit.

### Changing the title

By default, the block title will equal the type qualifier in titlecase. However,
it can easily be changed by adding a quoted string after the type qualifier.

Example:

``` markdown
!!! note "Phasellus posuere in sem ut cursus"
    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
```

Result:

!!! note "Phasellus posuere in sem ut cursus"

    Lorem ipsum dolor sit amet, consectetur adipiscing elit.

### Removing the title

Similar to setting a custom title, the icon and title can be omitted by
providing an empty string after the type qualifier:

Example:

``` markdown
!!! note ""
    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
```

Result:

!!! note ""

    Lorem ipsum dolor sit amet, consectetur adipiscing elit.

### Embedded code blocks

Example:

!!! note

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.

    ``` javascript
    import Messenger, { providers } from '@aragon/messenger'
    import { defer } from 'rxjs/observable/defer'
    import { empty } from 'rxjs/observable/empty'
    import { fromPromise } from 'rxjs/observable/fromPromise'
    import { merge } from 'rxjs/observable/merge'

    export const AppProxyHandler = {
      get (target, name, receiver) {
        if (name in target) {
          return target[name]
        }

        return function (...params) {
          return target.rpc.sendAndObserveResponse(
            'intent',
            [name, ...params]
          ).pluck('result')
        }
      }
    }
    ```

    Nunc eu odio eleifend, blandit leo a, volutpat sapien. Phasellus posuere in
    sem ut cursus. Nullam sit amet tincidunt ipsum, sit amet elementum turpis.
    Etiam ipsum quam, mattis in purus vitae, lacinia fermentum enim.

## Footnotes

### Usage

The markup for footnotes is similar to the standard Markdown markup for links.
A reference is inserted in the text, which can then be defined at any point in
the document.

#### Inserting the reference

The footnote reference is enclosed in square brackets and starts with a caret,
followed by an arbitrary label which may contain numeric identifiers [1, 2, 3,
...] or names [Granovetter et al. 1998]. The rendered references are always
consecutive superscripted numbers.

Example:

``` markdown
Lorem ipsum[^1] dolor sit amet, consectetur adipiscing elit.[^2]
```

Result:

Lorem ipsum[^1] dolor sit amet, consectetur adipiscing elit.[^2]

#### Inserting the content

The footnote content is also declared with a label, which must match the label
used for the footnote reference. It can be inserted at an arbitrary position in
the document and is always rendered at the bottom of the page. Furthermore, a
backlink is automatically added to the footnote reference.

##### on a single line

Short statements can be written on the same line.

Example:

``` markdown
[^1]: Lorem ipsum dolor sit amet, consectetur adipiscing elit.
```

Result:

> <a href="#fn:1">Jump to footnote at the bottom of the page</a>

  [^1]: Lorem ipsum dolor sit amet, consectetur adipiscing elit.

##### on multiple lines

Paragraphs should be written on the next line. As with all Markdown blocks, the
content must be indented by four spaces.

Example:

``` markdown
[^2]:
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.
```

Result:

  [^2]:
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
      nulla. Curabitur feugiat, tortor non consequat finibus, justo purus
      auctor massa, nec semper lorem quam in massa.

> <a href="#fn:2">Jump to footnote at the bottom of the page</a>

!!! quote ""
    ## Tasklists

    Tasklists are useful for keeping track of tasks and showing what has been done and has yet to be done. Checkbox lists are like regular lists, but prefixed with `[ ]` for empty or `[x]` for filled checkboxes.

    Example:

    ``` markdown
    - [x] Lorem ipsum dolor sit amet, consectetur adipiscing elit
    - [x] Nulla lobortis egestas semper
    - [ ] Vestibulum convallis sit amet nisi a tincidunt
        - [x] In hac habitasse platea dictumst
        - [x] In scelerisque nibh non dolor mollis congue sed et metus
        - [ ] Praesent sed risus massa
    - [ ] Aenean pretium efficitur erat, donec pharetra, ligula non scelerisque
    - [ ] Nulla vel eros venenatis, imperdiet enim id, faucibus nisi
    ```

    Result:

    - [x] Lorem ipsum dolor sit amet, consectetur adipiscing elit
    - [x] Nulla lobortis egestas semper
    - [ ] Vestibulum convallis sit amet nisi a tincidunt
        - [x] In hac habitasse platea dictumst
        - [x] In scelerisque nibh non dolor mollis congue sed et metus
        - [ ] Praesent sed risus massa
    - [ ] Aenean pretium efficitur erat, donec pharetra, ligula non scelerisque
    - [ ] Nulla vel eros venenatis, imperdiet enim id, faucibus nisi

## Code Highlighting

Using Markdown syntaxes, code blocks can be opened and closed by writing three backticks on separate lines. To add code highlighting to those blocks, the easiest way is to specify the language directly after the opening block.

Examples:

```` markdown
``` python
import tensorflow as tf
```
````

````
``` javascript
import Messenger, { providers } from '@aragon/messenger'
import { defer } from 'rxjs/observable/defer'
import { empty } from 'rxjs/observable/empty'
import { fromPromise } from 'rxjs/observable/fromPromise'
import { merge } from 'rxjs/observable/merge'

export const AppProxyHandler = {
  get (target, name, receiver) {
    if (name in target) {
      return target[name]
    }

    return function (...params) {
      return target.rpc.sendAndObserveResponse(
        'intent',
        [name, ...params]
      ).pluck('result')
    }
  }
}
```
````

Results:

``` python
import tensorflow as tf
```

``` javascript
import Messenger, { providers } from '@aragon/messenger'
import { defer } from 'rxjs/observable/defer'
import { empty } from 'rxjs/observable/empty'
import { fromPromise } from 'rxjs/observable/fromPromise'
import { merge } from 'rxjs/observable/merge'

export const AppProxyHandler = {
  get (target, name, receiver) {
    if (name in target) {
      return target[name]
    }

    return function (...params) {
      return target.rpc.sendAndObserveResponse(
        'intent',
        [name, ...params]
      ).pluck('result')
    }
  }
}
```

### Supported languages

The Code Highlighting uses [Pygments](http://pygments.org/), a generic syntax highlighter.

It supports over [300 languages](http://pygments.org/languages).

### Grouping code blocks

You can use grouping for code blocks with tabs.

Example:

````
=== "Bash"

    ```bash
    #!/bin/bash

    echo "Hello world!"
    ```

=== "C"

    ```c
    #include <stdio.h>

    int main(void) {
      printf("Hello world!\n");
    }
    ```

=== "C++"

    ```c++
    #include <iostream>

    int main(void) {
      std::cout << "Hello world!" << std::endl;
      return 0;
    }
    ```
````

Result:

=== "Bash"

    ```bash
    #!/bin/bash

    echo "Hello world!"
    ```

=== "C"

    ```c
    #include <stdio.h>

    int main(void) {
      printf("Hello world!\n");
    }
    ```

=== "C++"

    ```c++
    #include <iostream>

    int main(void) {
      std::cout << "Hello world!" << std::endl;
      return 0;
    }
    ```

### Highlighting specific lines

Specific lines can be highlighted by passing the line numbers to the `hl_lines`
argument placed right after the language identifier. Line counts start at 1.

Example:

````
``` python hl_lines="2 3"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```
```
````

Result:

``` python hl_lines="2 3"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```
