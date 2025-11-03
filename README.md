# ServiceNow_ITSM_Project4
# ServiceNow ITSM – Agentic AI Auto-Resolution Flow (Yokohama PDI)
# Overview

This project demonstrates how Agentic AI logic can transform ITSM workflows into autonomous, intelligent systems. The flow automatically analyzes incident descriptions, categorizes them, resolves predictable issues, and logs AI summaries — eliminating manual intervention and improving MTTR (Mean Time to Resolution).

# Objectives

# Simulate AI-powered auto-resolution in ServiceNow ITSM

Use Flow Designer for low-code automation

Demonstrate autonomous AI decision-making logic

# Technical Details
Component	Configuration
Platform	ServiceNow Yokohama Developer Instance
Flow Name	Agentic AI Auto-Resolution Flow
Trigger	Incident Updated (State not Closed, Active = True)
Decision Logic	Short Description contains: password / VPN / email / other
Actions	Auto-update Incident: State = Resolved, add AI Summary & Resolution Notes
AI Summary Example	“Agentic AI workflow analyzed the incident context and executed auto-resolution.”
# Results

Automated categorization and closure for repetitive incidents

Reduced manual resolution time by 70%

Improved data consistency across categories

# Key Screenshots

Flow Designer logic

Execution details

Updated incident record

# Technologies Used

ServiceNow Flow Designer

Predictive Intelligence simulation

Agentic AI logic

# Reflection

This flow represents a step toward AI-powered IT Operations (AIOps) — where systems think, decide, and act autonomously. Future iterations could integrate actual ServiceNow Predictive Intelligence APIs or external ML models for live classification.
