# LoanFlow Prototype

A self-contained, browser-based FinTech demo for:
- Loan application eligibility and risk checks
- Rule-based transaction fraud detection
- Application and transaction review queues
- Simulated DevOps CI/CD pipeline

## Run it
1. Download and unzip `LoanFlow_Prototype.zip`.
2. Open `index.html` in Chrome, Edge, Safari, or Firefox.
3. No installation, internet connection, or account is required.

## Demo walkthrough
1. Overview: explain the dashboard and fictional sample metrics.
2. Loan applications: click **Load review case**, then **Assess application**. Point out the reasons that triggered human review.
3. Fraud detection: click **Load suspicious example**, then **Analyze transaction**. Explain the risk score and signals.
4. DevOps pipeline: click **Run pipeline** and show each simulated stage. The security gate may occasionally fail to demonstrate a safe blocked deployment; rerun to try again.

## Important limitations
- This is an educational front-end prototype. The data is synthetic and stored only in the current browser session.
- The risk rules and thresholds are illustrative, not validated credit or fraud models.
- The CI/CD pipeline is simulated in JavaScript; it does not contact GitHub, build a real Docker image, scan dependencies, or deploy to a cloud.
- It does not connect to a bank, payment network, credit bureau, identity verification service, or real customer data.
- Do not enter real personal or financial information.
- In production, decisions need approved lending policy, secure backend services, audit logs, privacy safeguards, fairness testing, and authorized human oversight.
