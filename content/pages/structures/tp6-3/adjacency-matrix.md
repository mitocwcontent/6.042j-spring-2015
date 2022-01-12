---
content_type: page
parent_title: '2.5  Digraphs: Walks & Paths'
parent_uid: 711aeeca-1552-65f2-21e5-af2643f1a05f
title: '2.5  Digraphs: Walks & Paths'
uid: e2165a11-69e6-c54f-cd9f-f1a57a2ef044
---

*   [<Longest Path]({{< baseurl >}}/pages/structures/tp6-3/vertical-588ea67bd5d7)
*   [2.5.1Digraphs: Walks & Paths: Video]({{< baseurl >}}/pages/structures/tp6-3)
*   [2.5.2Walks and Paths]({{< baseurl >}}/pages/structures/tp6-3/vertical-5a67aa9a3a6d)
*   [2.5.3Digraphs: Connected Vertices: Video]({{< baseurl >}}/pages/structures/tp6-3/vertical-2c95b0b170e2)
*   [2.5.4Longest Path]({{< baseurl >}}/pages/structures/tp6-3/vertical-588ea67bd5d7)
*   [2.5.5Adjacency Matrix]({{< baseurl >}}/pages/structures/tp6-3/adjacency-matrix)
*   [2.5.6Counting Paths]({{< baseurl >}}/pages/structures/tp6-3/counting-paths)
*   [\>Counting Paths]({{< baseurl >}}/pages/structures/tp6-3/counting-paths)

Adjacency Matrix
----------------

Suppose we have an adjacency matrix A representation of a directed graph G.

Which of the following must be true for any adjacency matrix, regardless of the underlying graph?

Some matrix definitions:  
{{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;\\(A = A^T\\)&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp;A cell \\((i, j)\\) in the matrix \\(A^2\\) has non-zero value iff there is a length 2 path between the \\(i\\)-th and \\(j\\)-th vertices.&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp;Every row in \\(A\\) must be different.&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
{{< quiz_solution >}}For an undirected graph, the transpose of a matrix is itself because having an edge from \\(i\\) to \\(j\\) is equivalent to having an edge from \\(i\\) to \\(j\\). However, for directed graphs, this is not the case because these two edges would point in opposite directions.  
There is a length 2 path iff there exists some k such that \\(i, k, j\\) are connected iff exists index k such that \\((i, k) = 1\\) and \\((k, j) = 1\\) iff row \\(i\\) times column \\(j\\) is not 0 iff In \\(A^2, (i, j)\\) is not zero.  
If two rows in an adjacency matrix are the same, then this just represents that two vertices have edges leading to the same set of vertices.{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}

*   [BackLongest Path]({{< baseurl >}}/pages/structures/tp6-3/vertical-588ea67bd5d7)
*   [ContinueCounting Paths]({{< baseurl >}}/pages/structures/tp6-3/counting-paths)