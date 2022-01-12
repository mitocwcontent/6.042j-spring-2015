---
content_type: page
parent_title: 4.5 Expectation
parent_uid: 025c498f-3f5e-1c53-924f-7e40eb06a220
title: 4.5 Expectation
uid: 806a4693-2318-694a-48c3-8ec44933fcaf
---
<ul class="navigation pagination"><li id="top_bck_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-1/vertical-49116fd8c065';><<span>Binomial Board Breaking</span></a></li><li id="flp_btn_1" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-1'>4.5.1<span>Expectation: Video</span></a></li><li id="flp_btn_2" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-1/vertical-d324b518e79a'>4.5.2<span>Uneven Dice</span></a></li><li id="flp_btn_3" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-1/vertical-07d1783f0da3'>4.5.3<span>Expected Number Of Heads: Video</span></a></li><li id="flp_btn_4" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-1/vertical-932dca21218a'>4.5.4<span>Expected Number of Heads</span></a></li><li id="flp_btn_5" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-1/vertical-6913b2097610'>4.5.5<span>Total Expectation: Video</span></a></li><li id="flp_btn_6" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-1/vertical-3506cf32b49b'>4.5.6<span>Another Dice and Coin Game</span></a></li><li id="flp_btn_7" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-1/vertical-e8dee31ddd76'>4.5.7<span>Mean Time to Failure: Video</span></a></li><li id="flp_btn_8" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-1/vertical-f2cac6de0392'>4.5.8<span>Three Machines Failing</span></a></li><li id="flp_btn_9" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-1/vertical-49ea207a6233'>4.5.9<span>Linearity of Expectation: Video</span></a></li><li id="flp_btn_10" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-1/vertical-4f20b89f006a'>4.5.10<span>Fair and Biased Coins</span></a></li><li id="flp_btn_11" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-1/vertical-49116fd8c065'>4.5.11<span>Binomial Board Breaking</span></a></li><li id="flp_btn_12" class="button_selected"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-1/vertical-88fafb62d4f8'>4.5.12<span>Great Expectations</span></a></li><li id="flp_btn_13" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-1/vertical-0a1dc9049ff4'>4.5.13<span>Expectation of a Uniform Distribution</span></a></li><li id="top_continue_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-1/vertical-0a1dc9049ff4';>><span>Expectation of a Uniform Distribution</span></a></li></ul><h2 class="subhead">Great Expectations</h2><div class="self_assessment">
<br display_name="Great Expectations" url_name="Great_Expectations_0" />
<p display_name="Great Expectations" url_name="Great_Expectations_1">
<ol display_name="Great Expectations" url_name="Great_Expectations_2">
<li>
<div id="Q1_div" class="problem_question"><p>
        What is the expected sum of the numbers that come up when you roll a fair 6-sided die and a fair 12-sided die? <br /> <i>[Assume the faces have values 1-6 and 1-12, respectively.]</i>
</p><fieldset><legend class="visually-hidden">Exercise 1</legend><div class="choice"><label id="Q1_label"><span id="Q1_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Numerical Response</span><input type="text" id="Q1_input" value="" onkeypress="numericTypedOrDropDownSelected(1)" class="problem_text_input"><input type="hidden" id="Q1_ans" value="10"><input type="hidden" id="Q1_tolerance" value="0.0001"><span id="Q1_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><p id="S1_ans" tabindex="-1" class="problem_answer"></p></fieldset></div><div id="S1_div" class="problem_solution" tabindex="-1">The expectation of a sum is the sum of the individual expectations, so
        <center>\(\frac{1+2+...+6}{6} + \frac{1+2+...+12}{12} = \frac{7}{2} + \frac{13}{2}=10\).</center>
</div></li>
<br />
<li>
<p>
      Suppose you have two computers: Computer 1 generates a random number in the set \(\{1,2,\ldots,99\}\) with all numbers equally likely.
      Similarly, Computer 2 generates a random number in \(\{1,2,\ldots,999\}\) with all numbers equally likely.
      </p>
<div id="Q2_div" class="problem_question"><p>
        You roll a fair die, and if a 5 comes up, you generate a random number using Computer 1,
        otherwise you generate a random number using Computer 2. What is the expected value of the number you generate?
      </p><fieldset><legend class="visually-hidden">Exercise 2</legend><div class="choice"><label id="Q2_label"><span id="Q2_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Numerical Response</span><input type="text" id="Q2_input" value="" onkeypress="numericTypedOrDropDownSelected(2)" class="problem_text_input"><input type="hidden" id="Q2_ans" value="425"><input type="hidden" id="Q2_tolerance" value="0.0001"><span id="Q2_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><p id="S2_ans" tabindex="-1" class="problem_answer"></p></fieldset></div><div id="S2_div" class="problem_solution" tabindex="-1">
          Let \(R\) denote the value on the die, let \(G\) denote the generated number,
          let \(C_1\) denote the number Computer 1 generates and \(C_2\) the one Computer 2 generates. <br />
        By the law of Total Expectation,
          \[E[G] = E[G\;|\;R=5]\Pr[R=5]  + E[G\;|\;R\neq 5]\Pr[R\neq 5]\]
          \(E[G\;|\;R=5] = E[C_1]=50\), since each number is equally likely.
          Similarly, \(E[G\;|\;R\neq 5]= E[C_2]=500\). Hence,
          \(E[G] = \frac{1}{6}\cdot 50+\frac{5}{6}\cdot 500 = \frac{2550}{6} = \fbox{425}.\)
      </div></li>
<br />
<li>
      Assuming that Computers 1 &amp; 2 act independently, what is the expected value of the product of the numbers they generate?
      <br />
<div id="Q3_div" class="problem_question"><fieldset><legend class="visually-hidden">Exercise 3</legend><div class="choice"><label id="Q3_label"><span id="Q3_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Numerical Response</span><input type="text" id="Q3_input" value="" onkeypress="numericTypedOrDropDownSelected(3)" class="problem_text_input"><input type="hidden" id="Q3_ans" value="25000"><input type="hidden" id="Q3_tolerance" value="0.01"><span id="Q3_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><p id="S3_ans" tabindex="-1" class="problem_answer"></p></fieldset></div><div id="S3_div" class="problem_solution" tabindex="-1">
        The Product Rule can be used because the two random variables are independent, so
        \[E[C_1\cdot C_2]=E[C_1]\cdot E[C_2]=50\cdot 500 = 25000.\]
      </div><div class="action"><button id="Q1_button" onclick="checkAnswer({1: 'numerical', 2: 'numerical', 3: 'numerical'})" class="problem_mo_button">Check</button><button id="Q1_button_show" onclick="showHideSolution({1: 'numerical', 2: 'numerical', 3: 'numerical'}, 1, [1, 2, 3])" class="problem_mo_button">Show Answer</button></div></li>
</ol>
</p></div><ul class="navigation progress"><li id="bck_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-1/vertical-49116fd8c065';>Back<span>Binomial Board Breaking</span></a></li><li id="continue_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-1/vertical-0a1dc9049ff4';>Continue<span>Expectation of a Uniform Distribution</span></a></li></ul>