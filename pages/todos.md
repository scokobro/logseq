---
title: ToDos
---

## Block title
#+BEGIN_QUERY
{:title "ToDos tagged GRAD"
 :query [:find (pull ?b [*])
         :where
         [?p :page/name "GII"]
         [?b :block/ref-pages ?p]
         ]}
#+END_QUERY$  $
 ]}
#+END_QUERY$  $
Y
{:title "Now tasks with tag Global Insights"
 :query [:find (pull ?b [*])
         :where
         [?p :page/name "GII"]
         [?b :block/ref-pages ?p]
         ]}
#+END_QUERY
-pages ?p]
         ]}
#+END_QUERY$  $
Title
#+BEGIN_QUERY
{:title "Now tasks with tag Global Insights"
 :query [:find (pull ?b [*])
         :where
         [?p :page/name "GI"]
         [?b :block/ref-pages ?p]
         ]}
#+END_QUERY
 ]}
#+END_QUERY$  $
Title
+BEGIN_QUERY
{:title "Now tasks with tag Global Insights"
 :query [:find (pull ?b [*])
         :where
         [?p :page/name "GI"]
         [?b :block/ref-pages ?p]
         ]}
#+END_QUERY
