---
layout: api
class: Bench_Transliterate
---
<h1>Bench_Transliterate</h1>
extends <a href='/documentation/api/Codebench'>Codebench</a>
<br />
extends <a href='/documentation/api/Mountain Valley Church of God_Codebench'>Mountain Valley Church of God_Codebench</a>
<br />
<p>
<i>
</i>
</p>
<dl class='tags'>
<dt>package</dt>
<dd>Mountain Valley Church of God/Codebench</dd>
<dt>category</dt>
<dd>Tests</dd>
<dt>author</dt>
<dd>Geert De Deckere <geert@idoe.be></dd>
</dl>
<br />
<div class='toc row d-none d-sm-flex d-md-flex d-lg-flex d-xl-flex'>
<div class='constants col-4'>
<h3>Constants</h3>
<ul>
<li>
<em>None</em>
</li>
</ul>
</div>
<div class='properties col-4'>
<h3>Properties</h3>
<ul>
<li>
<a href="#property-description">$description</a>
</li>
<li>
<a href="#property-grades">$grades</a>
</li>
<li>
<a href="#property-loops">$loops</a>
</li>
<li>
<a href="#property-subjects">$subjects</a>
</li>
</ul>
</div>
<div class='methods col-4'>
<h3>Methods</h3>
<ul>
<li>
<a href="#bench_iconv">bench_iconv()</a>
</li>
<li>
<a href="#bench_utf8">bench_utf8()</a>
</li>
<li>
<a href="#__construct">__construct()</a>
</li>
<li>
<a href="#run">run()</a>
</li>
<li>
<a href="#_grade">_grade()</a>
</li>
<li>
<a href="#_method_filter">_method_filter()</a>
</li>

</ul>
</div>
</div>
<h1 id='properties'>Properties</h1>
<div class='properties'>
<dl>
<dt>
<h4 id='property-description'><small>public</small>  <span class='blue'></span> $description</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>string</small><span>(79)</span> "Inspired by:
		 http://forum.Mountain Valley Church of Godframework.org/comments.php?DiscussionID=6113"</pre></dd>
<dt>
<h4 id='property-grades'><small>public</small>  <span class='blue'>array</span> $grades</h4>
</dt>
<dd>
 <p>Grade letters with their maximum scores. Used to color the graphs.</p>
</dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>array</small><span>(6)</span> <span>(
    125 => <small>string</small><span>(1)</span> "A"
    150 => <small>string</small><span>(1)</span> "B"
    200 => <small>string</small><span>(1)</span> "C"
    300 => <small>string</small><span>(1)</span> "D"
    500 => <small>string</small><span>(1)</span> "E"
    "default" => <small>string</small><span>(1)</span> "F"
)</span></pre></dd>
<dt>
<h4 id='property-loops'><small>public</small>  <span class='blue'></span> $loops</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>integer</small> 10</pre></dd>
<dt>
<h4 id='property-subjects'><small>public</small>  <span class='blue'></span> $subjects</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>array</small><span>(215)</span> <span>(
    0 => <small>string</small><span>(1)</span> "a"
    1 => <small>string</small><span>(1)</span> "b"
    2 => <small>string</small><span>(1)</span> "c"
    3 => <small>string</small><span>(1)</span> "d"
    4 => <small>string</small><span>(1)</span> "1"
    5 => <small>string</small><span>(1)</span> "2"
    6 => <small>string</small><span>(1)</span> "3"
    7 => <small>string</small><span>(2)</span> "??"
    8 => <small>string</small><span>(2)</span> "??"
    9 => <small>string</small><span>(2)</span> "??"
    10 => <small>string</small><span>(3)</span> "???"
    11 => <small>string</small><span>(2)</span> "??"
    12 => <small>string</small><span>(2)</span> "??"
    13 => <small>string</small><span>(2)</span> "??"
    14 => <small>string</small><span>(2)</span> "??"
    15 => <small>string</small><span>(2)</span> "??"
    16 => <small>string</small><span>(2)</span> "??"
    17 => <small>string</small><span>(2)</span> "??"
    18 => <small>string</small><span>(2)</span> "??"
    19 => <small>string</small><span>(2)</span> "??"
    20 => <small>string</small><span>(2)</span> "??"
    21 => <small>string</small><span>(2)</span> "??"
    22 => <small>string</small><span>(3)</span> "???"
    23 => <small>string</small><span>(2)</span> "??"
    24 => <small>string</small><span>(2)</span> "??"
    25 => <small>string</small><span>(2)</span> "??"
    26 => <small>string</small><span>(3)</span> "???"
    27 => <small>string</small><span>(2)</span> "??"
    28 => <small>string</small><span>(2)</span> "??"
    29 => <small>string</small><span>(2)</span> "??"
    30 => <small>string</small><span>(2)</span> "??"
    31 => <small>string</small><span>(2)</span> "??"
    32 => <small>string</small><span>(3)</span> "???"
    33 => <small>string</small><span>(2)</span> "??"
    34 => <small>string</small><span>(2)</span> "??"
    35 => <small>string</small><span>(3)</span> "???"
    36 => <small>string</small><span>(2)</span> "??"
    37 => <small>string</small><span>(2)</span> "??"
    38 => <small>string</small><span>(2)</span> "??"
    39 => <small>string</small><span>(2)</span> "??"
    40 => <small>string</small><span>(2)</span> "??"
    41 => <small>string</small><span>(2)</span> "??"
    42 => <small>string</small><span>(2)</span> "??"
    43 => <small>string</small><span>(2)</span> "??"
    44 => <small>string</small><span>(2)</span> "??"
    45 => <small>string</small><span>(2)</span> "??"
    46 => <small>string</small><span>(2)</span> "??"
    47 => <small>string</small><span>(2)</span> "??"
    48 => <small>string</small><span>(3)</span> "???"
    49 => <small>string</small><span>(2)</span> "??"
    50 => <small>string</small><span>(2)</span> "??"
    51 => <small>string</small><span>(2)</span> "??"
    52 => <small>string</small><span>(2)</span> "??"
    53 => <small>string</small><span>(2)</span> "??"
    54 => <small>string</small><span>(2)</span> "??"
    55 => <small>string</small><span>(2)</span> "??"
    56 => <small>string</small><span>(2)</span> "??"
    57 => <small>string</small><span>(2)</span> "??"
    58 => <small>string</small><span>(2)</span> "??"
    59 => <small>string</small><span>(2)</span> "??"
    60 => <small>string</small><span>(2)</span> "??"
    61 => <small>string</small><span>(2)</span> "??"
    62 => <small>string</small><span>(2)</span> "??"
    63 => <small>string</small><span>(3)</span> "???"
    64 => <small>string</small><span>(3)</span> "???"
    65 => <small>string</small><span>(2)</span> "??"
    66 => <small>string</small><span>(2)</span> "??"
    67 => <small>string</small><span>(2)</span> "??"
    68 => <small>string</small><span>(3)</span> "???"
    69 => <small>string</small><span>(2)</span> "??"
    70 => <small>string</small><span>(2)</span> "??"
    71 => <small>string</small><span>(2)</span> "??"
    72 => <small>string</small><span>(2)</span> "??"
    73 => <small>string</small><span>(2)</span> "??"
    74 => <small>string</small><span>(2)</span> "??"
    75 => <small>string</small><span>(2)</span> "??"
    76 => <small>string</small><span>(2)</span> "??"
    77 => <small>string</small><span>(2)</span> "??"
    78 => <small>string</small><span>(2)</span> "??"
    79 => <small>string</small><span>(2)</span> "??"
    80 => <small>string</small><span>(2)</span> "??"
    81 => <small>string</small><span>(2)</span> "??"
    82 => <small>string</small><span>(2)</span> "??"
    83 => <small>string</small><span>(2)</span> "??"
    84 => <small>string</small><span>(2)</span> "??"
    85 => <small>string</small><span>(2)</span> "??"
    86 => <small>string</small><span>(2)</span> "??"
    87 => <small>string</small><span>(2)</span> "??"
    88 => <small>string</small><span>(2)</span> "??"
    89 => <small>string</small><span>(2)</span> "??"
    90 => <small>string</small><span>(2)</span> "??"
    91 => <small>string</small><span>(2)</span> "??"
    92 => <small>string</small><span>(2)</span> "??"
    93 => <small>string</small><span>(3)</span> "???"
    94 => <small>string</small><span>(2)</span> "??"
    95 => <small>string</small><span>(2)</span> "??"
    96 => <small>string</small><span>(2)</span> "??"
    97 => <small>string</small><span>(2)</span> "??"
    98 => <small>string</small><span>(3)</span> "???"
    99 => <small>string</small><span>(2)</span> "??"
    100 => <small>string</small><span>(2)</span> "??"
    101 => <small>string</small><span>(2)</span> "??"
    102 => <small>string</small><span>(2)</span> "??"
    103 => <small>string</small><span>(2)</span> "??"
    104 => <small>string</small><span>(2)</span> "??"
    105 => <small>string</small><span>(2)</span> "??"
    106 => <small>string</small><span>(2)</span> "??"
    107 => <small>string</small><span>(2)</span> "??"
    108 => <small>string</small><span>(2)</span> "??"
    109 => <small>string</small><span>(2)</span> "??"
    110 => <small>string</small><span>(2)</span> "??"
    111 => <small>string</small><span>(2)</span> "??"
    112 => <small>string</small><span>(2)</span> "??"
    113 => <small>string</small><span>(2)</span> "??"
    114 => <small>string</small><span>(2)</span> "??"
    115 => <small>string</small><span>(3)</span> "???"
    116 => <small>string</small><span>(2)</span> "??"
    117 => <small>string</small><span>(2)</span> "??"
    118 => <small>string</small><span>(2)</span> "??"
    119 => <small>string</small><span>(2)</span> "??"
    120 => <small>string</small><span>(2)</span> "??"
    121 => <small>string</small><span>(2)</span> "??"
    122 => <small>string</small><span>(2)</span> "??"
    123 => <small>string</small><span>(2)</span> "??"
    124 => <small>string</small><span>(2)</span> "??"
    125 => <small>string</small><span>(2)</span> "??"
    126 => <small>string</small><span>(2)</span> "??"
    127 => <small>string</small><span>(3)</span> "???"
    128 => <small>string</small><span>(2)</span> "??"
    129 => <small>string</small><span>(2)</span> "??"
    130 => <small>string</small><span>(2)</span> "??"
    131 => <small>string</small><span>(3)</span> "???"
    132 => <small>string</small><span>(2)</span> "??"
    133 => <small>string</small><span>(2)</span> "??"
    134 => <small>string</small><span>(2)</span> "??"
    135 => <small>string</small><span>(2)</span> "??"
    136 => <small>string</small><span>(2)</span> "??"
    137 => <small>string</small><span>(3)</span> "???"
    138 => <small>string</small><span>(2)</span> "??"
    139 => <small>string</small><span>(2)</span> "??"
    140 => <small>string</small><span>(3)</span> "???"
    141 => <small>string</small><span>(2)</span> "??"
    142 => <small>string</small><span>(2)</span> "??"
    143 => <small>string</small><span>(2)</span> "??"
    144 => <small>string</small><span>(2)</span> "??"
    145 => <small>string</small><span>(2)</span> "??"
    146 => <small>string</small><span>(2)</span> "??"
    147 => <small>string</small><span>(2)</span> "??"
    148 => <small>string</small><span>(2)</span> "??"
    149 => <small>string</small><span>(2)</span> "??"
    150 => <small>string</small><span>(2)</span> "??"
    151 => <small>string</small><span>(2)</span> "??"
    152 => <small>string</small><span>(2)</span> "??"
    153 => <small>string</small><span>(3)</span> "???"
    154 => <small>string</small><span>(2)</span> "??"
    155 => <small>string</small><span>(2)</span> "??"
    156 => <small>string</small><span>(2)</span> "??"
    157 => <small>string</small><span>(2)</span> "??"
    158 => <small>string</small><span>(2)</span> "??"
    159 => <small>string</small><span>(2)</span> "??"
    160 => <small>string</small><span>(2)</span> "??"
    161 => <small>string</small><span>(2)</span> "??"
    162 => <small>string</small><span>(2)</span> "??"
    163 => <small>string</small><span>(2)</span> "??"
    164 => <small>string</small><span>(2)</span> "??"
    165 => <small>string</small><span>(2)</span> "??"
    166 => <small>string</small><span>(2)</span> "??"
    167 => <small>string</small><span>(2)</span> "??"
    168 => <small>string</small><span>(3)</span> "???"
    169 => <small>string</small><span>(3)</span> "???"
    170 => <small>string</small><span>(2)</span> "??"
    171 => <small>string</small><span>(2)</span> "??"
    172 => <small>string</small><span>(2)</span> "??"
    173 => <small>string</small><span>(3)</span> "???"
    174 => <small>string</small><span>(2)</span> "??"
    175 => <small>string</small><span>(2)</span> "??"
    176 => <small>string</small><span>(2)</span> "??"
    177 => <small>string</small><span>(2)</span> "??"
    178 => <small>string</small><span>(2)</span> "??"
    179 => <small>string</small><span>(2)</span> "??"
    180 => <small>string</small><span>(2)</span> "??"
    181 => <small>string</small><span>(2)</span> "??"
    182 => <small>string</small><span>(2)</span> "??"
    183 => <small>string</small><span>(2)</span> "??"
    184 => <small>string</small><span>(2)</span> "??"
    185 => <small>string</small><span>(2)</span> "??"
    186 => <small>string</small><span>(2)</span> "??"
    187 => <small>string</small><span>(2)</span> "??"
    188 => <small>string</small><span>(2)</span> "??"
    189 => <small>string</small><span>(2)</span> "??"
    190 => <small>string</small><span>(2)</span> "??"
    191 => <small>string</small><span>(2)</span> "??"
    192 => <small>string</small><span>(2)</span> "??"
    193 => <small>string</small><span>(2)</span> "??"
    194 => <small>string</small><span>(2)</span> "??"
    195 => <small>string</small><span>(2)</span> "??"
    196 => <small>string</small><span>(2)</span> "??"
    197 => <small>string</small><span>(2)</span> "??"
    198 => <small>string</small><span>(3)</span> "???"
    199 => <small>string</small><span>(2)</span> "??"
    200 => <small>string</small><span>(2)</span> "??"
    201 => <small>string</small><span>(2)</span> "??"
    202 => <small>string</small><span>(2)</span> "??"
    203 => <small>string</small><span>(3)</span> "???"
    204 => <small>string</small><span>(2)</span> "??"
    205 => <small>string</small><span>(2)</span> "??"
    206 => <small>string</small><span>(2)</span> "??"
    207 => <small>string</small><span>(2)</span> "??"
    208 => <small>string</small><span>(2)</span> "??"
    209 => <small>string</small><span>(2)</span> "??"
    210 => <small>string</small><span>(2)</span> "??"
    211 => <small>string</small><span>(2)</span> "??"
    212 => <small>string</small><span>(2)</span> "??"
    213 => <small>string</small><span>(2)</span> "??"
    214 => <small>string</small><span>(2)</span> "??"
)</span></pre></dd>
</dl>
</div>
<h1 id='methods'>Methods</h1>
<div class='methods'>

