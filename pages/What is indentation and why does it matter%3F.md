title:: What is indentation and why does it matter?

- Indentation is one of the fundamental concept in Logseq (and outliners in general). It's the feature that allows block references and queries to work. In other words: indentation helps you to find stuff in Logseq.
- The idea of indentation is simple: anytime you hit the `Tab` key, the block your cursor is in moves to the right. Indenting a block _nests_ it under the block above, creating a parent-child relationship:
	- ![parent-child-example-letters.png](../assets/parent-child-example-letters_1641572097841_0.png)
- Let's walk through the example step-by-step:
	- Block **A** is a parent block; **B** and **C** are _children_ of **A**; block **D** is a _grandchild_ of **A**.
	- Block **B** is a _child_ of **A** and it's in the same _branch_ as blocks **C** and **D**.
	- Block **C** is a _child_ of **A** and the _parent_ of **D**.
- Why is this important? As we've discussed in previous lessons, Logseq is a graph-based, networked note-taking tool. We mentioned that Logseq does not enforce a hierarchy—you can create all the hierarchies you need and modify them as your needs change. After all, a hierarchy is just one type of graph.
- Anyway, hierarchy in Logseq happens at the block level. By indenting blocks, you create a branch that you can navigate. Let's turn the example above into links and navigate to the _**Linked references**_ section of the page of _Child **D,**_ created for block **D**:
	- ![child-d-path.png](../assets/child-d-path_1641572255030_0.png)
- By going to the page of _Child **D**_, we can see this hierarchy as it's composed on this documentation page: first up is _Parent and child **C**_ and then _Parent **A**_.
- By clicking on one of the parents, the whole branch becomes visible:
	- ![child-d-branch.png](../assets/child-d-branch_1641572326932_0.png)
- Click again on one of the parents, and you will end up on that parent's page, again showing the composed hierarchy in the _**Linked Reference**_ section.
- That's the basics of indentation! It's not much more complex than this, but it opens up a world of possibilities.
