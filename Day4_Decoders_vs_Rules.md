# Day 4: Wazuh Decoders vs Rules

## 2-Sentence Summary

Wazuh decoders extract and normalize information from raw log data into structured fields. Wazuh rules analyze those decoded fields and determine whether an alert should be generated.

## Full AI Response (for reference)

Wazuh decoders are responsible for reading raw log messages and extracting useful information such as usernames, IP addresses, event IDs, and timestamps. They convert different log formats into a common structured format that Wazuh can understand.

Wazuh rules operate after decoding. Rules inspect the decoded fields, compare them against predefined conditions, and decide whether an event should generate an alert and what severity level it should have.

In simple terms, decoders translate logs into a common language, while rules decide whether the translated information is important enough to trigger an alert.

## Date

2026-06-17
