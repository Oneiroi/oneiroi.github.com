.. David Busby documentation master file, created by
   sphinx-quickstart on Wed Feb  8 13:10:22 2012.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

NAME
====
David Busby

SYNOPSIS
========


DESCRIPTION
===========

Information Security Architect @ Percona

EXAMPLES
========

Blog / Publications
-------------------

* https://blog.oneiroi.co.uk (personal blog, many articles within)
* https://www.percona.com/blog/author/david-busby/ (mutliple posts)
* https://www.dbta.com/Authors/David-Busby-7218.aspx (2 accepted articles)
* https://www.scmagazine.com/news/network-security/cybersecurity-made-simple

Skills Tree
-----------

Last updated 2022-05-11 (Incomplete)::

     
    |-- Systems Administration
    |        |-- Ansible
    |        |   |- Authored CIS baseline requirments in Ansible CFG managment for CentOS 7.x
    |        |   `- Bespoke extension of ansible to procure system metrics for analysis.    
    |        |-- Systemtap (https://github.com/Oneiroi/sysadmin/tree/master/linux/systemtap) 
    |        |-- Logstash 
    |        |-- Kibana
    |        |-- Elastic search
    |        |-- Suricata
    |        |-- Subverison
    |        |    |-- Administration
    |        |    |-- Backup strategies
    |        |    `-- Hooks customisation
    |        |-- GIT
    |        |    |-- Administration
    |        |    |-- gitosis
    |        |    |-- github
    |        |    `-- Migration from subversion
    |        |-- RHEL / CentOS / Fedora / Scientific Linux Administration
    |             |-- RPM Packaging (spec authoring, mock builds etc ..)
    |             |-- EPEL Contributor for Openstack packages
    |             |-- Nginx
    |             |   `-- Deployment / Monitoring / Patching / Customisation
    |             |-- Apache
    |             |        |-- mod_security
    |             |        |-- Extensive rewrite experience
    |             |        `-- Deployment / Monitoring / Patching / Customisation
    |             |-- KVM
    |             |-- ISCSI
    |             |-- iptables
    |             |-- Xen
    |             |-- Strace
    |             |-- gdb
    |             |    `-- grabbing memory of running process, grabbing stack traces
    |             |-- SELinux
    |             |     `-- audit* tools, still working on this skill set at this time.
    |             |-- Gluster
    |             |-- DRBD
    |             |-- SNMP
    |             |     `-- Customisation and data collection
    |             |-- rsync
    |             |-- netcat / socat
    |             |-- system tap
    |             |     `-- wrote system tap extension to record semaphore lock counts on a mySQL system.
    |             |-- percona
    |             |     `-- percona-toolkit
    |             |-- cut / awk / lsof / type / ldd / man (And generally the majority of tools too numerous to list here)
    |             |-- Openstack
    |             |    |-- Nova
    |             |    |-- Glance
    |             |    |-- Keystone
    |             |    |-- Swift
    |             |    `-- Horizon
    |             | -- ldirectord
    |-- Numerous programming languages.
    |        |-- Python
    |        |    |-- Multiprocessing
    |        |    |    `-- Written daemons, for numerous tasks, and data processing programs.
    |        |    |-- Daemon design and authoring.
    |        |    |-- 0mq
    |        |    |-- scapy
    |        |    |-- Exploit P.O.C
    |        |    |-- Django
    |        |    `-- Some app engine
    |        |-- C++ /  C
    |        |    `-- Linux api / php extensions / simple cli tools / email daemon
    |        |-- PHP
    |        |    |-- Web application development       
    |        |    |-- Application analytics / tuning (XHProf / XDebug)
    |        |    `-- Security and Pentesting
    |        |-- jQuery
    |        |    |-- Web application AJAX
    |        |    `-- Some text animation effects via jQuery extension
    |        |-- VCL
    |        |    |-- extended with inline C to load .so objects for custom functionality
    |        |    |-- extended to trigger execution of script to snapshot system state to aid 503 diagnostics.
    |        |    `-- Designed and Authored modular Varnish cache configuration
    |        |-- RST
    |        |    `-- restructured text, used for documentation via python-sphinx, write once and deploy to man pages, pdf, html etc.
    |        |-- Bash
    |        |    |- TCP reverse shell payloads
    |        |    `-- "one liners", scripts etc.
    |        |-- TCL
    |        |    `-- expect syntax scripting to automate, sftp / ftp etc …
    |        |-- Ruby
    |        |    |-- Some experimentation with parallel programming
    |        |    `-- Some extension of MetaSploit
    |        |-- Markdown
    |             `- used for blogging via jekyll + octopress
    |-- Security / Netsec / Infosec
    |        |-- CTF (Capture The Flag)
    |        |    |- Curated puzzel material and deployed ctfd ~2019 for candidates technical assessment https://github.com/oneiroi/ctf
    |        |    `- Wrote cimilar puzzel to one I' experienced during a Live CTF at 44con from the NCC Group creating my own version (from scratch: https://github.com/Oneiroi/ctf/tree/master/python/2.x/tcp_lock_challenge )
    |        |-- PTES
    |        |-- Metasploit
    |        |    | - Used in pentest demoing issues with Tomcat 5
    |        |    | - Used in conjunction with msfvenom for talk @ PLMCE: https://www.slideshare.net/DavidBusby1/plmce-security-and-why-you-need-to-review-yours
    |        |    | - CVE-2015-1027 
    |        |    `-- Some extension writing experience
    |        |-- Sql injection
    |        |-- Malware authoring in python, go, bash
    |        |-- RedTeam
    |        |   |- Social engineering
    |        |   |- Phishing, Vishing, Smishing, etc
    |        |   |- C2
    |        |   |- Adversarial emulation
    |        |   |- Latteral movement, opportunistic exploitation
    |        |   |- Living off the land
    |        |   `- Social profile construction, impersonation
    |        |-- Command injection and custom exploitation, as per talk given: https://www.slideshare.net/DavidBusby1/security-and-why-you-need-to-review-yours
    |        |-- Maltego
    |        |-- WPA / WEP via Aircrack
    |        |-- SQLMap
    |        |-- Skipfish
    |        |-- Backtrack
    |        |-- dsniff
    |        |-- Burp suite pro
    |        |-- Suricata + logstash + Kibana @ http://blog.oneiroi.co.uk/ids/ips/security/visualization/kibana/logstash/suricata/arm/utilite/suricata-logstash-kibana-utilite-pro-arm/
    |        |-- Password hashing / lookups / Pass the hash.
    |        |-- CISSP (581907 - https://www.isc2.org/MemberVerification?LastName=Busby&MemberNumber=581907)
    |        |-- YPS tutor (NSRA)
    |        |-- PCI, HIPAA, CIS
    |        |-- Vulnerability research though to Proof of Concept e.g. CVE-2015-1027
    |        |-- Definition and establishing a security program (Policies, Baselines etc).
    |        |-- Curating responsible disclosure program, and promoting community contributions. 
    |        |-- Slack bug bounty (share channel BETA, which later became SlackConnect: https://blog.oneiroi.co.uk/security/shared/channel/slack/beta/beta-functionality-still-needs-security-slack-and-shared-channels/)
    |        `-- Several Talks:
    |            |- SlideShare: https://www.slideshare.net/DavidBusby1
    |            |- Talk supporting material:
    |            |    |- Github supporting code: https://github.com/Oneiroi/talks
    |            |    |- TSA lockpicking: https://www.youtube.com/edit?o=U&video_id=zDPWoB7v15o
    |            |    |- Live compromise, php, mysql, udf, metasploit, msfvenom: https://www.youtube.com/watch?v=e29kbX-rx0s
    |            |    |- Malcious HID demo backup video: https://youtu.be/LYY9OI2HHvo
    |            |    |- MySQL hash cracking using Hashcat backup video: https://youtu.be/sqEIhdITjkg https://youtu.be/A9kBpwSlbJw
    |            |    `- SELinux sebool httpd_can_network_connect backup video: https://youtu.be/BHm0Z-uUxBE
    |            `- Youtube recording of talks given:
    |                |- https://www.youtube.com/watch?v=dlcZyLVs5kE (Security Basics)
    |                |- https://www.youtube.com/watch?v=WhPWqo_Ptqc (Security More thant just your Database!)
    |                |- https://www.youtube.com/watch?v=-floDucby0M (Web application security and why you should review yours - Stachka)
    |                `- https://www.youtube.com/watch?v=O0hisREEIpU (OSInt - Do You Really Know What Data You're Leaking ?)
    |-- Opensource contributions
        |-- Majority of source code can be found here https://github.com/Oneiroi
        |-- Upstream commits
             |-- Ansible
             |-- Boxgrinder
             |-- Libcloud
             `-- EPEL Openstack

SEE ALSO
========

* Email: d.busby {at} oneiroi.co.uk / oneiroi {at} fedoraproject.org
* Blog: https://blog.oneiroi.co.uk/2


