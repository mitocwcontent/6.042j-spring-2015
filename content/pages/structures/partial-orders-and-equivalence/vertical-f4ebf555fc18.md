---
content_type: page
parent_title: 2.7 Partial Orders and Equivalence
parent_uid: e3bcfae1-ff3e-4391-a255-e7aa0a942756
title: 2.7 Partial Orders and Equivalence
uid: 8db7161b-cd48-7d10-5925-ec9b93051cad
---
<ul class="navigation pagination"><li id="top_bck_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/partial-orders-and-equivalence';><<span>Partial Orders and Equivalence</span></a></li><li id="flp_btn_1" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/partial-orders-and-equivalence'>2.7.1<span>Partial Orders: Video</span></a></li><li id="flp_btn_2" class="button_selected"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/partial-orders-and-equivalence/vertical-f4ebf555fc18'>2.7.2<span>Population Partial Order</span></a></li><li id="flp_btn_3" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/partial-orders-and-equivalence/vertical-a604c5db7bb5'>2.7.3<span>Representing Partial Orders As Subset Relations: Video</span></a></li><li id="flp_btn_4" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/partial-orders-and-equivalence/vertical-c6c01eb0d061'>2.7.4<span>Equivalence Relations: Video</span></a></li><li id="flp_btn_5" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/partial-orders-and-equivalence/vertical-6ea0ba8a2d05'>2.7.5<span>Relational Properties</span></a></li><li id="flp_btn_6" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/partial-orders-and-equivalence/vertical-d7f7704d23b4'>2.7.6<span>Properties Of Relations</span></a></li><li id="flp_btn_7" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/partial-orders-and-equivalence/vertical-d757201744eb'>2.7.7<span>Equivalence Relations &amp; Partial Orders</span></a></li><li id="top_continue_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/partial-orders-and-equivalence/vertical-a604c5db7bb5';>><span>Representing Partial Orders As Subset Relations: Video</span></a></li></ul><h2 class="subhead">Population Partial Order</h2><div class="self_assessment">
<br display_name="Population Partial Order" url_name="Population_Partial_Order_0" />
<p display_name="Population Partial Order" url_name="Population_Partial_Order_1">In a population of 10 people, let \(R \) be the "older than" relation and \(T \) be the "taller than" relation.</p>
<ol display_name="Population Partial Order" url_name="Population_Partial_Order_2">
<li>
<div id="Q1_div" class="problem_question"><p>Which of the following properties guarantee that \(R \) will be a linear order?</p><fieldset><legend class="visually-hidden">Exercise 1</legend><div class="choice"><label id="Q1_label"><span id="Q1_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><select onchange="numericTypedOrDropDownSelected(1)" id="Q1_select" class="problem_text_input"><option correct="false"></option><option correct="false">There is a unique oldest person</option><option correct="false">There are at most two people with the same age</option><option correct="true">No two people are the same age</option><option correct="false">There is an age that no one has</option><option correct="false">Some person appears twice in the list</option></select><span style="display:none;" id="Q1_ans_span" tabindex="-1">  No two people are the same age</span><span id="Q1_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div></fieldset></div></li>
<br />
<li>
<div id="Q2_div" class="problem_question">
<p>Assume both \(R \) and \(T \) are linear orders. Which properties are <b>guaranteed</b> to be true for the product relation \(R \times T \)?</p><fieldset><legend class="visually-hidden">Exercise 2</legend><div class="choice"><label id="Q2_input_1_label"><span id="Q2_input_1_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><input type="checkbox" id="Q2_input_1" onclick="optionSelected(2)" name="Q2_input" class="problem_radio_input" correct="false"><span class="choice">
            symmetric
          </span><span id="Q2_input_1_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><div class="choice"><label id="Q2_input_2_label"><span id="Q2_input_2_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><input type="checkbox" id="Q2_input_2" onclick="optionSelected(2)" name="Q2_input" class="problem_radio_input" correct="true"><span class="choice">
            antisymmetric
          </span><span id="Q2_input_2_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><div class="choice"><label id="Q2_input_3_label"><span id="Q2_input_3_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><input type="checkbox" id="Q2_input_3" onclick="optionSelected(2)" name="Q2_input" class="problem_radio_input" correct="true"><span class="choice">
            asymmetric
          </span><span id="Q2_input_3_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><div class="choice"><label id="Q2_input_4_label"><span id="Q2_input_4_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><input type="checkbox" id="Q2_input_4" onclick="optionSelected(2)" name="Q2_input" class="problem_radio_input" correct="false"><span class="choice">
            reflexive
          </span><span id="Q2_input_4_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><div class="choice"><label id="Q2_input_5_label"><span id="Q2_input_5_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><input type="checkbox" id="Q2_input_5" onclick="optionSelected(2)" name="Q2_input" class="problem_radio_input" correct="true"><span class="choice">
            transitive
          </span><span id="Q2_input_5_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><div class="choice"><label id="Q2_input_6_label"><span id="Q2_input_6_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><input type="checkbox" id="Q2_input_6" onclick="optionSelected(2)" name="Q2_input" class="problem_radio_input" correct="true"><span class="choice">
            acyclic
          </span><span id="Q2_input_6_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><div class="choice"><label id="Q2_input_7_label"><span id="Q2_input_7_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><input type="checkbox" id="Q2_input_7" onclick="optionSelected(2)" name="Q2_input" class="problem_radio_input" correct="false"><span class="choice">
            linear
          </span><span id="Q2_input_7_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><p id="Q2_status_combined" tabindex="-1" class="nostatus"></p></fieldset></div><div id="S1_div" class="problem_solution" tabindex="-1">
<p>Not <b>symmetric</b> because two distinct people cannot both be older and taller than each other.
        </p>
<p>
          Not <b>reflexive</b>
  because a person cannot be older/taller than himself.
        </p>
<p>
          Not <b>linear</b> because if person \(A \) is older than person \(B \) but \(B \) is taller than \(A \),
  then \(A\) and \(B\) are incomparable.
        </p>
</div><div class="action"><button id="Q1_button" onclick="checkAnswer({1: 'optionresponse', 2: 'choiceresponse'})" class="problem_mo_button">Check</button><button id="Q1_button_show" onclick="showHideSolution({1: 'optionresponse', 2: 'choiceresponse'}, 1, [1])" class="problem_mo_button">Show Answer</button></div></li>
<br />
</ol>
</div><ul class="navigation progress"><li id="bck_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/partial-orders-and-equivalence';>Back<span>Partial Orders and Equivalence</span></a></li><li id="continue_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/partial-orders-and-equivalence/vertical-a604c5db7bb5';>Continue<span>Representing Partial Orders As Subset Relations: Video</span></a></li></ul>