# HTML TAGS

Here is some html tags use case for biggeners who wants to start learning web development.

## Author
- [S M Shamim](https://github.com/smwithgithub)

## Documentation

[Go to docs](https://github.com/smwithgithub/web_thriler)

## The HTML Document Tree
Each HTML document can, in fact, be referred to as a document tree. We describe the elements within the tree as one might describe a family tree, with terms such as ancestors, descendants, parents, children, and siblings.

Understanding the document tree is crucial because CSS selectors rely on the document tree.

Use the sample HTML document provided below for these examples. Note that the <head> section of the document has been omitted for brevity.

```
<body>

  <div id="content">
    <h1>Heading here</h1>
    <p>Lorem ipsum dolor sit amet.</p>
    <p>Lorem ipsum dolor <em>sit</em> amet.</p>
    <hr>
  </div>
  
  <div id="nav">
    <ul>
      <li>item 1</li>
      <li>item 2</li>
      <li>item 3</li>
    </ul>
  </div>

</body>
```

• A diagram of the above HTML document tree would look like this.

![tree](https://github.com/smwithgithub/web_thriler/assets/126904136/de7a85d2-9cc2-41d8-81c9-0d6ff195d75b)

# Ancestor
An ancestor refers to any element that is connected but further up the document tree - no matter how many levels higher.

In the diagram below, the <body> element is the ancestor of all other elements on the page.

![img2](https://github.com/smwithgithub/web_thriler/assets/126904136/36e73b9c-5519-4154-98ed-df7bac4b982a)

# Descendant
A descendant refers to any element that is connected but lower down the document tree - no matter how many levels lower.
In the diagram below, all elements that are connected below the <div> element are descendants of that <div>.

![img3](https://github.com/smwithgithub/web_thriler/assets/126904136/dfcd4a66-201f-4ef9-9f5b-48b398bf66cb)

# Parent and Child
A parent is an element that is directly above and connected to another element in the document tree. In the diagram below, the <div> element is a parent of the <ul> element.

A child is an element that is directly below and connected to another element in the document tree. In the diagram above, the <ul> element is a child of the <div> elemen

![img4](https://github.com/smwithgithub/web_thriler/assets/126904136/9695c174-b39b-498d-bfc0-0952624d7ff7)

# Sibling
A sibling is an element that shares the same parent as another element.

In the diagram below, the <li> elements are siblings because they all share the same parent, the <ul>.

![img5](https://github.com/smwithgithub/web_thriler/assets/126904136/a1bbe2ab-8a14-47f6-89dd-6bee235fe7ce)
