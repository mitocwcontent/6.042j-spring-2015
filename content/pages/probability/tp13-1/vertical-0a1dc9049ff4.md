---
content_type: page
parent_title: 4.5 Expectation
parent_uid: 025c498f-3f5e-1c53-924f-7e40eb06a220
title: 4.5 Expectation
uid: 90fda877-efb6-3e46-64c0-2e2391cf24bc
---

*   [<Great Expectations]({{< baseurl >}}/pages/probability/tp13-1/vertical-88fafb62d4f8)
*   [4.5.1Expectation: Video]({{< baseurl >}}/pages/probability/tp13-1)
*   [4.5.2Uneven Dice]({{< baseurl >}}/pages/probability/tp13-1/vertical-d324b518e79a)
*   [4.5.3Expected Number Of Heads: Video]({{< baseurl >}}/pages/probability/tp13-1/vertical-07d1783f0da3)
*   [4.5.4Expected Number of Heads]({{< baseurl >}}/pages/probability/tp13-1/vertical-932dca21218a)
*   [4.5.5Total Expectation: Video]({{< baseurl >}}/pages/probability/tp13-1/vertical-6913b2097610)
*   [4.5.6Another Dice and Coin Game]({{< baseurl >}}/pages/probability/tp13-1/vertical-3506cf32b49b)
*   [4.5.7Mean Time to Failure: Video]({{< baseurl >}}/pages/probability/tp13-1/vertical-e8dee31ddd76)
*   [4.5.8Three Machines Failing]({{< baseurl >}}/pages/probability/tp13-1/vertical-f2cac6de0392)
*   [4.5.9Linearity of Expectation: Video]({{< baseurl >}}/pages/probability/tp13-1/vertical-49ea207a6233)
*   [4.5.10Fair and Biased Coins]({{< baseurl >}}/pages/probability/tp13-1/vertical-4f20b89f006a)
*   [4.5.11Binomial Board Breaking]({{< baseurl >}}/pages/probability/tp13-1/vertical-49116fd8c065)
*   [4.5.12Great Expectations]({{< baseurl >}}/pages/probability/tp13-1/vertical-88fafb62d4f8)
*   [4.5.13Expectation of a Uniform Distribution]({{< baseurl >}}/pages/probability/tp13-1/vertical-0a1dc9049ff4)
*   [\>Deviation: Markov & Chebyshev Bounds]({{< baseurl >}}/pages/probability/tp13-2)

Expectation of a Uniform Distribution
-------------------------------------

Let \\(X\\) be a random variable with uniform distribution over the integers from \\(-n\\) to \\(n\\). Let \\(Y := X^2\\).

{{< quiz_multiple_choice questionId="Q1_div" >}}{{< quiz_choices >}}{{< quiz_choice isCorrect="true" >}}&nbsp;\\(E\[X\] = 0\\)&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp;\\(E\[Y\] = 0\\)&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp;\\(E\[Y\] > E\[X\]\\)&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp;\\(E\[X+Y\] = E\[X\]+E\[Y\]\\)&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="true" >}}&nbsp; \\(E\[XY\] = E\[X\]E\[Y\]\\)&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp;\\(X\\) and \\(Y\\) are independent variables&nbsp;{{< /quiz_choice >}}
{{< quiz_choice isCorrect="false" >}}&nbsp;\\(E\[Y^2\] = E\[Y\]\\)&nbsp;{{< /quiz_choice >}}{{< /quiz_choices >}}
{{< quiz_solution >}}1.  Since \\(PDF\_X(x)\\) is symmetric around 0, we know the mean has to be 0.
2.  All values of \\(Y\\) are nonnegative and most of them are actually positive with non-zero probability. There is no way for the mean to be 0. It has to be some positive value.
3.  Obvious, since \\(E\[X\]=0\\) and \\(E\[Y\]>0\\).
4.  True by linearity of expectation, no matter what \\(X\\) and \\(Y\\) are.
5.  This is tricky. The equation does not hold in general for non-independent \\(X\\) and \\(Y\\). However, in this particular case, it happens to hold. To see this, note that the right hand side is 0, since \\(E\[X\]=0\\). At the same time, the random variable \\(XY=X^3\\). Its PDF is symmetric around 0, so its mean must be 0 as well.
6.  \\(X\\) and \\(Y\\) are obviously not independent.
7.  \\(E\[Y\]=\\sum\_{i=0}^n 2i^2\\frac{1}{2n+1} < \\sum\_{i=0}^n 2i^4\\frac{1}{2n+1} = E\[Y^2\]\\).{{< /quiz_solution >}}{{< /quiz_multiple_choice >}}

*   [BackGreat Expectations]({{< baseurl >}}/pages/probability/tp13-1/vertical-88fafb62d4f8)
*   [ContinueDeviation: Markov & Chebyshev Bounds]({{< baseurl >}}/pages/probability/tp13-2)