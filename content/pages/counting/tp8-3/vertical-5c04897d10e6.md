---
content_type: page
parent_title: 3.2 Asymptotics
parent_uid: 7fcb0761-6e29-48a6-ad10-caa832263c78
title: 3.2 Asymptotics
uid: 1f7846ca-c133-388f-d786-cae947c99035
---

*   [<Asymptotic Properties: Video]({{< baseurl >}}/pages/counting/tp8-3/vertical-e35ce9684389)
*   [3.2.1Asymptotic Notation: Video]({{< baseurl >}}/pages/counting/tp8-3)
*   [3.2.2Asymptotics as Relations]({{< baseurl >}}/pages/counting/tp8-3/vertical-3800c4b1c397)
*   [3.2.3Asymptotic Properties: Video]({{< baseurl >}}/pages/counting/tp8-3/vertical-e35ce9684389)
*   [3.2.4Little oh Big Oh]({{< baseurl >}}/pages/counting/tp8-3/vertical-5c04897d10e6)
*   [3.2.5Theta]({{< baseurl >}}/pages/counting/tp8-3/theta)
*   [3.2.6Asymptotic Blunders: Video]({{< baseurl >}}/pages/counting/tp8-3/vertical-f4d8cd185706)
*   [3.2.7Asymptotics the Right Way]({{< baseurl >}}/pages/counting/tp8-3/vertical-9df50ab7aa43)
*   [3.2.8Practice with Big O]({{< baseurl >}}/pages/counting/tp8-3/vertical-4c14279fa60f)
*   [3.2.9Practice with Order of Growth]({{< baseurl >}}/pages/counting/tp8-3/vertical-171ad650135b)
*   [\>Theta]({{< baseurl >}}/pages/counting/tp8-3/theta)

Little oh Big Oh
----------------

  

1.  {{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="true" >}}&nbsp;If \\(f = o(g) \\), then \\(f = O(g) \\).&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;If \\(f = o(g) \\), then \\(g \\neq O(f) \\).&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;When \\(f \\sim g \\) and \\(f \\neq o(g) \\), \\(f = O(g) \\).&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;When \\(f \\nsim g \\) and \\(f = o(g) \\), \\(f = O(g) \\).&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;If \\(f = O(g) \\), then \\(f = o(g) \\).&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution / >}}{{< /quiz_multiple_choice >}}
2.  {{< quiz_multiple_choice questionId="Q2_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="true" >}}&nbsp;\\(x^{a} = o(x^{b}) \\) for all integers \\(a \\) and \\(b \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(b \\cdot x^{a} = o(x^{b}) \\) for all nonnegative constants \\(b > a\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(ln(x)=o(x^{\\varepsilon}) \\) for all \\(\\varepsilon > 0 \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(x^{c} = o(a^{x}) \\) for any \\(a, c \\in \\mathbb{R} \\) with \\(a > 1 \\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(log(x)=o(x^{\\epsilon}) \\) for all \\(\\epsilon > 0 \\)&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution / >}}{{< /quiz_multiple_choice >}}
3.  {{< quiz_multiple_choice questionId="Q3_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="true" >}}&nbsp;It accommodates cases in which a limit of \\(f(x)/g(x) \\) does not exist.&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;The limit superior, \\(limsup \\), is a more strict limit compared to the ordinary limit, \\(lim \\).&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(O(g(x)) \\) gives an upper bound instead of a lower bound on the growth of \\(f(n) \\).&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;\\(f(x) \\) can oscillate wildly as long as it never gets bigger than \\(c \\cdot g(x) \\) for \\(x > n \\) and \\(c > 0 \\).&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution / >}}{{< /quiz_multiple_choice >}}

*   [BackAsymptotic Properties: Video]({{< baseurl >}}/pages/counting/tp8-3/vertical-e35ce9684389)
*   [ContinueTheta]({{< baseurl >}}/pages/counting/tp8-3/theta)