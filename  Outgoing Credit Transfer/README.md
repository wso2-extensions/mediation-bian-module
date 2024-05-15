# BIAN OutgoingCreditTransfer Micro Integrator Project

This repository contains the codebase for a WSO2 Micro Integrator project to implement a sample BIAN OutgoingCreditTransfer user scenario.

## Introduction

The BIAN OutgoingCreditTransfer user scenario addresses the processing of outgoing credit transfers. It refers to the movement of funds from one bank account to another, typically from the sender's account to a recipient's account, which can be within the same bank or at a different financial institution. This project aims to provide a sample solution to integrate this sequence flow.

## Sequence Diagram

![Sequence Diagram - OutgoingCreditTransfer](<Sequence Diagram OutgoingCreditTransfer.png>)

## Getting Started

To get started with this project, follow these steps:

1. Clone the project **OutgoingCreditTransfer**
2. Download WSO2 [Integration Studio](https://wso2.com/micro-integrator/#)
3. Navigate to **File** -> **Import**, select **Existing WSO2 Projects into workspace**, and click **Next**.
4. Browse the cloned **OutgoingCreditTransfer** repository and click **Open**.
5. Click **Finish**

To Run the project please follow these steps:

1. Right-click on the project
2. Select **Run As** -> **Run on Micro Integrator**

## Try Out

1. Import the [Postman Collection](https://elements.getpostman.com/redirect?entityId=899173-8ea5decb-c6c1-4051-bdeb-30f712de015a&entityType=collection)
2. Invoke /PaymentInitiation POST call to test the complete flow with the inbuilt sequences. 
