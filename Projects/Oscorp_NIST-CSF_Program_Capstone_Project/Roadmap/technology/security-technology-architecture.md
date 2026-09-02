# Security Technology Architecture

  ------------------------------------------------------------------------------------
  Capability        Proposed Solution Related Risks     Assessment
  ----------------- ----------------- ----------------- ------------------------------
  IAM / MFA /       Microsoft Entra   R-007, R-008      Appropriate if configured and
  Conditional       ID                                  governed correctly
  Access                                                

  Endpoint / EDR    Microsoft         R-012             Strong fit for the assessed
                    Defender                            endpoint gap

  Device Management Microsoft Intune  R-007, R-010,     Supports configuration/device
                                      R-012             governance

  SIEM              Microsoft         R-011, R-013,     Appropriate, but requires
                    Sentinel          R-014             logging architecture, analysts
                                                        and response processes

  DLP / Data        Microsoft Purview R-009             Strong fit in a
  Governance                                            Microsoft-centric environment,
                                                        subject to
                                                        classification/configuration

  Secrets / Keys    Azure Key Vault   R-009, R-010      Appropriate for applicable
                                                        key/secrets use cases

  CSPM              Defender for      R-003, R-010,     Appropriate for Azure/cloud
                    Cloud             R-011             workloads

  GRC               Drata             R-001, R-002 +    Potential strong fit; requires
                                      evidence          evaluation and quote

  Backup            Azure Backup +    R-006, R-015      Appropriate subject to
                    Existing DR                         workload RTO/RPO

  IR / Forensics    Internal Team +   R-013, R-014      Practical alternative to
                    Specialist                          building full internal
                    Retainer                            forensics initially
  ------------------------------------------------------------------------------------

## Control Effectiveness

Technology does not equal compliance. Sentinel, for example, still
requires logging requirements, detection rules, analysts, escalation
procedures, incident-response processes, testing and evidence.

Prefer consolidation where a platform meets the requirement, but do not
retain a product solely for vendor consistency if it cannot meet
Oscorp's risk/control needs.
