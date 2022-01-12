---
content_type: page
parent_title: 4.3 Independence & Causality
parent_uid: 90eace8a-4b31-0417-7362-8667f8f3497b
title: 4.3 Independence & Causality
uid: 07fdf977-125d-4132-cfdd-043131c8b67c
---

*   [<Independence & Causality]({{< baseurl >}}/pages/probability/tp12-2)
*   [4.3.1Independence: Video]({{< baseurl >}}/pages/probability/tp12-2)
*   [4.3.2Independent Dice Rolls]({{< baseurl >}}/pages/probability/tp12-2/vertical-8ff8e74ce854)
*   [4.3.3Mutual Independence: Video]({{< baseurl >}}/pages/probability/tp12-2/vertical-9c80216b7495)
*   [4.3.4Mutually Independent Dice Rolls]({{< baseurl >}}/pages/probability/tp12-2/vertical-725617c4e7c2)
*   [4.3.5Independent vs Disjoint]({{< baseurl >}}/pages/probability/tp12-2/vertical-6700220de664)
*   [4.3.6Labeled Balls]({{< baseurl >}}/pages/probability/tp12-2/vertical-324cac33b048)
*   [4.3.7Paradox]({{< baseurl >}}/pages/probability/tp12-2/paradox)
*   [\>Mutual Independence: Video]({{< baseurl >}}/pages/probability/tp12-2/vertical-9c80216b7495)

Independent Dice Rolls
----------------------

  

Consider the following events for rolling 2 dice:

\\(\\begin{align}A\_i&:=\\text{the first die is a \\(i\\), for \\(i\\in\[1,6\]\\)}&\\\\B\_i&:=\\text{the second die is a \\(i\\), for \\(i\\in\[1,6\]\\)}&\\\\S\_i&:=\\text{sum of the dice is \\(i\\), for \\(i\\in\[2,12\]\\)}&\\end{align}\\)

{{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="true" >}}&nbsp; \\(A\_1\\) and \\(B\_1\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp; \\(A\_1\\) and \\(B\_6\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; \\(A\_3\\) and \\(S\_2\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; \\(A\_2\\) and \\(S\_6\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp; \\(A\_1\\) and \\(S\_7\\) &nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
{{< quiz_solution >}}Two dice throws are independent.

\\(\\Pr\[A\_3 \\cap S\_2\]=\\Pr\[\\emptyset\]=0\\neq \\frac{1}{6}\\cdot\\frac{1}{36}=\\Pr\[A\_3\]\\Pr\[S\_2\].\\) \\(\\Pr\[A\_2 \\cap S\_6\]= \\Pr\[A\_2 \\cap B\_4\]=\\frac{1}{36}\\neq \\frac{1}{6}\\cdot\\frac{5}{36}=\\Pr\[A\_2\]\\Pr\[S\_6\].\\) \\(\\Pr\[A\_1 \\cap S\_7\]= \\Pr\[A\_1 \\cap B\_6\]=\\frac{1}{36} = \\frac{1}{6}\\cdot\\frac{6}{36}=\\Pr\[A\_1\]\\Pr\[S\_7\].\\){{< /quiz_solution >}}{{< /quiz_multiple_choice >}}

*   [BackIndependence & Causality]({{< baseurl >}}/pages/probability/tp12-2)
*   [ContinueMutual Independence: Video]({{< baseurl >}}/pages/probability/tp12-2/vertical-9c80216b7495)