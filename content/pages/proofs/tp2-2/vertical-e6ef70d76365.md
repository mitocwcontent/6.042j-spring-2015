---
content_type: page
parent_title: 1.4 Logic & Propositions
parent_uid: 8de160a9-e729-9f7f-ec8a-58aef5106eef
title: 1.4 Logic & Propositions
uid: 4d61a7cb-0514-9b23-d952-27df02bc700f
---

*   [<Logic & Propositions]({{< baseurl >}}/pages/proofs/tp2-2)
*   [1.4.1Propositional Operators: Video]({{< baseurl >}}/pages/proofs/tp2-2)
*   [1.4.2Propositional Operators]({{< baseurl >}}/pages/proofs/tp2-2/vertical-e6ef70d76365)
*   [1.4.3Digital Logic: Video]({{< baseurl >}}/pages/proofs/tp2-2/digital-logic-video)
*   [1.4.4Truth Tables: Video]({{< baseurl >}}/pages/proofs/tp2-2/truth-tables-video)
*   [1.4.5Equivalence and Truth Table]({{< baseurl >}}/pages/proofs/tp2-2/vertical-b8b2711c0ce8)
*   [1.4.6Implies: Video]({{< baseurl >}}/pages/proofs/tp2-2/implies-video)
*   [1.4.7Propositional Logic: Video]({{< baseurl >}}/pages/proofs/tp2-2/propositional-logic-video)
*   [1.4.8Soundness and Validity]({{< baseurl >}}/pages/proofs/tp2-2/vertical-ed6030bda119)
*   [1.4.9Logical Connectives]({{< baseurl >}}/pages/proofs/tp2-2/vertical-a28e46f96fa1)
*   [\>Digital Logic: Video]({{< baseurl >}}/pages/proofs/tp2-2/digital-logic-video)

Propositional Operators
-----------------------

{{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp; \\(P \\text{ XOR } Q\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp; \\(P \\text{ AND } Q\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp; \\(P \\text{ OR } Q\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; \\(\\text{NOT }\[P \\text{ AND } Q\]\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; \\(\\text{NOT }\[P \\text{ OR } Q\]\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; \\(\\text{NOT } P\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; \\(\\text{NOT } Q\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; \\(\\text{NOT } \[P\] \\text{ AND } Q\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp; \\(P \\text{ OR } \\text{NOT } Q\\) &nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
{{< quiz_solution / >}}{{< /quiz_multiple_choice >}}{{< quiz_multiple_choice questionId="Q2_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp; \\(P \\text{ XOR } Q\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; \\(P \\text{ AND } Q\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; \\(P \\text{ OR } Q\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp; \\(\\text{NOT }\[P \\text{ AND } Q\]\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp; \\(\\text{NOT }\[P \\text{ OR } Q\]\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp; \\(\\text{NOT } P\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp; \\(\\text{NOT } Q\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; \\(\\text{NOT } \[P\] \\text{ AND } Q\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp; \\(P \\text{ OR } \\text{NOT } Q\\) &nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
{{< quiz_solution / >}}{{< /quiz_multiple_choice >}}{{< quiz_multiple_choice questionId="Q3_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="true" >}}&nbsp; \\(P \\text{ XOR } Q\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; \\(P \\text{ AND } Q\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp; \\(P \\text{ OR } Q\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp; \\(\\text{NOT }\[P \\text{ AND } Q\]\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; \\(\\text{NOT }\[P \\text{ OR } Q\]\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; \\(\\text{NOT } P\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp; \\(\\text{NOT } Q\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; \\(\\text{NOT } \[P\] \\text{ AND } Q\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp; \\(P \\text{ OR } \\text{NOT } Q\\) &nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
{{< quiz_solution / >}}{{< /quiz_multiple_choice >}}{{< quiz_multiple_choice questionId="Q4_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="true" >}}&nbsp; \\(P \\text{ XOR } Q\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; \\(P \\text{ AND } Q\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp; \\(P \\text{ OR } Q\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp; \\(\\text{NOT }\[P \\text{ AND } Q\]\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; \\(\\text{NOT }\[P \\text{ OR } Q\]\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp; \\(\\text{NOT } P\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; \\(\\text{NOT } Q\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp; \\(\\text{NOT } \[P\] \\text{ AND } Q\\) &nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp; \\(P \\text{ OR } \\text{NOT } Q\\) &nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
{{< quiz_solution / >}}{{< /quiz_multiple_choice >}}

*   [BackLogic & Propositions]({{< baseurl >}}/pages/proofs/tp2-2)
*   [ContinueDigital Logic: Video]({{< baseurl >}}/pages/proofs/tp2-2/digital-logic-video)