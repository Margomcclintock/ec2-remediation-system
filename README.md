# EC2 Monitoring and Remediation System \- ServiceNow Implementation

## Overview

**Company Context:** You're a ServiceNow Administrator and Jr Developer at Netflix, where reliable streaming infrastructure is critical for delivering content to over 260 million subscribers worldwide. AWS EC2 instances power Netflix's content delivery network, recommendation engines, and streaming services across multiple AWS regions.

**Your Role:** As a ServiceNow Admin and Jr Developer at Netflix, you've been tasked with building a semi-automated incident response system that helps the DevOps engineer team quickly remediate failing AWS EC2 instances that could impact streaming quality for millions of viewers.

**Why This Matters:** Last week, a critical AWS EC2 instance failure in the US-East region caused buffering issues for viewers streaming popular series during peak hours. The incident went undetected for 45 minutes because the existing monitoring system wasn't integrated with ServiceNow, and DevOps engineers had to manually search through documentation to find remediation procedures. This resulted in viewer complaints, trending social media criticism, and potential subscriber churn.

**The Business Problem:** Netflix's DevOps team needs a centralized system that automatically creates incidents when EC2 instances fail, provides AI-powered knowledge retrieval for remediation guidance, sends remediation guidance through Slack notifications, and allows engineers to trigger AWS remediation directly from ServiceNow during critical incidents.
