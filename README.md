# AWS Billing Alarm Project

## 📌 Overview
The **AWS Billing Alarm Project** demonstrates how to monitor and control AWS cloud spending by setting up three distinct billing alarms at **$5**, **$25**, and **$100**. These alarms help track estimated charges, prevent unexpected cost overruns, and ensure better cost management for cloud resources.

---

## 🎯 Objectives
- Create a billing alarm for **$5**  
- Create a billing alarm for **$25**  
- Create a billing alarm for **$100**  

---

## 🛠️ AWS Services Used
- **Amazon CloudWatch** → To create billing alarms and monitor usage costs.  
- **AWS Billing and Cost Management** → Provides estimated charge data.  
- **Amazon SNS (Simple Notification Service)** → Sends email/SMS alerts when thresholds are exceeded.  

---

## 🚀 Steps to Implement
1. **Enable Billing Alerts** in the AWS Billing Preferences.  
2. **Create an SNS Topic** and subscribe with your email to receive notifications.  
3. **Set up three CloudWatch Alarms** at thresholds of **$5, $25, and $100**.  
4. Verify alarms under **CloudWatch → Alarms** and test notifications.  

---

## ✅ Deliverables
- Billing Alarms:  
  - `BillingAlarm5USD`  
  - `BillingAlarm25USD`  
  - `BillingAlarm100USD`  
- SNS Topic for notifications (`BillingAlerts`)  
- Email notifications confirming alarms when limits are crossed.  

---

## 📖 Reference
- [AWS Documentation: Create a Billing Alarm](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/monitor_estimated_charges_with_cloudwatch.html)

---

## ✨ Outcome
By implementing this project, users gain hands-on experience with AWS **CloudWatch Alarms**, **SNS notifications**, and **Billing monitoring**, enabling proactive cloud cost management.
