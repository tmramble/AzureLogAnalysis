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
            white-space: pre-wrap;
            word-wrap: break-word;
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

        <h3 id="admin-mode-configuration-setup">Admin Mode: Configuration & Setup</h3>
        <ol>
            <li><strong>Create a Windows VM in an Azure region outside the US</strong>
                <ul>
                    <li><strong>VM Name</strong>: attack-vm</li>
                    <li><strong>Resource Group</strong>: RG-Cyber-Lab-Attacker</li>
                    <li><strong>Virtual Network</strong>: Lab-VNet-Attacker</li>
                </ul>
            </li>
            <li><strong>Verify VM Accessibility</strong>
                <ul>
                    <li>Log into the VM (attack-vm) to ensure it is functioning as expected.</li>
                </ul>
            </li>
            <li><strong>Retrieve Public IP Address</strong>
                <ul>
                    <li>From the Azure Portal, locate and save the public IP address of the windows-vm for use in the next steps.</li>
                </ul>
            </li>
        </ol>

        <h3 id="attacker-mode-simulated-attacks">Attacker Mode: Simulated Attacks</h3>
        <ol>
            <li><strong>Simulate Failed RDP (Remote Desktop Protocol) Login Attempts</strong>
                <ul>
                    <li>From attack-vm, attempt to RDP into windows-vm with incorrect credentials (wrong username/password).</li>
                    <li>Repeat the login attempts with different invalid credentials to simulate a brute force attack.</li>
                </ul>
            </li>
            <li><st

