---
content_type: page
parent_title: 2.6 Directed Acyclic Graphs (DAGs) & Scheduling
parent_uid: 30a03ec2-6577-751d-fb8c-5b6d0813ce12
title: 2.6 Directed Acyclic Graphs (DAGs) & Scheduling
uid: b45275d3-3f15-3918-1675-e5af6c1f8e3f
---
<ul class="navigation pagination">
    <li id="top_bck_btn"><a href="/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp7-1/vertical-0b187f2dedb6">&lt;<span>Scheduling: Video</span></a></li>
    <li id="flp_btn_1"><a href="/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp7-1">2.6.1<span>DAGs: Video</span></a></li>
    <li id="flp_btn_2"><a href="/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp7-1/vertical-dcde59c77eab">2.6.2<span>DAGs</span></a></li>
    <li id="flp_btn_3"><a href="/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp7-1/vertical-0b187f2dedb6">2.6.3<span>Scheduling: Video</span></a></li>
    <li id="flp_btn_4" class="button_selected"><a href="/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp7-1/vertical-cb2dbc0f9d11">2.6.4<span>Scheduling Prerequisites</span></a></li>
    <li id="flp_btn_5"><a href="/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp7-1/vertical-ce9e54c9d251">2.6.5<span>Time versus Processors: Video</span></a></li>
    <li id="flp_btn_6"><a href="/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp7-1/vertical-a69125071411">2.6.6<span>Processor Time Bounds</span></a></li>
    <li id="flp_btn_7"><a href="/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp7-1/vertical-839e7a19a176">2.6.7<span>The Divisibility DAG</span></a></li>
    <li id="top_continue_btn"><a href="/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp7-1/vertical-ce9e54c9d251">&gt;<span>Time versus Processors: Video</span></a></li>
</ul>
<h2 class="subhead">Scheduling Prerequisites</h2>
<div class="self_assessment"><br display_name="Scheduling Prerequisites" url_name="Scheduling_Prerequisites_0" />
<p display_name="Scheduling Prerequisites" url_name="Scheduling_Prerequisites_1">The prerequisites of some MIT subjects are given in the following table:</p>
<center display_name="Scheduling Prerequisites" url_name="Scheduling_Prerequisites_2">
<div class="maintabletemplate">
<table border="1" align="center" class="tablewidth50">
    <thead>
        <tr>
            <th>Direct Prerequisites</th>
            <th>Subject</th>
        </tr>
    </thead>
    <tbody>
        <tr class="row">
            <td>18.01</td>
            <td>6.042</td>
        </tr>
        <tr class="alt-row">
            <td>18.01</td>
            <td>18.02</td>
        </tr>
        <tr class="row">
            <td>18.01</td>
            <td>18.03</td>
        </tr>
        <tr class="alt-row">
            <td>8.01</td>
            <td>8.02</td>
        </tr>
        <tr class="row">
            <td>8.01</td>
            <td>6.01</td>
        </tr>
        <tr class="alt-row">
            <td>6.042</td>
            <td>6.046</td>
        </tr>
        <tr class="row">
            <td>18.02, 18.03, 8.02, 6.01</td>
            <td>6.02</td>
        </tr>
        <tr class="alt-row">
            <td>6.01,6.042</td>
            <td>6.006</td>
        </tr>
        <tr class="row">
            <td>6.01</td>
            <td>6.034</td>
        </tr>
        <tr class="alt-row">
            <td>6.02</td>
            <td>6.004</td>
        </tr>
    </tbody>
