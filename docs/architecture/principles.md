1. Core must remain framework-independent.

2. Architecture decisions must be documented.

3. Approved contracts must not be changed silently.

4. Immutable domain objects are never mutated to represent recovery.

5. Recovery creates new actions/plans where appropriate.

6. Event Store is the source of truth.

7. AgentState is a materialized state.

8. External integrations belong outside Core.

9. Every major feature requires tests.

10. Every contract change requires documentation.

11. One active implementation task at a time.

12. Completed work must have a checkpoint.

13. Breaking changes require explicit contract version changes.

14. No framework-specific dependency may leak into Core.

15. Deterministic execution should be preferred over LLM reasoning
   whenever the behavior can be expressed deterministically.