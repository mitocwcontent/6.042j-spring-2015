---
content_type: page
parent_title: 1.2 Proof Methods
parent_uid: 604f8e07-2680-3e77-8aac-7885f0f6eaf0
title: 1.2 Proof Methods
uid: 62bbb99c-a9ee-dcc2-6f2b-179d17f08907
---

*   [<Friends and Strangers]({{< baseurl >}}/pages/proofs/tp1-2/vertical-9380624edebc)
*   [1.2.1Proof By Contradiction: Video]({{< baseurl >}}/pages/proofs/tp1-2)
*   [1.2.2Proof By Contradiction]({{< baseurl >}}/pages/proofs/tp1-2/vertical-2835de2f30b6)
*   [1.2.3Proof By Cases: Video]({{< baseurl >}}/pages/proofs/tp1-2/vertical-f502ca28cf17)
*   [1.2.4When to Prove by Cases]({{< baseurl >}}/pages/proofs/tp1-2/vertical-ba5ad72ae7ec)
*   [1.2.5Friends and Strangers]({{< baseurl >}}/pages/proofs/tp1-2/vertical-9380624edebc)
*   [1.2.6A Bogus Proof by Cases]({{< baseurl >}}/pages/proofs/tp1-2/vertical-70c0b579a359)
*   [1.2.7A Bogus Proof by Contradiction]({{< baseurl >}}/pages/proofs/tp1-2/vertical-cdf72f5374ab)
*   [\>A Bogus Proof by Contradiction]({{< baseurl >}}/pages/proofs/tp1-2/vertical-cdf72f5374ab)

A Bogus Proof by Cases
----------------------

  

Which step(s) contain the logical error?

{{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;This proof is by case analysis.&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; There are two cases:

**Case 1**: _\\(a\\) is positive._

**Case 2**: _\\(a\\) is negative._

&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp; One of these cases must always hold, because an integer is either positive or negative. &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp;**Case 1**: Suppose \\(a\\) is positive. &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; Since \\(a\\) is an integer, we must have that \\(a\\geq 1\\). &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; Hence, \\(2a^2 = 2a\\cdot a \\geq 2a\\cdot 1 > a\\). &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; This implies the claim holds in Case 1. &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp;**Case 2**: Suppose \\(a\\) is negative. &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; Since \\(a\\) is an integer, we must have that \\(a\\leq -1\\). &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; Hence, \\(2a^2 \\geq 2\\cdot (-1\\cdot -1) = 2 > -1 \\geq a\\). &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; This implies the claim holds in Case 2. &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; The claim therefore holds in both cases. \\(\\blacksquare\\) &nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
{{< quiz_solution >}}Explanation

These two cases are NOT exhaustive, they leave out the case where \\(a=0\\), in which case \\(2a^2=2\\cdot 0^2=0=a\\).

Line 2 is not logically erranous because saying "There are two cases" implies the existence of **at least** two cases.

Line 3 claims that those are the ONLY two cases, and is therefore incorrect.

You should note that this proof can easily be modified to prove the correct claim that for any integer \\(a\\), \\(2a^2 \\geq a\\){{< /quiz_solution >}}{{< /quiz_multiple_choice >}}

*   [BackFriends and Strangers]({{< baseurl >}}/pages/proofs/tp1-2/vertical-9380624edebc)
*   [ContinueA Bogus Proof by Contradiction]({{< baseurl >}}/pages/proofs/tp1-2/vertical-cdf72f5374ab)