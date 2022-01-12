---
content_type: page
parent_title: 4.7 Sampling & Confidence
parent_uid: a3bc4574-329a-2834-df03-0de577ce1f81
title: 4.7 Sampling & Confidence
uid: b813e15c-ee92-01b1-bead-5e84b0aee9d8
---

*   [<Confidence]({{< baseurl >}}/pages/probability/tp14-1/vertical-b6f0d030cb36)
*   [4.7.1Law Of Large Numbers: Video]({{< baseurl >}}/pages/probability/tp14-1)
*   [4.7.2Not So Strong]({{< baseurl >}}/pages/probability/tp14-1/vertical-84aa6f70d1c0)
*   [4.7.3Independent Sampling Theorem: Video]({{< baseurl >}}/pages/probability/tp14-1/vertical-872c5ec0974e)
*   [4.7.4Sampling Coin Tosses]({{< baseurl >}}/pages/probability/tp14-1/vertical-b7cee8c0e19c)
*   [4.7.5Birthday Matching: Video]({{< baseurl >}}/pages/probability/tp14-1/vertical-82840a0ba306)
*   [4.7.6Birthdays On Naboo]({{< baseurl >}}/pages/probability/tp14-1/vertical-20063bed5f4a)
*   [4.7.7Sampling & Confidence: Video]({{< baseurl >}}/pages/probability/tp14-1/vertical-83cee7032f8c)
*   [4.7.8Confidence]({{< baseurl >}}/pages/probability/tp14-1/vertical-b6f0d030cb36)
*   [4.7.9Random Sampling]({{< baseurl >}}/pages/probability/tp14-1/vertical-0a9b074af4b4)
*   [4.7.10Above Average Number of Fingers]({{< baseurl >}}/pages/probability/tp14-1/vertical-2f9ccec3fdf7)
*   [\>Above Average Number of Fingers]({{< baseurl >}}/pages/probability/tp14-1/vertical-2f9ccec3fdf7)

Random Sampling
---------------

  

You work for the president and you want to estimate the fraction \\(p\\) of voters in the entire nation that will prefer him in the upcoming elections. You do this by random sampling. Specifically, you select \\(n\\) voters independently and randomly, ask them who they are going to vote for, and use the fraction \\(P\\) of those that say they will vote for the President as an estimate for \\(p\\).

1.  Our theorems about sampling and distributions allow us to calculate how confident we can be that the random variable \\(P\\) takes a value near the constant \\(p\\). This calculation uses some facts about voters and the way they are chosen.
    
    {{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;Given a particular voter, the probability of that voter preferring the President is \\(p\\).&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;Given a particular voter, the probability of that voter preferring the President is 1 or 0.&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;The probability that some voter is chosen more than once in the sequence goes to zero as \\(n\\) increases.&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;All voters are equally likely to be selected as the third in our sequence of \\(n\\) choices of voters (assuming \\(n \\geq 3\\)).&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;The probability that the second voter chosen will favor the President, given that the first voter chosen prefers the President, is greater than \\(p\\).&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;The probability that the second voter chosen will favor the President, given that the second voter chosen is from the same state as the first, may not equal \\(p\\).&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}The preference of any particular voter is a constant: either "the President" or "not the President", so (1) is false and (2) is true. (3) is false; in fact, the Birthday "paradox" implies the probability of some voter being chosen more than once rapidly approaches 1 as \\(n\\) grows beyond 100. (4) holds by definition of randomly choosing an item from a set. (5) is false because successive voters in the sequence are chosen independently. (6) is true because, for example, the fraction of voters who prefer the President in the largest states may all be \\(< p\\).{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}
  
3.  Suppose that, according to your calculations, the following is true about your polling:
    
    \\\[\\Pr\[ |P-p| \\leq 0.04 \] \\geq 0.95\\\]
    
    {{< quiz_multiple_choice questionId="Q2_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="false" >}}&nbsp;Mr. President, \\(p\\)=0.53.&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="false" >}}&nbsp;Mr. President, with probability at least 95%, \\(p\\) is within 0.04 of 0.53.&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;Mr. President, either \\(p\\) is within 0.04 of 0.53 or something very strange (5-in-100) has happened.&nbsp;{{< /quiz_choice >}}
    {{< quiz_choice isCorrect="true" >}}&nbsp;Mr. President, we can be 95% confident that \\(p\\) is within 0.04 of 0.53.&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
    {{< quiz_solution >}}You cannot say (1): the only way to know the exact value of the constant \\(p\\) is to ask all 250,000,000 voters.
    
    You cannot say (2) either: \\(p\\) is a \\(constant\\) which can either be or not be within 0.04 of 0.53. If it is, then the probability that it is is 1, and thus at least 0.95, and therefore (2) will be true. If it is not, then the probability that it is is 0, and thus smaller than 0.95, and therefore (2) will be false.
    
    You can say (3): To see why, start with the statement
    
    either \\(|0.53 - p| \\leq 0.04\\) **or** \\(|0.53 - p| > 0.04\\) is true.
    
    which is obviously true. Now read it as follows: Either \\(p\\) is within 0.04 of 0.53 **or** it is not and therefore my random variable \\(P\\) took a value from a set that is hit only 5 times in 100. So, clearly, either \\(p\\) is within 0.04 of 0.53 **or** something strange has happened.
    
    You can say (4): By rephrasing (2) as "confidence" rather than probability, you are correctly indicating that you are talking about the probable behavior of your methodology for sampling \\(p\\), not the actual value of \\(p\\).{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}

*   [BackConfidence]({{< baseurl >}}/pages/probability/tp14-1/vertical-b6f0d030cb36)
*   [ContinueAbove Average Number of Fingers]({{< baseurl >}}/pages/probability/tp14-1/vertical-2f9ccec3fdf7)