---
title: ToDos
---

## $  $
#+BEGIN_QUERY
{:title "Now tasks with tag GRAD"
 :query [:find (pull ?b [*])
         :where
         [?p :page/name "grad"]
         [?b :block/ref-pages ?p]
         ]}
#+END_QUERY
