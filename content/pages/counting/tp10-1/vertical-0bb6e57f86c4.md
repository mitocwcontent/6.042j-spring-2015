---
content_type: page
parent_title: 3.5 Pigeonhole Principle, Inclusion-Exclusion
parent_uid: d45e9517-2acf-2a43-0d67-a0ef15468161
title: 3.5 Pigeonhole Principle, Inclusion-Exclusion
uid: c076cbe4-f659-fcd5-229c-b670f62eec68
---
<ul class="navigation pagination"><li id="top_bck_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp10-1/vertical-138fcb49e968';><<span>Pigeonhole Principle</span></a></li><li id="flp_btn_1" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp10-1'>3.5.1<span>The Pigeonhole Principle: Video</span></a></li><li id="flp_btn_2" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp10-1/vertical-4e860a9da2fe'>3.5.2<span>Rolling Dice</span></a></li><li id="flp_btn_3" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp10-1/vertical-6d18e84b97d0'>3.5.3<span>Inclusion-Exclusion Example: Video</span></a></li><li id="flp_btn_4" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp10-1/vertical-d7d25ffeb295'>3.5.4<span>Inclusion-Exclusion 2 Sets: Video</span></a></li><li id="flp_btn_5" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp10-1/vertical-138fcb49e968'>3.5.5<span>Pigeonhole Principle</span></a></li><li id="flp_btn_6" class="button_selected"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp10-1/vertical-0bb6e57f86c4'>3.5.6<span>6.042 TEAL Table</span></a></li><li id="flp_btn_7" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp10-1/class-schedules'>3.5.7<span>Class Schedules</span></a></li><li id="top_continue_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp10-1/class-schedules';>><span>Class Schedules</span></a></li></ul><h2 class="subhead">6.042 TEAL Table</h2><div class="self_assessment">
<br display_name="6.042 TEAL Table" url_name="6_042_TEAL_Table_1" />
<p display_name="6.042 TEAL Table" url_name="6_042_TEAL_Table_2">
    A 6.042 problem-solving team has 8 students (Alyssa, Ben, Carlos, ...) seated around a circular table. Since there are whiteboards all around,
    it doesn't matter which way students face, so two seatings are regarded as defining the same <em>arrangement</em>
    if each student has the same student on their right in both seatings. We'll be interested in counting how many arrangements
    there are of these 8 students, given some restrictions.
    Either input the final result or an equivalent form, using fact(x) to denote \(x!\), explictly write out multiplication with *, and ** for exponentiation.
  </p>
<ol display_name="6.042 TEAL Table" url_name="6_042_TEAL_Table_3">
<li>
<div id="Q1_div" class="problem_question"><p>
        How many different arrangements of these 8 students around the table are there without any restrictions?
      </p><fieldset><legend class="visually-hidden">Exercise 1</legend><div class="choice"><label id="Q1_label"><span id="Q1_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Numerical Response</span><input type="text" id="Q1_input" value="" onkeypress="numericTypedOrDropDownSelected(1)" class="problem_text_input"><input type="hidden" id="Q1_ans" value="5040"><input type="hidden" id="Q1_tolerance" value="0"><span id="Q1_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><p id="S1_ans" tabindex="-1" class="problem_answer"></p></fieldset></div><div id="S1_div" class="problem_solution" tabindex="-1">
        There are 8! ways to seat the 8 around the table, but all the 8 cyclic shifts of a seating define the same arrangement,
        giving a total of \(\frac{8!}{8} = 7!\) seating arrangements.
      </div></li>
