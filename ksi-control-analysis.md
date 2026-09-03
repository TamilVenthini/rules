# KSI–Control Analysis

## Purpose

This document analyzes the relationship between FedRAMP Key Security Indicators (KSIs)
and Rev5 controls.

The goal is to identify:
- which controls are shared by multiple KSIs
- which KSIs depend on the same controls
- which controls have the highest overlap
- what this means for implementation and evidence

## Source

- `fedramp-consolidated-rules.json`
- `schemas/fedramp-consolidated-rules.schema.json`

## Initial Observation

The KSI-to-control mapping shows that some controls are referenced by multiple KSIs.
These shared controls are potential high-impact areas because satisfying one control
may support evidence or implementation for several KSIs.
