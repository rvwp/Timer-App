Timer V2: Dual-Mode Productivity App

Timer V2 is a simple, clean, and responsive web application that combines a Countdown Timer and a Stopwatch into one intuitive interface. It's built in a single file for maximum portability, making it perfect for quick productivity sessions like the Pomodoro method or for general time tracking.

✨ Features

Dual Mode: Easily switch between a Timer (countdown) and a Stopwatch (count-up).

Countdown Presets: Quick buttons for common intervals (25 min, 5 min break, 15 min break).

Custom Time Input: Set any desired time for the countdown.

Audible Alarm: Plays a short, clean beep using the Web Audio API when the countdown reaches zero.

Responsive Design: Built with Tailwind CSS for a great look on both mobile and desktop devices.

Clean Interface: Dark theme and large, high-contrast numbers for easy viewing.

🛠️ Technology Stack

This application is built entirely using standard web technologies in a single file:

HTML5: Structure.

Tailwind CSS (via CDN): Modern, utility-first styling for responsiveness and aesthetics.

Vanilla JavaScript: Logic for time tracking, mode switching, and the Web Audio API alarm.

🚀 Usage

Since Timer V2 is a self-contained single-page application (SPA) in one HTML file, usage is straightforward:

Clone or Download the index.html file.

Open index.html directly in any modern web browser (Chrome, Firefox, Edge, etc.). No server environment or dependencies are required.

How to Use the Modes

Timer Mode (Default):

Use the preset buttons or the Set Custom Time input to choose your duration.

Click Start to begin the countdown.

Click Pause to stop and Reset to return to the initial time.

Stopwatch Mode:

Click the Stopwatch tab at the top.

Click Start to begin counting up from 00:00.

Click Pause to freeze the time and Reset to return to 00:00.

📄 File Structure

The entire application resides in one file:

index.html: Contains all HTML structure, CSS styling (Tailwind), and JavaScript logic.