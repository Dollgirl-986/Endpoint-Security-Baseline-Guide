# Endpoint Security Baseline Guide for a Real Estate Agency

## Project Overview
This project demonstrates a basic endpoint security monitoring approach for a real estate agency using Splunk Cloud in a safe lab environment.

## Tool Used
- Splunk Cloud Platform

## Detection Rules

### 1. Multiple Failed Login Attempts
Detects repeated failed login attempts.

### 2. Malware Detection
Identifies a sample malware detection event.

### 3. Suspicious PowerShell Activity
Identifies suspicious PowerShell activity.

### 4. Unusual Login Activity
Highlights unusual login activity such as an unexpected login time or location.

### 5. Unauthorized Software Installation
Identifies sample unauthorized software installation activity.

## Incident Response Steps

- Failed Login: Verify the user and investigate the source.
- Malware: Isolate the affected endpoint and perform a security scan.
- PowerShell: Investigate the process and verify whether the activity is authorized.
- Unusual Login: Verify the login with the user and secure the account if unauthorized.
- Unauthorized Software: Verify whether the software is approved and remove it if unauthorized.

## Lab Note
All events used in this demonstration are sample/lab events created for learning purposes. No production or third-party systems were monitored.

## Evidence
Screenshots of the Splunk searches and sample detection results are included with this project.
