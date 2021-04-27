---
layout: api
class: Database_Query_Builder_Select
---
<h1>Database_Query_Builder_Select</h1>
extends <a href='/documentation/api/Kohana_Database_Query_Builder_Select'>Kohana_Database_Query_Builder_Select</a>
<br />
extends <a href='/documentation/api/Database_Query_Builder_Where'>Database_Query_Builder_Where</a>
<br />
extends <a href='/documentation/api/Kohana_Database_Query_Builder_Where'>Kohana_Database_Query_Builder_Where</a>
<br />
extends <a href='/documentation/api/Database_Query_Builder'>Database_Query_Builder</a>
<br />
extends <a href='/documentation/api/Kohana_Database_Query_Builder'>Kohana_Database_Query_Builder</a>
<br />
extends <a href='/documentation/api/Database_Query'>Database_Query</a>
<br />
extends <a href='/documentation/api/Kohana_Database_Query'>Kohana_Database_Query</a>
<br />
<p>
<i><p>Database query builder for SELECT statements. See <a href="/database/query/builder">Query Builder</a> for usage and examples.</p>
</i>
</p>
<dl class='tags'>
<dt>package</dt>
<dd>Kohana/Database</dd>
<dt>category</dt>
<dd>Query</dd>
<dt>author</dt>
<dd>Kohana Team</dd>
<dt>copyright</dt>
<dd>(c) Kohana Team</dd>
<dt>license</dt>
<dd>https://mvcog.github.io/LICENSE.md</dd>
</dl>
<br />
<div class='callout-block callout-info'>
<div class='icon-holder'>
<i class='fas fa-info-circle'></i>
</div>
<div class='content'>
<h4 class='callout-title'>Information</h4>
<p>This class is a transparent base class for <a href='/documentation/api/Kohana_Database_Query_Builder_Select'>Kohana_Database_Query_Builder_Select</a></p>
</div>
</div>
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
<a href="#property-_as_object">$_as_object</a>
</li>
<li>
<a href="#property-_distinct">$_distinct</a>
</li>
<li>
<a href="#property-_force_execute">$_force_execute</a>
</li>
<li>
<a href="#property-_from">$_from</a>
</li>
<li>
<a href="#property-_group_by">$_group_by</a>
</li>
<li>
<a href="#property-_having">$_having</a>
</li>
<li>
<a href="#property-_join">$_join</a>
</li>
<li>
<a href="#property-_last_join">$_last_join</a>
</li>
<li>
<a href="#property-_lifetime">$_lifetime</a>
</li>
<li>
<a href="#property-_limit">$_limit</a>
</li>
<li>
<a href="#property-_object_params">$_object_params</a>
</li>
<li>
<a href="#property-_offset">$_offset</a>
</li>
<li>
<a href="#property-_order_by">$_order_by</a>
</li>
<li>
<a href="#property-_parameters">$_parameters</a>
</li>
<li>
<a href="#property-_select">$_select</a>
</li>
<li>
<a href="#property-_sql">$_sql</a>
</li>
<li>
<a href="#property-_type">$_type</a>
</li>
<li>
<a href="#property-_union">$_union</a>
</li>
<li>
<a href="#property-_where">$_where</a>
</li>
</ul>
</div>
<div class='methods col-4'>
<h3>Methods</h3>
<ul>
<li>
<a href="#__construct">__construct()</a>
</li>
<li>
<a href="#and_having">and_having()</a>
</li>
<li>
<a href="#and_having_close">and_having_close()</a>
</li>
<li>
<a href="#and_having_open">and_having_open()</a>
</li>
<li>
<a href="#compile">compile()</a>
</li>
<li>
<a href="#distinct">distinct()</a>
</li>
<li>
<a href="#from">from()</a>
</li>
<li>
<a href="#group_by">group_by()</a>
</li>
<li>
<a href="#having">having()</a>
</li>
<li>
<a href="#having_close">having_close()</a>
</li>
<li>
<a href="#having_open">having_open()</a>
</li>
<li>
<a href="#join">join()</a>
</li>
<li>
<a href="#offset">offset()</a>
</li>
<li>
<a href="#on">on()</a>
</li>
<li>
<a href="#or_having">or_having()</a>
</li>
<li>
<a href="#or_having_close">or_having_close()</a>
</li>
<li>
<a href="#or_having_open">or_having_open()</a>
</li>
<li>
<a href="#reset">reset()</a>
</li>
<li>
<a href="#select">select()</a>
</li>
<li>
<a href="#select_array">select_array()</a>
</li>
<li>
<a href="#union">union()</a>
</li>
<li>
<a href="#using">using()</a>
</li>
<li>
<a href="#and_where">and_where()</a>
</li>
<li>
<a href="#and_where_close">and_where_close()</a>
</li>
<li>
<a href="#and_where_open">and_where_open()</a>
</li>
<li>
<a href="#limit">limit()</a>
</li>
<li>
<a href="#or_where">or_where()</a>
</li>
<li>
<a href="#or_where_close">or_where_close()</a>
</li>
<li>
<a href="#or_where_open">or_where_open()</a>
</li>
<li>
<a href="#order_by">order_by()</a>
</li>
<li>
<a href="#where">where()</a>
</li>
<li>
<a href="#where_close">where_close()</a>
</li>
<li>
<a href="#where_close_empty">where_close_empty()</a>
</li>
<li>
<a href="#where_open">where_open()</a>
</li>
<li>
<a href="#__toString">__toString()</a>
</li>
<li>
<a href="#as_assoc">as_assoc()</a>
</li>
<li>
<a href="#as_object">as_object()</a>
</li>
<li>
<a href="#bind">bind()</a>
</li>
<li>
<a href="#cached">cached()</a>
</li>
<li>
<a href="#execute">execute()</a>
</li>
<li>
<a href="#param">param()</a>
</li>
<li>
<a href="#parameters">parameters()</a>
</li>
<li>
<a href="#type">type()</a>
</li>
<li>
<a href="#_compile_conditions">_compile_conditions()</a>
</li>
<li>
<a href="#_compile_group_by">_compile_group_by()</a>
</li>
<li>
<a href="#_compile_join">_compile_join()</a>
</li>
<li>
<a href="#_compile_order_by">_compile_order_by()</a>
</li>
<li>
<a href="#_compile_set">_compile_set()</a>
</li>

