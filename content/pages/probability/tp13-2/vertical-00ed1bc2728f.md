---
content_type: page
parent_title: '4.6 Deviation: Markov & Chebyshev Bounds'
parent_uid: f195ee84-9b9a-ee3c-cf61-f90bea10cebb
title: '4.6 Deviation: Markov & Chebyshev Bounds'
uid: a33815ee-cc3a-b193-b175-8ac9d7fc6d18
---
<ul class="navigation pagination"><li id="top_bck_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-2/vertical-871f95303dd6';><<span>Flipping Coins</span></a></li><li id="flp_btn_1" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-2'>4.6.1<span>Deviation From The Mean: Video</span></a></li><li id="flp_btn_2" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-2/vertical-18d81b8ca2e1'>4.6.2<span>Don't Expect the Expectation</span></a></li><li id="flp_btn_3" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-2/vertical-8307292b80cb'>4.6.3<span>Markov Bounds: Video</span></a></li><li id="flp_btn_4" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-2/vertical-ecd276750fa8'>4.6.4<span>Markov Bound</span></a></li><li id="flp_btn_5" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-2/vertical-49f940bfd8d6'>4.6.5<span>Chebyshev Bounds: Video</span></a></li><li id="flp_btn_6" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-2/vertical-82fa33baa07e'>4.6.6<span>Inside the TA's Brain</span></a></li><li id="flp_btn_7" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-2/vertical-0646c16ad916'>4.6.7<span>Variance: Video</span></a></li><li id="flp_btn_8" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-2/vertical-1b1a945bfd78'>4.6.8<span>Practice with Variance</span></a></li><li id="flp_btn_9" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-2/vertical-871f95303dd6'>4.6.9<span>Flipping Coins</span></a></li><li id="flp_btn_10" class="button_selected"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-2/vertical-00ed1bc2728f'>4.6.10<span>Practice with Bounds</span></a></li><li id="flp_btn_11" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-2/vertical-4699d069607e'>4.6.11<span>Implications of Expectation</span></a></li><li id="top_continue_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-2/vertical-4699d069607e';>><span>Implications of Expectation</span></a></li></ul><h2 class="subhead">Practice with Bounds</h2><div class="self_assessment">
<br display_name="Practice with Bounds" url_name="Practice_with_Bounds_1" />
<p display_name="Practice with Bounds" url_name="Practice_with_Bounds_2">
    Suppose 120 students take the 6.042 final exam and the mean of their
    grades is 90.  However, you have no other information about the
    students and the exam, for example, you should not assume that the
    final is worth 100 points.
  </p>
<ol display_name="Practice with Bounds" url_name="Practice_with_Bounds_3">
<li>
<div id="Q1_div" class="problem_question"><p>
        State the best possible upper bound on <b>the number of students</b> who scored at least 180.
      </p><fieldset><legend class="visually-hidden">Exercise 1</legend><div class="choice"><label id="Q1_label"><span id="Q1_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Numerical Response</span><input type="text" id="Q1_input" value="" onkeypress="numericTypedOrDropDownSelected(1)" class="problem_text_input"><input type="hidden" id="Q1_ans" value="60"><input type="hidden" id="Q1_tolerance" value="0"><span id="Q1_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><p id="S1_ans" tabindex="-1" class="problem_answer"></p></fieldset></div><div id="S1_div" class="problem_solution" tabindex="-1">
        Let \(R\) be the score of a student chosen at random. According to Markov's Theorem:
        \[\Pr[R \geq 180] \leq \frac{E[R]}{180} = \frac{90}{180} = \frac{1}{2}.\]
        So at most \(\frac{1}{2}\cdot 120 = 60\) students scored greater than or equal to 180.
      </div></li>
<br />
<li>
<div id="Q2_div" class="problem_question"><p>
        Now suppose somebody tells you that the lowest score on the exam is 30. Compute the new best possible upper bound on
        <b>the number of students</b> who scored at least 180. 
      </p><fieldset><legend class="visually-hidden">Exercise 2</legend><div class="choice"><label id="Q2_label"><span id="Q2_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Numerical Response</span><input type="text" id="Q2_input" value="" onkeypress="numericTypedOrDropDownSelected(2)" class="problem_text_input"><input type="hidden" id="Q2_ans" value="48"><input type="hidden" id="Q2_tolerance" value="0"><span id="Q2_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><p id="S2_ans" tabindex="-1" class="problem_answer"></p></fieldset></div><div id="S2_div" class="problem_solution" tabindex="-1">
        Let \(R\) be as in the above question. We can apply Markov's Theorem to the variable \(R-30\):
        \[\Pr[R \geq 180] = Pr[R-30 \geq 150] \leq \frac{E[R-30]}{150} = \frac{60}{150} = \frac{2}{5}.\]
        So at most \(\frac{2}{5}\cdot 120 = 48\) students scored greater than or equal to 180.
      </div><div class="action"><button id="Q1_button" onclick="checkAnswer({1: 'numerical', 2: 'numerical'})" class="problem_mo_button">Check</button><button id="Q1_button_show" onclick="showHideSolution({1: 'numerical', 2: 'numerical'}, 1, [1, 2])" class="problem_mo_button">Show Answer</button></div></li>
</ol>
</div><ul class="navigation progress"><li id="bck_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-2/vertical-871f95303dd6';>Back<span>Flipping Coins</span></a></li><li id="continue_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-2/vertical-4699d069607e';>Continue<span>Implications of Expectation</span></a></li></ul>