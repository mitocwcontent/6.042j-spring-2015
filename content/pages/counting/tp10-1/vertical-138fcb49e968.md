---
content_type: page
parent_title: 3.5 Pigeonhole Principle, Inclusion-Exclusion
parent_uid: d45e9517-2acf-2a43-0d67-a0ef15468161
title: 3.5 Pigeonhole Principle, Inclusion-Exclusion
uid: 8d15f3c1-6eec-4c49-5ea8-45cd7bfc5726
---
<ul class="navigation pagination"><li id="top_bck_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp10-1/vertical-d7d25ffeb295';><<span>Inclusion-Exclusion 2 Sets: Video</span></a></li><li id="flp_btn_1" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp10-1'>3.5.1<span>The Pigeonhole Principle: Video</span></a></li><li id="flp_btn_2" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp10-1/vertical-4e860a9da2fe'>3.5.2<span>Rolling Dice</span></a></li><li id="flp_btn_3" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp10-1/vertical-6d18e84b97d0'>3.5.3<span>Inclusion-Exclusion Example: Video</span></a></li><li id="flp_btn_4" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp10-1/vertical-d7d25ffeb295'>3.5.4<span>Inclusion-Exclusion 2 Sets: Video</span></a></li><li id="flp_btn_5" class="button_selected"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp10-1/vertical-138fcb49e968'>3.5.5<span>Pigeonhole Principle</span></a></li><li id="flp_btn_6" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp10-1/vertical-0bb6e57f86c4'>3.5.6<span>6.042 TEAL Table</span></a></li><li id="flp_btn_7" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp10-1/class-schedules'>3.5.7<span>Class Schedules</span></a></li><li id="top_continue_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp10-1/vertical-0bb6e57f86c4';>><span>6.042 TEAL Table</span></a></li></ul><h2 class="subhead">Pigeonhole Principle</h2><div class="self_assessment">
<br display_name="Pigeonhole Principle" url_name="Pigeonhole_Principle_1" />
<p display_name="Pigeonhole Principle" url_name="Pigeonhole_Principle_2">Below is a list of properties that a group of people might possess.</p>
<p display_name="Pigeonhole Principle" url_name="Pigeonhole_Principle_3">
    For each property, either give the minimum number of people that must be in a group to
    ensure that the property holds, or else write <b>nh</b> to indicate that the property need <b>n</b>ot <b>h</b>old
    even for arbitrarily large groups of people.
  </p>
<p display_name="Pigeonhole Principle" url_name="Pigeonhole_Principle_4">
<em>Assume that every year has exactly 365 days; ignore leap years.</em>
</p>
<ol display_name="Pigeonhole Principle" url_name="Pigeonhole_Principle_5">
<li>
<div id="Q1_div" class="problem_question"><p>At least 2 people were born on the same day of the year (ignore the year of birth).</p><fieldset><legend class="visually-hidden">Exercise 1</legend><div class="choice"><label id="Q1_label"><span id="Q1_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Numerical Response</span><input type="text" id="Q1_input" value="" onkeypress="numericTypedOrDropDownSelected(1)" class="problem_text_input"><input type="hidden" id="Q1_ans" value="366"><input type="hidden" id="Q1_tolerance" value="0"><span id="Q1_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><p id="S1_ans" tabindex="-1" class="problem_answer"></p></fieldset></div><div id="S1_div" class="problem_solution" tabindex="-1">
        We let the people be pigeons and the days of the year be holes (365 holes). If we have 365+1 pigeons,
        two of them must be in the same hole (i.e. the two must be born on the same day).
      </div></li>
<br />
<li>
<div id="Q2_div" class="problem_question"><p>At least 2 people were born on January 1st.</p><fieldset><legend class="visually-hidden">Exercise 2</legend><div class="choice"><label id="Q2_label"><span id="Q2_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Text Response</span><input ckecktype="ci" onkeypress="numericTypedOrDropDownSelected(2)" value="" answer="nh" type="text" id="Q2_input" class="problem_text_input"><span id="Q2_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span><span style="display:none;" id="Q2_ans_span" tabindex="-1">  Answer:nh</span></label></div></fieldset></div><div id="S2_div" class="problem_solution" tabindex="-1">
        No matter how many people you have, you cannot force any one of them to be born on a specific day.
        For example, everyone might be born on January 2nd.
      </div></li>
<br />
<li>
<div id="Q3_div" class="problem_question"><p>At least 3 people were born on the same day of the week.</p><fieldset><legend class="visually-hidden">Exercise 3</legend><div class="choice"><label id="Q3_label"><span id="Q3_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Numerical Response</span><input type="text" id="Q3_input" value="" onkeypress="numericTypedOrDropDownSelected(3)" class="problem_text_input"><input type="hidden" id="Q3_ans" value="15"><input type="hidden" id="Q3_tolerance" value="0"><span id="Q3_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><p id="S3_ans" tabindex="-1" class="problem_answer"></p></fieldset></div><div id="S3_div" class="problem_solution" tabindex="-1">
        We let people be pigeons and the days on the week be holes (7 holes). Using the generalized pigeonhole principle,
        we need 2\(\cdot\)7+1 people to force 3 of them to be in the same hole (i.e. born on the same day of the week).
      </div></li>
<br />
<li>
<div id="Q4_div" class="problem_question"><p>At least 4 people were born in the same month.</p><fieldset><legend class="visually-hidden">Exercise 4</legend><div class="choice"><label id="Q4_label"><span id="Q4_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Numerical Response</span><input type="text" id="Q4_input" value="" onkeypress="numericTypedOrDropDownSelected(4)" class="problem_text_input"><input type="hidden" id="Q4_ans" value="37"><input type="hidden" id="Q4_tolerance" value="0"><span id="Q4_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><p id="S4_ans" tabindex="-1" class="problem_answer"></p></fieldset></div><div id="S4_div" class="problem_solution" tabindex="-1">
        We let the people be pigeons and the months of the year be holes (12 holes).
        Using the generalized pigeonhole principle, we need 3\(\cdot\)12+1 people to force 4 of them to be born in the same month.
      </div></li>
<br />
<li>
<div id="Q5_div" class="problem_question"><p>At least 2 people were born exactly one week apart.</p><fieldset><legend class="visually-hidden">Exercise 5</legend><div class="choice"><label id="Q5_label"><span id="Q5_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Text Response</span><input ckecktype="ci" onkeypress="numericTypedOrDropDownSelected(5)" value="" answer="nh" type="text" id="Q5_input" class="problem_text_input"><span id="Q5_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span><span style="display:none;" id="Q5_ans_span" tabindex="-1">  Answer:nh</span></label></div></fieldset></div><div id="S5_div" class="problem_solution" tabindex="-1">
        Again, you cannot force this property. For example, everyone might be born on the same day of the year.
      </div><div class="action"><button id="Q1_button" onclick="checkAnswer({1: 'numerical', 2: 'stringresponse', 3: 'numerical', 4: 'numerical', 5: 'stringresponse'})" class="problem_mo_button">Check</button><button id="Q1_button_show" onclick="showHideSolution({1: 'numerical', 2: 'stringresponse', 3: 'numerical', 4: 'numerical', 5: 'stringresponse'}, 1, [1, 2, 3, 4, 5])" class="problem_mo_button">Show Answer</button></div></li>
</ol>
</div><ul class="navigation progress"><li id="bck_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp10-1/vertical-d7d25ffeb295';>Back<span>Inclusion-Exclusion 2 Sets: Video</span></a></li><li id="continue_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp10-1/vertical-0bb6e57f86c4';>Continue<span>6.042 TEAL Table</span></a></li></ul>