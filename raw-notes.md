## Scaling up Test-Time Compute with Latent Reasoning

- **What problem**: This paper proposes a new test-time scaling paradigm that increases reasoning capacity by iterating in latent space, rather than generating more reasoning tokens as in CoT-style methods.

- **Core idea**: Use a recurrent transformer that iterates the same block multiple times in latent space. At a high level, the method decomposes a standard transformer into embedding, recurrent core, and decoding stages, with the core block repeatedly applied. Beyond this structural simplicity, the main contribution lies in framing recurrent depth as a scalable test-time compute mechanism and demonstrating its effectiveness for reasoning.