</table>
</div>
</center>
<p display_name="Scheduling Prerequisites" url_name="Scheduling_Prerequisites_3">In the following sets of subjects, specify whether the set is a chain, anti-chain, or neither: <br />
(Hint, draw a DAG for the subjects first!)</p>
<ol display_name="Scheduling Prerequisites" url_name="Scheduling_Prerequisites_4">
    <li>
    <div id="Q1_div" class="problem_question">
    <p>6.042, 6.046, 6.01</p>
    <fieldset><legend class="visually-hidden">Exercise 1</legend>
    <div class="choice"><label id="Q1_label"><span id="Q1_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><select onchange="numericTypedOrDropDownSelected(1)" id="Q1_select" class="problem_text_input">
    <option correct="false"></option>
    <option correct="false">chain</option>
    <option correct="false">anti-chain</option>
    <option correct="true">neither</option>
    </select><span style="display:none;" id="Q1_ans_span" tabindex="-1">  neither</span><span id="Q1_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div>
    </fieldset></div>
    </li>
    <br />
    <li>
    <div id="Q2_div" class="problem_question">
    <p>18.01, 6.02, 6.004</p>
    <fieldset><legend class="visually-hidden">Exercise 2</legend>
    <div class="choice"><label id="Q2_label"><span id="Q2_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><select onchange="numericTypedOrDropDownSelected(2)" id="Q2_select" class="problem_text_input">
    <option correct="false"></option>
    <option correct="true">chain</option>
    <option correct="false">anti-chain</option>
    <option correct="false">neither</option>
    </select><span style="display:none;" id="Q2_ans_span" tabindex="-1">  chain</span><span id="Q2_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div>
    </fieldset></div>
    <div id="S1_div" class="problem_solution" tabindex="-1">A chain need not contain every possible element.</div>
    </li>
    <br />
    <li>
    <div id="Q3_div" class="problem_question">
    <p>6.042, 6.02, 6.034</p>
    <fieldset><legend class="visually-hidden">Exercise 3</legend>
    <div class="choice"><label id="Q3_label"><span id="Q3_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><select onchange="numericTypedOrDropDownSelected(3)" id="Q3_select" class="problem_text_input">
    <option correct="false"></option>
    <option correct="false">chain</option>
    <option correct="true">anti-chain</option>
    <option correct="false">neither</option>
    </select><span style="display:none;" id="Q3_ans_span" tabindex="-1">  anti-chain</span><span id="Q3_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div>
    </fieldset></div>
    </li>
    <br />
    <li>
    <div id="Q4_div" class="problem_question">
    <p>What is the length of the longest anti-chain?</p>
    <fieldset><legend class="visually-hidden">Exercise 4</legend>
    <div class="choice"><label id="Q4_label"><span id="Q4_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Numerical Response</span><input type="text" id="Q4_input" value="" onkeypress="numericTypedOrDropDownSelected(4)" class="problem_text_input" /><input type="hidden" id="Q4_ans" value="5" /><input type="hidden" id="Q4_tolerance" value="0" /><span id="Q4_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div>
    <p id="S4_ans" tabindex="-1" class="problem_answer">&nbsp;</p>
    </fieldset></div>
    </li>
    <br />
    <li>
    <div id="Q5_div" class="problem_question">
    <p>How many terms do you need to graduate if you take classes following the schedule given by a topological sort of the DAG?</p>
    <fieldset><legend class="visually-hidden">Exercise 5</legend>
    <div class="choice"><label id="Q5_label"><span id="Q5_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Numerical Response</span><input type="text" id="Q5_input" value="" onkeypress="numericTypedOrDropDownSelected(5)" class="problem_text_input" /><input type="hidden" id="Q5_ans" value="12" /><input type="hidden" id="Q5_tolerance" value="0" /><span id="Q5_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div>
    <p id="S5_ans" tabindex="-1" class="problem_answer">&nbsp;</p>
    </fieldset></div>
    <div id="S2_div" class="problem_solution" tabindex="-1">Topological sorting provides a schedule for taking one class per term, so the number of terms is the number of classes.</div>
    <div class="action"><button id="Q1_button" onclick="checkAnswer({1: 'optionresponse', 2: 'optionresponse', 3: 'optionresponse', 4: 'numerical', 5: 'numerical'})" class="problem_mo_button">Check</button><button id="Q1_button_show" onclick="showHideSolution({1: 'optionresponse', 2: 'optionresponse', 3: 'optionresponse', 4: 'numerical', 5: 'numerical'}, 1, [1, 2])" class="problem_mo_button">Show Answer</button></div>
    </li>
    <br />
</ol>
</div>
<ul class="navigation progress">
    <li id="bck_btn"><a href="/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp7-1/vertical-0b187f2dedb6">Back<span>Scheduling: Video</span></a></li>
    <li id="continue_btn"><a href="/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp7-1/vertical-ce9e54c9d251">Continue<span>Time versus Processors: Video</span></a></li>
</ul>