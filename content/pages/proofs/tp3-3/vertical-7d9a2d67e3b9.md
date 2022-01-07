---
content_type: page
parent_title: 1.7 Binary Relations
parent_uid: dc4329a2-0693-5f01-be73-cf0b227cc3ed
title: 1.7 Binary Relations
uid: f32fdc0c-97b3-80c9-9f28-e8ec9afa8b83
---

*   [<In- ,Sur-, and Bijections]({{< baseurl >}}/pages/proofs/tp3-3/vertical-e3a6326108c6)
*   [1.7.1Relations: Video]({{< baseurl >}}/pages/proofs/tp3-3)
*   [1.7.2Range of a Relation]({{< baseurl >}}/pages/proofs/tp3-3/vertical-70020f5936fa)
*   [1.7.3Relational Mappings: Video]({{< baseurl >}}/pages/proofs/tp3-3/vertical-360a6e85d0f4)
*   [1.7.4Total Injection]({{< baseurl >}}/pages/proofs/tp3-3/vertical-5c792a4ae3f8)
*   [1.7.5Finite Cardinality: Video]({{< baseurl >}}/pages/proofs/tp3-3/vertical-aecd80da5c9a)
*   [1.7.6A inj B]({{< baseurl >}}/pages/proofs/tp3-3/vertical-faefc8383410)
*   [1.7.7Total Relations]({{< baseurl >}}/pages/proofs/tp3-3/vertical-62aa874eafae)
*   [1.7.8Surjective Relations]({{< baseurl >}}/pages/proofs/tp3-3/vertical-73dfbcd9adb9)
*   [1.7.9Inverse Relations]({{< baseurl >}}/pages/proofs/tp3-3/vertical-b100bd3fedc5)
*   [1.7.10In- ,Sur-, and Bijections]({{< baseurl >}}/pages/proofs/tp3-3/vertical-e3a6326108c6)
*   [1.7.11Mapping Lemma: Sizes of Domains and Codomains]({{< baseurl >}}/pages/proofs/tp3-3/vertical-7d9a2d67e3b9)
*   [\> Induction]({{< baseurl >}}/pages/proofs/tp4-1)

Mapping Lemma: Sizes of Domains and Codomains
---------------------------------------------

  

For any binary relation \\(R: A \\to B \\) and subset \\(S \\subseteq A \\), let \\( R(S) \\) be the image of \\(S \\) under \\(R \\). An example of such an image is the doubling function with domain and codomain equal to the real numbers:

\\(sRt \\text{ IFF } t=2s \\)

such that \\(R(\\{0,3,11\\}) = \\{0,6,22\\} \\). Another example, \\(R(\\mathbb{Z}) \\), is the set of all even integers. For any finite set, we let \\(|S| \\) denotes the size (number of elements) of \\(S \\).

* * *

Now assume \\(R \\) is some **total function** and \\(A \\) is finite. Fill in the blanks to produce the **strongest** correct version of the following statements:

1.  {{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;\\(<\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;\\(\\leq\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(=\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(\\geq\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(>\\)&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}Note that \\(R(A)\\subseteq B \\).{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
2.  {{< quiz_multiple_choice questionId="Q2_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;\\(<\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(\\leq\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(=\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;\\(\\geq\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(>\\)&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution / >}}{{< /quiz_multiple_choice >}}
3.  {{< quiz_multiple_choice questionId="Q3_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;\\(<\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(\\leq\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;\\(=\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(\\geq\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(>\\)&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution / >}}{{< /quiz_multiple_choice >}}
4.  {{< quiz_multiple_choice questionId="Q4_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;\\(<\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(\\leq\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;\\(=\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(\\geq\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(>\\)&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution / >}}{{< /quiz_multiple_choice >}}
5.  {{< quiz_multiple_choice questionId="Q5_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;\\(<\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(\\leq\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;\\(=\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(\\geq\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;\\(>\\)&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution / >}}{{< /quiz_multiple_choice >}}

*   [BackIn- ,Sur-, and Bijections]({{< baseurl >}}/pages/proofs/tp3-3/vertical-e3a6326108c6)
*   [Continue Induction]({{< baseurl >}}/pages/proofs/tp4-1)