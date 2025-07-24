# PennyWise Setup for Linux

This guide will walk you through setting up the Arctic Fox project on a Linux environment.

## Prerequisites

- **Firebase Blaze Plan**: To use this project, you'll need to enable the Firebase "Blaze" (pay-as-you-go) plan. This requires adding a billing account to your Firebase project, for which a credit card is mandatory.
> **Note:** I have been using this project for tracking my expenses for the last 2 years, and I have rarely crossed the free tier limits. On a few occasions, I was billed ₹1-2 when I was testing Firestore with a high volume of requests. However, you can set up a billing budget to receive reminder emails, which helps ensure you stay within your desired spending limits.

## Minimum Technical Requirements

Before you begin, please ensure you have the following minimum versions installed on your system:

- **Node.js:** `v20.0.0` or higher
- **npm:** `v10.0.0` or higher

You can check your installed versions by running the following commands in your terminal:

```bash
node -v
npm -v
```

## Getting Started


### Firebase Setup

1.  **Navigate to the Firebase Console:**
    Open your web browser and go to [https://console.firebase.google.com/](https://console.firebase.google.com/).

2.  **Create a New Firebase Project:**
    - Click on **"Add project"** to start the setup process.
    - Enter a unique name for your project (e.g., `pennywise-2a`).
    - Uncheck **"Enable Google Analytics for this project"** and click **"Create project"**.

3.  **Access Your Project Dashboard:**
    Once the project is created, you will be redirected to the project's dashboard.
    ![Firebase Dashboard](pics/ss1.png)

4.  **Upgrade to the Blaze Plan:**
    - By default, your project will be on the "Spark" plan. To enable all features required for PennyWise, you must upgrade to the "Blaze" (pay-as-you-go) plan.
    - In the bottom-left corner of the navigation menu, click on the **"Upgrade"** button.
    - Select the **Blaze plan** and follow the prompts to create a Cloud Billing account. This will require a credit card for verification, which may involve a small transaction (e.g., 2 rupees).

5.  **Set a Billing Budget:**
    - After setting up your billing account, you will be prompted to create a budget. It is highly recommended to set a budget to prevent unexpected charges.
    - For example, you can set a monthly budget of ₹15.
    - Once your budget is set, link the Cloud Billing account to your project.
    ![Link Cloud Billing Account](pics/ss2.png)

      