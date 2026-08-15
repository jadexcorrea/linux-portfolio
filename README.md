# Linux Command Mastery Log

## Directory Navigation & File Management
* cd		- change working directory
* pwd		- Print absolute path of current directory 
* ls -la	- List all contents, including hidden files
* mkdir		- Create a new directory
* rmdir		- Remove an empty directory
* touch 	- Create an empty file/update timestamp
* rm 		- Permanenty delete a file

## Data Manipulation & Redirection
* echo 		- Print text strings to the terminal
* cat 		- View full contents of a file instantly
* less 		- Scroll through large text files page-by-page
* nano 		- Open the terminal-based text editor
* > 		- Standard Output Redirection (Overwrites file)
* >> 		- Append Output Redirection (Adds to bottom of file)
* | (Pipe) 	- Feeds output of one command into another

## Text Filtering & Live Systems
* grep 		- Search for matching strings/patterns
* grep -i 	- Case-insensitive text search (Crucial for triage)
* ss -a 	- Display all active network sockets and states
* df -h 	- Check disk space usage in human-readable format
* chmod +x 	- Grant executable permission to a file/script

## System Performance, Disk Utilization & Target Neuralization
* df -h 	- Check disk space usage in human-readable format
* rm [pattern]*	- Delete multiple files matching a wildcard pattern
* find [path]	- Search for files systematically across a directory tree
* find -size	- Locate files matching specific size criteria
* find -delete	- Locate and automatically destroy targeted file threats

## Access Control & Privilege Management
* ls -l		- View file permission and ownership metadata
* chmod		- Change/modify file access
* chmod 600	- Restrict file access exclusively to the owner
* sudo 		- Execute commands with administrative (root) authority
* id 		- Display active user identity and group assignments

## Process Management & Incident Response
* &		- Append to a command to execute it silently in the background
* ps aux 	- Snapshots all active system process across all users
* kill -9 	- Sends an uncatchable SIGKILL signal to forcefully terminate a PID

## Interactive Resource Telemetry
* htop 		- Launches and interactive real-time process and resource monitor
* k 		- Triggers the interactive process signals menu (Alternative to F9)
* SIGKILL (9)	- Forces immediate kernel-level termination of a highlighted target

## Automated Boot Analysis & Diagnostic Telemetry
* /var/log/boot.log	-Core repository for operating startup sequences
* tail -f [log]		- Live stream auditing for active runtime logs

## Network Telemetry & Packet Interception
* ip a		- Displays local hardwar interface bindings and IP configurations
* tcpdump	- Command-line network packet sniffer and analysis engine 
* port [num]	- Network layer logical filter constraint
* -X		- Prints packet paylods in hex and ASCII formatting structures

## Network Recconaissance & Port Auditing
* nmap		- Network Mapper utility used for network discovery and security auditing
* -sV		- Service version detection flag (probes open ports to determine software details)
* -A		- Aggressive scan flag (combines OS detection, version scanning, and traceroute)

## Package Infrastructure & SUpply-Chain integrity
* /etc/apt/source.list.d/	- Subdirectory housing modular DEB822 repository configuration files
* apt-get update 		- Synchronizes local package indexes using secure cryptographic signatures
* apt-cache depends		- Evaluates software library dependencies and architectural footprints
* apt autoremove		- Purges unlinked dependency files to minimize system attack surfaces

## Shell Environment & Memory Variables
* env		- Displays all active system-wide environment variables in memory
* export	- Injects user-defined variables into the current terminal shell environment

* $		- Reference operator used to call and read the data contents of a variable

## Storage Optimization, Compression & Archival Forensics
* tar -cvf	- Creates a consolidated tape archive bundle from target folders
* gzip		- Compresses files into high-efficientcy binary blocks (.gz)
* tar -xzvf	- Uncompresses adn extracts a multi-layer gzip tarball natively
* rm		- Permanently purges redundant or duplicate uncompressed storage payloads

## Verison Control & Open-Source Repositories
* git init	- Transforms a local filesystem directory into a Git tracking repository
* git add	- Stages Targeted file assets into the version control preparation index
* git commit	- Commits staged snapshots permanently to local repository history metrics

## Automated Task Scheduling & Daemon Engineering
* crontab -e	- Opens the native system time-scheduler configuration matrix
* * * * * *		- Five-axis timing parameter indicating execution intervals every consecutive minute
* crontab -r	- Purges all active scheduled cron tasks from the user profile database

# Cybersecurity Portfolio Assignments

