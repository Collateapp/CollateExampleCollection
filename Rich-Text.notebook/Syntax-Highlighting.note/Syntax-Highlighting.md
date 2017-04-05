---
title: Syntax Highlighting
tags: []
type: richtext
modified: '2017-04-04T15:50:31.286Z'
---
<p>Javascript:</p><pre class="ql-syntax" spellcheck="false">var fizzBuzz = <span class="hljs-function"><span class="hljs-keyword">function</span> <span class="hljs-params">()</span></span> {
  var i, <span class="hljs-built_in">output</span>;
  <span class="hljs-keyword">for</span> (i = <span class="hljs-number">1</span>; i &lt; <span class="hljs-number">101</span>; i += <span class="hljs-number">1</span>) {
    <span class="hljs-built_in">output</span> = <span class="hljs-string">''</span>;
    <span class="hljs-keyword">if</span> (!(i % <span class="hljs-number">3</span>)) { <span class="hljs-built_in">output</span> += <span class="hljs-string">'Fizz'</span>; }
    <span class="hljs-keyword">if</span> (!(i % <span class="hljs-number">5</span>)) { <span class="hljs-built_in">output</span> += <span class="hljs-string">'Buzz'</span>; }
    console.log(<span class="hljs-built_in">output</span> || i);//empty string is <span class="hljs-literal">false</span>, so we short-circuit
  }
};

</pre><p><br></p><p>Python:</p><pre class="ql-syntax" spellcheck="false"><span class="hljs-keyword">for</span> i <span class="hljs-keyword">in</span> xrange(1, 101):
    <span class="hljs-keyword">if</span> i&nbsp;% 15 == 0:
        <span class="hljs-built_in">print</span> <span class="hljs-string">"FizzBuzz"</span>
    <span class="hljs-keyword">elif</span> i&nbsp;% 3 == 0:
        <span class="hljs-built_in">print</span> <span class="hljs-string">"Fizz"</span>
    <span class="hljs-keyword">elif</span> i&nbsp;% 5 == 0:
        <span class="hljs-built_in">print</span> <span class="hljs-string">"Buzz"</span>
    <span class="hljs-keyword">else</span>:
        <span class="hljs-built_in">print</span> i
</pre><p><br></p><p>C:</p><pre class="ql-syntax" spellcheck="false"><span class="hljs-meta">#include&lt;stdio.h&gt;</span>
&nbsp;
<span class="hljs-function"><span class="hljs-keyword">int</span> <span class="hljs-title">main</span> <span class="hljs-params">(<span class="hljs-keyword">void</span>)</span>
</span>{
    <span class="hljs-keyword">int</span> i;
    <span class="hljs-keyword">for</span> (i = <span class="hljs-number">1</span>; i &lt;= <span class="hljs-number">100</span>; i++)
    {
        <span class="hljs-keyword">if</span> (!(i % <span class="hljs-number">15</span>))
            <span class="hljs-built_in">printf</span> (<span class="hljs-string">"FizzBuzz"</span>);
        <span class="hljs-keyword">else</span> <span class="hljs-keyword">if</span> (!(i % <span class="hljs-number">3</span>))
            <span class="hljs-built_in">printf</span> (<span class="hljs-string">"Fizz"</span>);
        <span class="hljs-keyword">else</span> <span class="hljs-keyword">if</span> (!(i % <span class="hljs-number">5</span>))
            <span class="hljs-built_in">printf</span> (<span class="hljs-string">"Buzz"</span>);
        <span class="hljs-keyword">else</span>
            <span class="hljs-built_in">printf</span> (<span class="hljs-string">"%d"</span>, i);
&nbsp;
        <span class="hljs-built_in">printf</span>(<span class="hljs-string">"\n"</span>);
    }
    <span class="hljs-keyword">return</span> <span class="hljs-number">0</span>;
}
</pre><p><br></p><p>R:</p><pre class="ql-syntax" spellcheck="false">xx &lt;- x &lt;- <span class="hljs-number">1</span>:<span class="hljs-number">100</span>
xx[x&nbsp;<span class="hljs-meta">%%</span> <span class="hljs-number">3</span> == <span class="hljs-number">0</span>] &lt;- <span class="hljs-string">"Fizz"</span>
xx[x&nbsp;<span class="hljs-meta">%%</span> <span class="hljs-number">5</span> == <span class="hljs-number">0</span>] &lt;- <span class="hljs-string">"Buzz"</span>
xx[x&nbsp;<span class="hljs-meta">%%</span> <span class="hljs-number">15</span> == <span class="hljs-number">0</span>] &lt;- <span class="hljs-string">"FizzBuzz"</span>
xx
</pre><p><br></p>
