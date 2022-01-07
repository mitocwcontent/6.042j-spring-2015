---
content_type: page
parent_title: 2.11 Stable Matching
parent_uid: 47305688-cc38-9e2f-9dc3-019a395b3b37
title: 2.11 Stable Matching
uid: d397571a-883c-dd2d-0047-b69418e0fa1c
---
<ul class="navigation pagination"><li id="top_bck_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/stable-matching/bipartite-graphs-5';><<span>Bipartite Graphs</span></a></li><li id="flp_btn_1" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/stable-matching'>2.11.1<span>Stable Matching: Video</span></a></li><li id="flp_btn_2" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/stable-matching/matching-ritual-video'>2.11.2<span>Matching Ritual: Video</span></a></li><li id="flp_btn_3" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/stable-matching/derived-variables-0'>2.11.3<span>Derived Variables</span></a></li><li id="flp_btn_4" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/stable-matching/mating-ritual-0'>2.11.4<span>Mating Ritual</span></a></li><li id="flp_btn_5" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/stable-matching/optimal-stable-matching-video'>2.11.5<span>Optimal Stable Matching: Video</span></a></li><li id="flp_btn_6" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/stable-matching/boy-optimal'>2.11.6<span>Boy Optimal</span></a></li><li id="flp_btn_7" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/stable-matching/bipartite-matching-video'>2.11.7<span>Bipartite Matching: Video</span></a></li><li id="flp_btn_8" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/stable-matching/bipartite-equivalence-relation'>2.11.8<span>Bipartite Equivalence Relation</span></a></li><li id="flp_btn_9" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/stable-matching/hall-s-theorem-video'>2.11.9<span>Hall's Theorem: Video</span></a></li><li id="flp_btn_10" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/stable-matching/bottleneck-3'>2.11.10<span>Bottleneck</span></a></li><li id="flp_btn_11" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/stable-matching/bipartite-graphs-5'>2.11.11<span>Bipartite Graphs</span></a></li><li id="flp_btn_12" class="button_selected"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/stable-matching/matching'>2.11.12<span>Matching</span></a></li><li id="flp_btn_13" ><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/stable-matching/stable-matching-invariants'>2.11.13<span>Stable Matching Invariants</span></a></li><li id="top_continue_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/stable-matching/stable-matching-invariants';>><span>Stable Matching Invariants</span></a></li></ul><h2 class="subhead">Match or No Match</h2><div class="self_assessment">
<ol display_name="Match or No Match" url_name="Match_or_No_Match_0">
<li>
<p> A Perfect Matching</p>
      Find a perfect matching the bipartite simple graph <em>G</em> whose vertices and edges are given by the following sets:
      <center><em>V</em> := {a,b,c,d} &#8746; {1,2,3,4}<br />
<em>E</em> := {{a,1}, {a,3}, {b,2}, {c,3}, {c,4}, {d,1}, {d,2}}
      </center>
<p>
        Input the edges of the matching in increasing alphabetic order, i.e. for each edge, you should write the letter in the pair first. Also list the edges separated by spaces. For example, if you want to answer {d, 1} and {c, 3}, type
      </p>
<center>
        (c 3) (d 1)
      </center>
<div id="Q1_div" class="problem_question"><fieldset><legend class="visually-hidden">Exercise 1</legend><div class="choice"><label id="Q1_label"><span id="Q1_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Text Response</span><input ckecktype="ci" onkeypress="numericTypedOrDropDownSelected(1)" value="" answer="(a 3) (b 2) (c 4) (d 1)" type="text" id="Q1_input" class="problem_text_input"><span id="Q1_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span><span style="display:none;" id="Q1_ans_span" tabindex="-1">  Answer:(a 3) (b 2) (c 4) (d 1)</span></label></div></fieldset></div><div id="S1_div" class="problem_solution" tabindex="-1">In this graph, the perfect matching happens to be unique.</div></li>
<li>
<p> No Perfect Matching</p>
<br />
<p>
      The bipartite simple graph <em>G</em> whose vertices and edges are given by the folowing sets:
      <center><em>V</em> := {a,b,c,d} &#8746; {1,2,3,4}<br />
<em>E</em> := {{a,3}, {a,4}, {b,1}, {b,2}, {c,1}, {c,2}, {d,1}, {d,2}}
      </center>
      does not have a perfect matching.
      </p><p>
        Which of the following properties of <em>G</em> make a perfect matching impossible?
      </p>
<ol><li>
          The set {1,3,4} has only 2 neighbors.
        </li><li>
          The vertices a,b,c,d, on the "left" side, all have degree 2, but none of the vertices 1,2,3,4, on the "right" side, has degree 2.
        </li><li>
          The set {b,c,d} has only 2 neighbors.
        </li><li><em>G</em> has 8 edges.
        </li><li>
          The set {3,4} has only 1 neighbor.
        </li><li>
          Vertex 1 has degree 3, but each of its neighbors only has degree 2.
        </li><li>
          The set {a,b} has 4 neighbors.
        </li></ol>
<div id="Q2_div" class="problem_question"><p>
        Give your answer as a sequence of numbers separated by some spaces<br />
(e.g., "6 9"). Don't use commas or parentheses.
      </p><fieldset><legend class="visually-hidden">Exercise 2</legend><div class="choice"><label id="Q2_label"><span id="Q2_aria_status" tabindex="-1" class="visually-hidden">&amp;nbsp;</span><span class="visually-hidden">Text Response</span><input ckecktype="ci" onkeypress="numericTypedOrDropDownSelected(2)" value="" answer="3 5" type="text" id="Q2_input" class="problem_text_input"><span id="Q2_normal_status" class="nostatus" aria-hidden="true">&amp;nbsp;</span><span style="display:none;" id="Q2_ans_span" tabindex="-1">  Answer:3 5</span></label></div></fieldset></div><div id="S2_div" class="problem_solution" tabindex="-1">
        If we let the letters be the "girls" and the numbers be the "boys", then property 3. is a bottleneck that prevents a perfect match. If we let the letters be the "boys" and the numbers be the "girls", then property 5. is another bottleneck in <em>G</em>.
        <p>
          Property 1. also describes a bottleneck, but it's not true <tt>:-)</tt>
</p>
</div><div class="action"><button id="Q1_button" onclick="checkAnswer({1: 'stringresponse', 2: 'stringresponse'})" class="problem_mo_button">Check</button><button id="Q1_button_show" onclick="showHideSolution({1: 'stringresponse', 2: 'stringresponse'}, 1, [1, 2])" class="problem_mo_button">Show Answer</button></div></li>
</ol>
</div><ul class="navigation progress"><li id="bck_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/stable-matching/bipartite-graphs-5';>Back<span>Bipartite Graphs</span></a></li><li id="continue_btn"><a href='/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/stable-matching/stable-matching-invariants';>Continue<span>Stable Matching Invariants</span></a></li></ul>