# Research notes

## Research question

What makes post-quantum cryptography difficult to adopt in existing systems, even when suitable algorithms are available?

## Approach

The paper uses a literature review and a comparison of algorithm features. It considers security, performance, implementation difficulty, and the effect on existing infrastructure.

It also looks at organizational concerns such as training, budgets, older equipment, and the ability to change algorithms in the future.

## Main findings

**Compatibility:** Existing applications, certificates, and devices may need changes to support different key and message sizes.

**Implementation:** A secure algorithm still needs careful implementation. Timing, power use, and other side channels can create weaknesses.

**Planning:** A cryptographic inventory helps an organization find affected systems and decide what to update first.

**Testing:** Pilot deployments can reveal performance and integration problems before wider use.

## Proposed migration steps

1. Find systems and data that depend on cryptography.
2. Prioritize them by risk and how long the data must stay protected.
3. Test selected approaches in a small pilot.
4. Plan hybrid deployments where appropriate.
5. Monitor the deployment and keep it up to date.

## Limits

This is a literature-based research project. The report's size and performance comparisons are not measurements produced by code in this repository. The original names and parameter sets need to be checked against the chosen library and specification before implementation.

The repository does not claim to be an up-to-date list of standards or deployment guidance.

## Next steps

Select a maintained library, document the parameter sets and test environment, compare key sizes and operation times, and publish repeatable tests with the implementation.
