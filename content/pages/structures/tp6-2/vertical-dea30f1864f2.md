---
content_type: page
parent_title: 2.4  RSA Encryption
parent_uid: df8008a7-9d68-087d-809b-bd4cc447cdea
title: 2.4  RSA Encryption
uid: 49990f53-f4a5-d8e5-3907-395cea3d37ee
---

*   [<Relative Primality]({{< baseurl >}}/pages/structures/tp6-2/vertical-d2f6dc0d86f4)
*   [2.4.1RSA Public Key Encryption: Video]({{< baseurl >}}/pages/structures/tp6-2)
*   [2.4.2RSA Encryption]({{< baseurl >}}/pages/structures/tp6-2/vertical-3299faa6fc3d)
*   [2.4.3Reducing Factoring To SAT: Video]({{< baseurl >}}/pages/structures/tp6-2/vertical-10e2576c9510)
*   [2.4.4Relative Primality]({{< baseurl >}}/pages/structures/tp6-2/vertical-d2f6dc0d86f4)
*   [2.4.5RSA computations]({{< baseurl >}}/pages/structures/tp6-2/vertical-dea30f1864f2)
*   [\> Digraphs: Walks & Paths]({{< baseurl >}}/pages/structures/tp6-3)

RSA computations
----------------

  

The feasibility and security of the RSA public-key encryption system using keys based on 300-digit primes \\(p, q\\) depends on the fact that certain computations listed below are "easy" and certain others are "hard."

1.  {{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="true" >}}&nbsp;testing if a 300-digit number is prime&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;finding \\(q\\) given \\(p\\) and the product \\(n ::= pq\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;finding \\(n ::= pq\\) given \\(p,q\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;finding 300-digit primes \\(p,q\\) given \\(n ::= pq\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;finding \\(\\Phi(pq)\\) given \\(p,q\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;generating 300 random digits&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;finding a 300-digit prime number&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;factoring a 600-digit number&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;testing whether a 300-digit number is relatively prime to a given 600-digit number&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;finding a 300-digit number that is relatively prime to a given 300-digit number&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;finding an inverse (if there is one) modulo a 600-digit number of a 300-digit number&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;raising a 600-digit number to a 600-digit power&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;finding the remainder on division by a 600 digit number \\(n\\) of a 600 digit number raised to a 600 digit power&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}2: EASY but IRRELEVANT  
    4,8: HARD  
    12: 36000-digit arithmetic is feasible, say using Mathematica, but IRRELEVANT{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
2.  Which of the following computations have to be "hard" in order for RSA to be secure using keys based on 300-digit primes \\(p,q\\)?  
    _Note that there are some hard computations in this list that are not relevant to RSA._{{< quiz_multiple_choice questionId="Q2_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;testing if a 300-digit number is prime&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;finding \\(q\\) given \\(p\\) and the product \\(n ::= pq\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;finding \\(n ::= pq\\) given \\(p,q\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;finding 300-digit primes \\(p,q\\) given \\(n ::= pq\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;finding \\(\\Phi(pq)\\) given \\(p,q\\)&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;generating 300 random digits&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;finding a 300-digit prime number&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;factoring a 600-digit number&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;testing whether a 300-digit number is relatively prime to a given 600-digit number&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;finding a 300-digit number that is relatively prime to a given 300-digit number&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;finding an inverse (if there is one) modulo a 600-digit number of a 300-digit number&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;raising a 600-digit number to a 600-digit power&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;finding the remainder on division by a 600-digit number \\(n\\) of a 600-digit number raised to a 600-digit power&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}See above explanation.{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}

*   [BackRelative Primality]({{< baseurl >}}/pages/structures/tp6-2/vertical-d2f6dc0d86f4)
*   [Continue Digraphs: Walks & Paths]({{< baseurl >}}/pages/structures/tp6-3)