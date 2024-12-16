<div class="lg:w-3/7 mx-auto mt-16 flex w-full flex-col items-center gap-8 p-8 sm:w-2/3 md:w-1/2 xl:w-1/3 2xl:w-1/4">
	<!-- svelte-ignore a11y-missing-attribute -->
	<img class="h-32 w-32 rounded-full object-cover" src="IMG_1580.jpeg" />

	<h1 class="text-3xl">Manav</h1>

	<div class="flex w-full flex-col gap-4">
		<p>Hello, I'm Manav! I have a love for mathematics and computers. I enjoy spending time wrestling, skiing and working on various projects.</p>

		<p>Winter has arrived bringing with it some much needed snow (for skiing)!</p>

		<img class="mx-auto h-32 w-32 object-cover" alt="Me with Wooly" src="IMG_4618.jpeg" />

		<p>When I'm not skiing, I've been spending some time playing <a href="https://store.steampowered.com/app/2358720/Black_Myth_Wukong/">Black Myth: Wukong</a>.</p>
		<p>Currently migrated stuff to a new host so some links may be broken, hope to have them up soon!</p>
	</div>

	<div class="flex w-full flex-col gap-6">
		<h2 class="w-fit border-b-2 border-black font-mono text-2xl">Projects</h2>


		<div>
			<a class="font-bold" href="https://pithyurl.duckdns.org">pithy url</a>
			<p>A URL shortener! Hosted on my home lab.</p>
		</div>

		<div>
			<a class="font-bold" href="https://pyai.duckdns.org">pyai</a>
			<p>An AI agent with access to a jupyter notebook. It can write and execute code, able to create scripts to analyze data. Most importantly it is able to receive feedback on errors with its code and iteratively fix them. Hosted in my home lab so it may be slow.</p>
		</div>

		<div>
			<a class="font-bold" href="https://modworm.com">modworm</a>
			<p>A site dedicated to modbus some utilities, specifically rain and soil.</p>
			<div class="flex flex-col gap-1 pt-1">
				<p><a href="https://modworm.com/rain">rain</a> - A CLI to run and manage simulated modbus servers.</p>
				<p><a href="https://modworm.com/soil">soil</a> - A frontend that can scan for and connect to any modbus server on a network, presenting register banks in an intuitive way. Keep an eye out for version 2.1!</p>
				<p>sod - The backend for soil, responsible scanning networking, mapping modbus devices and reading registers. It also persists discoverd devices and their maps across instances.</p>
				<p><a href="https://github.com/Modworm/homebrew-modworm">homebrew-modworm</a> - the brew for downloading rain and soil.</p>
				<p><a href="https://github.com/Modworm/choco-modworm">choco-modworm</a> - repo containing choc scripts for downloading rain and soil.</p>
			</div>
		</div>

		<div>
			<a class="font-bold" href="https://tidepoolfinance.com/">tidepool finance</a>
			<p>A site dedicated to preparing for retirement, still a wip but contains some useful tools. The backend is hosted locally by my home lab.</p>
		</div>

		<div>
			<a class="font-bold" href="https://costofwebsitehosting.github.io/">cost of web hosting</a>
			<p>I wanted to know how much it would cost to have my own domain name and site.</p>
		</div>

		<div>
			<a class="font-bold" href="https://sacrats.github.io/">sacrats</a>
			<p>A demo site for my RC flying club. Also I love drones and RC planes.</p>
		</div>

		<div>
			<a class="font-bold" href="https://ncgrapplers.github.io/">ncgrapplers</a>
			<p>A site for a youth wrestling club I coach at. It was migrated to wordpress for easier maintainability.</p>
		</div>

		<div>
			<a class="font-bold" href="https://github.com/manavsu/hastaginator">hastaginator</a>
			<p>Will usae a local LLM to generate hastags for your photos in exchange for more TOPS. built with Tranformers and Gradio.</p>
		</div>

		<div>
			<a class="font-bold" href="https://github.com/manavsu/dir_watcher">Directory Watcher</a>
			<p>A tool for watching for changes to directory in realtime and altering a server if any changes are detected.</p>
		</div>

		<div>
			<p class="font-bold text-teal-500">Solar Savings Calculator</p>
			<p>A tool to estimate the cost savings to switching to solar, taking into account your electricity bill and energy prices. It can also account for arbitrage with energy storage.</p>
		</div>

		<div>
			<a class="font-bold" href="https://github.com/manavsu/learn_c">learn c</a>
			<p>A set of modules to help me and other learn C.</p>
		</div>

		<div>
			<a class="font-bold" href="https://github.com/manavsu/simple-transfer-website">simple transfer website</a>
			<p>I wanted to share some large video files of me and my friends skiing but couldn't figure out how so I hosted them locally with docker and apache so people could download them.</p>
		</div>

		<div>
			<a class="font-bold" href="https://github.com/manavsu/scheduler">power scheduler</a>
			<p>A tool for scheduling power commands, similar to an EMS (Energy Management System).</p>
		</div>

		<div>
			<a class="font-bold" href="https://github.com/manavsu/birthday">birthday</a>
			<p>A tool for send people slack messages on their birthday! Includes a UI for managing birthdays.</p>
		</div>

		<div>
			<a class="font-bold" href="https://github.com/manavsu/GameOfLife">game of life</a>
			<p>Conway's game of life implemented in C#</p>
		</div>

		<div>
			<a class="font-bold" href="https://github.com/manavsu/packing">packing</a>
			<p>Packing shapes to generate art: circles, lines and fractals.</p>
		</div>

		<div>
			<a class="font-bold" href="https://github.com/manavsu/chatbottron">chatbottron</a>
			<p>A not so great chatbot running on a local LLM. Needs more TOPS.</p>
		</div>

		<div>
			<a class="font-bold" href="https://github.com/manavsu/Mandelbrot">mandelbrot</a>
			<p>Explorations with python and the mandelbrot set.</p>
		</div>

		<div>
			<a class="font-bold" href="https://github.com/manavsu/ChopSticks/">chopsticks</a>
			<p>A game where you play against the computer to see who can get the other to 0 fingers first. Computer not included. Built as an exercise to build a rudimentary AI.</p>
		</div>

		<div>
			<a class="font-bold" href="https://github.com/manavsu/Enigma/">enigma</a>
			<p>A virtual enigma machine, a WWII cipher device, with all the features and quirks of the original.</p>
		</div>

		<div>
			<a class="font-bold" href="https://github.com/manavsu/poison/">poison</a>
			<p>A game where you are poisoned and you must use spells and potions to delay the inevitable.</p>
		</div>
	</div>
</div>
