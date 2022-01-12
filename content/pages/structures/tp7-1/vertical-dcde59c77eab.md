---
content_type: page
parent_title: 2.6 Directed Acyclic Graphs (DAGs) & Scheduling
parent_uid: 30a03ec2-6577-751d-fb8c-5b6d0813ce12
title: 2.6 Directed Acyclic Graphs (DAGs) & Scheduling
uid: 4198e624-fc0a-b2e4-5693-34b068466d42
---
<ul class="navigation pagination"><li id="top_bck_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp7-1';><<span>Directed Acyclic Graphs (DAGs) &amp; Scheduling</span></a></li><li id="flp_btn_1" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp7-1'>2.6.1<span>DAGs: Video</span></a></li><li id="flp_btn_2" class="button_selected"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp7-1/vertical-dcde59c77eab'>2.6.2<span>DAGs</span></a></li><li id="flp_btn_3" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp7-1/vertical-0b187f2dedb6'>2.6.3<span>Scheduling: Video</span></a></li><li id="flp_btn_4" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp7-1/vertical-cb2dbc0f9d11'>2.6.4<span>Scheduling Prerequisites</span></a></li><li id="flp_btn_5" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp7-1/vertical-ce9e54c9d251'>2.6.5<span>Time versus Processors: Video</span></a></li><li id="flp_btn_6" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp7-1/vertical-a69125071411'>2.6.6<span>Processor Time Bounds</span></a></li><li id="flp_btn_7" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp7-1/vertical-839e7a19a176'>2.6.7<span>The Divisibility DAG</span></a></li><li id="top_continue_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp7-1/vertical-0b187f2dedb6';>><span>Scheduling: Video</span></a></li></ul><h2 class="subhead">DAGs</h2><div class="self_assessment">
<br display_name="DAGs" url_name="DAGs_0" />
<ol display_name="DAGs" url_name="DAGs_1">
<li>
<div id="Q1_div" class="problem_question">
<p>
    Which of the following graph features may <em>NOT</em> appear in a digraph:  
  </p><fieldset><legend class="visually-hidden">Exercise 1</legend><div class="choice"><label id="Q1_input_1_label"><span id="Q1_input_1_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><input type="checkbox" id="Q1_input_1" onclick="optionSelected(1)" name="Q1_input" class="problem_radio_input" correct="false"><span class="choice">
            self loops
          </span><span id="Q1_input_1_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><div class="choice"><label id="Q1_input_2_label"><span id="Q1_input_2_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><input type="checkbox" id="Q1_input_2" onclick="optionSelected(1)" name="Q1_input" class="problem_radio_input" correct="false"><span class="choice">
            isolated nodes (with no edges in or out)
          </span><span id="Q1_input_2_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><div class="choice"><label id="Q1_input_3_label"><span id="Q1_input_3_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><input type="checkbox" id="Q1_input_3" onclick="optionSelected(1)" name="Q1_input" class="problem_radio_input" correct="false"><span class="choice">
            two edges in opposite directions between a pair of nodes
          </span><span id="Q1_input_3_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><div class="choice"><label id="Q1_input_4_label"><span id="Q1_input_4_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><input type="checkbox" id="Q1_input_4" onclick="optionSelected(1)" name="Q1_input" class="problem_radio_input" correct="true"><span class="choice">
             two edges in the same direction between a pair of nodes
          </span><span id="Q1_input_4_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><div class="choice"><label id="Q1_input_5_label"><span id="Q1_input_5_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><input type="checkbox" id="Q1_input_5" onclick="optionSelected(1)" name="Q1_input" class="problem_radio_input" correct="false"><span class="choice">
            having no edges at all
          </span><span id="Q1_input_5_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><div class="choice"><label id="Q1_input_6_label"><span id="Q1_input_6_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><input type="checkbox" id="Q1_input_6" onclick="optionSelected(1)" name="Q1_input" class="problem_radio_input" correct="true"><span class="choice">
            having no nodes at all
          </span><span id="Q1_input_6_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><p id="Q1_status_combined" tabindex="-1" class="nostatus"></p></fieldset></div></li>
<br />
<li>
<p>
    Let \(V\) be a DAG and \(U\)
    be the DAG with only the covering edges of \(V\). Then,
  </p>
<ol>
<li>
<div id="Q2_div" class="problem_question"><p>compared to the length of the <i>shortest</i> path between two nodes in \(V\), the length of the <i>shortest</i> path in \(U\) between these nodes is:</p><fieldset><legend class="visually-hidden">Exercise 2</legend><div class="choice"><label id="Q2_label"><span id="Q2_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><select onchange="numericTypedOrDropDownSelected(2)" id="Q2_select" class="problem_text_input"><option correct="false"></option><option correct="false">the same</option><option correct="false">not longer</option><option correct="true">not shorter</option><option correct="false">may be shorter or longer</option></select><span style="display:none;" id="Q2_ans_span" tabindex="-1">  not shorter</span><span id="Q2_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div></fieldset></div></li>
<li>
<div id="Q3_div" class="problem_question"><p>compared to the length of the <i>longest</i> path between two nodes in \(V\), the length of the <i>longest</i> path in \(U\) between these nodes is:</p><fieldset><legend class="visually-hidden">Exercise 3</legend><div class="choice"><label id="Q3_label"><span id="Q3_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><select onchange="numericTypedOrDropDownSelected(3)" id="Q3_select" class="problem_text_input"><option correct="false"></option><option correct="true">the same</option><option correct="false">not longer</option><option correct="false">not shorter</option><option correct="false">may be shorter or longer</option></select><span style="display:none;" id="Q3_ans_span" tabindex="-1">  the same</span><span id="Q3_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div></fieldset></div><div class="action"><button id="Q1_button" onclick="checkAnswer({1: 'choiceresponse', 2: 'optionresponse', 3: 'optionresponse'})" class="problem_mo_button">Check</button><button id="Q1_button_show" onclick="showHideSolution({1: 'choiceresponse', 2: 'optionresponse', 3: 'optionresponse'}, 1, [])" class="problem_mo_button">Show Answer</button></div></li>
</ol>
</li>
</ol>
</div><ul class="navigation progress"><li id="bck_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp7-1';>Back<span>Directed Acyclic Graphs (DAGs) &amp; Scheduling</span></a></li><li id="continue_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp7-1/vertical-0b187f2dedb6';>Continue<span>Scheduling: Video</span></a></li></ul>