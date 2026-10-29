# Sluice

Sluice is a lightweight, embeddable Java library for bounded, observable background job execution, with no broker.

## Project Status

> ⚠️ **Sluice is in active development and is _not_ production-ready.**  
> APIs, behavior, and internals may change until the first release is finalized and officially scheduled.

This repository is currently in its early build stage and maintained by a single contributor.

## Vision

Sluice aims to provide a simple in-process job engine for Java applications that need:

- bounded execution with explicit backpressure
- observable queue and worker behavior
- predictable lifecycle and shutdown semantics
- zero external broker dependency

## Planned Direction (High-Level)

Planned work is currently focused on:

1. foundations and concurrency-safe core architecture
2. bounded queue + worker execution primitives
3. retries, delays, cancellation, and lifecycle management
4. rigorous testing, stress checks, and benchmarking
5. observability and framework integration
6. release hardening, documentation, and public 1.0 delivery

## Current State

- very early project setup phase
- APIs should be considered unstable
- no compatibility guarantees yet

## Contributing

Issues and suggestions are welcome while the project is being shaped.  
If you open feedback, please assume design and APIs are still evolving.
