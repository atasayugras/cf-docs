# Introduction

CyberFabric is an enterprise-grade framework for building multi-tenant Software-as-a-Service applications. Built with Rust, it provides a modular runtime system designed for reliability, performance, and cloud-native deployment.

## What is CyberFabric?

CyberFabric gives teams a structured foundation for XaaS development - handling cross-cutting concerns so you can focus on business logic:

- **ModKit** - a composable module system that manages the full service lifecycle
- **OData support** - standardized query and data access layer
- **Built-in security** - authentication and authorization primitives out of the box
- **gRPC + REST** - flexible transport options for every integration need

## Core Concepts

| Concept | Description |
|---------|-------------|
| Module  | The basic unit of functionality in CyberFabric |
| ModKit  | The SDK and macro system for building modules |
| Runtime | The lifecycle manager that initializes and coordinates modules |
| Tenant  | An isolated unit of multi-tenant data and configuration |

## Next Steps

- [Get Started](./getting-started.md) - Install the CLI and scaffold your first project
- [Architecture](./architecture.md) - Understand the runtime lifecycle
- [Core Concepts](./core/modules.md) - Deep dive into the module system
