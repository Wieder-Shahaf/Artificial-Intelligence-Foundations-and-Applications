<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<h1>Artificial Intelligence Foundations and Applications</h1>

<h2>Overview</h2>
<p>This repository contains exercises focused on fundamental AI techniques including deterministic and heuristic search, logical inference, stochastic environments, and Markov Decision Processes (MDPs). Each exercise emphasizes practical implementation, reasoning strategies, and model evaluations within diverse problem settings:</p>

<ol>
    <li><strong>Deterministic Search:</strong> Implementing systematic search algorithms to navigate deterministic environments.</li>
    <li><strong>Logical Inference:</strong> Using logical inference to reason and strategize in partially observable environments.</li>
    <li><strong>Stochastic Decision Making:</strong> Handling stochastic dynamics through probabilistic reasoning and optimizing decisions under uncertainty.</li>
</ol>

<h2>Deterministic Search (Exercise 1)</h2>
<p>This exercise required solving a deterministic search problem set in a Harry Potter-themed environment:</p>
<ul>
    <li>Implemented search algorithms (including A*) to control wizards tasked with finding and destroying horcruxes.</li>
    <li>Defined valid atomic actions including moving, waiting, destroying horcruxes, and ultimately defeating Voldemort.</li>
    <li>Ensured optimal solutions minimizing the number of turns while avoiding obstacles (Death Eaters, impassable terrain).</li>
</ul>
<p><strong>Challenge:</strong> Developing accurate heuristic functions for efficient A* search to guarantee optimal paths.</p>

<h2>Logical Inference (Exercise 2)</h2>
<p>This exercise involved logical reasoning in partially observable settings:</p>
<ul>
    <li>Implemented a logical inference agent guiding Harry Potter in finding a hidden "deathly hallow" within Gringotts Bank.</li>
    <li>Harry used logical inference based on partial observations (presence of sulfur, dragons, and vaults) to avoid traps and dragons.</li>
    <li>Actions included moving, destroying traps, collecting items, and strategically waiting.</li>
</ul>
<p><strong>Challenge:</strong> Using inference to safely navigate and reason under uncertainty, with limited visibility of the environment.</p>

<h2>Stochastic Decision Making (Exercise 3)</h2>
<p>This exercise focused on decision-making under uncertainty with stochastic dynamics:</p>
<ul>
    <li>Extended the deterministic wizard scenario to include stochastic movement for death eaters and horcruxes.</li>
    <li>Implemented two agents (WizardAgent and OptimalWizardAgent) to maximize points through strategic actions such as moving, destroying horcruxes, resetting, or terminating the game.</li>
    <li>Evaluated agents based on their ability to manage probabilistic changes and maximize cumulative rewards under uncertainty.</li>
</ul>
<p><strong>Challenge:</strong> Designing robust strategies capable of adapting to dynamic and uncertain environments to maximize expected scores.</p>

<h2>Key AI Techniques Covered in Course</h2>
<ul>
    <li>Systematic Search</li>
    <li>Heuristic (Informed) Search</li>
    <li>STRIPS Planning</li>
    <li>Logical Inference and Resolution</li>
    <li>Markov Decision Processes (MDPs)</li>
    <li>Adversarial Planning</li>
    <li>Learning from Feedback</li>
</ul>


<h2>Conclusion</h2>
<p>This repository showcases fundamental AI methodologies through structured exercises covering deterministic search, logical inference, and stochastic planning. Each task provided practical insights into effective AI problem-solving, logical reasoning, heuristic optimization, and decision-making under uncertainty.</p>

</body>
</html>
