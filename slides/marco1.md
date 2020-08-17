<section>
	<a href="https://revealjs.com">
		<img src="https://static.slid.es/reveal/logo-v1/reveal-white-text.svg" alt="reveal.js logo" style="height: 180px; margin: 0 auto 4rem auto; background: transparent;" class="demo-logo">
	</a>
	<h3>The HTML Presentation Framework</h3>
	<p>
		<small>Created by <a href="http://hakim.se">Hakim El Hattab</a> and <a href="https://github.com/hakimel/reveal.js/graphs/contributors">contributors</a></small>
	</p>
</section>



<section>
	<h2>Hello There</h2>
	<p>
		reveal.js enables you to create beautiful interactive slide decks using HTML. This presentation will show you examples of what it can do.
	</p>
</section>		



<!-- Example of nested vertical slides -->
<section>
	<h2>Vertical Slides</h2>
	<p>Slides can be nested inside of each other.</p>
	<p>Use the <em>Space</em> key to navigate through all slides.</p>
	<br>
	<a href="#" class="navigate-down">
		<img class="r-frame" style="background: rgba(255,255,255,0.1);" width="178" height="238" data-src="https://static.slid.es/reveal/arrow.png" alt="Down arrow">
	</a>


	<h2>Basement Level 1</h2>
	<p>Nested slides are useful for adding additional detail underneath a high level horizontal slide.</p>


	<h2>Basement Level 2</h2>
	<p>That's it, time to go back up.</p>
	<br>
	<a href="#/2">
		<img class="r-frame" style="background: rgba(255,255,255,0.1); transform: rotate(180deg);" width="178" height="238" data-src="https://static.slid.es/reveal/arrow.png" alt="Up arrow">
	</a>
</section>



<section>
	<h2>Slides</h2>
	<p>
		Not a coder? Not a problem. There's a fully-featured visual editor for authoring these, try it out at <a href="https://slides.com" target="_blank">https://slides.com</a>.
	</p>
</section>



<section data-auto-animate>
	<h2 data-id="code-title">Pretty Code</h2>
	<pre data-id="code-animation"><code class="hljs" data-trim data-line-numbers>
		import React, { useState } from 'react';

		function Example() {
		  const [count, setCount] = useState(0);

		  return (
		    ...
		  );
		}
	</code></pre>
	<p>Code syntax highlighting courtesy of <a href="https://highlightjs.org/usage/">highlight.js</a>.</p>
</section>



<section data-auto-animate>
	<h2 data-id="code-title">With animations</h2>
	<pre data-id="code-animation"><code class="hljs" data-trim data-line-numbers="|4,8-11|17|22-24">
		import React, { useState } from 'react';

		function Example() {
		  const [count, setCount] = useState(0);

		  return (
		    &lt;div&gt;
		      &lt;p&gt;You clicked {count} times&lt;/p&gt;
		      &lt;button onClick={() =&gt; setCount(count + 1)}&gt;
		        Click me
		      &lt;/button&gt;
		    &lt;/div&gt;
		  );
		}

		function SecondExample() {
		  const [count, setCount] = useState(0);

		  return (
		    &lt;div&gt;
		      &lt;p&gt;You clicked {count} times&lt;/p&gt;
		      &lt;button onClick={() =&gt; setCount(count + 1)}&gt;
		        Click me
		      &lt;/button&gt;
		    &lt;/div&gt;
		  );
		}
	</code></pre>
</section>



<section>
	<h2>Point of View</h2>
	<p>
		Press <strong>ESC</strong> to enter the slide overview.
	</p>
	<p>
		Hold down the <strong>alt</strong> key (<strong>ctrl</strong> in Linux) and click on any element to zoom towards it using <a href="http://lab.hakim.se/zoom-js">zoom.js</a>. Click again to zoom back out.
	</p>
	<p>
		(NOTE: Use ctrl + click in Linux.)
	</p>
</section>



