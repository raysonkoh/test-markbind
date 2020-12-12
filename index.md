<frontmatter>
  header: header.md
  pageNav: 2
  pageNavTitle: "Chapters of This Page"
  siteNav: site-nav.md
</frontmatter>

<br>

<div class="jumbotron jumbotron-fluid bg-primary text-white">
  <div class="container">
    <h1 class="display-4 no-index">Landing Page Title</h1>
    <p class="lead">A tagline can go here</p>
  </div>
</div>

# Heading 1
Some text some text some text some text some text some text some text. **Some text some text some text some text some text ==some text== some text**. Some text some text some text some text some text some text some text some text some text some text some text some text some text some text. Some text some text some text some text some text some text. Some text some text some text some text some text some text some text.

<panel header="expand with header" alt="this is the alt">
  Lorem ipsum ...
</panel>

<panel header="expand with no header" alt="this is the alt" expand-headerless>
  Lorem ipsum ...
</panel>

<panel header="min-expand with header" alt="min-expand with header" minimized>
  Lorem ipsum ...
</panel>

<panel header="min-expand with no header" alt="min-expand with no header" minimized expand-headerless>
  Lorem ipsum ...
</panel>

<panel header="expanded-expand with header" alt="expanded-expand with header" expanded>
  Lorem ipsum ...
</panel>

<panel header="expanded-expand no header" alt="expanded-expand no header" expanded expand-headerless>
  Lorem ipsum ...
</panel>

<panel header="type-dark-expand with header" alt="expanded-expand with header" type="dark">
  Lorem ipsum ...
</panel>

<panel header="type-dark-expand no header" alt="expanded-expand no header" type="dark" expand-headerless>
  Lorem ipsum ...
</panel>

<panel header="**expand with header** :rocket: ![](https://markbind.org/images/logo-lightbackground.png =x20)" type="seamless">
  ...
</panel>

<panel header="**expand with no header** :rocket: ![](https://markbind.org/images/logo-lightbackground.png =x20)" type="seamless" expand-headerless>
  ...
</panel>

<panel header="Parent Panel expand with header">
  <panel header="Level 1 Nested Panel">
    <panel header="Level 2 Nested Panel">
      <tip-box type="success">
        I'm a nested tip-box
      </tip-box>
      <panel header="Level 3 Nested Panel" type="minimal">
        minimal-type panel
      </panel>
    </panel>
  </panel>
  <panel header="Level 1 Nested Panel" type="info">
    Some Text
  </panel>
</panel>

<panel header="Parent Panel expand with no header" expand-headerless>
  <panel header="Level 1 Nested Panel">
    <panel header="Level 2 Nested Panel">
      <tip-box type="success">
        I'm a nested tip-box
      </tip-box>
      <panel header="Level 3 Nested Panel" type="minimal">
        minimal-type panel
      </panel>
    </panel>
  </panel>
  <panel header="Level 1 Nested Panel" type="info">
    Some Text
  </panel>
</panel>

**A block quote:**

> Some text some text some text some text some text some text some text. Some text some text some text some text some text some text some text. Some text some text some text some text some text some text some text some text some text some text some text some text some text some text. Some text some text some text some text some text some text. Some text some text some text some text some text some text some text.

**A list:**

* item A
* item B
  1. item b1
  1. item b2
  1. item b3

**A `code` example:**

```html
<foo>
  <bar type="name">goo</bar>
</foo>
```

## Sub Heading 1.1

A <tooltip effect="scale" content=":exclamation: some **important explanation**" placement="top" trigger="hover">tooltip</tooltip>, a <trigger for="modal:modalinfo" trigger="click">modal</trigger>, a <a href="https://markbind.org/">link</a>, a <span class="badge badge-danger">badge</span>, another <span class="badge badge-warning">badge</span>.

<modal header="Modal Title" id="modal:modalinfo">
Some text some text some text some text some text some text some text. Some text some text some text some text some text some text some text. Some text some text some text some text some text some text some text some text some text some text some text some text some text some text. Some text some text some text some text some text some text. Some text some text some text some text some text some text some text.
</modal>

**A table:**

Column 1 | Column 2 | Column 3 | :far-thumbs-up: / :far-thumbs-down:?
:------: | :------: | :------: | ----
value1   | x        | 5        | :far-thumbs-up:
value2   | y        | 20       | :far-thumbs-down:


## Sub Heading 1.2

**Media embeds:**

@[youtube](http://www.youtube.com/watch?v=v40b3ExbM0c)

**Tabs:**

<tabs>
  <tab header="Tab X">
    Some text some text some text some text some text some text some text. Some text some text some text some text some text some text some text. Some text some text some text some text some text some text some text some text some text some text some text some text some text some text. Some text some text some text some text some text some text. Some text some text some text some text some text some text some text.
  </tab>
  <tab header="Tab Y">
    ...
  </tab>
  <tab-group header="Tab group">
    <tab header="Tab Y.1">
      ...
    </tab>
    <tab header="Tab Y.2">
      ...
    </tab>
  </tab-group>
</tabs>

<br>

# Heading 2

**Some boxes:**

<box>
    default
</box>
<box type="info">
    info
</box>
<box type="warning" dismissible>
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
</box>
<box type="tip" header="Tip box heading">
    tip
</box>
<box type="success" header="Tip box heading">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
</box>
<box type="important" dismissible header="Tip box heading">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
</box>

<br>

# Heading 3

<panel header="Expandable panel" type="info">
  Some text some text some text some text some text some text some text. Some text some text some text some text some text some text some text. Some text some text some text some text some text some text some text some text some text some text some text some text some text some text. Some text some text some text some text some text some text. Some text some text some text some text some text some text some text.
</panel>
<br>
<panel header="Expanded panel" alt="Minimized panel" type="success" minimized>
  ...
</panel>
<br>
<panel header="Expanded panel" alt="Minimized panel" type="seamless">
  ...
</panel>
<br>

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
<panel header="___Minimal panel **->**___" type="minimal" alt="Minimal panel" popup-url="https://markbind.org/userGuide/usingComponents.html#panels" no-switch>
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</panel>

Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
