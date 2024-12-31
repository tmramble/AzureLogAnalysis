# AzureLogAnalysis

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio Project: Azure Cybersecurity Simulation & Log Analysis</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
        }
        h1, h2 {
            color: #333;
        }
        h2 {
            margin-top: 20px;
        }
        ul {
            list-style-type: square;
            margin: 10px 0;
        }
        li {
            margin: 5px 0;
        }
        pre {
            background-color: #f0f0f0;
            padding: 10px;
            border-radius: 5px;
            font-family: Consolas, monospace;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Portfolio Project: Azure Cybersecurity Simulation & Log Analysis</h1>

        <p><strong>Project Overview:</strong> This project simulates a cybersecurity scenario designed to test and analyze the security posture of virtual machines (VMs) in Microsoft Azure. The simulation involves creating and configuring VMs, performing multiple attack simulations (such as failed RDP, SQL, and SSH login attempts), and analyzing the resulting security logs from both an administrative and attacker's perspective. The goal is to learn how to identify and mitigate vulnerabilities, monitor security logs, and understand system behavior under attack.</p>

        <h2>Table of Contents</h2>
        <ul>
            <li><a href="#introduction">Introduction</a></li>
            <li><a href="#project-setup">Project Setup</a>
                <ul>
                    <li><a href="#admin-mode-configuration-setup">Admin Mode: Configuration & Setup</a></li>
                    <li><a href="#attacker-mode-simulated-attacks">Attacker Mode: Simulated Attacks</a></li>
                </ul>
            </li>
            <li><a href="#log-analysis">Log Analysis</a></li>
            <li><a href="#conclusion">Conclusion</a></li>
            <li><a href="#final-notes">Final Notes</a></li>
        </ul>

        <h2 id="introduction">Introduction</h2>
        <p>In this project, you will simulate a real-world cybersecurity scenario where both administrative and attacker roles are explored. You’ll configure Azure virtual machines, carry out different attack simulations, and then analyze the system's response through security logs. By the end of this project, you will have gained practical experience in detecting unauthorized activities, managing security events, and reviewing logs to identify potential threats.</p>

        <h2 id="project-setup">Project Setup</h2>

        <h3 id="admin-mode-configuration-setup">Admin Mode: Configuration & Setu
