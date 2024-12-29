<p align="center">
<img src="https://i.imgur.com/ygYqvUA.jpeg/800x300" height="40%" width="60%" alt="Jira SLA"/>
</p>

# Creating an SLA in Jira

## Prerequisites and Installation

This tutorial outlines the prerequisites and installation steps for configuring an SLA (Service Level Agreement) in **Jira Service Management**.


## Environments and Technologies Used
-  **Jira Service Management Cloud**
-  **Custom Workflows**
-  **JQL (Jira Query Language)**


## Operating Systems Used
-  **Windows 11**

## List of Prerequisites
-  **A Jira Service Management project**
-  **Admin access to Jira**
-  **Defined SLA goals (response and resolution times)**
-  **Understanding of Jira workflows and JQL**

## Installation Steps

### Step 1: Access SLA Configuration
1. Log in to your Jira account.
2. Navigate to your Service Management project.
3. Go to **Project Settings > SLAs**.
4. Click **SLAs**.
&nbsp;

![Add SLA Rule](https://i.imgur.com/jSBuMJR.png/600x300)
![Configure SLA Goals](https://i.imgur.com/ZwNJfYi.png/600x300)
![Configure SLA Goals](https://i.imgur.com/arfZl9V.png/600x300)

### Step 2: Create a New SLA
1. Create a **Name** for our SLA  `High Priority SLA` .
2. Define time to first response.
3. Set time target to 30 minutes.
4. Set the start and stop conditions based on the workflow.
&nbsp;
![New SLA Name](https://i.imgur.com/BCVXZdk.png/600x300)
![New SLA Page](https://i.imgur.com/MBjn9u1.png/600x300)
![Add Rules](https://i.imgur.com/6VAoNgt.png/600x300)


   

### Step 4: Choose SLA Format Display
1. Choose a format for hover states of this SLA to display. The format is effective on both issue and queue view.

- **Due Date Centric:** Displays the exact due date and time (e.g., `Today 06:30 AM`, `Feb 24 11:00 AM`).
- **Time Centric:** Displays the remaining time for the SLA (e.g., `7H 59M`, `-20H 46M`, `400H`).
2. Click **Save**
&nbsp;

![Working Hours](https://i.imgur.com/UhE9no6.png/600x300)


>You’ve now configured an SLA in Jira! For more details, visit the [Atlassian Documentation](https://support.atlassian.com/jira-service-management-cloud/docs/configure-slas/).


## FAQ
**Q: Can I create multiple SLAs for one project?**  
A: Yes, Jira allows you to create multiple SLAs with unique goals.

**Q: How do I handle SLA breaches?**  
A: Use Jira automation to notify team members or escalate tickets.

---

## Conclusion
🎉 You’ve successfully set up SLAs in Jira Service Management to monitor and improve service performance! 🎉

