# Automated Workflows

A collection of **Microsoft Power Automate workflows** using rule-based logic, conditional processing, and structured workflows.

## Workflows

### 📧 Automated Email Draft Reply

Automatically processes incoming emails and generates draft responses based on defined rules and conditions.

### 📎 Save Email Attachments

Detects email attachments and automatically saves files to a designated location.

### 📅 Automated Schedules

Uses scheduled triggers and date/time logic to automate recurring tasks and calendar-based processes.

## Workflow Architecture

```mermaid
flowchart LR
    A["📥 Trigger"]
    B["⚙️ Power Automate"]
    C["🔎 Rules & Conditions"]
    D["🔄 Automated Processing"]
    E["📤 Output"]

    A --> B --> C --> D --> E

    style A fill:#0969da,color:#fff,stroke:#0969da
    style B fill:#8250df,color:#fff,stroke:#8250df
    style C fill:#fff8c5,stroke:#bf8700
    style D fill:#ddf4ff,stroke:#0969da
    style E fill:#1a7f37,color:#fff,stroke:#1a7f37
```

## Technology

* **Microsoft Power Automate**
* Rule-based parsing
* Conditional logic
* Automated email processing
* File and attachment management
* Scheduled workflows