</ul>
</div>
</div>
<h1 id='properties'>Properties</h1>
<div class='properties'>
<dl>
<dt>
<h4 id='property-_as_object'><small>protected</small>  <span class='blue'></span> $_as_object</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>bool</small> FALSE</pre></dd>
<dt>
<h4 id='property-_distinct'><small>protected</small>  <span class='blue'></span> $_distinct</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>bool</small> FALSE</pre></dd>
<dt>
<h4 id='property-_force_execute'><small>protected</small>  <span class='blue'></span> $_force_execute</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>bool</small> FALSE</pre></dd>
<dt>
<h4 id='property-_from'><small>protected</small>  <span class='blue'></span> $_from</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>array</small><span>(0)</span> </pre></dd>
<dt>
<h4 id='property-_group_by'><small>protected</small>  <span class='blue'></span> $_group_by</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>array</small><span>(0)</span> </pre></dd>
<dt>
<h4 id='property-_having'><small>protected</small>  <span class='blue'></span> $_having</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>array</small><span>(0)</span> </pre></dd>
<dt>
<h4 id='property-_join'><small>protected</small>  <span class='blue'></span> $_join</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>array</small><span>(0)</span> </pre></dd>
<dt>
<h4 id='property-_last_join'><small>protected</small>  <span class='blue'></span> $_last_join</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>NULL</small></pre></dd>
<dt>
<h4 id='property-_lifetime'><small>protected</small>  <span class='blue'></span> $_lifetime</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>NULL</small></pre></dd>
<dt>
<h4 id='property-_limit'><small>protected</small>  <span class='blue'></span> $_limit</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>NULL</small></pre></dd>
<dt>
<h4 id='property-_object_params'><small>protected</small>  <span class='blue'></span> $_object_params</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>array</small><span>(0)</span> </pre></dd>
<dt>
<h4 id='property-_offset'><small>protected</small>  <span class='blue'></span> $_offset</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>NULL</small></pre></dd>
<dt>
<h4 id='property-_order_by'><small>protected</small>  <span class='blue'></span> $_order_by</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>array</small><span>(0)</span> </pre></dd>
<dt>
<h4 id='property-_parameters'><small>protected</small>  <span class='blue'></span> $_parameters</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>array</small><span>(0)</span> </pre></dd>
<dt>
<h4 id='property-_select'><small>protected</small>  <span class='blue'></span> $_select</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>array</small><span>(0)</span> </pre></dd>
<dt>
<h4 id='property-_sql'><small>protected</small>  <span class='blue'></span> $_sql</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>NULL</small></pre></dd>
<dt>
<h4 id='property-_type'><small>protected</small>  <span class='blue'></span> $_type</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>NULL</small></pre></dd>
<dt>
<h4 id='property-_union'><small>protected</small>  <span class='blue'></span> $_union</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>array</small><span>(0)</span> </pre></dd>
<dt>
<h4 id='property-_where'><small>protected</small>  <span class='blue'></span> $_where</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>array</small><span>(0)</span> </pre></dd>
</dl>
</div>
<h1 id='methods'>Methods</h1>
<div class='methods'>

<div class='method'>
<h3 id="__construct"><small>public</small>  __construct([ <small>array</small> <span class="param" title="Column list">$columns</span> <small>= <small>NULL</small></small> ] )<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder_Select'>Kohana_Database_Query_Builder_Select</a>)</small></h3>
<div class='description'><p>Sets the initial columns to select from.</p>
</div>
<h4>Parameters</h4>
<ul>
<li>
 <span class="blue">array </span><strong> $columns</strong> <small> = <small>NULL</small></small> - Column list</li>
