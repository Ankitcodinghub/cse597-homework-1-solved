# cse597-homework-1-solved
**TO GET THIS SOLUTION VISIT:** [CSE597 Homework 1 Solved](https://www.ankitcodinghub.com/product/cse597-homework-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93319&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE597 Homework 1 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
Specific Instructions

In this assignment, you will gain experience working with Markov models on text.

The template file homework1_cse597.py (which you will rename) has empty function definitions. Since portions of this assignment will be graded automatically, none of the names or function signatures in this file should be modified. However, you are free to introduce additional variables or functions if needed.

You may import definitions from standard Python utlity libraries and are encouraged to do so in case you find yourself reinventing the wheel, e.g., collections, itertools, math, random, queue, os, re, string, copy sys. DO NOT IMPORT: numpy, scikit or other special purposes packages or the autograder will not be able to grade your homework.

You will find that in addition to a problem specification, most programming questions also include a pair of examples from the Python interpreter. These are meant to illustrate typical use cases to clarify the assignment, and are not comprehensive test suites. In addition to performing your own testing, you are strongly encouraged to verify that your code gives the expected output for these examples before submitting.

You are strongly encouraged to follow the Python style guidelines set forth in PEP 8, which was written in part by the creator of Python. However, your code will not be graded for style.

1. Markov Models

In this section, you will build a simple language model that can be used to generate random text resembling a source document. Your use of external code should be limited to built-in Python modules, which excludes, for example, NumPy and NLTK.

1. [10 points] Write a simple tokenization function tokenize(text) which takes as input a string of text and returns a list of tokens derived from that text. Here, we define a token to be a contiguous sequence of non-whitespace characters, with the exception that any punctuation mark should be treated as an individual token. Hint: Use the built-in constant string.punctuation, found in the string module.

</div>
</div>
<div class="layoutArea">
<div class="column">
file:///Users/rebecca/Google Drive (rjp49@psu.edu)/teaching/NLP/Spring2021/homework/Assignment_1/homework1-cse597-nlp.html 1/4

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>&gt;&gt;&gt;tokenize("  This is an example.  ")
['This', 'is', 'an', 'example', '.']
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
2.&nbsp; Write a function ngrams(n, tokens) that produces a list of all n-grams of the specified size from the input token list. Each n-gram should consist of a 2-element tuple (context, token), where the context is itself an (n-1)-element tuple comprised of the n-1 words preceding the current token. The sentence should be padded with n-1 “&lt;START&gt;” tokens at the beginning and a single “&lt;END&gt;” token at the end. If n = 1, all contexts should be empty tuples. You may assume that n ≥ 1.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>&gt;&gt;&gt;ngrams(1, ["a", "b", "c"])
[((), 'a'), ((), 'b'), ((), 'c'),
</pre>
<pre> ((), '&lt;END&gt;')]
&gt;&gt;&gt;ngrams(2, ["a", "b", "c"])
[(('&lt;START&gt;',), 'a'), (('a',), 'b'),
</pre>
<pre> (('b',), 'c'), (('c',), '&lt;END&gt;')]
</pre>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>&gt;&gt;&gt;ngrams(3, ["a", "b", "c"])
[(('&lt;START&gt;', '&lt;START&gt;'), 'a'),
</pre>
<pre> (('&lt;START&gt;', 'a'), 'b'),
 (('a', 'b'), 'c'),
 (('b', 'c'), '&lt;END&gt;')]
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
3. In the NgramModel class, write an initialization method __init__(self, n) which stores the order n of the model and initializes any necessary internal variables. Then write a method

update(self, sentence) which computes the n-grams for the input sentence and updates the internal counts. Lastly, write a method prob(self, context, token) which accepts an (n-1)-tuple representing a context and a token, and returns the probability of that token occuring, given the preceding context.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>&gt;&gt;&gt;m = NgramModel(1)
&gt;&gt;&gt;m.update("a b c d")
&gt;&gt;&gt;m.update("a b a b")
&gt;&gt;&gt;m.prob((), "a")
0.3
</pre>
<pre>&gt;&gt;&gt;m.prob((), "c")
0.1
&gt;&gt;&gt;m.prob((), "&lt;END&gt;")
0.2
</pre>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>&gt;&gt;&gt;m = NgramModel(2)
&gt;&gt;&gt;m.update("a b c d")
&gt;&gt;&gt;m.update("a b a b")
&gt;&gt;&gt;m.prob(("&lt;START&gt;",), "a")
1.0
</pre>
<pre>&gt;&gt;&gt;m.prob(("b",), "c")
0.3333333333333333
&gt;&gt;&gt;m.prob(("a",), "x")
0.0
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
4. In the NgramModel class, write a method random_token(self, context) which returns a random token according to the probability distribution determined by the given context. Specifically, let T = &lt; t1, t2, . . . , tn &gt; be the set of tokens which can occur in the given context, sorted according to Python’s

natural lexicographic ordering, and let 0 ≤ r &lt; 1 be a random number between 0 and 1. Your method should return the token ti such that

You should use a single call to the random.random() function to generate r.

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>&gt;&gt;&gt;m = NgramModel(1)
&gt;&gt;&gt;m.update("a b c d")
&gt;&gt;&gt;m.update("a b a b")
</pre>
</div>
<div class="column">
<pre>&gt;&gt;&gt;m = NgramModel(2)
&gt;&gt;&gt;m.update("a b c d")
&gt;&gt;&gt;m.update("a b a b")
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
file:///Users/rebecca/Google Drive (rjp49@psu.edu)/teaching/NLP/Spring2021/homework/Assignment_1/homework1-cse597-nlp.html 2/4

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>&gt;&gt;&gt;tokenize("'Medium-rare,' she said.")
["'", 'Medium', '-', 'rare', ',', "'",
</pre>
<pre> 'she', 'said', '.']
</pre>
</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
2/3/2021

</div>
<div class="column">
Ho

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>    &gt;&gt;&gt;random.seed(1)
    &gt;&gt;&gt;[m.random_token(())
</pre>
<pre>         for i in range(25)]
    ['&lt;END&gt;', 'c', 'b', 'a', 'a', 'a', 'b',
</pre>
<pre>     'b', '&lt;END&gt;', '&lt;END&gt;', 'c', 'a', 'b',
     '&lt;END&gt;', 'a', 'b', 'a', 'd', 'd',
     '&lt;END&gt;', '&lt;END&gt;', 'b', 'd', 'a', 'a']
</pre>
5. [20 points] In the NgramModel class, write a method random_text(self, token_count) which returns a string of space-separated tokens chosen at random using the random_token(self, context) method. Your starting context should always be the (n-1)-tuple (“&lt;START&gt;”, …, “&lt;START&gt;”), and the context should be updated as tokens are generated. If n = 1, your context should always be the empty tuple. Whenever the special token “&lt;END&gt;” is encountered, you should reset the context to the starting context.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>&gt;&gt;&gt;m = NgramModel(1)
&gt;&gt;&gt;m.update("a b c d")
&gt;&gt;&gt;m.update("a b a b")
&gt;&gt;&gt;random.seed(1)
&gt;&gt;&gt;m.random_text(13)
'&lt;END&gt; c b a a a b b &lt;END&gt; &lt;END&gt; c a b'
</pre>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>&gt;&gt;&gt;m = NgramModel(2)
&gt;&gt;&gt;m.update("a b c d")
&gt;&gt;&gt;m.update("a b a b")
&gt;&gt;&gt;random.seed(2)
&gt;&gt;&gt;m.random_text(15)
'a b &lt;END&gt; a b c d &lt;END&gt; a b a b a b c'
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
6. [10 points] Write a function create_ngram_model(n, path) which loads the text at the given path and creates an n-gram model from the resulting data. Each line in the file should be treated as a separate sentence.

</div>
</div>
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
<pre># No random seeds, so your results may vary
</pre>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
7. [10 points] Suppose we define the perplexity of a sequence of m tokens &lt; w1, w2, . . . , wm &gt; to be

For example, in the case of a bigram model under the framework used in the rest of the assignment, we would generate the bigrams &lt; (w0 = &lt; START &gt;, w1), (w1, w2), . . . , (wm-1, wm), (wm, wm+1 = &lt;END&gt;) &gt;,

and would then compute the perplexity as

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>&gt;&gt;&gt;m = create_ngram_model(1, "frankenstein.txt"); m.random_text(15)
'beat astonishment brought his for how , door &lt;END&gt; his . pertinacity to I felt'
&gt;&gt;&gt;m = create_ngram_model(2, "frankenstein.txt"); m.random_text(15)
'As the great was extreme during the end of being . &lt;END&gt; Fortunately the sun'
&gt;&gt;&gt;m = create_ngram_model(3, "frankenstein.txt"); m.random_text(15)
'I had so long inhabited . &lt;END&gt; You were thrown , by returning with greater'
&gt;&gt;&gt;m = create_ngram_model(4, "frankenstein.txt"); m.random_text(15)
'We were soon joined by Elizabeth . &lt;END&gt; At these moments I wept bitterly and'
</pre>
</div>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
file:///Users/rebecca/Google Drive (rjp49@psu.edu)/teaching/NLP/Spring2021/homework/Assignment_1/homework1-cse597-nlp.html 3/4

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
mework 1

<pre> &gt;&gt;&gt;random.seed(2)
 &gt;&gt;&gt;[m.random_token(("&lt;START&gt;",))
</pre>
<pre>      for i in range(6)]
 ['a', 'a', 'a', 'a', 'a', 'a']
 &gt;&gt;&gt;[m.random_token(("b",))
</pre>
<pre>      for i in range(6)]
 ['c', '&lt;END&gt;', 'a', 'a', 'a', '&lt;END&gt;']
</pre>
</div>
</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="layoutArea">
<div class="column">
2/3/2021 Homework 1

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Intuitively, the lower the perplexity, the better the input sequence is explained by the model. Higher values indicate the input was “perplexing” from the model’s point of view, hence the term perplexity.

In the NgramModel class, write a method perplexity(self, sentence) which computes the n-grams for the input sentence and returns their perplexity under the current model. Hint: Consider performing an intermediate computation in log-space and re-exponentiating at the end, so as to avoid numerical overflow.

2. Feedback [5 points]

1. [1 point] Approximately how long did you spend on this assignment?

2. [2 points] Which aspects of this assignment did you find most challenging? Were there any significant stumbling blocks?

3. [2 points] Which aspects of this assignment did you like? Is there anything you would have changed?

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>&gt;&gt;&gt;m = NgramModel(1)
&gt;&gt;&gt;m.update("a b c d")
&gt;&gt;&gt;m.update("a b a b")
&gt;&gt;&gt;m.perplexity("a b")
3.815714141844439
</pre>
</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>&gt;&gt;&gt;m = NgramModel(2)
&gt;&gt;&gt;m.update("a b c d")
&gt;&gt;&gt;m.update("a b a b")
&gt;&gt;&gt;m.perplexity("a b")
1.4422495703074083
</pre>
</div>
</div>
</div>
</div>
</div>
</div>
