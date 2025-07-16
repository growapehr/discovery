# Shared User Identity

## Problem Statement

Different hospital numbers in different hospitals for the same patient create fragmented health records and identity confusion across healthcare systems.

## Current State

Healthcare systems assign unique identifiers per institution or region. For health services, people have an NHS number which is supposed to be unique to each individual across the country, but even in this case Scotland uses something different called CHI (Community Health Index). When you look between different health boards, the single NHS ID number doesn't always guarantee that health records for the same individual marry up between different trusts.

## Contributing Factors

- **Technology limitations**: Legacy systems with incompatible identifier schemas
- **Organizational challenges**: Different trusts and health boards maintaining separate databases
- **Policy/regulatory barriers**: Regional variations in identity management systems
- **Financial constraints**: Cost of harmonizing identity systems across organizations

## Impact Assessment

### On Patients

- **Health outcomes**: Critical medical history lost during provider transitions
- **Experience quality**: Repeated data entry and identity verification processes
- **Financial burden**: Duplicate testing and procedures due to missing records

### On Providers

- **Workflow disruption**: Time spent reconciling patient identities across systems
- **Clinical decision-making**: Incomplete patient histories leading to suboptimal care
- **Time and resource costs**: Administrative overhead for identity management

### On Healthcare System

- **Overall efficiency**: Duplicate records and fragmented data reduce system effectiveness
- **Cost implications**: Redundant testing and administrative processes
- **Quality metrics**: Patient safety risks from incomplete medical histories

## P2P EHR Connection

**Patient-controlled, peer-to-peer health records** using Pear/Holepunch would create a single, cryptographically secure record owned by the patient and shared to their health providers. This eliminates the need for institution-specific identifiers by making the patient the sovereign owner of their complete health identity and data.

## Real-World Examples

- Patient moving between England and Scotland facing CHI/NHS number conflicts
- Emergency room unable to access critical allergy information from different trust
- Specialist receiving incomplete history due to fragmented identity systems
- Patient forced to undergo duplicate testing when switching healthcare providers

## Severity & Frequency

- **How often**: Occurs with every inter-provider or inter-region healthcare interaction
- **Severity of impact**: Medium to high - can result in medical errors, delays in care, unnecessary costs
- **Patient populations most affected**: Mobile populations, military families, university students, elderly patients requiring multiple specialists

## Related Problems

- Data fragmentation across healthcare systems
- Incomplete medical histories during care transitions
- Provider communication breakdowns
- Duplicate testing and procedures

---

_Links to user stories: Growing up health record transitions, Cross-provider care coordination_
