#### Modularity
- It's easy to stray away from a modularity scheme in a monolith architecture.
- In microarchitectures, we need to consider how interactions between microservices could pan out and take measures like building timeouts.
#### Error Tolerance
- An entire monolith program can crash if we don't catch an exception.
- Microservices crash independently, so a software can still stay somewhat operational.