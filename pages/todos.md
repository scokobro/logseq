---
title: ToDos
---

## Custom query example:
#+BEGIN_QUERY
{:title "Now tasks with tag nibble"
 :query [:find (pull ?b [*])
         :where
         [?p :page/name "nibble"]
         [?b :block/ref-pages ?p]
         ]}
#+END_QUERY
