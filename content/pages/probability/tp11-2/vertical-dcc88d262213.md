---
content_type: page
parent_title: 4.1 Intro to Discrete Probability
parent_uid: 4414c612-ae42-4c73-7466-f4715f85e319
title: 4.1 Intro to Discrete Probability
uid: ad83e19e-58d2-92c4-85c4-b3cec4bca701
---
<ul class="navigation pagination"><li id="top_bck_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp11-2';><<span>Intro to Discrete Probability</span></a></li><li id="flp_btn_1" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp11-2'>4.1.1<span>Tree Model: Video</span></a></li><li id="flp_btn_2" class="button_selected"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp11-2/vertical-dcc88d262213'>4.1.2<span>Socks and Shoes</span></a></li><li id="flp_btn_3" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp11-2/vertical-65858dc50455'>4.1.3<span>Simplified Monty Hall Tree: Video</span></a></li><li id="flp_btn_4" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp11-2/vertical-9542d6e9bbc8'>4.1.4<span>Simplify Prize Tree</span></a></li><li id="flp_btn_5" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp11-2/vertical-7e0be1baca38'>4.1.5<span>Sample Spaces: Video</span></a></li><li id="flp_btn_6" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp11-2/vertical-eb54695f6f66'>4.1.6<span>Sum Rule Practice</span></a></li><li id="flp_btn_7" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp11-2/vertical-d95cbbc345c2'>4.1.7<span>Addition Rule</span></a></li><li id="flp_btn_8" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp11-2/vertical-a2b75a4824b8'>4.1.8<span>Fun With Coins</span></a></li><li id="top_continue_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp11-2/vertical-65858dc50455';>><span>Simplified Monty Hall Tree: Video</span></a></li></ul><h2 class="subhead">Socks And Shoes</h2><div class="self_assessment">
<br display_name="Socks And Shoes" url_name="Socks_And_Shoes_0" />
<p display_name="Socks And Shoes" url_name="Socks_And_Shoes_1">Parker has two pairs of black shoes and three pairs of brown shoes. He also has three pairs of red socks, four pairs of brown socks and six pairs of black socks.</p>
<p display_name="Socks And Shoes" url_name="Socks_And_Shoes_2">Now let's say that Parker chooses a pair of shoes at random and a pair of socks at random. We would like to know the probability of him choosing shoes and socks of the same color.</p>
<ol display_name="Socks And Shoes" url_name="Socks_And_Shoes_3">
<li>
<div id="Q1_div" class="problem_question"><p><b>Identify the outcomes!</b> An outcome is _____.
      </p><fieldset><legend class="visually-hidden">Exercise 1</legend><div class="choice"><label id="Q1_label"><span id="Q1_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><select onchange="numericTypedOrDropDownSelected(1)" id="Q1_select" class="problem_text_input"><option correct="false"></option><option correct="false">a pair of shoes</option><option correct="false">a pair of socks</option><option correct="true">a pair of colors</option><option correct="false">all permutations of shoes and socks</option><option correct="false">a color</option></select><span style="display:none;" id="Q1_ans_span" tabindex="-1">  a pair of colors</span><span id="Q1_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div></fieldset></div><div id="S1_div" class="problem_solution" tabindex="-1">We care about the color of the shoes and socks, so an outcome is determined by the color of the shoes and the color of the socks. Therefore, the correct answer is <em>a pair of colors.</em>
</div></li>
<br />
<li>
<p>
<b>Identify the event of interest!</b>
</p>
<ul>
<li>
<div id="Q2_div" class="problem_question"><p>How many outcomes are there in total?</p><fieldset><legend class="visually-hidden">Exercise 2</legend><div class="choice"><label id="Q2_label"><span id="Q2_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Numerical Response</span><input type="text" id="Q2_input" value="" onkeypress="numericTypedOrDropDownSelected(2)" class="problem_text_input"><input type="hidden" id="Q2_ans" value="6"><input type="hidden" id="Q2_tolerance" value=".001"><span id="Q2_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><p id="S2_ans" tabindex="-1" class="problem_answer"></p></fieldset></div><div id="S2_div" class="problem_solution" tabindex="-1">There are two possible colors for shoes and three possible for socks. Hence, the total is 2\(\cdot\)3=6.</div></li>
<br />
<li>
<div id="Q3_div" class="problem_question"><p>How many outcomes are there in the event of interest?</p><fieldset><legend class="visually-hidden">Exercise 3</legend><div class="choice"><label id="Q3_label"><span id="Q3_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Numerical Response</span><input type="text" id="Q3_input" value="" onkeypress="numericTypedOrDropDownSelected(3)" class="problem_text_input"><input type="hidden" id="Q3_ans" value="2"><input type="hidden" id="Q3_tolerance" value=".001"><span id="Q3_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><p id="S3_ans" tabindex="-1" class="problem_answer"></p></fieldset></div><div id="S3_div" class="problem_solution" tabindex="-1">The outcomes of interest (highlighted in tree below) are the ones where the colors are either both brown or both black. There is one of each.</div></li>
</ul>
</li>
<br />
<li>
<p>
<b>Assign outcome probabilities</b>
</p>
<p>
Please answer in the form of decimals with four significant digits.
	  </p>
