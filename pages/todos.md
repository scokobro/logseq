---
title: ToDos
---

## Things to do...
#+BEGIN_QUERY
{:title "All Tasks"
 :query [:find (pull ?b [*])
         :where
                  [?b :block/marker "TODO"]]}
#+END_QUERY
##
