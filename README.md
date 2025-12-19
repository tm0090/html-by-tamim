<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap');
        
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0d1117;
            color: #c9d1d9;
        }

        .gradient-text {
            background: linear-gradient(90deg, #58a6ff, #bc8cff);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .project-card {
            background: #161b22;
            border: 1px solid #30363d;
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }

        .project-card:hover {
            transform: translateY(-4px);
            border-color: #58a6ff;
            box-shadow: 0 10px 30px -10px rgba(88, 166, 255, 0.2);
        }

        .icon-container {
            background: rgba(88, 166, 255, 0.1);
            color: #58a6ff;
        }
    </style>
</head>
<body class="p-4 md:p-8">
    <div class="max-w-4xl mx-auto">
        <!-- Header Section -->
        <header class="mb-12 text-center md:text-left">
            <h1 class="text-4xl md:text-5xl font-bold mb-4">
                Hi, I'm <span class="gradient-text">Tamim</span> 👋
            </h1>
            <p class="text-xl text-gray-400 max-w-2xl">
                Full-stack developer focused on building minimalist, high-performance productivity tools. 
                I create web experiences that help people manage their most valuable resource: <span class="text-blue-400">Time</span>.
            </p>
        </header>

        <!-- Projects Grid -->
        <h2 class="text-2xl font-semibold mb-6 flex items-center gap-2">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-blue-500"><path d="m18 16 4-4-4-4"></path><path d="m6 8-4 4 4 4"></path><path d="m14.5 4-5 16"></path></svg>
            Productivity Suite
        </h2>
        
        <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
            <!-- Pomodoro -->
            <a href="https://pomodorobytamim.pages.dev/" target="_blank" class="project-card p-6 rounded-xl block">
                <div class="flex items-start justify-between">
                    <div class="icon-container p-3 rounded-lg mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"/><polyline points="12 6 12 12 16 14"/></svg>
                    </div>
                </div>
                <h3 class="text-xl font-bold text-white mb-2">Pomodoro Timer</h3>
                <p class="text-sm text-gray-400">Focus-enhancing timer designed to boost productivity through structured deep-work intervals.</p>
            </a>

            <!-- Deadline Tracker -->
            <a href="https://deadlinetrackerbytamim.pages.dev/" target="_blank" class="project-card p-6 rounded-xl block">
                <div class="flex items-start justify-between">
                    <div class="icon-container p-3 rounded-lg mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M8 2v4"/><path d="M16 2v4"/><rect width="18" height="18" x="3" y="4" rx="2"/><path d="M3 10h18"/><path d="M8 14h.01"/><path d="M12 14h.01"/><path d="M16 14h.01"/><path d="M8 18h.01"/><path d="M12 18h.01"/><path d="M16 18h.01"/></svg>
                    </div>
                </div>
                <h3 class="text-xl font-bold text-white mb-2">Deadline Tracker</h3>
                <p class="text-sm text-gray-400">Never miss a milestone. Keep track of important dates and countdowns with precision.</p>
            </a>

            <!-- Time Tracker -->
            <a href="https://timetrackerbytamim.pages.dev/" target="_blank" class="project-card p-6 rounded-xl block">
                <div class="flex items-start justify-between">
                    <div class="icon-container p-3 rounded-lg mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 20a8 8 0 1 0 0-16 8 8 0 0 0 0 16Z"/><path d="M12 14V8"/><path d="M12 2v2"/><path d="M12 20v2"/><path d="M20 12h2"/><path d="M2 12h2"/></svg>
                    </div>
                </div>
                <h3 class="text-xl font-bold text-white mb-2">Time Tracker</h3>
                <p class="text-sm text-gray-400">Detailed logging for your daily activities to visualize exactly where your hours go.</p>
            </a>

            <!-- Study Tracker -->
            <a href="https://studytrackerbytamim.pages.dev/" target="_blank" class="project-card p-6 rounded-xl block">
                <div class="flex items-start justify-between">
                    <div class="icon-container p-3 rounded-lg mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M4 19.5v-15A2.5 2.5 0 0 1 6.5 2H20v20H6.5a2.5 2.5 0 0 1-2.5-2.5Z"/><path d="M8 7h6"/><path d="M8 11h8"/></svg>
                    </div>
                </div>
                <h3 class="text-xl font-bold text-white mb-2">Study Tracker</h3>
                <p class="text-sm text-gray-400">Specially tailored for learners. Track study sessions, subjects, and academic progress.</p>
            </a>

            <!-- Stopwatch -->
            <a href="https://stopwatchbytamim.pages.dev/" target="_blank" class="project-card p-6 rounded-xl block">
                <div class="flex items-start justify-between">
                    <div class="icon-container p-3 rounded-lg mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="13" r="8"/><path d="M12 9v4l2 2"/><path d="M5 3 2 6"/><path d="m22 6-3-3"/><path d="M6.38 18.7a10.1 10.1 0 0 1 0-11.4"/><path d="M17.62 7.3a10.1 10.1 0 0 1 0 11.4"/></svg>
                    </div>
                </div>
                <h3 class="text-xl font-bold text-white mb-2">Stopwatch</h3>
                <p class="text-sm text-gray-400">A high-precision timing tool for laps and quick measurements.</p>
            </a>

            <!-- Digital Clock -->
            <a href="https://clockbytamim.pages.dev/" target="_blank" class="project-card p-6 rounded-xl block">
                <div class="flex items-start justify-between">
                    <div class="icon-container p-3 rounded-lg mb-4">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect width="20" height="12" x="2" y="6" rx="2"/><line x1="12" x2="12" y1="10" y2="14"/><line x1="7" x2="7" y1="10" y2="14"/><line x1="17" x2="17" y1="10" y2="14"/></svg>
                    </div>
                </div>
                <h3 class="text-xl font-bold text-white mb-2">Modern Clock</h3>
                <p class="text-sm text-gray-400">An aesthetic, minimalist digital clock for your workspace dashboard.</p>
            </a>
        </div>

        <!-- Footer -->
        <footer class="mt-16 pt-8 border-t border-gray-800 text-center">
            <p class="text-gray-500 text-sm">
                Built with ⚡ by Tamim
            </p>
            <div class="mt-4 flex justify-center gap-6">
                <div class="flex items-center gap-2 text-gray-400 hover:text-white transition-colors cursor-default">
                    <span class="w-2 h-2 rounded-full bg-green-500"></span>
                    Available for projects
                </div>
            </div>
        </footer>
    </div>
</body>
</html>
