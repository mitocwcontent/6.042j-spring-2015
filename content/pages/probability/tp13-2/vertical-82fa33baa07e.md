---
content_type: page
parent_title: '4.6 Deviation: Markov & Chebyshev Bounds'
parent_uid: f195ee84-9b9a-ee3c-cf61-f90bea10cebb
title: '4.6 Deviation: Markov & Chebyshev Bounds'
uid: 8cfdfe80-51ab-2e4d-f313-541e627aafbc
---
<ul class="navigation pagination"><li id="top_bck_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-2/vertical-49f940bfd8d6';><<span>Chebyshev Bounds: Video</span></a></li><li id="flp_btn_1" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-2'>4.6.1<span>Deviation From The Mean: Video</span></a></li><li id="flp_btn_2" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-2/vertical-18d81b8ca2e1'>4.6.2<span>Don't Expect the Expectation</span></a></li><li id="flp_btn_3" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-2/vertical-8307292b80cb'>4.6.3<span>Markov Bounds: Video</span></a></li><li id="flp_btn_4" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-2/vertical-ecd276750fa8'>4.6.4<span>Markov Bound</span></a></li><li id="flp_btn_5" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-2/vertical-49f940bfd8d6'>4.6.5<span>Chebyshev Bounds: Video</span></a></li><li id="flp_btn_6" class="button_selected"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-2/vertical-82fa33baa07e'>4.6.6<span>Inside the TA's Brain</span></a></li><li id="flp_btn_7" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-2/vertical-0646c16ad916'>4.6.7<span>Variance: Video</span></a></li><li id="flp_btn_8" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-2/vertical-1b1a945bfd78'>4.6.8<span>Practice with Variance</span></a></li><li id="flp_btn_9" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-2/vertical-871f95303dd6'>4.6.9<span>Flipping Coins</span></a></li><li id="flp_btn_10" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-2/vertical-00ed1bc2728f'>4.6.10<span>Practice with Bounds</span></a></li><li id="flp_btn_11" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-2/vertical-4699d069607e'>4.6.11<span>Implications of Expectation</span></a></li><li id="top_continue_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-2/vertical-0646c16ad916';>><span>Variance: Video</span></a></li></ul><h2 class="subhead">Inside the TA's brain</h2><div class="self_assessment">
<p display_name="Inside the TA's brain" url_name="Inside_the_TA_s_brain_1">
    Recent studies have shown that some small area in our brains is sensitive to <em>nonsensical structures</em>: the 1,000,000
    neurons of that area seem to be firing whenever the individual is presented with such structures. This area is now known as the
    Grader's Area.
  </p>
<p display_name="Inside the TA's brain" url_name="Inside_the_TA_s_brain_2">
    In a now famous series of experiments (Pseudoneurologica, 28(1):123-129, 1999), several 6.042 TAs have been presented
    with students' solutions to exam problems. On reading a solution, the <em>expected number</em> of neurons to fire in
    the Grader's Area was estimated to be 550,000. Assume that this estimate is indeed correct.
  </p>
<p display_name="Inside the TA's brain" url_name="Inside_the_TA_s_brain_3">
    Moreover, a TA realizes that a solution is <i>bad</i> if the number of neurons in his/her Grader's Area that fire is greater
    than the number of neurons that do not by 200,000.
  </p>
<ol display_name="Inside the TA's brain" url_name="Inside_the_TA_s_brain_4">
<li>
<div id="Q1_div" class="problem_question"><p>
       What is the least number of neurons in the Grader's Area that must fire in order for the TA to realize that a solution is bad?
      </p><fieldset><legend class="visually-hidden">Exercise 1</legend><div class="choice"><label id="Q1_label"><span id="Q1_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Numerical Response</span><input type="text" id="Q1_input" value="" onkeypress="numericTypedOrDropDownSelected(1)" class="problem_text_input"><input type="hidden" id="Q1_ans" value="600000"><input type="hidden" id="Q1_tolerance" value="0"><span id="Q1_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><p id="S1_ans" tabindex="-1" class="problem_answer"></p></fieldset></div><div id="S1_div" class="problem_solution" tabindex="-1">
        In order for the neurons that fire to be at least 200,000 more than those that do not fire,
        they should be at least 100,000 more than half the total number of neurons. That is: 500,000 + 100,000 = 600,000.
      </div></li>
