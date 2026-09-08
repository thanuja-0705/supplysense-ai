# System Architecture

## High-Level Flow

[ERP / POS / E-commerce / Spreadsheets / Supplier Data]
                         |
                         v
              [Data & Trust Layer]
          Validation • Normalization
          Operational Store • Audit Log
                         |
                         v
                [AI Intelligence]
       Forecasting • Anomaly Detection
       RAG • Risk Scoring • Scenarios
                         |
                         v
             [Decision Orchestrator]
        Prioritization • Policy Checks
                         |
                         v
                 [AI Agents]
       Draft PO • Supplier Query • Escalation
                         |
                         v
                [Human Approval]
                 Approve / Reject
                         |
                         v
                    [Execution]
                         |
                         v
             [Monitoring & Feedback]
