---
content_type: page
parent_title: '2.5  Digraphs: Walks & Paths'
parent_uid: 711aeeca-1552-65f2-21e5-af2643f1a05f
title: '2.5  Digraphs: Walks & Paths'
uid: e35dfdb4-de2b-e630-325d-55d289ab953a
---
<ul class="navigation pagination"><li id="top_bck_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp6-3';><<span> Digraphs: Walks &amp; Paths</span></a></li><li id="flp_btn_1" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp6-3'>2.5.1<span>Digraphs: Walks &amp; Paths: Video</span></a></li><li id="flp_btn_2" class="button_selected"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp6-3/vertical-5a67aa9a3a6d'>2.5.2<span>Walks and Paths</span></a></li><li id="flp_btn_3" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp6-3/vertical-2c95b0b170e2'>2.5.3<span>Digraphs: Connected Vertices: Video</span></a></li><li id="flp_btn_4" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp6-3/vertical-588ea67bd5d7'>2.5.4<span>Longest Path</span></a></li><li id="flp_btn_5" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp6-3/adjacency-matrix'>2.5.5<span>Adjacency Matrix</span></a></li><li id="flp_btn_6" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp6-3/counting-paths'>2.5.6<span>Counting Paths</span></a></li><li id="top_continue_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp6-3/vertical-2c95b0b170e2';>><span>Digraphs: Connected Vertices: Video</span></a></li></ul><h2 class="subhead">Walks and Paths</h2><div class="self_assessment">
<br display_name="Walks and Paths" url_name="Walks_and_Paths_0" />
<ol display_name="Walks and Paths" url_name="Walks_and_Paths_1">
<li>
<div id="Q1_div" class="problem_question"><p>
    Let \(\{a,b,c,d\}\) be four vertices of a directed graph. <br />
    Let \(E(G) = \{(a,b),(a,c),(a,d),(b,c),(b,d),(c,b),(c,d)\}\).
    <br />
    What is the length of the longest path?
  </p><fieldset><legend class="visually-hidden">Exercise 1</legend><div class="choice"><label id="Q1_label"><span id="Q1_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Numerical Response</span><input type="text" id="Q1_input" value="" onkeypress="numericTypedOrDropDownSelected(1)" class="problem_text_input"><input type="hidden" id="Q1_ans" value="3"><input type="hidden" id="Q1_tolerance" value="0"><span id="Q1_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div><p id="S1_ans" tabindex="-1" class="problem_answer"></p></fieldset></div><div id="S1_div" class="problem_solution" tabindex="-1">
<p>An example of a longest path in this graph is \(a~(a,b)~b~(b,c)~c~(c,d)~d\)
        </p>
<p>
    Recall that the length of a path is defined as the number of edges the path uses.
        </p>
<p>
    Also recall that a path cannot have repeated vertices, so we know this path is (one of) the longest because it uses all the vertices.
        </p>
</div></li>
<br />
<li>
<div id="Q2_div" class="problem_question"><p>
    If the sum of all the numbers in an adjacency matrix is equal to 6, what does this imply?
  </p><fieldset><legend class="visually-hidden">Exercise 2</legend><div class="choice"><label id="Q2_label"><span id="Q2_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><select onchange="numericTypedOrDropDownSelected(2)" id="Q2_select" class="problem_text_input"><option correct="false"></option><option correct="true">There are 6 edges in total.</option><option correct="false">There are 6 vertices in total.</option><option correct="false">The sum of the numbers of edges and vertices is equal to 6.</option><option correct="false">None of the above</option></select><span style="display:none;" id="Q2_ans_span" tabindex="-1">  There are 6 edges in total.</span><span id="Q2_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span></label></div></fieldset></div><div id="S2_div" class="problem_solution" tabindex="-1">
    The adjacency matrix represents the edges in a digraph.
  </div><div class="action"><button id="Q1_button" onclick="checkAnswer({1: 'numerical', 2: 'optionresponse'})" class="problem_mo_button">Check</button><button id="Q1_button_show" onclick="showHideSolution({1: 'numerical', 2: 'optionresponse'}, 1, [1, 2])" class="problem_mo_button">Show Answer</button></div></li>
</ol>
</div><ul class="navigation progress"><li id="bck_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp6-3';>Back<span> Digraphs: Walks &amp; Paths</span></a></li><li id="continue_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp6-3/vertical-2c95b0b170e2';>Continue<span>Digraphs: Connected Vertices: Video</span></a></li></ul>