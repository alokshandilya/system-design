# System Design

## Table of Contents

1. [What is System Design?](#what-is-system-design)
2. [Why is System Design so important?](#why-is-system-design-so-important)
3. [Computer Architecture](#computer-architecture) _(Disk, Memory/RAM, CPU, Cache)_
4. [Scalability](#scalability) _(Horizontal, Vertical Scaling, Moore's Law)_

## What is System Design?

- process of defining the architecture, modules, interfaces, and data for a system that satisfies specific requirements.
- meets the needs of the business or organization through coherent and efficient systems.
- requires a systematic approach to building and engineering systems.
  - a good system design requires us to think about everything, from infrastructure all the way down to the data and how it's stored.

## Why is System Design so important?

- System design helps us define a solution that meets the business requirements.
- It is one of the earliest decisions we can make when building a system.
  - Often it is essential to think from a high level as these decisions are very difficult to correct later.
- It also makes it easier to reason about and manage architectural changes as the system evolves.

## Computer Architecture

- **Disk** - _long term storage, slow, cheap, large capacity, non-volatile (data is not lost when power is lost)_
- **Memory/RAM** - _short term storage, fast, expensive, small capacity, volatile (data is lost when power is lost)_
- **CPU** - _processes data, fast, expensive, **read/write from disk/memory, executes instructions**_
- **Cache** - _fast, expensive, even smaller capacity, **stores frequently accessed data, closer to the CPU than memory**_

## Scalability

- **Horizontal Scaling** - _increasing the number of machines_
  - **easier to scale**
  - **more fault tolerant**
- **Vertical Scaling** - _increasing the capacity of a single machine (CPU, memory, disk space etc.)_
  - **limited by the capacity of a single machine**
  - **less fault tolerant**

> The number of transistors on a microchip doubles every two years, though the cost of computers is halved. But this can be reaching its limits due to physical constraints in semiconductor manufacturing.
>
> — **Moore's Law**
