# OSS Audit Project

Hey there! This is my Open Source Software audit project for the course at VIT Bhopal. I picked Python as the open-source software to explore because it's super useful for programming, data science, AI, and more. It's open-source, so anyone can contribute and make it better.

The goal was to understand how open-source tools work in Linux, learn shell scripting, and check out system stuff like packages, logs, and permissions.

## What's in here?

Five shell scripts to audit a Linux system:

- **script1_system_identity.sh**: Grabs basic system info like your username, Linux version, kernel, uptime, and current time.
- **script2_package_inspector.sh**: Checks if Python is installed, shows the version, and gives a quick description.
- **script3_disk_auditor.sh**: Looks at permissions, owners, and sizes for key directories like /etc, /var/log, /home, etc.
- **script4_log_analyzer.sh**: Scans log files for keywords like "error", counts them, and shows recent matches.
- **script5_manifesto_generator.sh**: Creates a fun manifesto about open-source philosophy.

Run them on a Linux machine to see how it all works. Enjoy exploring!

The final script is an interactive script that generates a small open-source philosophy statement.

The script asks the user three questions:

1)An open-source tool they use daily
2)What "freedom" means to them
3)Something they would build for the community

Based on the answers, the script generates a short Open Source Manifesto and saves it as a text file.

This script highlights the collaborative and philosophical aspect of open-source software.

How to Run the Scripts
First make the scripts executable:
chmod +x *.sh

Then run any script using:
./script_name.sh

Technologies Used:
1)Linux (Ubuntu / WSL)
2)Bash Shell Scripting
3)Python (audited software)
4)Git & GitHub for version control

Key Learnings

Working on this project helped me understand several important concepts, including:

1)The structure of Linux file systems
2)How open-source software is installed and maintained
3)The importance of automation through shell scripting
4)Basic system auditing techniques
5)The collaborative nature of open-source communities

It also improved my familiarity with GitHub and version control, which are essential tools in modern software development.

Conclusion

Open-source software plays a vital role in today's technology ecosystem. Projects like Python demonstrate how collaborative development can produce powerful tools used across industries.

This audit project provided practical experience with Linux systems, scripting, and open-source principles. It also highlighted the transparency and flexibility that make open-source software so valuable.

Project implemented and maintained by Aditya Kulkarni

