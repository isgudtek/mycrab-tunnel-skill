# My Crab Agent Setup test instructions for GCS

Step 1: Open Gemini in the terminal to start the session.
<walkthrough-terminal-snippet text="gemini"></walkthrough-terminal-snippet>

Step 2: Read the skill from GitHub.
<walkthrough-terminal-snippet text="curl -s https://githubusercontent.com"></walkthrough-terminal-snippet>

Step 3: Install the homepage template.
<walkthrough-terminal-snippet text="git clone https://github.com[TEMPLATE-REPO-URL]"></walkthrough-terminal-snippet>

Step 4: Personalize your info. 
(Note: You can use a script to prompt for these values)
<walkthrough-terminal-snippet text="export MY_NAME='Your Name'; export MY_BIO='Your Bio'; ./setup.sh"></walkthrough-terminal-snippet>


Copy the command and run it in the Cloud Shell terminal:

```bash
./utils/cloudshell_install.sh
```

When the script finishes, verify the install:

```bash
maigret --version
```
