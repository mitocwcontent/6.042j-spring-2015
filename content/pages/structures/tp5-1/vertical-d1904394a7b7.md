---
content_type: page
parent_title: 2.1  GCDs
parent_uid: 40569305-3755-e5d6-fb1b-1e2592fa311e
title: 2.1  GCDs
uid: 81921d91-f774-f6e9-5074-3785a5034462
---
<ul class="navigation pagination"><li id="top_bck_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp5-1/pulverizer-video';><<span>Pulverizer: Video</span></a></li><li id="flp_btn_1" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp5-1'>2.1.1<span>GCDs &amp; Linear Combinations: Video</span></a></li><li id="flp_btn_2" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp5-1/euclidean-algorithm-video'>2.1.2<span>Euclidean Algorithm: Video</span></a></li><li id="flp_btn_3" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp5-1/vertical-b30047e37cc7'>2.1.3<span>Run Euclid Run</span></a></li><li id="flp_btn_4" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp5-1/pulverizer-video'>2.1.4<span>Pulverizer: Video</span></a></li><li id="flp_btn_5" class="button_selected"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp5-1/vertical-d1904394a7b7'>2.1.5<span>GCDs I</span></a></li><li id="flp_btn_6" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp5-1/revisiting-die-hard-video'>2.1.6<span>Revisiting Die Hard: Video</span></a></li><li id="flp_btn_7" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp5-1/prime-factorization-video'>2.1.7<span>Prime Factorization: Video</span></a></li><li id="flp_btn_8" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp5-1/vertical-abe126e3ad2c'>2.1.8<span>Unique Primes</span></a></li><li id="flp_btn_9" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp5-1/vertical-70eb5a2913c0'>2.1.9<span>Divisors</span></a></li><li id="flp_btn_10" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp5-1/vertical-912ad2b397a4'>2.1.10<span>GCDs II</span></a></li><li id="top_continue_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp5-1/revisiting-die-hard-video';>><span>Revisiting Die Hard: Video</span></a></li></ul><h2 class="subhead">GCDs I</h2><div class="self_assessment">
<br display_name="GCDs I" url_name="GCDs_I_0" />
<strong display_name="GCDs I" url_name="GCDs_I_1">Consider the two integers:</strong>
<center display_name="GCDs I" url_name="GCDs_I_2">
      \(a = 21212121\)<br />
      \(b = 12121212\)
  </center>
<p display_name="GCDs I" url_name="GCDs_I_3">
<ol display_name="GCDs I" url_name="GCDs_I_4">
<li>
<p>What is the GCD of \(a\) and \(b\)?</p>
<div id="Q1_div" class="problem_question"><p><em>Hint: Looks scary, but it's not.</em></p><fieldset><legend class="visually-hidden">Exercise 1</legend><div class="choice"><label id="Q1_label"><span id="Q1_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Numerical Response</span><input type="text" id="Q1_input" value="" onkeypress="numericTypedOrDropDownSelected(1)" class="problem_text_input"><input type="hidden" id="Q1_ans" value="3030303"><input type="hidden" id="Q1_tolerance" value="0"><span id="Q1_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><p id="S1_ans" tabindex="-1" class="problem_answer"></p></fieldset></div><div id="S1_div" class="problem_solution" tabindex="-1"><p>We run the algorithm:</p><p>\[GCD(21212121,12121212)\\
            = GCD(12121212,9090909)\\
            = GCD(9090909,3030303)\\
            = GCD(3030303,0).\]
        </p></div></li>
<li>
<p>How many steps of the Euclidean algorithm are needed to compute this GCD?</p>
<p><em>A step of the Euclidean algorithm is defined as an application of the equation:</em></p>
<center>
  \(GCD(x,y) = GCD(y, rem(x, y)).\)
</center>
<p>The algorithm begins with \((a,b)\) and ends with \((gcd(a,b),0)\).</p>
<div id="S2_div" class="problem_solution" tabindex="-1">In the execution of the algorithm in Part 1 we needed 3 applications of the equation.</div><div id="Q2_div" class="problem_question"><fieldset><legend class="visually-hidden">Exercise 2</legend><div class="choice"><label id="Q2_label"><span id="Q2_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Numerical Response</span><input type="text" id="Q2_input" value="" onkeypress="numericTypedOrDropDownSelected(2)" class="problem_text_input"><input type="hidden" id="Q2_ans" value="3"><input type="hidden" id="Q2_tolerance" value="0"><span id="Q2_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><p id="S2_ans" tabindex="-1" class="problem_answer"></p></fieldset></div><div class="action"><button id="Q1_button" onclick="checkAnswer({1: 'numerical', 2: 'numerical'})" class="problem_mo_button">Check</button><button id="Q1_button_show" onclick="showHideSolution({1: 'numerical', 2: 'numerical'}, 1, [1, 2])" class="problem_mo_button">Show Answer</button></div></li>
</ol>
</p></div><ul class="navigation progress"><li id="bck_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp5-1/pulverizer-video';>Back<span>Pulverizer: Video</span></a></li><li id="continue_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp5-1/revisiting-die-hard-video';>Continue<span>Revisiting Die Hard: Video</span></a></li></ul>