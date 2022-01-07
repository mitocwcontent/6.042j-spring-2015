---
content_type: page
parent_title: 1.8  Induction
parent_uid: 5179d7c0-c3f7-a60a-33d7-c24d9d219172
title: 1.8  Induction
uid: 204cc8ce-9c42-a967-c8a9-370e652616a2
---

*   [<Induction Rules]({{< baseurl >}}/pages/proofs/tp4-1/vertical-7137716a91a6)
*   [1.8.1Induction: Video]({{< baseurl >}}/pages/proofs/tp4-1)
*   [1.8.2Bogus Induction: Video]({{< baseurl >}}/pages/proofs/tp4-1/vertical-9984d57d43e5)
*   [1.8.3Same Colored Horses]({{< baseurl >}}/pages/proofs/tp4-1/vertical-e9a3ad8170fd)
*   [1.8.4Strong Induction: Video]({{< baseurl >}}/pages/proofs/tp4-1/vertical-828ce2b900d3)
*   [1.8.5Unstacking Game Score]({{< baseurl >}}/pages/proofs/tp4-1/vertical-cc43092b621f)
*   [1.8.6WOP vs Induction: Video \[optional\]]({{< baseurl >}}/pages/proofs/tp4-1/vertical-98aa517cd42e)
*   [1.8.7Strong vs Ordinary Induction vs WOP \[optional\]]({{< baseurl >}}/pages/proofs/tp4-1/vertical-b16ab258826d)
*   [1.8.8Induction by n+3]({{< baseurl >}}/pages/proofs/tp4-1/vertical-32c871c0cb9b)
*   [1.8.9Induction Rules]({{< baseurl >}}/pages/proofs/tp4-1/vertical-7137716a91a6)
*   [1.8.10Postage by Induction]({{< baseurl >}}/pages/proofs/tp4-1/vertical-a8ffdfcb631b)
*   [1.8.11A Bogus Induction]({{< baseurl >}}/pages/proofs/tp4-1/vertical-87911985518e)
*   [\>A Bogus Induction]({{< baseurl >}}/pages/proofs/tp4-1/vertical-87911985518e)

Postage by Induction
--------------------

  
{{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;Induction (either Ordinary or Strong) would be simpler than WOP.&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp;Ordinary Induction would be the easiest to justify.&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp;Induction, Strong Induction, and WOP all work, but Ordinary Induction is simplest in this case.&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp;Induction, Strong Induction, and WOP all work, but Strong Induction and WOP are easier in this case.&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp;Induction, Strong Induction, and WOP all work, but WOP would be least desirable, since proof by contradiction should be avoided.&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
{{< quiz_solution >}}Proofs using the three principles, Ordinary Induction, Strong Induction, and Well Ordering, are equivalent - a proof of a theorem using one of them can be reformatted into a proof using either of the other two without additional insights. In this postage problem, however, Ordinary Induction requires an extra quantifier in the induction hypothesis, making the two other approaches more straightforward.

Specifically, strong induction is a good choice for this problem, using the straightforward induction hypothesis

\\(P(n)::= \\)\[4-cent and 5-cent stamps can form \\(n \\)-cent postage\]

with the base cases \\(n = 12, 13, 14, \\text{ and } 15.\\)

Using the Well Ordering Principle is also straightforward. The proof could start with the set of all _counterexamples_, namely,

\\(\\{n \\ge 12 \\;| \\; n \\text{-cent postage CANNOT be formed with } 4 \\text{-cent and } 5 \\text{-cent stamps } \\} \\)

Assuming that this set is not empty, the Well Ordering Principle implies that it has a minimum element. A contradiction can then be proved using the same base cases as those in the Strong Induction proof and the same reasoning as in the inductive step.

Let's try Ordinary Induction. Below is the induction hypothesis, \\(Q(n)\\), with the addition \\(\\forall \\):

\\(Q(n)::= \\forall k, 12 \\le k \\le n. \[4 \\text{-cent and } 5 \\text{-cent stamps can form } k \\text{-cent postage}\]\\)

Having proved \\(\\forall n.Q(n)\\) by Ordinary Induction, the desired assertion about postage: \\(\\forall n\\ge 12.P(n)\\) would then be an immediate corollary.{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}

*   [BackInduction Rules]({{< baseurl >}}/pages/proofs/tp4-1/vertical-7137716a91a6)
*   [ContinueA Bogus Induction]({{< baseurl >}}/pages/proofs/tp4-1/vertical-87911985518e)