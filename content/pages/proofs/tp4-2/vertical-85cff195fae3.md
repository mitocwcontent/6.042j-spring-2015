---
content_type: page
parent_title: 1.9  State Machines - Invariants
parent_uid: 470546ac-8124-6c93-8505-a0f7571765aa
title: 1.9  State Machines - Invariants
uid: bd55b53d-c54b-1a4a-4c52-a30e9c3119d3
---

*   [<Derived Variables and Termination]({{< baseurl >}}/pages/proofs/tp4-2/vertical-5bf3bfde6f69)
*   [1.9.1State Machines Invariants: Video]({{< baseurl >}}/pages/proofs/tp4-2)
*   [1.9.2State Machine Invariants]({{< baseurl >}}/pages/proofs/tp4-2/vertical-ee3144f200f1)
*   [1.9.3Derived Variables: Video]({{< baseurl >}}/pages/proofs/tp4-2/vertical-ef00ae29a8ca)
*   [1.9.4Derived Variables and Termination]({{< baseurl >}}/pages/proofs/tp4-2/vertical-5bf3bfde6f69)
*   [1.9.5Integer Multiplication]({{< baseurl >}}/pages/proofs/tp4-2/vertical-85cff195fae3)
*   [1.9.6Chocolate Bars]({{< baseurl >}}/pages/proofs/tp4-2/vertical-ffd6266c03ec)
*   [\>Chocolate Bars]({{< baseurl >}}/pages/proofs/tp4-2/vertical-ffd6266c03ec)

Integer Multiplication
----------------------

  

Suppose that the following procedure is used to multiply two non-negative integers _a_ and _b_.

*   \\(x ::= a\\)
*   \\(y ::= b\\)
*   \\(p ::= 0\\)

Repeat the following commands:

*   if \\(x = 0\\), then output \\(p\\) and terminate; else
*   if \\(x\\) is even, then set \\(x \\leftarrow x/2\\) and \\(y \\leftarrow 2y\\); else
*   if \\(x\\) is odd, then set \\(x \\leftarrow x - 1\\) and \\(p \\leftarrow p + y\\).

  

1.  {{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;\\(xy = p\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(xy = ab\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;\\(xy + p = ab\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(xyp = ab\\)&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}Predicates (1), (2), and (4) are preserved by the second command of the algorithm, but not necessarily by the third command. Predicate (3) is preserved by both commands. In the second command, the product \\(xy\\) remains the same and so does \\(p\\), so the sum keeps its old value. In the third command, the product \\(xy\\) decreases by \\(y\\) and \\(p\\) increases by \\(y\\), so the sum again keeps its old value.{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
  
3.  {{< quiz_multiple_choice questionId="Q2_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="true" >}}&nbsp;\\(x\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(xy\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(p - y\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(x + p\\)&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}In every transition, \\(x\\) is either halved or reduced by 1, so it is strictly decreasing. In contrast, \\(xy\\) either remains the same or reduces by \\(y\\), so it is weakly decreasing. \\(p-y\\) and \\(x+p\\) may each decrease or increase.{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}

*   [BackDerived Variables and Termination]({{< baseurl >}}/pages/proofs/tp4-2/vertical-5bf3bfde6f69)
*   [ContinueChocolate Bars]({{< baseurl >}}/pages/proofs/tp4-2/vertical-ffd6266c03ec)