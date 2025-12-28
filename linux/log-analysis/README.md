# Web Server Log Analysis — Educational Security Lab

## Context

This lab was conducted in a controlled educational environment and focused on
foundational analysis of web server log files. The objective was to practice
core defensive security skills related to identifying suspicious patterns in
log data. This exercise was not intended to represent a full incident response
or forensic investigation.

All data analyzed was part of a learning scenario and did not originate from a
production system.

## Objective

The goal of this lab was to develop baseline log analysis skills from a
security perspective, including:
- Understanding web access log structure
- Differentiating normal traffic from anomalous behavior
- Identifying suspicious request patterns
- Analyzing the temporal distribution of unusual activity
- Applying a consistent analytical mindset to multiple log sources

## High-Level Approach

The analysis focused on understanding overall traffic behavior, identifying
requests that deviated from expected patterns and correlating frequency and
timing to highlight potentially automated or malicious activity. Emphasis was
placed on reasoning and pattern recognition rather than procedural steps or
automated detection.

## Tools

The lab relied exclusively on standard Linux text-processing utilities commonly
available in Unix-like systems. No external security platforms or specialized
forensic tools were used, reinforcing the importance of strong foundational
Linux skills in security analysis.

## Result

The analysis provided visibility into suspicious access patterns within the
logs, including abnormal request behavior and concentration of activity over
specific time periods. Applying the same methodology to a secondary log source
helped reinforce consistency in analysis and interpretation.

## Security Relevance / Impact

Basic log analysis is a core skill for entry-level defensive security roles,
including SOC analysis and security operations. Exercises like this reflect
real-world scenarios where:
- Alerts may be limited or absent
- Analysts must rely on raw log data
- Pattern recognition supports further investigation and escalation

Strong fundamentals in log analysis enable more effective use of advanced
security tools later on.

## Key Takeaways

- Web server logs are a valuable source of security insight
- Understanding baseline behavior is essential before identifying anomalies
- Simple Linux tools can effectively support security investigations
- Pattern recognition is a critical skill in defensive security
- Consistent methodology improves analysis across different data sources
