AI Mystery Solver
An interactive, zero-API-key Google Colab application built with Gradio that parses raw investigative clues, extracts timestamps, reconstructs timelines, flags contradictions, and performs basic automated pattern detection for fictional mysteries, logic puzzles, or creative writing case files.

🚀 Features
Zero API Keys Required: Runs entirely locally within a Python environment using standard regex and rule-based parsing logic.

Automated Timeline Reconstruction: Detects time codes (HH:MM AM/PM) and extracts corresponding events into a chronological view.

Contradiction & Anomaly Flagging: Scans text for inconsistency markers (e.g., but, however, missing, never, impossible) to highlight statements requiring scrutiny.

Pattern Detection: Automatically tags categories like missing items, digital footprints, surveillance coverage, and payment records.

Interactive Web Interface: Powered by Gradio for quick deployment inside a single Google Colab cell.

🛠️ Tech Stack
Python 3.x

Gradio (Web UI interface)

Regular Expressions (re) (Pattern and timeline extraction)

📦 Installation & Quickstart
You can run this project instantly in Google Colab or locally on your machine.

1. Install Dependencies
Bash
pip install gradio
2. Run the Application
Copy the Python script into your environment and execute it:

Bash
python app.py
(If running in Google Colab, executing the script will output a local URL and an optional public share link automatically).

🧩 How It Works
Input Clues: Enter your case title and drop a set of sequenced or unsequenced clues into the text box.

Analysis Engine:

Splits input into individual statements.

Parses time references to build a structured event log.

Filters statements against a keyword dictionary to surface potential discrepancies.

Structured Output: Generates a comprehensive Markdown report detailing case summaries, timelines, anomalies, and confidence metrics.

⚠️ Prototype Notice
This tool is designed for creative writing, logic puzzle assistance, and prototype demonstration. It identifies heuristic patterns and textual inconsistencies—it does not perform forensic validation, criminal profiling, or establish real-world guilt.

📜 License
Distributed under the MIT License. See LICENSE for more information.
