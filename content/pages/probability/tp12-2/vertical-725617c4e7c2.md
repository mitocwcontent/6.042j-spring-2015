---
content_type: page
parent_title: 4.3 Independence & Causality
parent_uid: 90eace8a-4b31-0417-7362-8667f8f3497b
title: 4.3 Independence & Causality
uid: 88c2ead8-56df-d490-9166-d60a3f11e545
---

*   [<Mutual Independence: Video]({{< baseurl >}}/pages/probability/tp12-2/vertical-9c80216b7495)
*   [4.3.1Independence: Video]({{< baseurl >}}/pages/probability/tp12-2)
*   [4.3.2Independent Dice Rolls]({{< baseurl >}}/pages/probability/tp12-2/vertical-8ff8e74ce854)
*   [4.3.3Mutual Independence: Video]({{< baseurl >}}/pages/probability/tp12-2/vertical-9c80216b7495)
*   [4.3.4Mutually Independent Dice Rolls]({{< baseurl >}}/pages/probability/tp12-2/vertical-725617c4e7c2)
*   [4.3.5Independent vs Disjoint]({{< baseurl >}}/pages/probability/tp12-2/vertical-6700220de664)
*   [4.3.6Labeled Balls]({{< baseurl >}}/pages/probability/tp12-2/vertical-324cac33b048)
*   [4.3.7Paradox]({{< baseurl >}}/pages/probability/tp12-2/paradox)
*   [\>Independent vs Disjoint]({{< baseurl >}}/pages/probability/tp12-2/vertical-6700220de664)

Mutually Independent Dice Rolls
-------------------------------

  

Consider the following events the rolling 3 dice:

\\(\\begin{align}A\_i&:=\\text{the first die is a \\(i\\), for \\(i\\in\[1,6\]\\)}&\\\\B\_i&:=\\text{the second die is a \\(i\\), for \\(i\\in\[1,6\]\\)}&\\\\C\_i&:=\\text{the third die is a \\(i\\), for \\(i\\in\[1,6\]\\)}&\\\\S\_i&:=\\text{sum of the dice is \\(i\\), for \\(i\\in\[3,18\]\\)}&\\end{align}\\)

{{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="true" >}}&nbsp; \\(A\_1, B\_1, C\_1\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp; \\(A\_1, B\_6, C\_3\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; \\(A\_1, B\_1, S\_3\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; \\(A\_1, B\_1, S\_7\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; \\(A\_1, B\_1, S\_8\\) &nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
{{< quiz_solution >}}Three dice throws are mutually independent. Any pair of dice throws is also independent. \\(\\Pr\[A\_1 \\cap S\_3\]= \\Pr\[A\_1 \\cap B\_1 \\cap C\_1\]=\\frac{1}{216}\\neq \\frac{1}{6}\\cdot\\frac{1}{216}=\\Pr\[A\_1\]\\Pr\[S\_3\].\\) \\(\\Pr\[A\_1 \\cap B\_1 \\cap S\_7\]= \\Pr\[A\_1 \\cap B\_1 \\cap C\_5\]=\\frac{1}{216}\\neq \\frac{1}{6}\\cdot\\frac{1}{6}\\cdot\\frac{15}{216}= \\Pr\[A\_1\]\\Pr\[B\_1\]\\Pr\[S\_7\].\\) \\(\\Pr\[A\_1 \\cap B\_1 \\cap S\_8\]= \\Pr\[A\_1 \\cap B\_1 \\cap C\_6\]=\\frac{1}{216}\\neq \\frac{1}{6}\\cdot \\frac{1}{6}\\cdot\\frac{21}{216}=\\Pr\[A\_1\]\\Pr\[B\_1\]\\Pr\[S\_8\].\\){{< /quiz_solution >}}{{< /quiz_multiple_choice >}}

*   [BackMutual Independence: Video]({{< baseurl >}}/pages/probability/tp12-2/vertical-9c80216b7495)
*   [ContinueIndependent vs Disjoint]({{< baseurl >}}/pages/probability/tp12-2/vertical-6700220de664)