<section data-auto-animate data-auto-animate-easing="cubic-bezier(0.770, 0.000, 0.175, 1.000)">
	<h2>Auto-Animate</h2>
	<p>Automatically animate matching elements across slides with <a href="https://revealjs.com/auto-animate/">Auto-Animate</a>.</p>
	<div class="r-hstack justify-center">
		<div data-id="box1" style="background: #999; width: 50px; height: 50px; margin: 10px; border-radius: 5px;"></div>
		<div data-id="box2" style="background: #999; width: 50px; height: 50px; margin: 10px; border-radius: 5px;"></div>
		<div data-id="box3" style="background: #999; width: 50px; height: 50px; margin: 10px; border-radius: 5px;"></div>
	</div>
</section>
<section data-auto-animate data-auto-animate-easing="cubic-bezier(0.770, 0.000, 0.175, 1.000)">
	<div class="r-hstack justify-center">
		<div data-id="box1" data-auto-animate-delay="0" style="background: cyan; width: 150px; height: 100px; margin: 10px;"></div>
		<div data-id="box2" data-auto-animate-delay="0.1" style="background: magenta; width: 150px; height: 100px; margin: 10px;"></div>
		<div data-id="box3" data-auto-animate-delay="0.2" style="background: yellow; width: 150px; height: 100px; margin: 10px;"></div>
	</div>
	<h2 style="margin-top: 20px;">Auto-Animate</h2>
</section>
<section data-auto-animate data-auto-animate-easing="cubic-bezier(0.770, 0.000, 0.175, 1.000)">
	<div class="r-stack">
		<div data-id="box1" style="background: cyan; width: 300px; height: 300px; border-radius: 200px;"></div>
		<div data-id="box2" style="background: magenta; width: 200px; height: 200px; border-radius: 200px;"></div>
		<div data-id="box3" style="background: yellow; width: 100px; height: 100px; border-radius: 200px;"></div>
	</div>
	<h2 style="margin-top: 20px;">Auto-Animate</h2>
</section>



<section>
	<section>
		<h2>Touch Optimized</h2>
		<p>
			Presentations look great on touch devices, like mobile phones and tablets. Simply swipe through your slides.
		</p>
	</section>
	<section data-markdown>
		<script type="text/template">
			## Markdown support

			Write content using inline or external Markdown.
			Instructions and more info available in the [readme](https://revealjs.com/markdown/).

			```[]
			<section data-markdown>
			  ## Markdown support

			  Write content using inline or external Markdown.
			  Instructions and more info available in the [readme](https://revealjs.com/markdown/).
			</section>
			```

		</script>
	</section>
</section>




<section>
	<section id="fragments">
		<h2>Fragments</h2>
		<p>Hit the next arrow...</p>
		<p class="fragment">... to step through ...</p>
		<p><span class="fragment">... a</span> <span class="fragment">fragmented</span> <span class="fragment">slide.</span></p>

		<aside class="notes">
			This slide has fragments which are also stepped through in the notes window.
		</aside>
	</section>
	<section>
		<h2>Fragment Styles</h2>
		<p>There's different types of fragments, like:</p>
		<p class="fragment grow">grow</p>
		<p class="fragment shrink">shrink</p>
		<p class="fragment fade-out">fade-out</p>
		<p>
			<span style="display: inline-block;" class="fragment fade-right">fade-right, </span>
			<span style="display: inline-block;" class="fragment fade-up">up, </span>
			<span style="display: inline-block;" class="fragment fade-down">down, </span>
			<span style="display: inline-block;" class="fragment fade-left">left</span>
		</p>
		<p class="fragment fade-in-then-out">fade-in-then-out</p>
		<p class="fragment fade-in-then-semi-out">fade-in-then-semi-out</p>
		<p>Highlight <span class="fragment highlight-red">red</span> <span class="fragment highlight-blue">blue</span> <span class="fragment highlight-green">green</span></p>
	</section>
</section>

