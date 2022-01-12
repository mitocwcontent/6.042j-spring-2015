---
content_type: page
parent_title: 2.10 Trees
parent_uid: cbeb9c37-cb9c-a67c-cf21-6c0b8aeab325
title: 2.10 Trees
uid: 2a01183c-af7f-5488-2ed3-2634942e321c
---

*   [<Minimum Spanning Trees]({{< baseurl >}}/pages/structures/tp8-1/minimum-spanning-trees)
*   [2.10.1Trees: Video]({{< baseurl >}}/pages/structures/tp8-1)
*   [2.10.2Trees: Many Definitions]({{< baseurl >}}/pages/structures/tp8-1/vertical-91c45efd7596)
*   [2.10.3Tree Coloring: Video]({{< baseurl >}}/pages/structures/tp8-1/vertical-04923c3ed451)
*   [2.10.42-Colorable Trees]({{< baseurl >}}/pages/structures/tp8-1/vertical-b69812803f1e)
*   [2.10.5Spanning Trees: Video]({{< baseurl >}}/pages/structures/tp8-1/vertical-2ef65242598f)
*   [2.10.6Span all the Graphs!]({{< baseurl >}}/pages/structures/tp8-1/vertical-63394d192790)
*   [2.10.7Tree or Not Tree?]({{< baseurl >}}/pages/structures/tp8-1/vertical-7bacea60d91e)
*   [2.10.8Leaves]({{< baseurl >}}/pages/structures/tp8-1/vertical-425ace1eec7d)
*   [2.10.9Minimum Spanning Trees]({{< baseurl >}}/pages/structures/tp8-1/minimum-spanning-trees)
*   [2.10.10Graph Algorithm]({{< baseurl >}}/pages/structures/tp8-1/vertical-f8c5c236b9c0)
*   [\>Stable Matching]({{< baseurl >}}/pages/structures/stable-matching)

Graph Algorithm
---------------

  

The algorithm _STAR MARK_ starts with a simple undirected graph, \\(G\\), with a finite set of vertices, \\(V\\), and a set of one or more edges, \\(E\\). Initially, all edges are unmarked. Then, _STAR MARK_ proceeds to mark some of the edges, by repeatedly performing the following steps until no further step is possible:

1.  Choose any unmarked edge \\(e \\in E\\) such that there is currently no path of marked edges between the endpoints of \\(e\\).
2.  Mark edge \\(e\\).

* * *

**Preserved Invariants**  
{{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;There is always an edge that has not been marked.&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp;The marked edges form an acyclic graph.&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp;The marked edges form a tree.&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp;There is always a vertex not touching a marked edge.&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
{{< quiz_solution >}}1.  Predicate 1 is true for the start state, since by definition there is at least one edge, but it is _not_ preserved.
2.  Predicate 2 is a preserved invariant and vacuously holds for the start state, which has no marked edges.
3.  Predicate 3 is vacuously true for the start state, but it is _not_ preserved.
4.  Predicate 4 is true for the start state but is _not_ preserved.{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}

* * *

**Derived Variables**  

Choose the property that best describes each of the following derived variables.

Answer with the strongest applicable property. For example, for a variable that is constant, the answer should be "constant", even though it is also both weakly increasing and weakly decreasing.

1.  \# of unmarked edges{{< quiz_multiple_choice questionId="Q2_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp; strictly increasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; weakly increasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp; strictly decreasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; weakly decreasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; constant&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}In every iteration, the number of unmarked edges decreases by 1.{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
2.  \# of marked edges{{< quiz_multiple_choice questionId="Q3_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="true" >}}&nbsp; strictly increasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; weakly increasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; strictly decreasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; weakly decreasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; constant&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}In every iteration, the number of marked edges increases by 1.{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
3.  (# of unmarked edges) + (# of marked edges){{< quiz_multiple_choice questionId="Q4_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp; strictly increasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; weakly increasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; strictly decreasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; weakly decreasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp; constant&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}In every iteration, the number of marked edges increases by 1 and the number of unmarked edges decreases by 1. So, their sum remains constant and is always equal to the initial number of unmarked edges in the graph.{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
4.  (# of marked edges) - (# of unmarked edges){{< quiz_multiple_choice questionId="Q5_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="true" >}}&nbsp; strictly increasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; weakly increasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; strictly decreasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; weakly decreasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; constant&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}In every iteration, the number of marked edges increases by 1 and the number of unmarked edges decreases by 1. So, their difference increases by 2.{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
5.  (# of connected components) in \\(G'\\) with vertices in \\(V\\) and edges in \\(M\\), where \\(M\\) is the set of marked edges{{< quiz_multiple_choice questionId="Q6_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp; strictly increasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; weakly increasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp; strictly decreasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; weakly decreasing&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; constant&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}Each newly marked edge connects 2 vertices that previously had no path of marked edges between them, so these 2 vertices belonged to different connected components of \\(G'\\), and the newly marked edge "joins" these components into one. As a result, the number of components in \\(G'\\) decreases by 1.{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}

*   [BackMinimum Spanning Trees]({{< baseurl >}}/pages/structures/tp8-1/minimum-spanning-trees)
*   [ContinueStable Matching]({{< baseurl >}}/pages/structures/stable-matching)