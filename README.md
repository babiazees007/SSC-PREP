SSC CGL PrepDesk 📚
A fully offline, single-file dashboard for SSC CGL exam preparation. No installation, no internet, no account — just open and start studying.

What's Inside
FeatureDescriptionDashboardStreak, syllabus %, today's problems, activity heatmapSyllabus TrackerAll SSC CGL topics pre-loaded with difficulty tagsProblem TrackerLog problems per subject, daily vs target, running totalDaily LogWrite what you completed each day with categoriesNotesDate-tagged study notes with search and filterProgressAnalytics, exam countdown, subject-wise breakdownSettingsSet exam date, targets, subjects, and your name

Quick Setup (2 Minutes)
Step 1 — Download the file
Save ssc_cgl_dashboard.html to a folder on your desktop.
Suggested folder structure:
Desktop/
└── SSC-CGL-Prep/
    └── ssc_cgl_dashboard.html
Step 2 — Open in your browser
Double-click ssc_cgl_dashboard.html — it opens in your default browser.

✅ Works in Chrome, Firefox, Edge, Brave, and Safari.
✅ No internet required after the first open (fonts load once, then cache).

Step 3 — First-time setup

Click the Settings tab
Enter your name and exam date
Set your daily problems target (default: 50)
Set your total problems goal (default: 5000)
Add or remove subjects as needed
Click Save Settings

That's it. You're ready.

How Your Data is Saved
All data is stored in your browser's localStorage — a built-in storage system in every modern browser.

Data is tied to the browser + file path combination
Closing the tab or shutting down your PC does not delete your data
Next time you open the file, everything resumes exactly where you left off

What gets saved automatically

Syllabus topic completion
Problem counts per day per subject
Daily activity logs
Notes
Visit history and streak count
All settings


Daily Usage Guide
Morning routine

Open ssc_cgl_dashboard.html
Check the Dashboard — see your streak and today's targets
If you see a yellow reminder banner, it means yesterday's problems were below target

While studying

Go to Syllabus → click topics as you complete them
Go to Problems → enter how many problems you solved per subject
Click Save after entering problems

End of day

Go to Daily Log → type what you studied and hit Add Entry
Check your streak in the top-right corner

Taking notes

Go to Notes → add a title and write freely
Notes are saved with the date — useful for revision later
Use the search box to find notes by keyword


Reminder System
The dashboard automatically shows a warning banner when:

You solved fewer problems than your target yesterday
It is after 8 PM and you haven't hit today's target yet

Dismiss it with the ✕ button, or fix it by logging your problems.

Streak Logic
SituationStreakOpened the app todayCounts as a visitOpened yesterday and today2-day streakMissed a dayStreak resets to 0Best streak everShown in Progress tab

Keeping Your Data Safe
Because data lives in the browser, there are a few things to know:
⚠️ Things that will erase your data

Clearing your browser's site data / cookies / cache
Using the Clear All Data button in Settings
Opening the file from a different browser (data is not shared between browsers)
Reinstalling your browser

✅ Best practice — export a backup
Open your browser console (F12 → Console tab) and run:
javascriptconsole.log(localStorage.getItem('ssc_cgl_state'));
Copy the output and save it as a .txt file. To restore, run:
javascriptlocalStorage.setItem('ssc_cgl_state', '<paste your backup here>');
location.reload();

Pinning for Easy Access
Windows
Right-click ssc_cgl_dashboard.html → Send to → Desktop (create shortcut)
Or pin to taskbar:

Open the file in Chrome
Click the three-dot menu → More tools → Create shortcut
Check "Open as window" for an app-like experience

macOS
Drag ssc_cgl_dashboard.html to the Dock, or add it to your browser bookmarks bar with Cmd + D.
Browser Bookmark
Press Ctrl + D (Windows) or Cmd + D (macOS) when the file is open. This is the fastest way to reopen it daily.

Customising Subjects
By default, the problem tracker has 4 subjects:

Quantitative Aptitude
English
General Awareness
Reasoning

To add a subject: Settings → type in the box under "Subjects" → click Add
To remove one: click Remove next to any subject

Note: The syllabus section always shows the full SSC CGL official syllabus and cannot be edited.


Offline Mode
The dashboard works 100% offline after the fonts are cached (happens automatically on first open with internet). After that, you can use it on a train, in a library, anywhere — no Wi-Fi needed.
To force full offline use from day one, you can replace the Google Fonts link in the HTML with a local font or a system font. Open the file in a text editor and find this line near the top:
html<link href="https://fonts.googleapis.com/css2?family=Space+Grotesk...
Delete it, and the dashboard will fall back to your system's default sans-serif font.

Troubleshooting
ProblemFixData disappearedCheck you're opening the same file in the same browserFonts look differentOpen with internet once to cache the fontsStreak shows 0Make sure your system clock is correctProblems not savingClick the Save button after entering numbersFile won't openRight-click → Open with → choose Chrome/Firefox/Edge

File Info
PropertyValueFile typeSingle HTML fileFile size~35 KBDependenciesNone (zero npm, zero pip, zero server)Browser supportChrome 80+, Firefox 75+, Edge 80+, Safari 14+Data storageBrowser localStorage (~5 MB limit, more than enough)Internet requiredOnly for fonts on first load

Credits
Built with plain HTML, CSS, and JavaScript. No frameworks. No build tools. No backend.
Fonts: Space Grotesk + JetBrains Mono via Google Fonts.

Good luck with your SSC CGL prep! Consistency beats intensity — keep that streak alive. 🔥