<div class='method'>
<h3 id="bench_iconv"><small>public</small>  bench_iconv()<small> (defined in <a href='/documentation/api/Bench_Transliterate'>Bench_Transliterate</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function bench_iconv($subject)
{
	// Note: need to suppress errors on iconv because some chars trigger the following notice:
	// &quot;Detected an illegal character in input string&quot;
	return preg_replace(&#039;~[^-a-z0-9]+~i&#039;, &#039;&#039;, @iconv(&#039;UTF-8&#039;, &#039;ASCII//TRANSLIT&#039;, $subject));
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="bench_utf8"><small>public</small>  bench_utf8()<small> (defined in <a href='/documentation/api/Bench_Transliterate'>Bench_Transliterate</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function bench_utf8($subject)
{
	return UTF8::transliterate_to_ascii($subject);
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="__construct"><small>public</small>  __construct()<small> (defined in <a href='/documentation/api/Mountain Valley Church of God_Codebench'>Mountain Valley Church of God_Codebench</a>)</small></h3>
<div class='description'><p>Constructor.</p>
</div>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>void</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function __construct()
{
	// Set the maximum execution time
	set_time_limit(Mountain Valley Church of God::$config-&gt;load(&#039;codebench&#039;)-&gt;max_execution_time);
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="run"><small>public</small>  run()<small> (defined in <a href='/documentation/api/Mountain Valley Church of God_Codebench'>Mountain Valley Church of God_Codebench</a>)</small></h3>
<div class='description'><p>Runs Codebench on the extending class.</p>
</div>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>array</span>  - Benchmark output 
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function run()
{
	// Array of all methods to loop over
	$methods = array_filter(get_class_methods($this), [$this, &#039;_method_filter&#039;]);

	// Make sure the benchmark runs at least once,
	// also if no subject data has been provided.
	if (empty($this-&gt;subjects))
	{
		$this-&gt;subjects = [&#039;NULL&#039; =&gt; NULL];
	}

	// Initialize benchmark output
	$codebench = [
		&#039;class&#039;       =&gt; get_class($this),
		&#039;description&#039; =&gt; $this-&gt;description,
		&#039;loops&#039;       =&gt; [
			&#039;base&#039;    =&gt; (int) $this-&gt;loops,
			&#039;total&#039;   =&gt; (int) $this-&gt;loops * count($this-&gt;subjects) * count($methods),
		],
		&#039;subjects&#039;    =&gt; $this-&gt;subjects,
		&#039;benchmarks&#039;  =&gt; [],
	];

	// Benchmark each method
	foreach ($methods as $method)
	{
		// Initialize benchmark output for this method
		$codebench[&#039;benchmarks&#039;][$method] = [&#039;time&#039; =&gt; 0, &#039;memory&#039; =&gt; 0];

		// Using Reflection because simply calling $this-&gt;$method($subject) in the loop below
		// results in buggy benchmark times correlating to the length of the method name.
		$reflection = new ReflectionMethod(get_class($this), $method);

		// Benchmark each subject on each method
		foreach ($this-&gt;subjects as $subject_key =&gt; $subject)
		{
			// Prerun each method/subject combo before the actual benchmark loop.
			// This way relatively expensive initial processes won&#039;t be benchmarked, e.g. autoloading.
			// At the same time we capture the return here so we don&#039;t have to do that in the loop anymore.
			$return = $reflection-&gt;invoke($this, $subject);

			// Start the timer for one subject
			$token = Profiler::start(&#039;codebench&#039;, $method.$subject_key);

			// The heavy work
			for ($i = 0; $i &lt; $this-&gt;loops; ++$i)
			{
				$reflection-&gt;invoke($this, $subject);
			}

			// Stop and read the timer
			$benchmark = Profiler::total($token);

			// Benchmark output specific to the current method and subject
			$codebench[&#039;benchmarks&#039;][$method][&#039;subjects&#039;][$subject_key] = [
				&#039;return&#039; =&gt; $return,
				&#039;time&#039;   =&gt; $benchmark[0],
				&#039;memory&#039; =&gt; $benchmark[1],
			];

			// Update method totals
			$codebench[&#039;benchmarks&#039;][$method][&#039;time&#039;]   += $benchmark[0];
			$codebench[&#039;benchmarks&#039;][$method][&#039;memory&#039;] += $benchmark[1];
		}
	}

	// Initialize the fastest and slowest benchmarks for both methods and subjects, time and memory,
	// these values will be overwritten using min() and max() later on.
	// The 999999999 values look like a hack, I know, but they work,
	// unless your method runs for more than 31 years or consumes over 1GB of memory.
	$fastest_method = $fastest_subject = [&#039;time&#039; =&gt; 999999999, &#039;memory&#039; =&gt; 999999999];
	$slowest_method = $slowest_subject = [&#039;time&#039; =&gt; 0, &#039;memory&#039; =&gt; 0];

	// Find the fastest and slowest benchmarks, needed for the percentage calculations
	foreach ($methods as $method)
	{
		// Update the fastest and slowest method benchmarks
		$fastest_method[&#039;time&#039;]   = min($fastest_method[&#039;time&#039;],   $codebench[&#039;benchmarks&#039;][$method][&#039;time&#039;]);
		$fastest_method[&#039;memory&#039;] = min($fastest_method[&#039;memory&#039;], $codebench[&#039;benchmarks&#039;][$method][&#039;memory&#039;]);
		$slowest_method[&#039;time&#039;]   = max($slowest_method[&#039;time&#039;],   $codebench[&#039;benchmarks&#039;][$method][&#039;time&#039;]);
		$slowest_method[&#039;memory&#039;] = max($slowest_method[&#039;memory&#039;], $codebench[&#039;benchmarks&#039;][$method][&#039;memory&#039;]);

		foreach ($this-&gt;subjects as $subject_key =&gt; $subject)
		{
			// Update the fastest and slowest subject benchmarks
			$fastest_subject[&#039;time&#039;]   = min($fastest_subject[&#039;time&#039;],   $codebench[&#039;benchmarks&#039;][$method][&#039;subjects&#039;][$subject_key][&#039;time&#039;]);
			$fastest_subject[&#039;memory&#039;] = min($fastest_subject[&#039;memory&#039;], $codebench[&#039;benchmarks&#039;][$method][&#039;subjects&#039;][$subject_key][&#039;memory&#039;]);
			$slowest_subject[&#039;time&#039;]   = max($slowest_subject[&#039;time&#039;],   $codebench[&#039;benchmarks&#039;][$method][&#039;subjects&#039;][$subject_key][&#039;time&#039;]);
			$slowest_subject[&#039;memory&#039;] = max($slowest_subject[&#039;memory&#039;], $codebench[&#039;benchmarks&#039;][$method][&#039;subjects&#039;][$subject_key][&#039;memory&#039;]);
		}
	}

	// Percentage calculations for methods
	foreach ($codebench[&#039;benchmarks&#039;] as &amp; $method)
	{
		// Calculate percentage difference relative to fastest and slowest methods
		$method[&#039;percent&#039;][&#039;fastest&#039;][&#039;time&#039;]   = (empty($fastest_method[&#039;time&#039;]))   ? 0 : ($method[&#039;time&#039;]   / $fastest_method[&#039;time&#039;]   * 100);
		$method[&#039;percent&#039;][&#039;fastest&#039;][&#039;memory&#039;] = (empty($fastest_method[&#039;memory&#039;])) ? 0 : ($method[&#039;memory&#039;] / $fastest_method[&#039;memory&#039;] * 100);
		$method[&#039;percent&#039;][&#039;slowest&#039;][&#039;time&#039;]   = (empty($slowest_method[&#039;time&#039;]))   ? 0 : ($method[&#039;time&#039;]   / $slowest_method[&#039;time&#039;]   * 100);
		$method[&#039;percent&#039;][&#039;slowest&#039;][&#039;memory&#039;] = (empty($slowest_method[&#039;memory&#039;])) ? 0 : ($method[&#039;memory&#039;] / $slowest_method[&#039;memory&#039;] * 100);

		// Assign a grade for time and memory to each method
		$method[&#039;grade&#039;][&#039;time&#039;]   = $this-&gt;_grade($method[&#039;percent&#039;][&#039;fastest&#039;][&#039;time&#039;]);
		$method[&#039;grade&#039;][&#039;memory&#039;] = $this-&gt;_grade($method[&#039;percent&#039;][&#039;fastest&#039;][&#039;memory&#039;]);

		// Percentage calculations for subjects
		foreach ($method[&#039;subjects&#039;] as &amp; $subject)
		{
			// Calculate percentage difference relative to fastest and slowest subjects for this method
			$subject[&#039;percent&#039;][&#039;fastest&#039;][&#039;time&#039;]   = (empty($fastest_subject[&#039;time&#039;]))   ? 0 : ($subject[&#039;time&#039;]   / $fastest_subject[&#039;time&#039;]   * 100);
			$subject[&#039;percent&#039;][&#039;fastest&#039;][&#039;memory&#039;] = (empty($fastest_subject[&#039;memory&#039;])) ? 0 : ($subject[&#039;memory&#039;] / $fastest_subject[&#039;memory&#039;] * 100);
			$subject[&#039;percent&#039;][&#039;slowest&#039;][&#039;time&#039;]   = (empty($slowest_subject[&#039;time&#039;]))   ? 0 : ($subject[&#039;time&#039;]   / $slowest_subject[&#039;time&#039;]   * 100);
			$subject[&#039;percent&#039;][&#039;slowest&#039;][&#039;memory&#039;] = (empty($slowest_subject[&#039;memory&#039;])) ? 0 : ($subject[&#039;memory&#039;] / $slowest_subject[&#039;memory&#039;] * 100);

			// Assign a grade letter for time and memory to each subject
			$subject[&#039;grade&#039;][&#039;time&#039;]   = $this-&gt;_grade($subject[&#039;percent&#039;][&#039;fastest&#039;][&#039;time&#039;]);
			$subject[&#039;grade&#039;][&#039;memory&#039;] = $this-&gt;_grade($subject[&#039;percent&#039;][&#039;fastest&#039;][&#039;memory&#039;]);
		}
	}

	return $codebench;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_grade"><small>protected</small>  _grade(<small>integer|double</small> <span class="param" title="Score">$score</span> )<small> (defined in <a href='/documentation/api/Mountain Valley Church of God_Codebench'>Mountain Valley Church of God_Codebench</a>)</small></h3>
<div class='description'><p>Returns the applicable grade letter for a score.</p>
</div>
<h4>Parameters</h4>
<ul>
<li>
 <span class="blue">integer|double </span><strong> $score</strong> <small>required</small> - Score</li>
</ul>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>string</span>  - Grade letter 
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">protected function _grade($score)
{
	foreach ($this-&gt;grades as $max =&gt; $grade)
	{
		if ($max === &#039;default&#039;)
			continue;

		if ($score &lt;= $max)
			return $grade;
	}

	return $this-&gt;grades[&#039;default&#039;];
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_method_filter"><small>protected</small>  _method_filter(<small>string</small> <span class="param" title="Method name">$method</span> )<small> (defined in <a href='/documentation/api/Mountain Valley Church of God_Codebench'>Mountain Valley Church of God_Codebench</a>)</small></h3>
<div class='description'><p>Callback for array_filter().
Filters out all methods not to benchmark.</p>
</div>
<h4>Parameters</h4>
<ul>
<li>
 <span class="blue">string </span><strong> $method</strong> <small>required</small> - Method name</li>
</ul>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>boolean</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">protected function _method_filter($method)
{
	// Only benchmark methods with the &quot;bench&quot; prefix
	return (substr($method, 0, 5) === &#039;bench&#039;);
}</code>
</pre>
</div>
</div>
</div>