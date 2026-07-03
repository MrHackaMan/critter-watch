Threat Map Dashboard

A real-time security telemetry dashboard built to visualize network activity, device compliance, and incident response within a simulated environment.
Project Overview

This project functions as a front-end monitoring tool that translates network data into a visual map. It is designed to demonstrate how security events, such as brute force attempts, port scans, and phishing—can be tracked across a network, correlated with the MITRE ATT&CK framework, and managed via endpoint policy settings.
Features

    Live Threat Mapping: Uses HTML5 Canvas and SVG layers to animate attack traffic from various global origins to a centralized network.

    Incident Logging: Maintains a scrolling log of network events, including timestamps, source attribution, and threat severity.

    Endpoint Status: Displays a real-time list of network devices, identifying systems that are compliant or require security intervention.

    Policy Enforcement: Tracks active security measures like MDM compliance and authentication protocols.

    Attack Lifecycle Mapping: Correlates detections with stages of the MITRE ATT&CK framework to provide context for security analysts.

Technical Implementation

    Language: Vanilla JavaScript (ES6+).

    Styling: CSS Grid and Flexbox for layout management.

    Graphics: Native Canvas API for background maps and SVG for path-based animations.

    State Management: Event-driven architecture used to handle DOM updates and animation loops without external dependencies.

Installation

    Clone this repository to your local machine.

    Open index.html in any modern web browser.

    No build step or server environment is required.

Future Development

    Integrate external threat intelligence APIs to replace simulated traffic with live data.

    Implement user-controlled defense toggles to simulate the impact of security policies on network traffic.

    Expand the endpoint monitoring capabilities to include more granular vulnerability tracking.

Lessons Learned

    Managed SVG animation lifecycles to ensure performance remains stable during sustained high-volume simulated traffic.

    Focused on decoupling UI components from data logic to ensure that adding new threat types or device categories does not require a rewrite of the rendering engine.