</ul>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>void</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function __construct(array $columns = NULL)
{
	if ( ! empty($columns))
	{
		// Set the initial columns
		$this-&gt;_select = $columns;
	}

	// Start the query with no actual SQL statement
	parent::__construct(Database::SELECT, &#039;&#039;);
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="and_having"><small>public</small>  and_having(<small>mixed</small> <span class="param" title="Column name or array($column, $alias) or object">$column</span> , <small>string</small> <span class="param" title="Logic operator">$op</span> [, <small>mixed</small> <span class="param" title="Column value">$value</span> <small>= <small>NULL</small></small> ] )<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder_Select'>Kohana_Database_Query_Builder_Select</a>)</small></h3>
<div class='description'><p>Creates a new "AND HAVING" condition for the query.</p>
</div>
<h4>Parameters</h4>
<ul>
<li>
 <span class="blue">mixed </span><strong> $column</strong> <small>required</small> - Column name or array($column, $alias) or object</li>
<li>
 <span class="blue">string </span><strong> $op</strong> <small>required</small> - Logic operator</li>
<li>
 <span class="blue">mixed </span><strong> $value</strong> <small> = <small>NULL</small></small> - Column value</li>
</ul>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>$this</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function and_having($column, $op, $value = NULL)
{
	$this-&gt;_having[] = [&#039;AND&#039; =&gt; [$column, $op, $value]];

	return $this;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="and_having_close"><small>public</small>  and_having_close()<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder_Select'>Kohana_Database_Query_Builder_Select</a>)</small></h3>
<div class='description'><p>Closes an open "AND HAVING (...)" grouping.</p>
</div>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>$this</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function and_having_close()
{
	$this-&gt;_having[] = [&#039;AND&#039; =&gt; &#039;)&#039;];

	return $this;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="and_having_open"><small>public</small>  and_having_open()<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder_Select'>Kohana_Database_Query_Builder_Select</a>)</small></h3>
<div class='description'><p>Opens a new "AND HAVING (...)" grouping.</p>
</div>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>$this</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function and_having_open()
{
	$this-&gt;_having[] = [&#039;AND&#039; =&gt; &#039;(&#039;];

	return $this;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="compile"><small>public</small>  compile([ <small>mixed</small> <span class="param" title="Database instance or name of instance">$db</span> <small>= <small>NULL</small></small> ] )<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder_Select'>Kohana_Database_Query_Builder_Select</a>)</small></h3>
<div class='description'><p>Compile the SQL query and return it.</p>
</div>
<h4>Parameters</h4>
<ul>
<li>
 <span class="blue">mixed </span><strong> $db</strong> <small> = <small>NULL</small></small> - Database instance or name of instance</li>
</ul>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>string</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function compile($db = NULL)
{
	if ( ! is_object($db))
	{
		// Get the database instance
		$db = Database::instance($db);
	}

	// Callback to quote columns
	$quote_column = [$db, &#039;quote_column&#039;];

	// Callback to quote tables
	$quote_table = [$db, &#039;quote_table&#039;];

	// Start a selection query
	$query = &#039;SELECT &#039;;

	if ($this-&gt;_distinct === TRUE)
	{
		// Select only unique results
		$query .= &#039;DISTINCT &#039;;
	}

	if (empty($this-&gt;_select))
	{
		// Select all columns
		$query .= &#039;*&#039;;
	}
	else
	{
		// Select all columns
		$query .= implode(&#039;, &#039;, array_unique(array_map($quote_column, $this-&gt;_select)));
	}

	if ( ! empty($this-&gt;_from))
	{
		// Set tables to select from
		$query .= &#039; FROM &#039;.implode(&#039;, &#039;, array_unique(array_map($quote_table, $this-&gt;_from)));
	}

	if ( ! empty($this-&gt;_join))
	{
		// Add tables to join
		$query .= &#039; &#039;.$this-&gt;_compile_join($db, $this-&gt;_join);
	}

	if ( ! empty($this-&gt;_where))
	{
		// Add selection conditions
		$query .= &#039; WHERE &#039;.$this-&gt;_compile_conditions($db, $this-&gt;_where);
	}

	if ( ! empty($this-&gt;_group_by))
	{
		// Add grouping
		$query .= &#039; &#039;.$this-&gt;_compile_group_by($db, $this-&gt;_group_by);
	}

	if ( ! empty($this-&gt;_having))
	{
		// Add filtering conditions
		$query .= &#039; HAVING &#039;.$this-&gt;_compile_conditions($db, $this-&gt;_having);
	}

	if ( ! empty($this-&gt;_order_by))
	{
		// Add sorting
		$query .= &#039; &#039;.$this-&gt;_compile_order_by($db, $this-&gt;_order_by);
	}

	if ($this-&gt;_limit !== NULL)
	{
		// Add limiting
		$query .= &#039; LIMIT &#039;.$this-&gt;_limit;
	}

	if ($this-&gt;_offset !== NULL)
	{
		// Add offsets
		$query .= &#039; OFFSET &#039;.$this-&gt;_offset;
	}

	if ( ! empty($this-&gt;_union))
	{
		$query = &#039;(&#039;.$query.&#039;)&#039;;
		foreach ($this-&gt;_union as $u) {
			$query .= &#039; UNION &#039;;
			if ($u[&#039;all&#039;] === TRUE)
			{
				$query .= &#039;ALL &#039;;
			}
			$query .= &#039;(&#039;.$u[&#039;select&#039;]-&gt;compile($db).&#039;)&#039;;
		}
	}

	$this-&gt;_sql = $query;

	return parent::compile($db);
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="distinct"><small>public</small>  distinct(<small>boolean</small> <span class="param" title="Enable or disable distinct columns">$value</span> )<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder_Select'>Kohana_Database_Query_Builder_Select</a>)</small></h3>
<div class='description'><p>Enables or disables selecting only unique columns using "SELECT DISTINCT"</p>
</div>
<h4>Parameters</h4>
<ul>
<li>
 <span class="blue">boolean </span><strong> $value</strong> <small>required</small> - Enable or disable distinct columns</li>
</ul>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>$this</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function distinct($value)
{
	$this-&gt;_distinct = (bool) $value;

	return $this;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="from"><small>public</small>  from(<small>mixed</small> <span class="param" title="$table table name or array($table, $alias) or object">$tables</span> )<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder_Select'>Kohana_Database_Query_Builder_Select</a>)</small></h3>
<div class='description'><p>Choose the tables to select "FROM ..."</p>
</div>
<h4>Parameters</h4>
<ul>
<li>
 <span class="blue">mixed </span><strong> $tables</strong> <small>required</small> - $table  table name or array($table, $alias) or object</li>
</ul>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>$this</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function from($tables)
{
	$tables = func_get_args();

	$this-&gt;_from = array_merge($this-&gt;_from, $tables);

	return $this;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="group_by"><small>public</small>  group_by(<small>mixed</small> <span class="param" title="Column name or array($column, $alias) or object">$columns</span> )<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder_Select'>Kohana_Database_Query_Builder_Select</a>)</small></h3>
<div class='description'><p>Creates a "GROUP BY ..." filter.</p>
</div>
<h4>Parameters</h4>
<ul>
<li>
 <span class="blue">mixed </span><strong> $columns</strong> <small>required</small> - Column name or array($column, $alias) or object</li>
</ul>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>$this</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function group_by($columns)
{
	$columns = func_get_args();

	$this-&gt;_group_by = array_merge($this-&gt;_group_by, $columns);

	return $this;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="having"><small>public</small>  having(<small>mixed</small> <span class="param" title="Column name or array($column, $alias) or object">$column</span> , <small>string</small> <span class="param" title="Logic operator">$op</span> [, <small>mixed</small> <span class="param" title="Column value">$value</span> <small>= <small>NULL</small></small> ] )<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder_Select'>Kohana_Database_Query_Builder_Select</a>)</small></h3>
<div class='description'><p>Alias of and_having()</p>
</div>
<h4>Parameters</h4>
<ul>
<li>
 <span class="blue">mixed </span><strong> $column</strong> <small>required</small> - Column name or array($column, $alias) or object</li>
<li>
 <span class="blue">string </span><strong> $op</strong> <small>required</small> - Logic operator</li>
<li>
 <span class="blue">mixed </span><strong> $value</strong> <small> = <small>NULL</small></small> - Column value</li>
</ul>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>$this</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function having($column, $op, $value = NULL)
{
	return $this-&gt;and_having($column, $op, $value);
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="having_close"><small>public</small>  having_close()<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder_Select'>Kohana_Database_Query_Builder_Select</a>)</small></h3>
<div class='description'><p>Closes an open "AND HAVING (...)" grouping.</p>
</div>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>$this</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function having_close()
{
	return $this-&gt;and_having_close();
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="having_open"><small>public</small>  having_open()<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder_Select'>Kohana_Database_Query_Builder_Select</a>)</small></h3>
<div class='description'><p>Alias of and_having_open()</p>
</div>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>$this</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function having_open()
{
	return $this-&gt;and_having_open();
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="join"><small>public</small>  join(<small>mixed</small> <span class="param" title="Column name or array($column, $alias) or object">$table</span> [, <small>string</small> <span class="param" title="Join type (LEFT, RIGHT, INNER, etc)">$type</span> <small>= <small>NULL</small></small> ] )<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder_Select'>Kohana_Database_Query_Builder_Select</a>)</small></h3>
<div class='description'><p>Adds addition tables to "JOIN ...".</p>
</div>
<h4>Parameters</h4>
<ul>
<li>
 <span class="blue">mixed </span><strong> $table</strong> <small>required</small> - Column name or array($column, $alias) or object</li>
<li>
 <span class="blue">string </span><strong> $type</strong> <small> = <small>NULL</small></small> - Join type (LEFT, RIGHT, INNER, etc)</li>
</ul>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>$this</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function join($table, $type = NULL)
{
	$this-&gt;_join[] = $this-&gt;_last_join = new Database_Query_Builder_Join($table, $type);

	return $this;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="offset"><small>public</small>  offset(<small>integer</small> <span class="param" title="Starting result number or NULL to reset">$number</span> )<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder_Select'>Kohana_Database_Query_Builder_Select</a>)</small></h3>
<div class='description'><p>Start returning results after "OFFSET ..."</p>
</div>
<h4>Parameters</h4>
<ul>
<li>
 <span class="blue">integer </span><strong> $number</strong> <small>required</small> - Starting result number or NULL to reset</li>
</ul>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>$this</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function offset($number)
{
	$this-&gt;_offset = ($number === NULL) ? NULL : (int) $number;

	return $this;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="on"><small>public</small>  on(<small>mixed</small> <span class="param" title="Column name or array($column, $alias) or object">$c1</span> , <small>string</small> <span class="param" title="Logic operator">$op</span> , <small>mixed</small> <span class="param" title="Column name or array($column, $alias) or object">$c2</span> )<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder_Select'>Kohana_Database_Query_Builder_Select</a>)</small></h3>
<div class='description'><p>Adds "ON ..." conditions for the last created JOIN statement.</p>
</div>
<h4>Parameters</h4>
<ul>
<li>
 <span class="blue">mixed </span><strong> $c1</strong> <small>required</small> - Column name or array($column, $alias) or object</li>
<li>
 <span class="blue">string </span><strong> $op</strong> <small>required</small> - Logic operator</li>
<li>
 <span class="blue">mixed </span><strong> $c2</strong> <small>required</small> - Column name or array($column, $alias) or object</li>
</ul>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>$this</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function on($c1, $op, $c2)
{
	$this-&gt;_last_join-&gt;on($c1, $op, $c2);

	return $this;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="or_having"><small>public</small>  or_having(<small>mixed</small> <span class="param" title="Column name or array($column, $alias) or object">$column</span> , <small>string</small> <span class="param" title="Logic operator">$op</span> [, <small>mixed</small> <span class="param" title="Column value">$value</span> <small>= <small>NULL</small></small> ] )<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder_Select'>Kohana_Database_Query_Builder_Select</a>)</small></h3>
<div class='description'><p>Creates a new "OR HAVING" condition for the query.</p>
</div>
<h4>Parameters</h4>
<ul>
<li>
 <span class="blue">mixed </span><strong> $column</strong> <small>required</small> - Column name or array($column, $alias) or object</li>
<li>
 <span class="blue">string </span><strong> $op</strong> <small>required</small> - Logic operator</li>
<li>
 <span class="blue">mixed </span><strong> $value</strong> <small> = <small>NULL</small></small> - Column value</li>
</ul>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>$this</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function or_having($column, $op, $value = NULL)
{
	$this-&gt;_having[] = [&#039;OR&#039; =&gt; [$column, $op, $value]];

	return $this;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="or_having_close"><small>public</small>  or_having_close()<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder_Select'>Kohana_Database_Query_Builder_Select</a>)</small></h3>
<div class='description'><p>Closes an open "OR HAVING (...)" grouping.</p>
</div>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>$this</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function or_having_close()
{
	$this-&gt;_having[] = [&#039;OR&#039; =&gt; &#039;)&#039;];

	return $this;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="or_having_open"><small>public</small>  or_having_open()<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder_Select'>Kohana_Database_Query_Builder_Select</a>)</small></h3>
<div class='description'><p>Opens a new "OR HAVING (...)" grouping.</p>
</div>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>$this</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function or_having_open()
{
	$this-&gt;_having[] = [&#039;OR&#039; =&gt; &#039;(&#039;];

	return $this;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="reset"><small>public</small>  reset()<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder_Select'>Kohana_Database_Query_Builder_Select</a>)</small></h3>
<div class='description'><p>Reset the current builder status.</p>
</div>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>$this</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function reset()
{
	$this-&gt;_select   =
	$this-&gt;_from     =
	$this-&gt;_join     =
	$this-&gt;_where    =
	$this-&gt;_group_by =
	$this-&gt;_having   =
	$this-&gt;_order_by =
	$this-&gt;_union = [];

	$this-&gt;_distinct = FALSE;

	$this-&gt;_limit     =
	$this-&gt;_offset    =
	$this-&gt;_last_join = NULL;

	$this-&gt;_parameters = [];

	$this-&gt;_sql = NULL;

	return $this;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="select"><small>public</small>  select([ <small>mixed</small> <span class="param" title="Column name or array($column, $alias) or object">$columns</span> <small>= <small>NULL</small></small> ] )<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder_Select'>Kohana_Database_Query_Builder_Select</a>)</small></h3>
<div class='description'><p>Choose the columns to select from.</p>
</div>
<h4>Parameters</h4>
<ul>
<li>
 <span class="blue">mixed </span><strong> $columns</strong> <small> = <small>NULL</small></small> - Column name or array($column, $alias) or object</li>
</ul>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>$this</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function select($columns = NULL)
{
	$columns = func_get_args();

	$this-&gt;_select = array_merge($this-&gt;_select, $columns);

	return $this;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="select_array"><small>public</small>  select_array(<small>array</small> <span class="param" title="List of column names or aliases">$columns</span> )<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder_Select'>Kohana_Database_Query_Builder_Select</a>)</small></h3>
<div class='description'><p>Choose the columns to select from, using an array.</p>
</div>
<h4>Parameters</h4>
<ul>
<li>
 <span class="blue">array </span><strong> $columns</strong> <small>required</small> - List of column names or aliases</li>
</ul>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>$this</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function select_array(array $columns)
{
	$this-&gt;_select = array_merge($this-&gt;_select, $columns);

	return $this;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="union"><small>public</small>  union(<small>mixed</small> <span class="param" title="If string, it must be the name of a table. Else must be an instance of Database_Query_Builder_Select">$select</span> [, <small>boolean</small> <span class="param" title="Decides if it's an UNION or UNION ALL clause">$all</span> <small>= <small>bool</small> TRUE</small> ] )<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder_Select'>Kohana_Database_Query_Builder_Select</a>)</small></h3>
<div class='description'><p>Adds an other UNION clause.</p>
</div>
<h4>Parameters</h4>
<ul>
<li>
 <span class="blue">mixed </span><strong> $select</strong> <small>required</small> - If string, it must be the name of a table. Else
 must be an instance of Database_Query_Builder_Select</li>
<li>
 <span class="blue">boolean </span><strong> $all</strong> <small> = <small>bool</small> TRUE</small> - Decides if it's an UNION or UNION ALL clause</li>
</ul>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>$this</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function union($select, $all = TRUE)
{
	if (is_string($select))
	{
		$select = DB::select()-&gt;from($select);
	}
	if ( ! $select instanceof Database_Query_Builder_Select)
		throw new Kohana_Exception(&#039;first parameter must be a string or an instance of Database_Query_Builder_Select&#039;);
	$this-&gt;_union []= [&#039;select&#039; =&gt; $select, &#039;all&#039; =&gt; $all];
	return $this;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="using"><small>public</small>  using(<small>string</small> <span class="param" title="Column name">$columns</span> )<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder_Select'>Kohana_Database_Query_Builder_Select</a>)</small></h3>
<div class='description'><p>Adds "USING ..." conditions for the last created JOIN statement.</p>
</div>
<h4>Parameters</h4>
<ul>
<li>
 <span class="blue">string </span><strong> $columns</strong> <small>required</small> - Column name</li>
</ul>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>$this</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function using($columns)
{
	$columns = func_get_args();

	call_user_func_array([$this-&gt;_last_join, &#039;using&#039;], $columns);

	return $this;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="and_where"><small>public</small>  and_where(<small>mixed</small> <span class="param" title="Column name or array($column, $alias) or object">$column</span> , <small>string</small> <span class="param" title="Logic operator">$op</span> , <small>mixed</small> <span class="param" title="Column value">$value</span> )<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder_Where'>Kohana_Database_Query_Builder_Where</a>)</small></h3>
<div class='description'><p>Creates a new "AND WHERE" condition for the query.</p>
</div>
<h4>Parameters</h4>
<ul>
<li>
 <span class="blue">mixed </span><strong> $column</strong> <small>required</small> - Column name or array($column, $alias) or object</li>
<li>
 <span class="blue">string </span><strong> $op</strong> <small>required</small> - Logic operator</li>
<li>
 <span class="blue">mixed </span><strong> $value</strong> <small>required</small> - Column value</li>
</ul>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>$this</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function and_where($column, $op, $value)
{
	$this-&gt;_where[] = [&#039;AND&#039; =&gt; [$column, $op, $value]];

	return $this;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="and_where_close"><small>public</small>  and_where_close()<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder_Where'>Kohana_Database_Query_Builder_Where</a>)</small></h3>
<div class='description'><p>Closes an open "WHERE (...)" grouping.</p>
</div>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>$this</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function and_where_close()
{
	$this-&gt;_where[] = [&#039;AND&#039; =&gt; &#039;)&#039;];

	return $this;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="and_where_open"><small>public</small>  and_where_open()<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder_Where'>Kohana_Database_Query_Builder_Where</a>)</small></h3>
<div class='description'><p>Opens a new "AND WHERE (...)" grouping.</p>
</div>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>$this</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function and_where_open()
{
	$this-&gt;_where[] = [&#039;AND&#039; =&gt; &#039;(&#039;];

	return $this;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="limit"><small>public</small>  limit(<small>integer</small> <span class="param" title="Maximum results to return or NULL to reset">$number</span> )<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder_Where'>Kohana_Database_Query_Builder_Where</a>)</small></h3>
<div class='description'><p>Return up to "LIMIT ..." results</p>
</div>
<h4>Parameters</h4>
<ul>
<li>
 <span class="blue">integer </span><strong> $number</strong> <small>required</small> - Maximum results to return or NULL to reset</li>
</ul>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>$this</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function limit($number)
{
	$this-&gt;_limit = ($number === NULL) ? NULL : (int) $number;

	return $this;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="or_where"><small>public</small>  or_where(<small>mixed</small> <span class="param" title="Column name or array($column, $alias) or object">$column</span> , <small>string</small> <span class="param" title="Logic operator">$op</span> , <small>mixed</small> <span class="param" title="Column value">$value</span> )<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder_Where'>Kohana_Database_Query_Builder_Where</a>)</small></h3>
<div class='description'><p>Creates a new "OR WHERE" condition for the query.</p>
</div>
<h4>Parameters</h4>
<ul>
<li>
 <span class="blue">mixed </span><strong> $column</strong> <small>required</small> - Column name or array($column, $alias) or object</li>
<li>
 <span class="blue">string </span><strong> $op</strong> <small>required</small> - Logic operator</li>
<li>
 <span class="blue">mixed </span><strong> $value</strong> <small>required</small> - Column value</li>
</ul>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>$this</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function or_where($column, $op, $value)
{
	$this-&gt;_where[] = [&#039;OR&#039; =&gt; [$column, $op, $value]];

	return $this;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="or_where_close"><small>public</small>  or_where_close()<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder_Where'>Kohana_Database_Query_Builder_Where</a>)</small></h3>
<div class='description'><p>Closes an open "WHERE (...)" grouping.</p>
</div>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>$this</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function or_where_close()
{
	$this-&gt;_where[] = [&#039;OR&#039; =&gt; &#039;)&#039;];

	return $this;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="or_where_open"><small>public</small>  or_where_open()<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder_Where'>Kohana_Database_Query_Builder_Where</a>)</small></h3>
<div class='description'><p>Opens a new "OR WHERE (...)" grouping.</p>
</div>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>$this</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function or_where_open()
{
	$this-&gt;_where[] = [&#039;OR&#039; =&gt; &#039;(&#039;];

	return $this;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="order_by"><small>public</small>  order_by(<small>mixed</small> <span class="param" title="Column name or array($column, $alias) or object">$column</span> [, <small>string</small> <span class="param" title="Direction of sorting">$direction</span> <small>= <small>NULL</small></small> ] )<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder_Where'>Kohana_Database_Query_Builder_Where</a>)</small></h3>
<div class='description'><p>Applies sorting with "ORDER BY ..."</p>
</div>
<h4>Parameters</h4>
<ul>
<li>
 <span class="blue">mixed </span><strong> $column</strong> <small>required</small> - Column name or array($column, $alias) or object</li>
<li>
 <span class="blue">string </span><strong> $direction</strong> <small> = <small>NULL</small></small> - Direction of sorting</li>
</ul>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>$this</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function order_by($column, $direction = NULL)
{
	$this-&gt;_order_by[] = [$column, $direction];

	return $this;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="where"><small>public</small>  where(<small>mixed</small> <span class="param" title="Column name or array($column, $alias) or object">$column</span> , <small>string</small> <span class="param" title="Logic operator">$op</span> , <small>mixed</small> <span class="param" title="Column value">$value</span> )<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder_Where'>Kohana_Database_Query_Builder_Where</a>)</small></h3>
<div class='description'><p>Alias of and_where()</p>
</div>
<h4>Parameters</h4>
<ul>
<li>
 <span class="blue">mixed </span><strong> $column</strong> <small>required</small> - Column name or array($column, $alias) or object</li>
<li>
 <span class="blue">string </span><strong> $op</strong> <small>required</small> - Logic operator</li>
<li>
 <span class="blue">mixed </span><strong> $value</strong> <small>required</small> - Column value</li>
</ul>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>$this</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function where($column, $op, $value)
{
	return $this-&gt;and_where($column, $op, $value);
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="where_close"><small>public</small>  where_close()<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder_Where'>Kohana_Database_Query_Builder_Where</a>)</small></h3>
<div class='description'><p>Closes an open "WHERE (...)" grouping.</p>
</div>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>$this</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function where_close()
{
	return $this-&gt;and_where_close();
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="where_close_empty"><small>public</small>  where_close_empty()<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder_Where'>Kohana_Database_Query_Builder_Where</a>)</small></h3>
<div class='description'><p>Closes an open "WHERE (...)" grouping or removes the grouping when it is
empty.</p>
</div>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>$this</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function where_close_empty()
{
	$group = end($this-&gt;_where);

	if ($group AND reset($group) === &#039;(&#039;)
	{
		array_pop($this-&gt;_where);

		return $this;
	}

	return $this-&gt;where_close();
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="where_open"><small>public</small>  where_open()<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder_Where'>Kohana_Database_Query_Builder_Where</a>)</small></h3>
<div class='description'><p>Alias of and_where_open()</p>
</div>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>$this</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function where_open()
{
	return $this-&gt;and_where_open();
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="__toString"><small>public</small>  __toString()<small> (defined in <a href='/documentation/api/Kohana_Database_Query'>Kohana_Database_Query</a>)</small></h3>
<div class='description'><p>Return the SQL query string.</p>
</div>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>string</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function __toString()
{
	try
	{
		// Return the SQL string
		return $this-&gt;compile(Database::instance());
	}
	catch (Exception $e)
	{
		return Kohana_Exception::text($e);
	}
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="as_assoc"><small>public</small>  as_assoc()<small> (defined in <a href='/documentation/api/Kohana_Database_Query'>Kohana_Database_Query</a>)</small></h3>
<div class='description'><p>Returns results as associative arrays</p>
</div>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>$this</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function as_assoc()
{
	$this-&gt;_as_object = FALSE;

	$this-&gt;_object_params = [];

	return $this;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="as_object"><small>public</small>  as_object([ <small>string</small> <span class="param" title="Classname or TRUE for stdClass">$class</span> <small>= <small>bool</small> TRUE</small> , <small>array</small> <span class="param" title="$params">$params</span> <small>= <small>NULL</small></small> ] )<small> (defined in <a href='/documentation/api/Kohana_Database_Query'>Kohana_Database_Query</a>)</small></h3>
<div class='description'><p>Returns results as objects</p>
</div>
<h4>Parameters</h4>
<ul>
<li>
 <span class="blue">string </span><strong> $class</strong> <small> = <small>bool</small> TRUE</small> - Classname or TRUE for stdClass</li>
<li>
 <span class="blue">array </span><strong> $params</strong> <small> = <small>NULL</small></small> - $params</li>
</ul>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>$this</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function as_object($class = TRUE, array $params = NULL)
{
	$this-&gt;_as_object = $class;

	if ($params)
	{
		// Add object parameters
		$this-&gt;_object_params = $params;
	}

	return $this;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="bind"><small>public</small>  bind(<small>string</small> <span class="param" title="Parameter key to replace">$param</span> , <small>mixed</small> <small><abbr title="passed by reference">&</abbr></small> <span class="param" title="Variable to use">$var</span> )<small> (defined in <a href='/documentation/api/Kohana_Database_Query'>Kohana_Database_Query</a>)</small></h3>
<div class='description'><p>Bind a variable to a parameter in the query.</p>
</div>
<h4>Parameters</h4>
<ul>
<li>
 <span class="blue">string </span><strong> $param</strong> <small>required</small> - Parameter key to replace</li>
<li>
byref  <span class="blue">mixed </span><strong> $var</strong> <small>required</small> - Variable to use</li>
</ul>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>$this</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function bind($param, &amp; $var)
{
	// Bind a value to a variable
	$this-&gt;_parameters[$param] =&amp; $var;

	return $this;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="cached"><small>public</small>  cached([ <small>integer</small> <span class="param" title="Number of seconds to cache, 0 deletes it from the cache">$lifetime</span> <small>= <small>NULL</small></small> , <small>boolean</small> <span class="param" title="Whether or not to execute the query during a cache hit">$force</span> <small>= <small>bool</small> FALSE</small> ] )<small> (defined in <a href='/documentation/api/Kohana_Database_Query'>Kohana_Database_Query</a>)</small></h3>
<div class='description'><p>Enables the query to be cached for a specified amount of time.</p>
</div>
<h4>Parameters</h4>
<ul>
<li>
 <span class="blue">integer </span><strong> $lifetime</strong> <small> = <small>NULL</small></small> - Number of seconds to cache, 0 deletes it from the cache</li>
<li>
 <span class="blue">boolean </span><strong> $force</strong> <small> = <small>bool</small> FALSE</small> - Whether or not to execute the query during a cache hit</li>
</ul>
<h4>Tags</h4>
<ul class='tags'>
<li>Uses - <a href="#property:cache_life">Kohana::$cache_life</a></li>
</ul>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>$this</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function cached($lifetime = NULL, $force = FALSE)
{
	if ($lifetime === NULL)
	{
		// Use the global setting
		$lifetime = Kohana::$cache_life;
	}

	$this-&gt;_force_execute = $force;
	$this-&gt;_lifetime = $lifetime;

	return $this;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="execute"><small>public</small>  execute([ <small>mixed</small> <span class="param" title="Database instance or name of instance">$db</span> <small>= <small>NULL</small></small> , <small>string</small> <span class="param" title="Result object classname, TRUE for stdClass or FALSE for array">$as_object</span> <small>= <small>NULL</small></small> , <small>array</small> <span class="param" title="Result object constructor arguments">$object_params</span> <small>= <small>NULL</small></small> ] )<small> (defined in <a href='/documentation/api/Kohana_Database_Query'>Kohana_Database_Query</a>)</small></h3>
<div class='description'><p>Execute the current query on the given database.</p>
</div>
<h4>Parameters</h4>
<ul>
<li>
 <span class="blue">mixed </span><strong> $db</strong> <small> = <small>NULL</small></small> - Database instance or name of instance</li>
<li>
 <span class="blue">string </span><strong> $as_object</strong> <small> = <small>NULL</small></small> - Result object classname, TRUE for stdClass or FALSE for array</li>
<li>
 <span class="blue">array </span><strong> $object_params</strong> <small> = <small>NULL</small></small> - Result object constructor arguments</li>
</ul>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>object</span>  - Database_Result for SELECT queries 
</li><li>
<span class='blue'>mixed</span>  - The insert id for INSERT queries 
</li><li>
<span class='blue'>integer</span>  - Number of affected rows for all other queries 
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function execute($db = NULL, $as_object = NULL, $object_params = NULL)
{
	if ( ! is_object($db))
	{
		// Get the database instance
		$db = Database::instance($db);
	}

	if ($as_object === NULL)
	{
		$as_object = $this-&gt;_as_object;
	}

	if ($object_params === NULL)
	{
		$object_params = $this-&gt;_object_params;
	}

	// Compile the SQL query
	$sql = $this-&gt;compile($db);

	if ($this-&gt;_lifetime !== NULL AND $this-&gt;_type === Database::SELECT)
	{
		// Set the cache key based on the database instance name and SQL
		$cache_key = &#039;Database::query(&quot;&#039;.$db.&#039;&quot;, &quot;&#039;.$sql.&#039;&quot;)&#039;;

		// Read the cache first to delete a possible hit with lifetime &lt;= 0
		if (($result = Kohana::cache($cache_key, NULL, $this-&gt;_lifetime)) !== NULL
			AND ! $this-&gt;_force_execute)
		{
			// Return a cached result
			return new Database_Result_Cached($result, $sql, $as_object, $object_params);
		}
	}

	// Execute the query
	$result = $db-&gt;query($this-&gt;_type, $sql, $as_object, $object_params);

	if (isset($cache_key) AND $this-&gt;_lifetime &gt; 0)
	{
		// Cache the result array
		Kohana::cache($cache_key, $result-&gt;as_array(), $this-&gt;_lifetime);
	}

	return $result;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="param"><small>public</small>  param(<small>string</small> <span class="param" title="Parameter key to replace">$param</span> , <small>mixed</small> <span class="param" title="Value to use">$value</span> )<small> (defined in <a href='/documentation/api/Kohana_Database_Query'>Kohana_Database_Query</a>)</small></h3>
<div class='description'><p>Set the value of a parameter in the query.</p>
</div>
<h4>Parameters</h4>
<ul>
<li>
 <span class="blue">string </span><strong> $param</strong> <small>required</small> - Parameter key to replace</li>
<li>
 <span class="blue">mixed </span><strong> $value</strong> <small>required</small> - Value to use</li>
</ul>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>$this</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function param($param, $value)
{
	// Add or overload a new parameter
	$this-&gt;_parameters[$param] = $value;

	return $this;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="parameters"><small>public</small>  parameters(<small>array</small> <span class="param" title="List of parameters">$params</span> )<small> (defined in <a href='/documentation/api/Kohana_Database_Query'>Kohana_Database_Query</a>)</small></h3>
<div class='description'><p>Add multiple parameters to the query.</p>
</div>
<h4>Parameters</h4>
<ul>
<li>
 <span class="blue">array </span><strong> $params</strong> <small>required</small> - List of parameters</li>
</ul>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>$this</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function parameters(array $params)
{
	// Merge the new parameters in
	$this-&gt;_parameters = $params + $this-&gt;_parameters;

	return $this;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="type"><small>public</small>  type()<small> (defined in <a href='/documentation/api/Kohana_Database_Query'>Kohana_Database_Query</a>)</small></h3>
<div class='description'><p>Get the type of the query.</p>
</div>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>integer</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">public function type()
{
	return $this-&gt;_type;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_compile_conditions"><small>protected</small>  _compile_conditions(<small>object</small> <span class="param" title="Database instance">$db</span> , <small>array</small> <span class="param" title="Condition statements">$conditions</span> )<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder'>Kohana_Database_Query_Builder</a>)</small></h3>
<div class='description'><p>Compiles an array of conditions into an SQL partial. Used for WHERE
and HAVING.</p>
</div>
<h4>Parameters</h4>
<ul>
<li>
 <span class="blue">object </span><strong> $db</strong> <small>required</small> - Database instance</li>
<li>
 <span class="blue">array </span><strong> $conditions</strong> <small>required</small> - Condition statements</li>
</ul>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>string</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">protected function _compile_conditions(Database $db, array $conditions)
{
	$last_condition = NULL;

	$sql = &#039;&#039;;
	foreach ($conditions as $group)
	{
		// Process groups of conditions
		foreach ($group as $logic =&gt; $condition)
		{
			if ($condition === &#039;(&#039;)
			{
				if ( ! empty($sql) AND $last_condition !== &#039;(&#039;)
				{
					// Include logic operator
					$sql .= &#039; &#039;.$logic.&#039; &#039;;
				}

				$sql .= &#039;(&#039;;
			}
			elseif ($condition === &#039;)&#039;)
			{
				$sql .= &#039;)&#039;;
			}
			else
			{
				if ( ! empty($sql) AND $last_condition !== &#039;(&#039;)
				{
					// Add the logic operator
					$sql .= &#039; &#039;.$logic.&#039; &#039;;
				}

				// Split the condition
				list($column, $op, $value) = $condition;

				if ($value === NULL)
				{
					if ($op === &#039;=&#039;)
					{
						// Convert &quot;val = NULL&quot; to &quot;val IS NULL&quot;
						$op = &#039;IS&#039;;
					}
					elseif ($op === &#039;!=&#039; OR $op === &#039;&lt;&gt;&#039;)
					{
						// Convert &quot;val != NULL&quot; to &quot;valu IS NOT NULL&quot;
						$op = &#039;IS NOT&#039;;
					}
				}

				// Database operators are always uppercase
				$op = strtoupper($op);

				if ($op === &#039;BETWEEN&#039; AND is_array($value))
				{
					// BETWEEN always has exactly two arguments
					list($min, $max) = $value;

					if ((is_string($min) AND array_key_exists($min, $this-&gt;_parameters)) === FALSE)
					{
						// Quote the value, it is not a parameter
						$min = $db-&gt;quote($min);
					}

					if ((is_string($max) AND array_key_exists($max, $this-&gt;_parameters)) === FALSE)
					{
						// Quote the value, it is not a parameter
						$max = $db-&gt;quote($max);
					}

					// Quote the min and max value
					$value = $min.&#039; AND &#039;.$max;
				}
				elseif ($op === &#039;IN&#039; AND is_array($value) AND count($value) === 0)
				{
					$value = &#039;(NULL)&#039;;
				}
				elseif ((is_string($value) AND array_key_exists($value, $this-&gt;_parameters)) === FALSE)
				{
					// Quote the value, it is not a parameter
					$value = $db-&gt;quote($value);
				}

				if ($column)
				{
					if (is_array($column))
					{
						// Use the column name
						$column = $db-&gt;quote_identifier(reset($column));
					}
					else
					{
						// Apply proper quoting to the column
						$column = $db-&gt;quote_column($column);
					}
				}

				// Append the statement to the query
				$sql .= trim($column.&#039; &#039;.$op.&#039; &#039;.$value);
			}

			$last_condition = $condition;
		}
	}

	return $sql;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_compile_group_by"><small>protected</small>  _compile_group_by(<small>object</small> <span class="param" title="Database instance">$db</span> , <small>array</small> <span class="param" title="$columns">$columns</span> )<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder'>Kohana_Database_Query_Builder</a>)</small></h3>
<div class='description'><p>Compiles an array of GROUP BY columns into an SQL partial.</p>
</div>
<h4>Parameters</h4>
<ul>
<li>
 <span class="blue">object </span><strong> $db</strong> <small>required</small> - Database instance</li>
<li>
 <span class="blue">array </span><strong> $columns</strong> <small>required</small> - $columns</li>
</ul>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>string</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">protected function _compile_group_by(Database $db, array $columns)
{
	$group = [];

	foreach ($columns as $column)
	{
		if (is_array($column))
		{
			// Use the column alias
			$column = $db-&gt;quote_identifier(end($column));
		}
		else
		{
			// Apply proper quoting to the column
			$column = $db-&gt;quote_column($column);
		}

		$group[] = $column;
	}

	return &#039;GROUP BY &#039;.implode(&#039;, &#039;, $group);
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_compile_join"><small>protected</small>  _compile_join(<small>object</small> <span class="param" title="Database instance">$db</span> , <small>array</small> <span class="param" title="Join statements">$joins</span> )<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder'>Kohana_Database_Query_Builder</a>)</small></h3>
<div class='description'><p>Compiles an array of JOIN statements into an SQL partial.</p>
</div>
<h4>Parameters</h4>
<ul>
<li>
 <span class="blue">object </span><strong> $db</strong> <small>required</small> - Database instance</li>
<li>
 <span class="blue">array </span><strong> $joins</strong> <small>required</small> - Join statements</li>
</ul>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>string</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">protected function _compile_join(Database $db, array $joins)
{
	$statements = [];

	foreach ($joins as $join)
	{
		// Compile each of the join statements
		$statements[] = $join-&gt;compile($db);
	}

	return implode(&#039; &#039;, $statements);
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_compile_order_by"><small>protected</small>  _compile_order_by(<small>Database</small> <span class="param" title="Database instance">$db</span> , <small>array</small> <span class="param" title="Sorting columns ">$columns</span> )<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder'>Kohana_Database_Query_Builder</a>)</small></h3>
<div class='description'><p>Compiles an array of ORDER BY statements into an SQL partial.</p>
</div>
<h4>Parameters</h4>
<ul>
<li>
 <span class="blue">Database </span><strong> $db</strong> <small>required</small> - Database instance</li>
<li>
 <span class="blue">array </span><strong> $columns</strong> <small>required</small> - Sorting columns
</li>
</ul>
<h4>Tags</h4>
<ul class='tags'>
<li>Throws - <a href="/index.php/">Database_Exception</a></li>
</ul>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>string</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">protected function _compile_order_by(Database $db, array $columns)
{
	$sort = [];
	foreach ($columns as $group)
	{
		list ($column, $direction) = $group;

		if (is_array($column))
		{
			// Use the column alias
			$column = $db-&gt;quote_identifier(end($column));
		}
		else
		{
			// Apply proper quoting to the column
			$column = $db-&gt;quote_column($column);
		}

		if ($direction)
		{
			// Make the direction uppercase
			$direction = &#039; &#039;.strtoupper($direction);

			// Make sure direction is either ASC or DESC to prevent injections
			if ( ! in_array($direction, [&#039; ASC&#039;, &#039; DESC&#039;])) {
				throw new Database_Exception(&#039;Invalid sorting direction: &#039; . $direction);
			}
		}

		$sort[] = $column.$direction;
	}

	return &#039;ORDER BY &#039;.implode(&#039;, &#039;, $sort);
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_compile_set"><small>protected</small>  _compile_set(<small>object</small> <span class="param" title="Database instance">$db</span> , <small>array</small> <span class="param" title="Updated values">$values</span> )<small> (defined in <a href='/documentation/api/Kohana_Database_Query_Builder'>Kohana_Database_Query_Builder</a>)</small></h3>
<div class='description'><p>Compiles an array of set values into an SQL partial. Used for UPDATE.</p>
</div>
<h4>Parameters</h4>
<ul>
<li>
 <span class="blue">object </span><strong> $db</strong> <small>required</small> - Database instance</li>
<li>
 <span class="blue">array </span><strong> $values</strong> <small>required</small> - Updated values</li>
</ul>
<h4>Return Values</h4>
<ul class='return'>
<li>
<span class='blue'>string</span>  
</li></ul>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">protected function _compile_set(Database $db, array $values)
{
	$set = [];
	foreach ($values as $group)
	{
		// Split the set
		list ($column, $value) = $group;

		// Quote the column name
		$column = $db-&gt;quote_column($column);

		if ((is_string($value) AND array_key_exists($value, $this-&gt;_parameters)) === FALSE)
		{
			// Quote the value, it is not a parameter
			$value = $db-&gt;quote($value);
		}

		$set[$column] = $column.&#039; = &#039;.$value;
	}

	return implode(&#039;, &#039;, $set);
}</code>
</pre>
</div>
</div>
</div>