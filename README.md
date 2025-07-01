# Cyber-Security-task-4


Opened Windows Defender Firewall with Advanced Security from the Start menu.
Navigated to Inbound Rules and Outbound Rules to review existing configurations.
 Created a New Inbound Rule:
  - Selected Port
  - Chose TCP and entered port `23`
  - Action: Block the connection
  - Applied to Domain, Private, Public
  - Named it Block Telnet Port

  - Used Command Prompt:
   telnet 127.0.0.1 23
