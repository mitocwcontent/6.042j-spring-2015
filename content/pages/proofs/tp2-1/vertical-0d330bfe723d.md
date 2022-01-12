---
content_type: page
parent_title: 1.3 Well Ordering Principle
parent_uid: 376535e1-bbaf-1919-fdc3-bdd7b7043dea
title: 1.3 Well Ordering Principle
uid: 741f3260-8193-4295-dbbc-bb664f773ab7
---

*   [<Well Ordering Principle - Examples]({{< baseurl >}}/pages/proofs/tp2-1/vertical-69c747468b20)
*   [1.3.1Well Ordering Principle 1: Video]({{< baseurl >}}/pages/proofs/tp2-1)
*   [1.3.2Domain for Well Ordering Principle]({{< baseurl >}}/pages/proofs/tp2-1/vertical-1d9c2a0e507a)
*   [1.3.3Well Ordering Principle 2: Video]({{< baseurl >}}/pages/proofs/tp2-1/vertical-735460178366)
*   [1.3.4Well Ordering Proofs and Counterexamples]({{< baseurl >}}/pages/proofs/tp2-1/vertical-001819756631)
*   [1.3.5Well Ordering Principle 3: Video]({{< baseurl >}}/pages/proofs/tp2-1/vertical-4bb7930de7ec)
*   [1.3.6WOP Proof for Geometric Sum]({{< baseurl >}}/pages/proofs/tp2-1/vertical-21c9adce63e4)
*   [1.3.7Well Ordering Principle - Examples]({{< baseurl >}}/pages/proofs/tp2-1/vertical-69c747468b20)
*   [1.3.8A Bogus Well Ordering Principle Proof]({{< baseurl >}}/pages/proofs/tp2-1/vertical-0d330bfe723d)
*   [\>Logic & Propositions]({{< baseurl >}}/pages/proofs/tp2-2)

A Bogus Well Ordering Principle Proof
-------------------------------------

  

The Fibonacci numbers

\\(0, 1, 1, 2, 3, 5, 8, 13, \\ldots \\)

are defined as follows. Let \\(F(n)\\) be the \\(n^{th}\\) Fibonacci number. Then

*   \\(F(0) ::= 0\\)
*   \\(F(1) ::= 1\\)
*   \\(F(n) ::= F(n-1) + F(n-2), \\;\\; \\text{ for } n \\geq 2 \\text{ } (\\star)\\)

* * *

  

Identify which step(s) contain the logical error!

{{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp; The proof is by the WOP. &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; Let \\(Even(n)\\) mean that \\(F(n)\\) is even. &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; Let \\(C\\) be the set of counterexamples to the assertion that \\(Even(n)\\) holds for all \\(n \\geq 0\\). That is

\\(C ::=\\{n \\geq 0 \\;|\\; \\text{NOT}(Even(n))\\}\\)

We prove by contradiction that \\(C\\) is empty. &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; Assume that \\(C\\) is not empty. &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; By the WOP, there is a least nonnegative integer, \\(m \\in C\\). &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; Then \\(m \\geq 0\\), since \\(F(0) = 0\\) is an even number. &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; Now, suppose \\(m \\geq 2\\) so the definition \\((\\star)\\) of \\(F(m)\\) applies. &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; In this case, both \\(F(m-1)\\) and \\(F(m-2)\\) are both even, since \\(m\\) is the minimum counterexample such that \\(F(m)\\) is not even. &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; But by \\((\\star)\\) in the case that \\(n = m\\), we see that \\(F(m)\\) is the sum of two even numbers, so it is also even; thus \\(Even(m)\\) is true. &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; This deduction contradicts the condition in the definition of \\(m\\) that \\(\\text{NOT}(Even(m))\\) is true. &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp; This contradiction implies that \\(C\\) must be empty. Hence, \\(F(n)\\) is even for all \\(n \\geq 0.\\;\\;\\blacksquare\\) &nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
{{< quiz_solution >}}Steps 1 through 10 contain no logical errors. The fatal flaw is in the final step 11. The proof only shows that there is a minimum \\(m\\) in \\(C\\) and it is not 0. The assumption that \\(m \\geq 2\\) leads to a contradiction; it leaves the case \\(m = 1\\) unexamined, while in fact, \\(1 \\in C\\). (The supposition that "\\(m \\geq 2\\) so the definition (\*) of \\(F(m)\\) applies" is no excuse for ignoring the case \\(m = 1\\).)

If you said that step 7 contains a logical error, you were on the right track. The natural place to handle the case \\(F(1)\\) would have been right after step 6. But the the proof explicitly avoided the case \\(m = 1\\), by saying, "suppose \\(m \\geq 2\\)." However, there is no _logical_ error in line 7: it is simply the beginning of a proof for the case when \\(m \\geq 2\\). On the other hand, it's reasonable to say that line 7 is the place where the proof makes an organizational, or perhaps strategic, error because it skips the \\(m = 1\\) case.{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}

*   [BackWell Ordering Principle - Examples]({{< baseurl >}}/pages/proofs/tp2-1/vertical-69c747468b20)
*   [ContinueLogic & Propositions]({{< baseurl >}}/pages/proofs/tp2-2)