## Assignment 1: Automated Compromised Accounts& Live Port Triage
* Objective: Detect unauthorized local user access and malicious server ports.
* Action Taken:
	1. Isolated system-level users utilizing bash shells grep filtering on '/etc/passwd'
	2. Captured live network socket structures via case-insensitive pattern matching ('ss -a | grep -i "u").
	3. Created an executable automated Bash script ('auto_audit.sh') to run full machine diagnostics with a single command.
	4. Structured standard outputs into an active incident response log ('incident_report.txt') using append operators.
* Security Outcomes: Demonstrated understanding of data auditing, automated log generation, shell scripting, and defensive system visibility.

## Assignments 2: Storage Optimization & Target Threat Neutralization
* Objective: Hunt hidden local file threats and execute automated storage remediation.
* Actions Taken:
	1. Audited system partition thresholds utilizing human-readable flags (`df -h`).
	2. Leveraged multi-file wildcard matching (`rm attack*`) to simulate mass log clearing.
	3. Deployed system-wide target tracking arrays (`find ~ -name "malware_test.exe"`) to uncover buried files.
	4. Executed automated combined logic parsing (`find -delete`) to locate and vaporize a threat in a single motion.
* Security Outcomes: Mastered proactive storage management, automated threat discovery, and file pattern annihilation.

## Assignment 3: Access Control Hardening & Administration Auditing 
* Objective: Implement strict file control lists (ACLs) and audit priviliged system configuration files.
* Actions Taken:
	1. Generated an intrustrial-grade sensitive log asses ('secrets.log') via command line.
	2. Evaluated standard discretionary access controls using extended listing metrics ('ls -l').
	3. Applied advanced numerical permission masks ('chmod 600') to completely strip public and group read/write privileges.
	4. Executeed superuser privileges elevation commands ('sudo') to bypass standard system restrictions and audit secure credential datbases ('/etc/shadow').
* Security Outcomes: Demonstrated practical mastery of the principle of least privilege, administrative group verification, and raw host-level hardening.

## Assignment 4: Live Process Traige & Threat Termination
* Objective: Detect, isolate, and forcefully terminate unauthorized background daemons.
* Actions Taken: 
	1. Initialized a persistent background process pay;oad ('sleep 9999 &') to simulate silent malware execution.
	2. Generated a full system memory diagnostic mapping using comprehensive process tracking ('ps aux').
	3. Integrated pipeline filtering ('grep -i') to bypass system noise and pinpoint the unauthorized target process infrastructure.
	4. Discovered and isolated the unique Process ID (PID: 4391).
	5. Issued an absolute kernel-level termination signal ('kill -9 4391') to instantly neutralize the background threat.
* Security Outcomes: Acquired foundational incident response capabilities , process lifecycle control, and real-time volatile memory auditing.

## Assignment 5: Real-Time Resource Auditing & Signal Interception 
* Objective: Monitor volatile system vital signs and execute internal process terminations.
* Actions Taken: 
	1. Deployed an interactive telemetry layer ('htop') to evaluate multi-core CPU distribution and physical memory (RAM( allocation scales.
	2. Map-sorted running operational clusters by processor density utlization.
	3. Navigated hardware abstraction constraints by overriding macOS keyboard mapping using internal system hotkeys ('k').
	4. Executed an abrupt SIGKILL sequence directly within the execution stack to isolate a targeted system shell.
* Security Outcomes: Advanced comprehension of system infrastructure monitoring, volatile telemetry interpretation, and native shell disruption management.

## Assignement 6: Enterprise Boot Infrastructure & Network Initialization Auditing
* Objective: Capture live hardware abstraction sequences and audit network daemon initialization.
* Actions Taken:
	1. Maintained platform consistency within a virtualized Kali Linux deployment framework.
	2. Isolated the central boot diagnostic log arhitecture located at '/var/log/boot.log'.
	3. Deployed a live administrative intercept stream ('sudo tail -f boot.log') to evaluate core daemon startups.
	4. Monitored real-time systemd thread executions ('lightdm.service' and 'network-manager.service').
	5. Implemetned post-stream case-insensitive data filters ('grep -i "network"') to extract a clean operational network timeline.
* Security Outcomes: Acheived advanced competency in systemd architecture auditing, boot-sequence forensics, and network telemetry isolation. 

## Assignment 7: Real-Time Packet Sniffing & Logical Network Traffic Filtering
* Objective: Tap physical network interfaces to intercept and analyze live packet streams.
* Action Taken: 
	1. Identified local network hardware interfaces ('eth0') utitlizing kernel IP mapping arrays.
	2. Initiated an administrative wiretap layer ('sudo tcpdump -i eth0 -c 10') to capture ambient network broadcasts.
	3. Evaluated kernel drop and packet capture success rates under active network load environment.
	4. Deployed Berkley Packet Filters ('port 443') tp isolate secure corporate web data from background home network traffic.
	5. Extracted raw hex/ASCII crytographic payloads ('-X') to audit data-in-transit configurations.
* Security Outcomes: Achieved live traffic visibility, protocol-layer filtering capabilities, and raw hexadecimal artifact extraction mastery.

## Assignment 8: Automated Infrastructure Mapping & Defensive Reconnaissance
* Objective: Conduct internal asset discovery and audit local host system ports for software exposure.
* Actions Taken:
	1. Provisioned the industry-standard scanning suite ('nmap') within the local virtualized environment.
	2. Executed baseline port audit against the loopback interface ('127.0.0.1') to evaluate the system perimeter.
	3. Deployed advanced service version detection arrays ('-sV') to probe active sockets for software metadata.
	4. Launched an aggressive diagnostic scan framework ('sudo nmap -A') to analyze host-level kernel fingerprints and trace route configurations.
* Security Outcomes: Acquired foundational penetration testing capabilities, system perimeter auditing mastery, and version-specific vulnerability detection visibility.

## Assignment 9: Advanced Package Infrastructure & Supply-Chain Integrity Auditing
* Objective:Audit cryptographic software repositories and evaluate package dependency chains.
* Actions Taken: 
	1. Nagivated modern Linux package architecture modifications by isolating structured DEB822 configuration files ('/etc/apt/source.list.d/kali.sources').
	2. Analyzed critical secure supply-chain metadata controls including components, suites, and cryptographic 'Signed-By' public key anchors.
	3. Orchestrated a secure repository database synchronization ('sudo apt-get update') to verify digital signature integrity.
	4. Mapped multi-layer binary dependency trees ('apt-cache depends wireshark') to audit an application's execution footprint prior to deployment.
	5. Deployed system cleanup loop ('sudo apt autoremove') to maintain a lean, optimized system storage environment.
* Security Outcomes: Mastered supply-chain validation techniques, repository access auditing, and host-level dependency minimization controls.

## Assignment 10: Environment Variables Injection & Shell Telemetry Auditing
* Objective: Evaluate system runtime environments and execute custom variable memory configurations.
* Actions Taken:
	1. Audited active shell telemetry configurations and user structure using system environment calls ('env').
	2. Isolated critical security system mappings by evaluating binary execution directories ('echo $PATH').
	3. Deployed custom identity-state variables ('export MY_ROLE="CyberSecurity Specialist"') directly into volatile terminal memory.
	4. Utilized reference operators ('$') to recall and verify custom environmental memory assets.
* Security Outcomes: Mastered volatile system configuration management, path-variable auditing, and porgrammatic environment control.

## Assignment 11: Enterprise Storage Optimization & Multilayer Archive Forensics
* Objective: Author consilidated system archives, execute multi-layerdata compression workflows, and maintain filesystem hygiene.
* Actions Taken:
	1. Engineered a dedicated local staging directory ('forensic_vault') containing mock security logs.
	2. Synthesized an enterprise tape archive structure ('tar -cvf')to bind discrete assets into a single object.
	3. Deployed the cryptographic 'gzip' compression engine to shrink the physical storage footprint into a 'tar.gz' payload.
	4. Performed proactive filesystem auditing by manually isolating and deleting duplicate uncompressed storage payloads ('rm') to prevent data redundancy.
* Security Outcomes: Mastered advanced file-system bundling, live archive triage, evidence preservation mechanics, and storage surface minimization tactics.

## Assignment 12: Distibuted Version Control Initialization & Portfolio Structuring
* Objective: Configure local version control tracking systems and stage technical portfolio logs.
* Actions Taken: 
	1. Installed and configured global crytographic signature identities within the distribured version suite ('git').
	2. Executed local repository initializations ('git init') to track desktop security assets.
	3. Managed local indexing pipelines ('git add') to stage master markdown project summaries.
	4. Engineered permanent repository baseline checkpoints ('git commit') utilizing descriptive deployment notes.
Security Outcomes: Mastered source code auditing basics, configuration version control, and infrastructure documentation deployment pipelines.

## Assignment 13: Decoupled System Automation & Temporal Daemon Configuration
* Objective: Configure low-level system cron daemons to execute automated security scans without human intervention.
Action Taken:
	1. Initialized the system's runtime scheduler framework ('crontab -e') using native text manipulation.
	2. Engineered a five-axis precision timing string ('* * * * *') to establish minute-interval execution triggers.
	3. Intergrated active network pipeline telemetry arrays ('ss -a' | grep -i') into the automated background runtime environment.
	4. Monitored real-time filesystem adjustments to observe automated asset materialization ('auto_network_log.txt').
	5. Executed post-operational cleanup routines ('crontab - r') to strip out volatile task loops and protect system capacity thresholds.
* Security Outcomes: Mastered autonomous persistence techniques, script automation architecture, amd host-level cron security controls.
