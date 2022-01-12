---
content_type: page
parent_title: 4.8 Random Walks & Pagerank
parent_uid: ec31be5e-21ec-45ab-3eab-7ab45d2e85b7
title: 4.8 Random Walks & Pagerank
uid: 1ab26783-f36c-e84d-ea0b-68e44c1ccbb6
---

*   [<Random Walks]({{< baseurl >}}/pages/probability/random-walks-pagerank/random-walks-0)
*   [4.8.1Random Walks: Video]({{< baseurl >}}/pages/probability/random-walks-pagerank)
*   [4.8.2Stationary Distributions: Video]({{< baseurl >}}/pages/probability/random-walks-pagerank/stationary-distributions-video)
*   [4.8.3Page Rank: Video]({{< baseurl >}}/pages/probability/random-walks-pagerank/page-rank-video)
*   [4.8.4Random Walks]({{< baseurl >}}/pages/probability/random-walks-pagerank/random-walks-0)
*   [4.8.5Random Walks (cont.)]({{< baseurl >}}/pages/probability/random-walks-pagerank/random-walks-cont)

Random Walks (cont.)
--------------------

Consider the following random-walk graphs:

![random walks](/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/random-walks-pagerank/random-walks-cont/random_walk.jpg)

1.  If you start at node \\(w\\) in graph 2 and take a (long) random walk, does the distribution over nodes ever get close to the stationary distribution? Try a few steps to see what is happening.{{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="true" >}}&nbsp; Yes&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; No&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution / >}}{{< /quiz_multiple_choice >}}
2.  How many stationary distributions are there for graph 3?{{< quiz_multiple_choice questionId="Q2_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp; 0&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; 1&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; 2&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; 4&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; \\(2^4\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp; infinitely many&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution / >}}{{< /quiz_multiple_choice >}}
3.  If you start at node \\(b\\) in graph 3 and take a (long) random walk, the probabililty you are at node \\(d\\) will be close to:{{< quiz_multiple_choice questionId="Q3_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;\\(0\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; \\(\\left(\\frac{1}{2}\\right)^n\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(\\dfrac{1}{4}\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(\\dfrac{5}{16}\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp; \\(\\dfrac{1}{3}\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; \\(\\dfrac{1}{2}\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; \\(\\dfrac{2}{3}\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; \\(1\\)&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution / >}}{{< /quiz_multiple_choice >}}

*   [BackRandom Walks]({{< baseurl >}}/pages/probability/random-walks-pagerank/random-walks-0)