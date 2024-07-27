<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
</head>
<body>

<h1>Pomodoro Timer</h1>

<p>This is a simple Pomodoro timer application built using Python and the Tkinter library. The Pomodoro Technique is a time management method that involves working for a set period (usually 25 minutes) followed by a short break. This application helps you manage your work sessions and breaks efficiently.</p>

<h2>Features</h2>
<ul>
    <li><strong>Work Timer</strong>: Set to 25 minutes by default.</li>
    <li><strong>Short Break Timer</strong>: Set to 5 minutes by default.</li>
    <li><strong>Long Break Timer</strong>: Set to 20 minutes by default.</li>
    <li><strong>Start and Reset Buttons</strong>: Start the timer or reset it to the initial state.</li>
    <li><strong>Visual Countdown</strong>: Displays the remaining time for the current session.</li>
    <li><strong>Session Tracking</strong>: Displays a checkmark for each completed work session.</li>
</ul>

<h2>Installation</h2>
<ol>
    <li><strong>Clone the repository:</strong>
        <pre class="highlight"><code>git clone https://github.com/your-username/pomodoro-timer.git</code></pre>
    </li>
    <li><strong>Navigate to the project directory:</strong>
        <pre class="highlight"><code>cd pomodoro-timer</code></pre>
    </li>
    <li><strong>Ensure you have Python installed</strong>. This project requires Python 3.x.</li>
    <li><strong>Install Tkinter:</strong>
        <ul>
            <li><strong>For Windows:</strong>
                <pre class="highlight"><code>pip install tk</code></pre>
            </li>
            <li><strong>For macOS:</strong>
                <pre class="highlight"><code>brew install python-tk</code></pre>
            </li>
            <li><strong>For Linux:</strong>
                <pre class="highlight"><code>sudo apt-get install python3-tk</code></pre>
            </li>
        </ul>
    </li>
</ol>

<h2>Usage</h2>
<ol>
    <li><strong>Run the application:</strong>
        <pre class="highlight"><code>python pomodoro_timer.py</code></pre>
    </li>
    <li><strong>Start the timer</strong> by clicking the "Start" button.</li>
    <li><strong>Reset the timer</strong> by clicking the "Reset" button.</li>
    <li><strong>Observe the timer</strong> as it counts down the work and break periods. The application will switch between work and break sessions automatically.</li>
</ol>

<h2>Code Explanation</h2>

<h3>Constants</h3>
<ul>
    <li><strong>PINK, RED, GREEN, YELLOW:</strong> Color codes used for UI elements.</li>
    <li><strong>FONT_NAME:</strong> The font used in the application.</li>
    <li><strong>WORK_MIN, SHORT_BREAK_MIN, LONG_BREAK_MIN:</strong> Duration of work sessions, short breaks, and long breaks, respectively.</li>
</ul>

<h3>Functions</h3>
<ul>
    <li><strong>reset_timer():</strong> Resets the timer and all UI elements to their initial state.</li>
    <li><strong>start_timer():</strong> Starts the timer and alternates between work and break sessions.</li>
    <li><strong>count_down(count):</strong> Handles the countdown mechanism and updates the UI every second.</li>
</ul>

<h3>UI Setup</h3>
<ul>
    <li><strong>Tkinter window setup:</strong> Initializes the main application window and its components (labels, buttons, canvas).</li>
    <li><strong>Canvas:</strong> Displays the timer text and background image.</li>
    <li><strong>Labels:</strong> Display the timer title and checkmarks for completed sessions.</li>
    <li><strong>Buttons:</strong> Start and reset buttons to control the timer.</li>
</ul>

<h2>Contributing</h2>
<p>Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.</p>

<h2>License</h2>
<p>This project is licensed under the MIT License - see the <a href="LICENSE">LICENSE</a> file for details.</p>

<h2>Acknowledgments</h2>
<ul>
    <li>This application was built following the Pomodoro Technique, a time management method developed by Francesco Cirillo.</li>
    <li>Inspired by various Pomodoro timer implementations and tutorials.</li>
</ul>

</body>
</html>
