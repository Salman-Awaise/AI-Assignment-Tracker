Steps to Run the Project
Open the Project

Launch VS Code.

Go to File → Open Folder…

Select your project folder, for example:

C:\Users\<your-name>\tracker


Wait for the files to load in the Explorer panel.

Open a Terminal

In VS Code’s top menu, click Terminal → New Terminal
(or press Ctrl + ` — the backtick key).

You’ll see a terminal open at the bottom.
Make sure the prompt path shows your project folder:

PS C:\Users\<your-name>\tracker>


If not, type:

cd "C:\Users\<your-name>\tracker"

Install Dependencies

If this is your first time running the project on this computer, install all required packages:

npm install


Wait until the terminal shows something like:

added 400 packages in 25s

Start the Development Server

Run:

npm start


This compiles the app and opens your default browser.
When you see this message:

Compiled successfully!
You can now view tracker in the browser.

Local: http://localhost:3000


visit → http://localhost:3000

You should now see the Tracker app running with:

Home screen (Effort bar + Task cards)

AI summaries visible on each card

Navigation tabs (Home / Weekly / Add / Profile)

Stop the Server

To stop the server, press Ctrl + C in the terminal, then Y if prompted.

(Optional) Create a Production Build

To generate an optimized static version for submission or hosting:

npm run build


This creates a build/ folder containing the compiled version of the app.