<ul>
<li>
<div id="Q4_div" class="problem_question"><p>What is the probability of choosing black shoes?</p><fieldset><legend class="visually-hidden">Exercise 4</legend><div class="choice"><label id="Q4_label"><span id="Q4_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Numerical Response</span><input type="text" id="Q4_input" value="" onkeypress="numericTypedOrDropDownSelected(4)" class="problem_text_input"><input type="hidden" id="Q4_ans" value="0.4"><input type="hidden" id="Q4_tolerance" value=".001"><span id="Q4_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><p id="S4_ans" tabindex="-1" class="problem_answer"></p></fieldset></div><div id="S4_div" class="problem_solution" tabindex="-1">There are 5 pairs of shoes in total, 3 brown and 2 black. Since Parker chooses the shoes at random, the probability of choosing black shoes is \(\frac{2}{5}\).</div></li>
<br />
<li>
<div id="Q5_div" class="problem_question"><p>What is the probability of choosing red socks?</p><fieldset><legend class="visually-hidden">Exercise 5</legend><div class="choice"><label id="Q5_label"><span id="Q5_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Numerical Response</span><input type="text" id="Q5_input" value="" onkeypress="numericTypedOrDropDownSelected(5)" class="problem_text_input"><input type="hidden" id="Q5_ans" value=".2307"><input type="hidden" id="Q5_tolerance" value=".001"><span id="Q5_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><p id="S5_ans" tabindex="-1" class="problem_answer"></p></fieldset></div><div id="S5_div" class="problem_solution" tabindex="-1">There are 13 pairs of socks in total, 3 red, 4 brown, and 6 black. Since Parker chooses the socks at random, the probability of choosing red socks is \(\frac{3}{13}\).</div></li>
</ul>
</li>
<br />
<li>
<p>
<b>Compute event probabilities!</b>
</p>
<p>
Please answer in the form of decimals with four significant digits.
	  </p>
<div id="Q6_div" class="problem_question"><p>What is the probability that he chooses shoes and socks of the same color?</p><fieldset><legend class="visually-hidden">Exercise 6</legend><div class="choice"><label id="Q6_label"><span id="Q6_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Numerical Response</span><input type="text" id="Q6_input" value="" onkeypress="numericTypedOrDropDownSelected(6)" class="problem_text_input"><input type="hidden" id="Q6_ans" value="0.3692"><input type="hidden" id="Q6_tolerance" value=".001"><span id="Q6_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><p id="S6_ans" tabindex="-1" class="problem_answer"></p></fieldset></div><div id="S6_div" class="problem_solution" tabindex="-1">Using the four step method we construct a probability tree:
      <img align="bottom" alt="Socks and Shoes Tree" border="0" src="/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp11-2/vertical-dcc88d262213/socks_and_shoes_tree.jpg" />
<br />
      The probability of the event of interest is the sum of its outcomes. Therefore the probability that he chooses shoes and socks of the same color is: \(\frac{12}{65}+\frac{12}{65}=\frac{24}{65}\).</div><div class="action"><button id="Q1_button" onclick="checkAnswer({1: 'optionresponse', 2: 'numerical', 3: 'numerical', 4: 'numerical', 5: 'numerical', 6: 'numerical'})" class="problem_mo_button">Check</button><button id="Q1_button_show" onclick="showHideSolution({1: 'optionresponse', 2: 'numerical', 3: 'numerical', 4: 'numerical', 5: 'numerical', 6: 'numerical'}, 1, [1, 2, 3, 4, 5, 6])" class="problem_mo_button">Show Answer</button></div></li>
</ol>
</div><ul class="navigation progress"><li id="bck_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp11-2';>Back<span>Intro to Discrete Probability</span></a></li><li id="continue_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp11-2/vertical-65858dc50455';>Continue<span>Simplified Monty Hall Tree: Video</span></a></li></ul>