<br />
<li>
<div id="Q2_div" class="problem_question"><p>
        How many arrangements of these 8 students are there with Alyssa sitting next to Ben?
      </p><fieldset><legend class="visually-hidden">Exercise 2</legend><div class="choice"><label id="Q2_label"><span id="Q2_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Numerical Response</span><input type="text" id="Q2_input" value="" onkeypress="numericTypedOrDropDownSelected(2)" class="problem_text_input"><input type="hidden" id="Q2_ans" value="1440"><input type="hidden" id="Q2_tolerance" value="0"><span id="Q2_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><p id="S2_ans" tabindex="-1" class="problem_answer"></p></fieldset></div><div id="S2_div" class="problem_solution" tabindex="-1">
        Consider Alyssa and Ben to be 1 person, say AB. Now, there are 6! arrangements of these 7 people to seat around the table.
        Now, break up AB to be Alyssa and Ben - there are 2 ways to do this - Ben could be on Alyssa's left or Ben could be on
        Alyssa's right, giving a total of 2\(\cdot\)6! seating arrangements.
      </div></li>
<br />
<li>
<div id="Q3_div" class="problem_question"><p>
        How many arrangements are there with Ben sitting next to both Alyssa AND Carlos?
      </p><fieldset><legend class="visually-hidden">Exercise 3</legend><div class="choice"><label id="Q3_label"><span id="Q3_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Numerical Response</span><input type="text" id="Q3_input" value="" onkeypress="numericTypedOrDropDownSelected(3)" class="problem_text_input"><input type="hidden" id="Q3_ans" value="240"><input type="hidden" id="Q3_tolerance" value="0"><span id="Q3_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><p id="S3_ans" tabindex="-1" class="problem_answer"></p></fieldset></div><div id="S3_div" class="problem_solution" tabindex="-1">
        Consider Alyssa, Ben and Carlos to be 1 person, say ABC, to ensure they are seated together.
        Now, you have 6 people you want to seat around a table.
        There are 5! ways of doing this.
        Now, break up ABC so Ben is in between Alyssa and Carlos; there are 2 ways to do this:
        Alyssa is on Ben's left and Carlos on his right or vice versa.
        That gives 2\(\cdot\)5! seating arrangements.
      </div></li>
<br />
<li>
<div id="Q4_div" class="problem_question"><p>
        How many arrangements are there with Ben sitting next to Alyssa OR Carlos?
      </p><fieldset><legend class="visually-hidden">Exercise 4</legend><div class="choice"><label id="Q4_label"><span id="Q4_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Numerical Response</span><input type="text" id="Q4_input" value="" onkeypress="numericTypedOrDropDownSelected(4)" class="problem_text_input"><input type="hidden" id="Q4_ans" value="2640"><input type="hidden" id="Q4_tolerance" value="0"><span id="Q4_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><p id="S4_ans" tabindex="-1" class="problem_answer"></p></fieldset></div><div id="S4_div" class="problem_solution" tabindex="-1">
        The inclusion-exclusion principle and the previous parts can be used to solve this question.
        Number of arrangements with Ben sitting next to Alyssa OR Carlos is the number of arrangements with
        Ben next to Alyssa (2\(\cdot\)6!) plus number of arrangements with Ben next to Carlos (2\(\cdot\)6!)
        minus number of arrangements with Ben next to both Alyssa AND Carlos (2\(\cdot\)5!).
        That gives us \(2\cdot 6! + 2\cdot 6! - 2\cdot 5! = 4\cdot 6! - 2\cdot 5! = (4\cdot6)5! - 2\cdot 5!= 22\cdot 5!\).
      </div><div class="action"><button id="Q1_button" onclick="checkAnswer({1: 'numerical', 2: 'numerical', 3: 'numerical', 4: 'numerical'})" class="problem_mo_button">Check</button><button id="Q1_button_show" onclick="showHideSolution({1: 'numerical', 2: 'numerical', 3: 'numerical', 4: 'numerical'}, 1, [1, 2, 3, 4])" class="problem_mo_button">Show Answer</button></div></li>
</ol>
</div><ul class="navigation progress"><li id="bck_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp10-1/vertical-138fcb49e968';>Back<span>Pigeonhole Principle</span></a></li><li id="continue_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/counting/tp10-1/class-schedules';>Continue<span>Class Schedules</span></a></li></ul>