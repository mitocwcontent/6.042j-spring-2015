---
content_type: page
parent_title: 4.4 Random Variables, Density Functions
parent_uid: 5d000a4e-2a13-daae-80b1-331e90d2f442
title: 4.4 Random Variables, Density Functions
uid: e7aa0adb-5b48-0a55-efe0-0aed18e3a0ae
---
<ul class="navigation pagination"><li id="top_bck_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp12-3/vertical-5a2c58463701';><<span>Late For A Date</span></a></li><li id="flp_btn_1" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp12-3'>4.4.1<span>Bigger Number Game: Video</span></a></li><li id="flp_btn_2" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp12-3/vertical-af2ad400f984'>4.4.2<span>Random Variables: Independence: Video</span></a></li><li id="flp_btn_3" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp12-3/vertical-12926a05d1ba'>4.4.3<span>Odd Heads and Matches</span></a></li><li id="flp_btn_4" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp12-3/vertical-c596d4103fc3'>4.4.4<span>Random Variables: Uniform &amp; Binomial: Video</span></a></li><li id="flp_btn_5" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp12-3/vertical-5a2c58463701'>4.4.5<span>Late For A Date</span></a></li><li id="flp_btn_6" class="button_selected"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp12-3/vertical-fd04358ad7c2'>4.4.6<span>A Random Number</span></a></li><li id="flp_btn_7" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp12-3/vertical-0527081b6af3'>4.4.7<span>PDF to CDF</span></a></li><li id="flp_btn_8" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp12-3/vertical-f27f5990f502'>4.4.8<span>Dice And Coin Game</span></a></li><li id="top_continue_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp12-3/vertical-0527081b6af3';>><span>PDF to CDF</span></a></li></ul><h2 class="subhead">A Random Number</h2><div class="self_assessment">
<br display_name="A Random Number" url_name="A_Random_Number" />
<p display_name="A Random Number" url_name="A_Random_Number_0">
    Here is a process to construct a random number:
    <ol><li>
        Flip a biased coin that comes up heads with probability \(\frac{3}{5}\).
      </li><li><ul><li>
            If you get heads, you roll a fair die and return the result.
          </li><li>
            Otherwise, you flip a fair coin 3 times and return twice the number of heads.
          </li></ul></li></ol>
</p>
<p display_name="A Random Number" url_name="A_Random_Number_1">
    Let \(N\) be the number that you return.
  </p>
<p display_name="A Random Number" url_name="A_Random_Number_2">
    Let \(F\) be the indicator random variable for the first coin flip (1 if heads and 0 if tails).
  </p>
<p>
Please answer in the form of a decimal with three significant figures.
  </p>
<ol display_name="A Random Number" url_name="A_Random_Number_3">
<li>
<div id="Q1_div" class="problem_question"><p>What is \(\Pr[N=0]\)?</p><fieldset><legend class="visually-hidden">Exercise 1</legend><div class="choice"><label id="Q1_label"><span id="Q1_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Numerical Response</span><input type="text" id="Q1_input" value="" onkeypress="numericTypedOrDropDownSelected(1)" class="problem_text_input"><input type="hidden" id="Q1_ans" value=".05"><input type="hidden" id="Q1_tolerance" value="0.0001"><span id="Q1_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><p id="S1_ans" tabindex="-1" class="problem_answer"></p></fieldset></div><div id="S1_div" class="problem_solution" tabindex="-1">The only way to get 0 is if you first flip tails and then flip 0 heads. Therefore,
        <center>\(\Pr[N=0] = \Pr[F=0 \text{ AND } 0 \text{ heads}] = \Pr[F=0]\Pr[0 \text{ heads}] = \frac{2}{5}\cdot\frac{1}{8}=\frac{1}{20}\).</center>
