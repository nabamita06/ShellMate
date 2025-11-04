<h1 align="center">⚙️ <b>AI Powered CLI Assistant</b></h1> <h3 align="center"><i>Your Smart Command-Line Co-Pilot</i></h3>

AI Powered CLI Assistant (Shellmate) is an intelligent terminal companion that turns natural language instructions into safe, executable shell commands.
It explains what each command does, evaluates risk levels, and allows dry-run or real execution — making command-line automation effortless, educational, and secure.
Powered by Google Gemini AI, it blends reasoning, safety, and clarity in one sleek CLI experience.

<h2>✨ Features</h2>

💬 Natural Language → Command Conversion – Type what you mean; the AI writes the correct shell command.
🧠 Command Explanation – Understand every line before executing.
⚠️ Risk Assessment – Automatically grades each command as Low, Medium, or High risk.
🧪 Dry-Run Mode – Safely preview the command without running it.
🔒 Safe Execution – Approve and execute commands only when ready.
⚡ Gemini-Powered Intelligence – Uses Google Gemini AI for deep understanding and accurate command crafting.
🧾 Execution Summary – Displays result code, stdout, and stderr after each run.

<h2>🧠 Tech Stack</h2>

Python – Core development & CLI logic

Google Gemini AI – Natural language understanding & command reasoning

Click / Argparse – Command-line interface framework

dotenv – Secure API key configuration

OS / subprocess – Command execution & system integration

<h2>📁 Project Modules</h2>

🧩 Command Parser & Generator – Converts natural language to valid shell syntax
🔍 Explanation & Risk Analyzer – Describes what the command does and assesses safety
🧪 Dry-Run / Safe Execution Engine – Offers interactive confirmation before execution
🧰 CLI Interface (Shellmate) – Elegant text-based output with color-coded sections
🔐 Gemini API Integration – Powers intelligent command synthesis and reasoning

<h2>🚀 Example Usage</h2>
./run.py gen "Can you list all my files in Downloads that I have downloaded more than 1 year ago and not used for 1 year" --no-dry


Instruction
Can you list all my files in Downloads that I have downloaded more than 1 year ago and not used for 1 year

Generated Command

find ~/Downloads -type f -mtime +365 -atime +365


Explanation
Lists all regular files in your Downloads folder that were modified over a year ago and not accessed for a year — identifying old, unused files.

Risk Level: LOW ✅

Execution Result:

/Users/.../googlechrome.dmg
/Users/.../971.eps
/Users/.../.localized

<h2>💡 Why You’ll Love It</h2>

✅ Eliminates guesswork from terminal usage
✅ Prevents risky command execution
✅ Educates you about shell commands
✅ Boosts productivity through automation
