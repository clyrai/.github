# clyrai  – Engineering Trust in a World of AI

<div align="center">
  <img width="618" alt="clyrai - Engineering Trustworthy AI Infrastructure" src="https://github.com/user-attachments/assets/dbbf5a4f-7b0b-4f43-9b37-ef77dc761ff1" /> 
  <h3>Pioneering Secure, Resilient, and Trustworthy AI Infrastructure</h3>
  <img width="400" alt="Pixelcut Export Example" src="https://raw.githubusercontent.com/clyrai/.github/refs/heads/main/pixelcut-export-2.png" />
</div>

## About clyrai

**clyrai**  is at the vanguard of AI security, engineering the essential frameworks, tools, and models that empower organizations to build and deploy artificial intelligence they can fundamentally trust. Our mission is to ensure that as AI's power grows, its potential is unlocked safely, with uncompromising security, reliability, and alignment to human values.

The evolution to **clyrai** signifies our ambitious, long-term commitment to defining the future of AI + security, building upon the strong foundation and community established as TBH.AI.

### Our Core Focus

*   **AI Security Frameworks**: Architecting end-to-end security for complex, multi-agent AI ecosystems.
*   **Secure LLM Infrastructure**: Delivering hardened tools and protocols for deploying large language models in mission-critical environments.
*   **Trustworthy AI Research**: Pushing the frontier in AI alignment, safety, and operational security to solve tomorrow's challenges today.

## Our Projects

### [SecureAgents](https://github.com/tbh-ai/SecureAgents)

**SecureAgents** is our flagship open-source framework for building provably secure and trustworthy multi-agent systems. It provides a comprehensive, zero-trust security architecture designed to meet the unique threats of distributed, autonomous AI.

**Key Features:**
*   **Robust Hijacking Defense**: Protects agents from unauthorized takeover and malicious control.
*   **Ironclad Data Security**: Prevents data leakage with encrypted, policy-controlled communication channels.
*   **Secure Inter-Agent Communication**: Guarantees authenticity and integrity for all agent interactions.
*   **Precision Access Control**: Enforces fine-grained permissions for operations and data access.
*   **Comprehensive Auditing**: Delivers complete visibility with immutable logs for monitoring and forensics.

```python
from tbh_secure_agents import Expert, Operation, Squad
import os

# Ensure output directory exists
os.makedirs("output", exist_ok=True)

# Define an expert with a specific role and security context
content_strategist = Expert(
    specialty="AI Content Strategist",
    objective="Produce insightful and engaging technical content on AI security.",
    background="Expert in translating complex security concepts into clear, compelling narratives.",
    security_profile="sandboxed" # Isolate agent with minimal permissions
)

# Define a secure operation with a clear destination
blog_post_operation = Operation(
    instructions="Write a concise blog post analyzing the top 3 security risks in multi-agent systems.",
    output_format="A well-structured markdown article with a title, introduction, key points, and a forward-looking conclusion.",
    expert=content_strategist,
    result_destination="output/secure_agents_blog.md" # All output is sandboxed to this file
)

# Deploy the operation securely
result = blog_post_operation.deploy()
```

### [AI Security Toolkit](https://github.com/tbh-ai/ai-security-toolkit)

A battle-tested arsenal of tools for rigorously evaluating and fortifying AI systems against emerging threats. The toolkit includes:
*   LLM Vulnerability Scanners
*   Advanced Prompt Injection Detection
*   Data Poisoning and Adulteration Analysis
*   Model Backdoor Detection and Mitigation
*   Automated Red Teaming and Threat Simulation

## Research and Publications

Our research continuously advances the state of the art in AI security. Recent highlights include:
*   **A Zero-Trust Architecture for Enterprise AI**: A definitive implementation blueprint for deploying AI in regulated industries.
*   **Design Patterns for Secure Multi-Agent Systems**: Proven architectural patterns for building resilient, distributed AI.
*   **LLM Security Benchmarks**: Standardized evaluation protocols for assessing large language model security and robustness.

## Getting Started

Begin your journey with trustworthy AI:
1.  Dive into the **[SecureAgents repository](https://github.com/tbh-ai/SecureAgents)**.
2.  Explore our comprehensive **[documentation](https://tbh-ai.github.io/SecureAgents/)**.
3.  Experiment with our collection of **[examples](https://github.com/tbh-ai/SecureAgents/tree/main/examples)**.

## Join Our Mission

We are building a community dedicated to solving the most critical challenges in AI security. To contribute:
1.  Review our **[contribution guidelines](https://github.com/tbh-ai/SecureAgents/blob/main/CONTRIBUTING.md)**.
2.  Find issues tagged `good first issue` or `help wanted` to get started.
3.  Engage with our developers and community in discussions.

## Connect With Us

*   **Website**: [https://tbh.ai](https://tbh.ai)
*   **Email**: [saish.shinde.jb@gmail.com](mailto:saish.shinde.jb@gmail.com)
*   **GitHub**: [https://github.com/tbh-ai](https://github.com/tbh-ai)

## License

Our open-source projects are released under the **Apache 2.0 License**. Please refer to individual repositories for specific licensing details.