</div></li>
<br />
<li>
<div id="Q2_div" class="problem_question"><p>What is \(\Pr[N=3]\)?</p><fieldset><legend class="visually-hidden">Exercise 2</legend><div class="choice"><label id="Q2_label"><span id="Q2_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Numerical Response</span><input type="text" id="Q2_input" value="" onkeypress="numericTypedOrDropDownSelected(2)" class="problem_text_input"><input type="hidden" id="Q2_ans" value=".1"><input type="hidden" id="Q2_tolerance" value="0.0001"><span id="Q2_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><p id="S2_ans" tabindex="-1" class="problem_answer"></p></fieldset></div><div id="S2_div" class="problem_solution" tabindex="-1">
        The only way to get 3 is if you first flip heads and then roll a 3. Therefore,
        <center>\(\Pr[N=3] = \Pr[F=1 \text{ AND roll } 3] = \Pr[F=1] \Pr[\text{roll } 3] = \frac{3}{5}\cdot \frac{1}{6} = \frac{1}{10}\).</center>
</div></li>
<br />
<li>
<div id="Q3_div" class="problem_question"><p>What is \(\Pr[N=6]\)?</p><fieldset><legend class="visually-hidden">Exercise 3</legend><div class="choice"><label id="Q3_label"><span id="Q3_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Numerical Response</span><input type="text" id="Q3_input" value="" onkeypress="numericTypedOrDropDownSelected(3)" class="problem_text_input"><input type="hidden" id="Q3_ans" value=".15"><input type="hidden" id="Q3_tolerance" value="0.0001"><span id="Q3_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><p id="S3_ans" tabindex="-1" class="problem_answer"></p></fieldset></div><div id="S3_div" class="problem_solution" tabindex="-1">
        You can get 6 either by flipping heads and rolling a 6 or by flipping tails and then flipping 3 heads. Therefore,
        <center>\(\Pr[N=6] = \Pr[F=1 \text{ AND roll } 6] + \Pr[F=0 \text{ AND } 3 \text{ heads}] = \frac{3}{5}\cdot \frac{1}{6} + \frac{2}{5}\cdot \frac{1}{8} = \frac{3}{20}\).</center>
</div></li>
<br />
<li>
<div id="Q4_div" class="problem_question"><p>What is \(\Pr[N=7]\)?</p><fieldset><legend class="visually-hidden">Exercise 4</legend><div class="choice"><label id="Q4_label"><span id="Q4_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Numerical Response</span><input type="text" id="Q4_input" value="" onkeypress="numericTypedOrDropDownSelected(4)" class="problem_text_input"><input type="hidden" id="Q4_ans" value="0"><input type="hidden" id="Q4_tolerance" value="0.0001"><span id="Q4_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><p id="S4_ans" tabindex="-1" class="problem_answer"></p></fieldset></div><div id="S4_div" class="problem_solution" tabindex="-1">There is no way to end up with the number 7.</div></li>
<br />
<li>
<div id="Q5_div" class="problem_question"><p>What is \(\Pr[N=6\;|\;F=0]\)?</p><fieldset><legend class="visually-hidden">Exercise 5</legend><div class="choice"><label id="Q5_label"><span id="Q5_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Numerical Response</span><input type="text" id="Q5_input" value="" onkeypress="numericTypedOrDropDownSelected(5)" class="problem_text_input"><input type="hidden" id="Q5_ans" value=".125"><input type="hidden" id="Q5_tolerance" value="0.0001"><span id="Q5_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><p id="S5_ans" tabindex="-1" class="problem_answer"></p></fieldset></div><div id="S5_div" class="problem_solution" tabindex="-1">
        Given that \(F=0\), we know that the first coin flip was tails. So, we are in the case where the fair coin is flipped 3 times.
        In that case, we get 6 only by flipping 3 heads. The probability of this happening is \(\frac{1}{8}\).
      </div></li>
