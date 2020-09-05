---
title: ToDos
---

## Block title
#+BEGIN_QUERY
{:title "ToDos tagged GRAD"
 :query [:find (pull ?b [*])
         :where
         [?p :page/name "gii"]
         [?b :block/ref-pages ?p]
         ]}
#+END_QUERY
