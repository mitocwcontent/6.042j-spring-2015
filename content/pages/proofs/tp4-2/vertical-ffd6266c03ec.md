---
content_type: page
parent_title: 1.9  State Machines - Invariants
parent_uid: 470546ac-8124-6c93-8505-a0f7571765aa
title: 1.9  State Machines - Invariants
uid: 00863914-a78e-473a-cade-704c69bead8e
---

*   [<Integer Multiplication]({{< baseurl >}}/pages/proofs/tp4-2/vertical-85cff195fae3)
*   [1.9.1State Machines Invariants: Video]({{< baseurl >}}/pages/proofs/tp4-2)
*   [1.9.2State Machine Invariants]({{< baseurl >}}/pages/proofs/tp4-2/vertical-ee3144f200f1)
*   [1.9.3Derived Variables: Video]({{< baseurl >}}/pages/proofs/tp4-2/vertical-ef00ae29a8ca)
*   [1.9.4Derived Variables and Termination]({{< baseurl >}}/pages/proofs/tp4-2/vertical-5bf3bfde6f69)
*   [1.9.5Integer Multiplication]({{< baseurl >}}/pages/proofs/tp4-2/vertical-85cff195fae3)
*   [1.9.6Chocolate Bars]({{< baseurl >}}/pages/proofs/tp4-2/vertical-ffd6266c03ec)
*   [\>Recursive Definition]({{< baseurl >}}/pages/proofs/recursive-definition)

Chocolate Bars
--------------

We are given a chocolate bar with \\(m \\times n\\) squares of chocolate, and our task is to divide it into \\(mn\\) individual squares. We are only allowed to split a chocolate bar using a vertical or a horizontal cut.

For example, suppose that the chocolate bar is \\(3 \\times 2\\). A horizontal cut between the first and second rows of squares splits it into two bars, a \\(1 \\times 2\\) bar and a \\(2 \\times 2\\) bar. One cut of the \\(1 \\times 2\\) splits it into individual squares, and three more cuts splits the \\(2 \\times 2\\) bar into squares. So a total of 5 cuts splits the whole \\(3 \\times 2\\) bar into squares.

At each step of the division process, let \\(s\\) be the number of splits already performed, and \\(p\\) the number of pieces of chocolate obtained.  

* * *

1.  {{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="true" >}}&nbsp;\\(s = p - 1\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp; \\(s \\neq p\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(s = mn - p\\)&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}With each split, both \\(s\\) and \\(p\\) increase by 1; therefore, the first two predicates are preserved invariants. In contrast, the left side in the third predicate increases while the right side decreases.{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
2.  {{< quiz_multiple_choice questionId="Q2_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="true" >}}&nbsp;\\(mn - p\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; \\(s\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(p - s\\)&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}Given a set of \\(m\\) and \\(n\\) (i.e., the size of the chocolate bar), \\(mn\\) does not change. With each split, both \\(s\\) and \\(p\\) increase by 1, \\(mn-p\\) decreases by 1, and \\(p-s\\) remains constant.{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
3.  {{< quiz_multiple_choice questionId="Q3_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;\\(p = mn - 1\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; \\(p = s - 1\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;\\(p = mn\\)&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}At the end of the process every square is separated, so \\(p=mn\\).{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
4.  {{< quiz_multiple_choice questionId="Q4_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="true" >}}&nbsp;\\(s = mn - 1\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp; \\(s = mn\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(s = mn + 1\\)&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}In Part 1, we found \\(s=p-1\\) a preserved invariant. This invariancy is also true at the beginning before the first split: \\(s=0\\) and \\(p=1\\). By the Invariant Theorem, the predicate \\(s=p-1\\) is true throughout the division process, thus, it is true at the end. From Part 3, we know that at the end \\(p=mn\\); substituting it into the invariant, we get \\(s=mn-1\\).{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}

*   [BackInteger Multiplication]({{< baseurl >}}/pages/proofs/tp4-2/vertical-85cff195fae3)
*   [ContinueRecursive Definition]({{< baseurl >}}/pages/proofs/recursive-definition)