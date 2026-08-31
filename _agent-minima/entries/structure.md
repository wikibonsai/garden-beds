: title    :: Structure
: hypernym :: [[knowledge-base]]
: tldr     :: "How the knowledge base is organized — the semantic tree, typed links, and attribute system."

The knowledge base has three structural layers:

1. The semantic tree (semtree): a hierarchical index that places
   every note in a taxonomy. Defined in index files using
   indented [[wikirefs]].
2. Typed links: [[wikirefs]] with type annotations that create
   a web of relationships across the tree.
3. Attributes: CAML key-value pairs at the top of each note
   that carry metadata and semantic information.

These layers compose: the tree gives hierarchy, the links give
association, and the attributes give properties.

See also: [[maintenance]]
