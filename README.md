java c
MATH32091 Coursework Assignment
Solutions must be submitted via the link in AssessmentFeedback folder in Blackboard.  This assignment uses Gradescope, there is further informa- tion available about  it at https://www.elearning.fse.manchester.ac.  uk/fseta/student-guide-gradescope, but the submission process should be straightforward, even if you have not used Gradescope before .
Help on converting hand-written work to PDF is available at https:// tinyurl.com/mrr64s24 and at https://tinyurl.com/bdez838u.   If you do the  Ford-Fulkerson algorithm by hand and the rest in  LATEX or by some other electronic method, you can merge PDFs by using PDFsam from http:  //pdfsam.org or there are various websites which can do it for you . Submit one file only, not each page separately.
Check that the your file is legible, not blurry, not too faint, not too dark and that all the  pages are  in the correct orientation.  You can check your submission and if the file did not upload correctly or you discover a mistake, you can submit again via the same link.
Only your last attempt will be marked.  The deadline is 24 October, 2024, 4  p.m .   If  you  have  a  disability  support  plan  which  includes an automatic extension for assignments, your deadline is 31 October, 2024, 4 p.m .  If you are unable to submit your work on time due to illness or other serious reason, you can apply for an extension via the mitigating circumstances process .  If you submit after the (possibly extended) deadline, your work will still be marked, but your mark will be reduced in accordance with university policy (https:  //documents.manchester.ac.uk/display.aspx?DocID=24561) .
This assignment is worth 15% of the marks available for this course unit.
Answer all three questions.  You may use any result from the notes, books, or the exercise sheets provided you reference it properly.  You can also use calculators and computers, but output from a computer program on its own is not acceptable as a solution. You should be able to do this assignment in less than 2 hours.This  is  not  a  group  project,  any  work  you  submit  must  be  your  own . The university’s guidance on academic malpractice can be found at http:  //documents.manchester.ac.uk/display.aspx?DocID=2870.1.  [8 marks] The graph below represents an electrical network with the re- sistance of each edge in appropriate代 写MATH32091 Coursework AssignmentPython
代做程序编程语言 units shown next to it.  s  is the source and t is the sink.  The resistances of four of the edges are known,  Rsb  = 8, Rac  = 2 , Rbc  = 1 , Rct  = 1/2 in suitable units, while Rsa  = Rab  = z, but the value of z is not known .
You are given that Ict  = 12 and Iab  = Isb .  Use the method of spanning trees to calculate z and the current Iab .
2.  [8 marks] Let n be a positive integer, n ≥ 2.  The graph G illustrated below has vertices a1 , a2 , . . . , an , b1 , b2 , . . . , bn , c1 , c2 , . . . , cn  and d1 , d2 , . . . , dn .  Its edges are aiai+1 , bibi+1 , cici+1 , didi+1  for every i , 1 ≤ i ≤ n − 1, and an b1 , bnc1 , cnd1 , dna1 , a1 c1 , b1 d1 .Show that G has 4n3 + 8n2 + 4n spanning trees. (Hint: The Matrix Tree Theorem is probably not useful here.  Instead, think about how many edges you have to remove to get a spanning tree and what conditions those edges have to satisfy.)

3.  [14 marks in total]
Let G be the graph shown below, s is the source, t is the sink.  Some steps of the Ford-Fulkerson algorithm have already been carried out.  Let  f denote the flow shown in the graph. The number in parentheses next to an edge xy is the capacity c(x, y), while the number in front of the parentheses is the flow in the edge, f (x, y), as usual.

(a) [2 marks] Let S = {s,q,r, w} and T = {t,p,u, v}.
Calculate Σ f (x, y) −Σ f (x, y) and c(S, T) . (Show your working, do not
x∈S, y∈T               x∈T, y∈S
x−∈E                      x−∈E
just give numerical answers without any explanation.)
(b) [9 marks] Find a maximal flow in G by using the Ford-Fulkerson algorithm starting with the flow f shown in the graph above and prove that the flow you have found is indeed maximal by exhibiting a cut whose capacity is equal to the value of the flow .   At  each  step,  indicate  clearly  the  flow  in  each edge, the augmenting path along which you are increasing the flow and the amount by which you are increasing the flow .  Also show how you find the cut corresponding to your maximal flow .  Diagrams are provided on the next page, the first diagram shows the flow f you must start with.
(c) [3 marks] Show that if f(¯) is any maximal flow in G , then f(¯)(q, r) = 5 .


Use these diagrams to solve Question 3 (b) .


















         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