<br />
<li>
<div id="Q6_div" class="problem_question"><p>What is \(\Pr[F=0\;|\;N=6]\)?</p><fieldset><legend class="visually-hidden">Exercise 6</legend><div class="choice"><label id="Q6_label"><span id="Q6_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Numerical Response</span><input type="text" id="Q6_input" value="" onkeypress="numericTypedOrDropDownSelected(6)" class="problem_text_input"><input type="hidden" id="Q6_ans" value=".33"><input type="hidden" id="Q6_tolerance" value="0.0001"><span id="Q6_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><p id="S6_ans" tabindex="-1" class="problem_answer"></p></fieldset></div><div id="S6_div" class="problem_solution" tabindex="-1">
        We use the definition of conditional probability to compute:
        <center>\(\Pr[F=0\;|\;N=6] = \dfrac{\Pr[F=0 \text{ AND } N=6]}{\Pr[N=6]} = \dfrac{\frac{2}{5}\cdot \frac{1}{8}}{\frac{3}{20}} = \frac{1}{3}\),</center>
        (where, for the denominator, we used the answer to a previous question). Hence, if somebody else has run the process and
        ended up with 6, we know there is 1 in 3 chance that he had to flip the fair coin.
      </div></li>
<br />
<li>
<div id="Q7_div" class="problem_question"><p>What is \(\Pr[N+F=5]\)?</p><fieldset><legend class="visually-hidden">Exercise 7</legend><div class="choice"><label id="Q7_label"><span id="Q7_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Numerical Response</span><input type="text" id="Q7_input" value="" onkeypress="numericTypedOrDropDownSelected(7)" class="problem_text_input"><input type="hidden" id="Q7_ans" value=".1"><input type="hidden" id="Q7_tolerance" value="0.0001"><span id="Q7_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><p id="S7_ans" tabindex="-1" class="problem_answer"></p></fieldset></div><div id="S7_div" class="problem_solution" tabindex="-1">
        If \(F=0\), then we are flipping the fair coin and doubling the number of heads, so \(N\) is even, and therefore, \(N+F\) cannot be odd.
        Hence, the only way for \(N+F\) to be odd is if \(F=1\). Then \(N+F=5\) if and only if \(N=4\), which happens exactly when we roll a 4. Overall,
        <center>\(\Pr[N+F=5] = \Pr[F=1 \text{ AND } N=4] = \Pr[F=1] \Pr[\text{roll } 4] = \frac{3}{5}\cdot \frac{1}{6} = \frac{1}{10}\).</center>
</div></li>
<br />
<li>
<div id="Q8_div" class="problem_question"><p>What is \(\Pr[N+F=6]\)?</p><fieldset><legend class="visually-hidden">Exercise 8</legend><div class="choice"><label id="Q8_label"><span id="Q8_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Numerical Response</span><input type="text" id="Q8_input" value="" onkeypress="numericTypedOrDropDownSelected(8)" class="problem_text_input"><input type="hidden" id="Q8_ans" value=".15"><input type="hidden" id="Q8_tolerance" value="0.0001"><span id="Q8_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><p id="S8_ans" tabindex="-1" class="problem_answer"></p></fieldset></div><div id="S8_div" class="problem_solution" tabindex="-1">
        This can happen either because \(F=1\) and \(N=5\) or because \(F=0\) and \(N=6\).
        <center>\(\Pr[N+F=6] = \Pr[F=1 \text{ AND } N=5] + \Pr[F=0 \text{ AND } N=6] = \frac{3}{5}\cdot \frac{1}{6} + \frac{2}{5}\cdot \frac{1}{8} = \frac{3}{20}\).</center>
</div><div class="action"><button id="Q1_button" onclick="checkAnswer({1: 'numerical', 2: 'numerical', 3: 'numerical', 4: 'numerical', 5: 'numerical', 6: 'numerical', 7: 'numerical', 8: 'numerical'})" class="problem_mo_button">Check</button><button id="Q1_button_show" onclick="showHideSolution({1: 'numerical', 2: 'numerical', 3: 'numerical', 4: 'numerical', 5: 'numerical', 6: 'numerical', 7: 'numerical', 8: 'numerical'}, 1, [1, 2, 3, 4, 5, 6, 7, 8])" class="problem_mo_button">Show Answer</button></div></li>
</ol>
</div><ul class="navigation progress"><li id="bck_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp12-3/vertical-5a2c58463701';>Back<span>Late For A Date</span></a></li><li id="continue_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp12-3/vertical-0527081b6af3';>Continue<span>PDF to CDF</span></a></li></ul>