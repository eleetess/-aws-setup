# -aws-setup -Notes
# What is Amazon DynamoDB?

Amazon DynamoDB is a **fully managed, serverless NoSQL database** provided by AWS.  
It delivers **single-digit millisecond performance** at any scale and handles all the heavy lifting, including:

- **Automatic scaling** based on demand
- **Infrastructure management** (no servers to provision or maintain)
- **Backup and restore** capabilities
- **Security** with built-in encryption

DynamoDB supports **key–value** and **document** data models, and even offers **ACID transactions** for mission-critical applications.

## Key Benefits
- **Fast and consistent performance** – Low latency for both small and massive workloads.
- **Scales automatically** – Handles millions of requests per second without manual intervention.
- **Serverless** – Pay only for what you use with on-demand pricing.
- **Global reach** – Replicate data across multiple AWS Regions with *Global Tables*.
- **Highly available** – 99.999% availability SLA.

## Common Use Cases
- **Financial services** – Real-time transaction processing, fraud detection, token management.
- **Gaming** – Leaderboards, player data, in-game event tracking.
- **Streaming & media** – Metadata storage, watchlists, real-time analytics.
- **Mobile & web apps** – User profiles, session management, chat applications.
- **Multi-region apps** – Global, low-latency user experiences.

## Key Insight
> DynamoDB’s on-demand mode can **scale to zero**, meaning you only pay when your tables are used—perfect for unpredictable or bursty workloads.

# One Key Insight
- It’s surprising how DynamoDB offers true "scale-to-zero" capability in its on-demand mode—letting you pay only when your table is being used, with no cold-start delays or maintenance windows.

### 1. Create an AWS Account
1. Go to [https://aws.amazon.com/](https://aws.amazon.com/).
2. Click **Create an AWS Account**.
3. Enter your email address, password, and account name.
4. Provide payment details (credit/debit card).
5. Verify your identity (phone verification).
6. Choose a **Support Plan** (start with the free Basic plan).
7. Sign in to the **AWS Management Console**.

---

### 2. Set a Budget in AWS
1. In the AWS Management Console, search for **Budgets**.
2. Click **Create budget**.
3. Choose **Cost budget** and click **Next**.
4. Set:
   - **Period** (monthly, quarterly, yearly)
   - **Budgeted amount**
   - **Start date**
5. Add **Alerts** (e.g., email notifications at 80% and 100% of budget).
6. Review and click **Create budget**.