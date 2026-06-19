# stark-schedule
live: https://golapsaroar.github.io/stark-schedule/
It all started with a piece of paper. Or rather, a standard, lifeless black-and-white PDF of my university class routine. Every day involved staring at a static grid of times and room numbers. It was functional, sure, but it lacked soul. It lacked energy. It felt like I was accessing data on an MS-DOS terminal from the 80s when I wanted to feel like I was stepping into the future.


🛠️ The "Stark" Upgrade: Forging the Interface
I threw out the black-and-white grid and started building from scratch. Here is how the transformation happened:

Phase 1: The Armor (UI/UX)
I started with a deep, dark void (#020205) and injected neon cyan, warning reds, and stark gold. Using Tailwind CSS, I shaped a Heads-Up Display (HUD) that felt alive. I added scanlines, grid overlays, and custom sci-fi fonts (Orbitron and Share Tech Mono). The routine wasn't just a table anymore; it was a Tactical Matrix.

Phase 2: The Arc Reactor (Animations & Interactivity)
A static Iron Man is just a statue. I needed motion.

I built a boot sequence with heavy, mechanical blast doors that slide open upon ignition.

I rendered a custom SVG Iron Man hull that floats seamlessly on the launch pad.

I added a custom HTML5 Canvas particle system for the thruster combustion. When you hit the reactor trigger, the screen shakes, the boosters fire, and the suit launches you into your daily workflow.

Phase 3: The Brains (J.A.R.V.I.S. Integration)
A pretty interface means nothing without intelligence. I integrated the Gemini 3.0 Flash Preview API to act as J.A.R.V.I.S. Now, instead of manually clicking buttons, I can type: "J.A.R.V.I.S., schedule a lab on Sunday at 14:30," and the AI parses the command, checks for conflicts, and injects the payload directly into the storage matrix.

Top it off with synthesized audio responses, and the black-and-white routine was officially dead. The Tactical Matrix was born.

🚀 System Capabilities (Features)
Interactive Boot Sequence: Mechanical blast doors, thruster ignition, and screen-shake launch mechanics.

Dynamic Data Core: Saturday through Wednesday class routing, saved locally to your browser (localStorage).

J.A.R.V.I.S. AI Core: Natural language processing to analyze, add, or purge class sectors dynamically using the Gemini API.

Audio Synthesis: Sci-fi interface sounds (clicks, hums, launches) and TTS (Text-to-Speech) readouts.

Chronological Duty Load: A live circular gauge tracking how much of your day you've completed based on real-time system clocks.

Stark Security Override: A hidden architect mode locked behind a passcode.

⚙️ How to Deploy
Clone the Core: Download the index.html file to your local machine.

Inject the API Key: Open the file in a code editor and locate the apiKey variable inside the executeJarvisTask and playGeminiTTS functions. Paste your Google Gemini API key there.

Ignite: Open the file in any modern web browser (Chrome, Edge, Firefox).

Launch: Click the Arc Reactor trigger to open the blast doors.

🔒 Master Control Override
Attempting to delete or add core data will trigger the Stark Security System.
To bypass this and enter ARCHITECT MODE, use the master encryption key:
*******

Developed for CSE-A 2024 © 2026
Developed by 
Golap Saroar
CSE 24
