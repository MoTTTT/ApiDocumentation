# Onboarding Process

```text
Phase I - Provide API Consumer Portal for API consumers (replaces email).
This should overlap with the following business processes:
- Scope determination (i.e. which supported use-cases are required in the CR),
- Commercial Agreements - a process operated by Business, 
- Network Access Agreement - also a process operated by Business.

Phase II - Unit Testing: API consumer accesses to the simulator environment
- The intention of this phase is to allow the consumer to exercise the API, observe typical behavior, and unit test code, without an assigned ETE environment.
- Per-consumer prerequisites: None. (There is a once-off configuration required, and the platform needs to stay updated with the prod releases)
- Uses a generic profile. All API consumers use the same set of username:password.
- No test data requirement.
- Sign off on use-cases in scope.

Phase III - End-to-End Testing: Assign onboarding CR to Quarterly Releases.
- Per-consumer prerequisites: Test data creation (SQA currently, invest in automation)
- Per-consumer prerequisites: Dedicated profile creation. (Ops currently, invest in automation)
- Sign off on use-cases in scope.

Phase IV - Production
- Per-consumer prerequisites: Prod profile creation
- Verification of Deal-sheet and SIM inventory (ICCIDS)
- Verification of use-cases in scope.
- Completion signoff
```