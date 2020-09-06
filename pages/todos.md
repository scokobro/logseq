---
title: ToDos
---

## Block title
#+BEGIN_QUERY
{:title "Tasks marked grad"
 :query [:find (pull ?b [*])
         :where
         [?p :page/name "grad"]
         [?b :block/ref-pages ?p]
         [?b :block/marker "TODO"]]}
#+END_QUERY
## Title
#+BEGIN_QUERY
{:title "ToDos tagged GRAD"
 :query [:find (pull ?b [*])
         :where
         [?p :page/name "gii"]
         [?b :block/ref-pages ?p]]}
#+END_QUERY
