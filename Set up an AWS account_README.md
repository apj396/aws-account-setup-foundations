<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Set Up An AWS Account

**Project Link:** [View Project](http://learn.nextwork.org/projects/aws-account-setup)

**Author:** Adwait Joshi  
**Email:** apjadwait.joshi93@gmail.com

---

![Image](http://learn.nextwork.org/intense_indigo_vibrant_tayberry/uploads/aws-account-setup_r6s1t7u3)

---

## Introducing Today's Project!

In this project, I'm going to set up my AWS account, learn about the AWS Free Tier and configure billing alerts to avoid surprise charges.

### Key tools and concepts

The key tools I used include authenticator app to enable MFA to AWS account.
Key concepts I learnt include:-
1. Create an AWS account with root user credentials.
2. Enable billing alerts to prevent surprise charges.
3. Verify your identity.
4. Add multi-factor authentication to secure your root account.

### Challenges and wins

This project took me approximately 15 mins.

---

## Creating My AWS Account

In this step, I'm going to
1. Sign up for a new AWS account.
2. Verify your email address.
3. Create a strong root user password.

### Understanding the root user

I learned that a root user is the main account owner with full access to everything in your AWS account. It is like the master key to a building. Every AWS account has exactly one root user, and it is created during sign-up.
Strong password is important for the safety of the account.

---

## Setting Up Billing and Payment

In this step, I'm going to:
1. Choose your account plan.
2. Enter your contact information.
3. Add a payment method.

### Why AWS requires a payment method

I learned that AWS requires a payment method for two main reasons:
1. They want to make sure you’re a real person (not a bot trying to get free cloud resources).
2. If you choose to go past your Free Tier limits, they need a way to charge for that extra usage.

---

## Completing Account Activation

In this step, I'm going to:-
1. Confirm my identity.
2. Select a support plan.

### Identity verification and support plan

I verified my identity by requesting and entering verification code through sms by selecting my country code and entering mobile number.
The Basic support plan includes access to AWS documentation, forums, and AWS Trusted Advisor checks.

---

## Enabling Free Tier Alerts

In this step, I'm going to:-
1. Log in to the AWS Console.
2. Navigate to Billing Preferences.
3. Enable Free Tier usage alerts.

![Image](http://learn.nextwork.org/intense_indigo_vibrant_tayberry/uploads/aws-account-setup_j6k1l7m3)

### Why usage alerts matter

I set up usage alerts because AWS will send you an email when your usage reaches 85% of a Free Tier limit. This gives you time to stop or adjust your usage before any charges apply. It is one of the simplest ways to protect yourself from surprise bills.

---

## Securing the Account with MFA

To enable MFA, I clicked on add MFA in the Security recommendations section on the IAM Dashboard. Then I entered root-mfa as the MFA device name and selected Authenticator app as the MFA device type. Then I scanned the QR code shown from my authenticator app after clicking 'Show QR code'. Then entered the first code in the MFA code 1 field and after waiting for 30 seconds, entered the second code in the MFA code 2 field. Finally, clicked "Add MFA".
The authenticator app works by generating a new 6-digit code every 30 seconds. When you log in to AWS, you enter your password and the current code from the app. Since the code changes constantly and only exists on your phone, it is nearly impossible for an attacker to guess or steal it.

![Image](http://learn.nextwork.org/intense_indigo_vibrant_tayberry/uploads/aws-account-setup_e3f7g2h8)

---

---
