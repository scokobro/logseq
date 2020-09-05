---
title: ToDos
---

## Block title
Custom query example:
#+BEGIN_QUERY
{:title "Tasks marked grad"
 :query [:find (pull ?b [*])
         :where
         [?p :page/name "grad"]
         [?b :block/ref-pages ?p]]}
#+END_QUERY
## Title
#+BEGIN_QUERY
{:title "ToDos tagged GRAD"
 :query [:find (pull ?b [*])
         :where
         [?p :page/name "gii"]
         [?b :block/ref-pages ?p]
         ]}
#+END_QUERY
