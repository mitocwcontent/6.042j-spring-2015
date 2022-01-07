---
content_type: page
parent_title: 3.2 Asymptotics
parent_uid: 7fcb0761-6e29-48a6-ad10-caa832263c78
title: 3.2 Asymptotics
uid: 2b8275cb-f5d7-304c-3775-80b64cb09fc8
---

*   [<Practice with Big O]({{< baseurl >}}/pages/counting/tp8-3/vertical-4c14279fa60f)
*   [3.2.1Asymptotic Notation: Video]({{< baseurl >}}/pages/counting/tp8-3)
*   [3.2.2Asymptotics as Relations]({{< baseurl >}}/pages/counting/tp8-3/vertical-3800c4b1c397)
*   [3.2.3Asymptotic Properties: Video]({{< baseurl >}}/pages/counting/tp8-3/vertical-e35ce9684389)
*   [3.2.4Little oh Big Oh]({{< baseurl >}}/pages/counting/tp8-3/vertical-5c04897d10e6)
*   [3.2.5Theta]({{< baseurl >}}/pages/counting/tp8-3/theta)
*   [3.2.6Asymptotic Blunders: Video]({{< baseurl >}}/pages/counting/tp8-3/vertical-f4d8cd185706)
*   [3.2.7Asymptotics the Right Way]({{< baseurl >}}/pages/counting/tp8-3/vertical-9df50ab7aa43)
*   [3.2.8Practice with Big O]({{< baseurl >}}/pages/counting/tp8-3/vertical-4c14279fa60f)
*   [3.2.9Practice with Order of Growth]({{< baseurl >}}/pages/counting/tp8-3/vertical-171ad650135b)
*   [\>Counting with Bijections]({{< baseurl >}}/pages/counting/tp9-1)

Practice with Order of Growth
-----------------------------

  

For each pair of \\(f(n) \\) and \\(g(n) \\) below, determine which of the listed relations apply.

1.  {{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;\\(f(n) \\sim g(n) \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(f(n) = o(g(n)) \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;\\(f(n) = O(g(n)) \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;\\(f(n) = \\Theta(g(n)) \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;None of the above&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}\\(\\lim\_{n \\rightarrow \\infty} |\\frac{f(n)}{g(n)}| = \\lim\_{n \\rightarrow \\infty} \\frac{ln(n) / ln(3)}{ln(n) / ln(7)} = \\frac{ln(7)}{ln(3)} \\){{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
2.  {{< quiz_multiple_choice questionId="Q2_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;\\(f(n) \\sim g(n) \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;\\(f(n) = o(g(n)) \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;\\(f(n) = O(g(n)) \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(f(n) = \\Theta(g(n)) \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;None of the above&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}\\(\\lim\_{n \\rightarrow \\infty} |\\frac{f(n)}{g(n)}| = \\lim\_{n \\rightarrow \\infty} \\frac{0}{33} = 0 \\){{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
3.  {{< quiz_multiple_choice questionId="Q3_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;\\(f(n) \\sim g(n) \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(f(n) = o(g(n)) \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(f(n) = O(g(n)) \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(f(n) = \\Theta(g(n)) \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;None of the above&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}\\(\\frac{f(n)}{g(n)} = 0 \\) for \\(n \\equiv 1 (\\text{mod } 4) \\), and \\(\\frac{g(n)}{f(n)} = 0 \\) for \\(n \\equiv 0 (\\text{mod } 4) \\), so the 2 functions and their quotient never converge to some limit.{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
4.  {{< quiz_multiple_choice questionId="Q4_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;\\(f(n) \\sim g(n) \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(f(n) = o(g(n)) \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(f(n) = O(g(n)) \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(f(n) = \\Theta(g(n)) \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;None of the above&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}\\(\\lim\_{n \\rightarrow \\infty} |\\frac{f(n)}{g(n)}| = \\lim\_{n \\rightarrow \\infty} \\frac{1.01^{n}}{n^{100}} = \\lim\_{n \\rightarrow \\infty} \\frac{1.01^{n} ln(1.01)}{100 \\cdot n^{99}} = ... = \\lim\_{n \\rightarrow \\infty} \\frac{1.01^{n} ln(1.01)^{100}}{100!} = \\infty \\){{< /quiz_solution >}}{{< /quiz_multiple_choice >}}

*   [BackPractice with Big O]({{< baseurl >}}/pages/counting/tp8-3/vertical-4c14279fa60f)
*   [ContinueCounting with Bijections]({{< baseurl >}}/pages/counting/tp9-1)