<br />
<li>
<div id="Q2_div" class="problem_question"><p>
		With the information given, provide the best bound on the probability that the TA realizes a solution is bad. Please answer as a fraction of the form x/y.
      </p><fieldset><legend class="visually-hidden">Exercise 2</legend><div class="choice"><label id="Q2_label"><span id="Q2_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Numerical Response</span><input type="text" id="Q2_input" value="" onkeypress="numericTypedOrDropDownSelected(2)" class="problem_text_input"><input type="hidden" id="Q2_ans" value="11/12"><input type="hidden" id="Q2_tolerance" value="0"><span id="Q2_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><p id="S2_ans" tabindex="-1" class="problem_answer"></p></fieldset></div><div id="S2_div" class="problem_solution" tabindex="-1">
        Let \(R\) be the number of neurons that fire. Then \(E[R]=550,000\) and a bad solution is recognized iff
        \(R\geq 600,000\). Therefore, the probability we want is \(\Pr[R\geq 600,000]\). We are not given the variance, so we cannot use Chebyshev.
        By Markov's Theorem,
        \[\Pr[R\geq 600,000] \leq \frac{E[R]}{600,000} = \frac{550,000}{600,000} = \frac{11}{12}.\]
      </div></li>
<br />
<li>
<div id="Q3_div" class="problem_question"><p>
        In a follow-up study the standard deviation of the number of neurons that fire on seeing a bad solution was found to be 25,000.
        Using this additional information, provide a better bound on the probability that the TA realizes a solution is bad. Please answer as a fraction of the form x/y.
      </p><fieldset><legend class="visually-hidden">Exercise 3</legend><div class="choice"><label id="Q3_label"><span id="Q3_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Numerical Response</span><input type="text" id="Q3_input" value="" onkeypress="numericTypedOrDropDownSelected(3)" class="problem_text_input"><input type="hidden" id="Q3_ans" value="1/4"><input type="hidden" id="Q3_tolerance" value="0"><span id="Q3_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><p id="S3_ans" tabindex="-1" class="problem_answer"></p></fieldset></div><div id="S3_div" class="problem_solution" tabindex="-1">
        Let \(R\) be as above. Then the new study says that \(Var[R]=(25,000)^2\). According to Chebyshev, 
        \[\Pr[|R - E[R]|\geq x] \leq \frac{Var[R]}{x^2} = \] 
        <p> We want to upper bound the probability that \(R \geq 600,000\).
        Equivalently, this is the probability that \(R - 550,000 \geq 50,000\).
        The way to use Chebyshev's Theorem is to plug in \(x = 50,000\). Then, we get
        \[Pr[|R-550,000| \geq 50,000] \leq \frac{25,000^2}{50,000^2} = \frac{1}{4}.\]
        </p>
<p>Note that this is really an upper bound for the probability that</p>
<center>\(R \geq 600,000\) <b>or</b> \(R \leq 500,000\).</center>
<p><em>
            There are "one-sided" versions of Chebyshev Bounds, which we omit,
            that give a slightly tighter bound for the probability of just \(R \geq 600,000\).
          </em></p>
</div><div class="action"><button id="Q1_button" onclick="checkAnswer({1: 'numerical', 2: 'numerical', 3: 'numerical'})" class="problem_mo_button">Check</button><button id="Q1_button_show" onclick="showHideSolution({1: 'numerical', 2: 'numerical', 3: 'numerical'}, 1, [1, 2, 3])" class="problem_mo_button">Show Answer</button></div></li>
</ol>
</div><ul class="navigation progress"><li id="bck_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-2/vertical-49f940bfd8d6';>Back<span>Chebyshev Bounds: Video</span></a></li><li id="continue_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/probability/tp13-2/vertical-0646c16ad916';>Continue<span>Variance: Video</span></a></li></ul>