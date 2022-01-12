---
content_type: page
parent_title: 1.10 Recursive Definition
parent_uid: dc6ecd4f-10b9-4f9f-9744-a385e4bab210
title: 1.10 Recursive Definition
uid: 07b69d15-ceb4-77f3-20ed-fe861b5c21fc
---

*   [<Recursive Definition]({{< baseurl >}}/pages/proofs/recursive-definition)
*   [1.10.1Recursive Data: Video]({{< baseurl >}}/pages/proofs/recursive-definition)
*   [1.10.2Matching Parentheses]({{< baseurl >}}/pages/proofs/recursive-definition/matching-parentheses)
*   [1.10.3Functions of F18]({{< baseurl >}}/pages/proofs/recursive-definition/functions-of-f18)
*   [1.10.4Structural Induction: Video]({{< baseurl >}}/pages/proofs/recursive-definition/structural-induction-video)
*   [1.10.5Structural Induction: Definition]({{< baseurl >}}/pages/proofs/recursive-definition/structural-induction-definition)
*   [1.10.6Counting Cases]({{< baseurl >}}/pages/proofs/recursive-definition/counting-cases)
*   [1.10.7Recursive Functions: Video]({{< baseurl >}}/pages/proofs/recursive-definition/recursive-functions-video)
*   [\>Functions of F18]({{< baseurl >}}/pages/proofs/recursive-definition/functions-of-f18)

Matching Parentheses
--------------------

  
{{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="true" >}}&nbsp;No string in \\(M\\) can start with a right parenthesis.&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp;Every string in \\(M\\) must start with a left parentheses.&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp;\\(M\\) is an infinite set.&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp;Every string in \\(M\\) must have even length. &nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
{{< quiz_solution >}}For any string of length greater than \\(0\\), if it starts with a right parenthesis, it is immediately unmatched. The empty string also vacuously satisfies this statement.

The empty string is a counterexample.

There are a variety of ways to show \\(M\\) is infinite. For example, for any proposed longest string, simply append "()" to the end.

In order for a string to be matched, its length must be a multiple of 2, for pairs of left and right parentheses. Note that the empty string has length 0 which is also even.{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}

*   [BackRecursive Definition]({{< baseurl >}}/pages/proofs/recursive-definition)
*   [ContinueFunctions of F18]({{< baseurl >}}/pages/proofs/recursive-definition/functions-of-f18)