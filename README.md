# API Security Risk Analysis

## Overview

This project focuses on analyzing the security posture of publicly accessible APIs using Postman. The objective was to identify common API security risks, evaluate authentication and authorization mechanisms, analyze data exposure issues, and provide practical security recommendations.

## Tools Used

* Postman
* Public/Test APIs
* Browser Developer Tools
* Google Docs / MS Word / PDF

## Skills Demonstrated

* API Security Analysis
* Authentication Assessment
* Authorization Testing
* Data Exposure Identification
* Risk Classification
* Security Documentation
* Security Reporting

## Objective

The goal of this assessment was to evaluate API endpoints for potential security weaknesses and determine whether sensitive information could be exposed through insecure API configurations.

## Key Features

### Authentication Analysis

* Tested API authentication mechanisms
* Reviewed token usage and access controls
* Verified endpoint accessibility

### Authorization Assessment

* Checked whether users could access resources they should not be able to access
* Evaluated access control implementation
* Identified potential authorization weaknesses

### Data Exposure Analysis

* Inspected API responses for unnecessary data disclosure
* Reviewed sensitive information returned by endpoints
* Evaluated data minimization practices

### Endpoint Security Review

* Analyzed API request and response behavior
* Tested API parameters and inputs
* Reviewed API error handling mechanisms

## Methodology / Assessment Steps

### Step 1: Identify API Endpoints

Public API endpoints were collected and documented for testing.

### Step 2: Import API into Postman

API requests were created and organized using Postman collections.

### Step 3: Analyze Request Structure

Reviewed:

* HTTP methods (GET, POST, PUT, DELETE)
* Headers
* Parameters
* Request body data

### Step 4: Test Authentication

Verified:

* API key requirements
* Authentication tokens
* Unauthorized access behavior

### Step 5: Review API Responses

Checked for:

* Sensitive data exposure
* Excessive information disclosure
* Error message leakage

### Step 6: Assess Authorization Controls

Tested whether users could access data or resources beyond their intended permissions.

### Step 7: Classify Risks

Findings were categorized as:

* Low Risk
* Medium Risk
* High Risk

### Step 8: Document Findings

Prepared a professional security report including:

* Finding description
* Risk rating
* Business impact
* Remediation recommendations

## Sample Findings

### Finding 1: Excessive Data Exposure

Risk: Medium

Impact:
The API returns more information than required, potentially exposing sensitive data.

Recommendation:
Return only necessary data fields and implement proper data filtering.

### Finding 2: Missing Authentication

Risk: High

Impact:
Unauthorized users may access protected API resources.

Recommendation:
Implement strong authentication controls for sensitive endpoints.

### Finding 3: Verbose Error Messages

Risk: Low

Impact:
Detailed error messages may reveal internal system information.

Recommendation:
Use generic error responses and avoid exposing backend details.

## Risk Classification Matrix

### Low Risk

Minor security weakness with limited impact.

### Medium Risk

Security issue that may contribute to unauthorized access or information disclosure.

### High Risk

Critical weakness that could result in significant data exposure or unauthorized access.

## Deliverables

* API Security Risk Analysis Report
* Postman Collection
* API Request and Response Evidence
* Risk Assessment Matrix
* Security Recommendations
* Professional Documentation

## Repository Contents

* /Postman-Collection
* /Report
* /Screenshots
* /Findings
* /Recommendations
* README.md

## Disclaimer

This assessment was conducted using publicly available or authorized APIs for educational and security awareness purposes only. No unauthorized access, exploitation, or disruptive testing was performed.
