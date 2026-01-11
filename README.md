# Full Executive Report Automation

This repository contains the HTML template and related assets  
used to generate the **Full Executive Report (التقرير التنفيذي الكامل)** automatically via n8n.

## Scope:
- Single report: Comprehensive client and balance executive summary  
- HTML template rendered dynamically with live client data  
- Converted to PDF and delivered through automated n8n workflows  
- Supports Arabic (RTL) formatting and custom styling  

## Usage:
- n8n fetches the HTML template directly from this repository  
- Client data is injected dynamically at runtime  
- iLovePDF API converts the rendered HTML into a formatted PDF report  
- The final output is stored or emailed automatically  

This repository is intentionally limited to this report only.  
Any styling or structure updates should be handled through this template.
