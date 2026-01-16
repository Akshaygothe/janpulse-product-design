# JanPulse - System Architecture
Version: v0.1

Last updated: 16 Jan 2026

JanPulse is designed as a system that converts collective intent into accountable action. Its architecture is not centred on features or technology, but on how intent, money, truth, and execution move through the system without losing integrity.

The primary goal of this architecture is to ensure that public priorities cannot be distorted, hidden, or acted upon without visibility. Every component exists to make responsibility explicit and traceable.

## Architecture Overview
<img width="2880" height="2048" alt="image" src="https://github.com/user-attachments/assets/7dfafea5-9c42-4251-9152-34684023d646" />
System architecture showing the flow of intent, money, truth, and action.

The diagram illustrates JanPulse as a closed accountability loop where intent, money, and action flow through clearly defined layers. Each layer has a single responsibility and no layer can override another.

## Core Components
### Contributor (User)
The contributor is the source of intent. Contributors create wishes and attach money to them, transforming personal concern into a measurable signal. The system does not assume trust in the contributor; it only records their intent and contribution.

### Wish Engine
The Wish Engine is responsible for meaning, not authority. It normalizes incoming wishes, merges duplicates, assigns identifiers, and tracks location and totals. It structures intent but does not decide truth or priority. The Wish Engine can suggest structure and interpretation, but the Public Ledger determines what exists.

### Payment Rail (UPI + Gateway)
The payment rail moves money independently of the platform’s logic. It transfers funds from contributors to the JanPulse account and sends confirmation events. JanPulse cannot alter or intercept this flow, ensuring financial neutrality.

### Public Ledger (Single Source of Truth)
The Public Ledger is the backbone of the system. No wish, payment, status update, or proof is considered real unless it exists here. All totals, execution states, and records are derived from the ledger, making it the only authoritative source of truth. No system component, including the Wish Engine or JanPulse Organization, can rewrite or reinterpret records once committed to the ledger.

### JanPulse Organization
The JanPulse Organization is the sole execution body. It receives funded wishes from the ledger, allocates resources, executes work, and uploads progress and proof back into the system. Execution responsibility is centralized to avoid diffused accountability.

## Explicit System Constraints
* JanPulse cannot move, redirect, or modify money once it enters the payment rail
* JanPulse cannot edit or erase past records from the Public Ledger
* JanPulse cannot execute work without publicly recording proof and status

## The Accountability Loop
JanPulse operates as a closed loop:

* A wish enters the system as intent.
* Money validates that intent.
* The ledger records it.
* Execution responds to it.
* Proof closes the loop.
  
Contributors gain visibility into every stage, from funding to execution, without needing to trust individuals or institutions. Trust emerges from transparency, not authority. If execution stalls or fails, the system exposes failure explicitly rather than masking it with activity or partial progress.
