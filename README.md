Download Link: https://assignmentchef.com/product/solved-mlcs-homework1
<br>
<strong>Exercise 1 </strong>Let <em>R </em>be a predicate symbol of arity 1. Show that ∃<em>x</em>(<em>R</em>(<em>x</em>) → ∀<em>yR</em>(<em>y</em>)) is logically valid.

<strong>Exercise 2 </strong>Show that the following sentence is unsatisfiable, where <em>S </em>is any formula with two free variables: ∃<em>x</em>∀<em>y</em>(<em>S</em>(<em>x,y</em>) &#x2194; ¬<em>S</em>(<em>y,y</em>)).

<strong>Exercise 3 </strong>Prove or disprove: for any formulas <em>G </em>and <em>F</em>,

<em>F </em>|= <em>G </em>if and only if |= (<em>F </em>→ <em>G</em>)<em>.</em>

<strong>Exercise 4 </strong>Is the following formula logically valid for any formula <em>F </em>and any term <em>t</em>?

∀<em>xF</em>(<em>x</em>) → <em>F</em>(<em>t</em>)<em>.</em>

If not, give an example of a formula <em>F</em>, a structure A and an assignment <em>α </em>witnessing this fact.

<strong>Exercise 5 </strong>Is the following implication true for any choice of formulas? Is it true for sentences?

If

If |= <em>G </em>then |= <em>F,</em>

then

|= (<em>G </em>→ <em>F</em>)<em>.</em>

Recall that for a formula <em>G</em>, |= <em>G </em>means that for all structures A, for all assignments <em>α </em>in A, A |= <em>G</em>[<em>α</em>].

<strong>Exercise 6 </strong>Let <em>F </em>be a formula with no quantifiers, function symbols, or constants. Prove the following two statements.

<ul>

 <li>A closed formula of the form ∀<em>x</em><sub>1 </sub><em>…</em>∀<em>x<sub>n</sub></em>∃<em>y</em><sub>1 </sub><em>…</em>∃<em>y<sub>m</sub>F </em>with <em>m </em>≥ 0 and <em>n </em>≥ 1 is valid if and only if it is true in every non-empty structure with ≤ <em>n </em></li>

 <li>A closed formula (a sentence) of the form ∃<em>y</em><sub>1 </sub><em>…</em>∃<em>y<sub>m</sub>F </em>is valid if and only if it is true in every structure with 1 element.</li>

</ul>

Can we draw some conclusion about the decidability of the validity of formulas in item (1)?

<strong>Exercise 7 </strong>Let A and B be two structures for the same predicative language with no constant or function symbols. Prove that if <em>f </em>is a bijection from <em>A </em>to <em>B </em>such that, for all atomic formulas <em>G </em>the following holds

A if and only if B<em> ,</em>

then A and B satisfy the same sentences.

(Hint: Induction of sentences is not a viable option (subformulas of a sentence may not be sentences). So typically one proves a result about formulas. In this case one would prove by induction on formulas the following: For any formula <em>F</em>(<em>x</em><sub>1</sub><em>,…,x<sub>n</sub></em>), for any (<em>a</em><sub>1</sub><em>,…,a<sub>n</sub></em>) ∈ <em>A<sup>n</sup></em>, A |= <em>F</em>(<em>x</em><sub>1</sub><em>,…,x<sub>n</sub></em>)[<em>a</em><sub>1</sub><em>,…,a<sub>n</sub></em>] if and only if B |= <em>F</em>(<em>x</em><sub>1</sub><em>,…,x<sub>n</sub></em>)[<em>f</em>(<em>a</em><sub>1</sub>)<em>,…,f</em>(<em>a<sub>n</sub></em>)]<em>. </em>The result for sentences then follows.)

<strong>Exercise 8 </strong>Consider the empty language (only logical symbols, including =, but no further relation, function or constant symbols).

Can you write a sentence that is true only in finite models? Can you write a sentence that is true only in infinite models? Can you write a set of sentences <em>X </em>such that all models satisfying <em>X </em>are infinite? Does any of the answers change if you use the language {<em>&lt;</em>} (one binary relation symbol)?

<strong>Exercise 9 </strong>In the language L = {<em>&lt;</em>} of DLO, write a sentence that distinguishes (<strong>N</strong><em>,&lt;</em>) from (<strong>Q</strong><em>,&lt;</em>) i.e., that is true in one structure but not in the other.

<strong>Exercise 10 </strong>Assume that the validity of a sentence in a fixed finite model can be algorithmically decided (this is indeed the case). Consider the set <em>V </em>of logically valid sentences (in a fixed first-order language) and the set <em>U </em>of all unsatisfiable sentences. Is there a decision algorithm (i.e. a deterministic 0,1 valued procedure) that separates <em>V </em>from <em>U </em>in the following sense: <em>V </em>is a subset of the inputs on which the algorithm <em>A </em>returns 1 and <em>U </em>is a subset of the inputs on which the algorithm <em>A </em>returns 0?

(If your answer is yes, describe (informally) an algorithm that separates the two sets; else if your answer is no give an informal proof.)

<strong>Exercise 11 </strong>Let <em>T </em>be a theory (i.e., a set of sentences) in some relational language L. Let <em>F</em>(<em>x</em>) be a formula in the language L. Let <em>c </em>be a constant symbol not present in the language L. Let L<sup>0 </sup>be the language

L ∪ {<em>c</em>}. Show that

<em>T </em>|= ∀<em>xF</em>(<em>x</em>) if and only if <em>T </em>|= <em>F</em>(<em>c</em>)<em>.</em>

Note that in the left-hand side we are dealing with structures adequate for L while on the right-hand side we are dealing with structures adequate for L<sup>0</sup>.

<ol start="2">

 <li>Group2</li>

</ol>

<strong>Definition </strong>B is a <strong>substructure </strong>of A if: <em>B </em>⊆ <em>A</em>; for every constant symbol <em>c</em>, <em>c</em><sup>A </sup>= <em>c</em><sup>B</sup>, every relation <em>R</em><sup>B </sup>(resp. function <em>f</em><sup>B</sup>) is the restriction of <em>R</em><sup>A </sup>(resp. <em>f</em><sup>A</sup>) to <em>B</em>.

<strong>Exercise 1 </strong>Prove the following two points.

<ul>

 <li>If B is a substructure of A, then for any atomic formula <em>F</em>(<em>x</em><sub>1</sub><em>,…,x<sub>n</sub></em>), for all <em>b</em><sub>1</sub><em>,…,b<sub>n </sub></em>in <em>B</em>, B |= <em>F</em>[<em>b</em><sub>1</sub><em>,…,b<sub>n</sub></em>] iff A |= <em>F</em>[<em>b</em><sub>1</sub><em>,…,b<sub>n</sub></em>].</li>

 <li>Let <em>T </em>be a set of purely universal sentences (i.e. sentences starting with universal quantifiers followed by an atomic formula). If B is a substructure of A and A |= <em>T </em>then also B |= <em>T</em>.</li>

</ul>

<strong>Definition </strong>B substructure of A is called <strong>elementary </strong>if for all formulas <em>F</em>(<em>x</em><sub>1</sub><em>,…,x<sub>n</sub></em>) for all <em>b</em><sub>1</sub><em>,…,b<sub>n </sub></em>in <em>B</em>, A |= <em>F</em>[<em>b</em><sub>1</sub><em>,…,b<sub>n</sub></em>] iff B |= <em>F</em>[<em>b</em><sub>1</sub><em>,…,b<sub>n</sub></em>]. That is, A and B agree on elements of <em>B</em>.

<strong>Exercise 2 </strong>Let A<sub>1 </sub>= (<strong>N</strong><em>,</em>+<em>,</em>0) and A<sub>2 </sub>= (2<strong>N</strong><em>,</em>+<em>,</em>0) be two structures for the language L = {<em>f,c</em>} where <em>f </em>is a function symbol of arity 2 and <em>c </em>is a constant symbol and 2<strong>N </strong>denotes the set of even natural numbers. A<sub>1 </sub>and A<sub>2 </sub>interpret <em>f </em>as the sum on their domains and <em>c </em>as 0. Indicate whether the following are true or false, giving a short justification of your answer.

<ul>

 <li>A<sub>2 </sub>is a substructure ofA<sub>1</sub>.</li>

 <li>A<sub>1 </sub>e A<sub>2 </sub>are isomorphic.</li>

 <li>A<sub>1 </sub>e A<sub>2 </sub>satisfy the same sentences in L.</li>

 <li>If A<sub>1 </sub>|= ∃<em>xF</em>(<em>x</em>)[<em>α</em>] for an assignment <em>α </em>in <em>A</em><sub>2</sub>, then there exists <em>a </em>∈ <em>A</em><sub>2 </sub>such that A</li>

 <li>If <em>E </em>is a sentence of the form ∀<em>xF</em>(<em>x</em>) with <em>F</em>(<em>x</em>) a quantifier-free formula then: If A<sub>1 </sub>|= <em>E </em>then A<sub>2 </sub>|= <em>E</em>.</li>

 <li>If <em>E </em>is a sentence of the form ∃<em>xF</em>(<em>x</em>) with <em>F</em>(<em>x</em>) a quantifier-free formula then:</li>

</ul>

If A<sub>1 </sub>|= <em>E </em>then A<sub>2 </sub>|= <em>E</em>.

<strong>Exercise 3 </strong>Is the structure Q = (Q<em>,</em>+<em>,</em>×<em>,</em>0<em>,</em>1) a substructure of the structure R = (R<em>,</em>+<em>,</em>×<em>,</em>0<em>,</em>1)? is it an elementary substructure?

<strong>Exercise 4 </strong>Prove that the following structures are not isomorphic:

<ul>

 <li>(N<em>,</em>+<em>,</em>×<em>,</em>0<em>,</em>1<em>,&lt;</em>) and (Q<em>,</em>+<em>,</em>×<em>,</em>0<em>,</em>1<em>,&lt;</em>)</li>

 <li>(N<em>,&lt;</em>) and (Z<em>,&lt;</em>) (3) (Q<em>,&lt;</em>) and (R<em>,&lt;</em>).</li>

</ul>

(Hint: in some case you can use the fact that if A and B are isomorphic then they satisfy the same sentences).

<strong>Exercise 5 </strong>A theory <em>T </em>has property <em>M </em>if the following holds: For A and B models of <em>T</em>, if A is a substructure of B then A is also an elementary substructure of B. Prove that if a theory <em>T </em>admits Quantifier Elimination (i.e., every formula is <em>T</em>-equivalent to a quantifier-free formula with no extra free variables) then the theory <em>T </em>has property <em>M</em>.

<strong>Exercise 6 </strong>Apply the Quantifier Elimination procedure for the theory DLO to the following sentence <em>E</em>:

∃<em>x</em>∃<em>y</em>∃<em>z</em>∀<em>u</em>(<em>x &lt; y </em>∧ <em>x &lt; z </em>∧ <em>z &lt; y </em>∧ (<em>u </em>= <em>z </em>∨ <em>u &lt; y </em>∨ <em>u </em>= <em>x</em>))<em>.</em>

Decide if DLO |= <em>E </em>or DLO |= ¬<em>E</em>.