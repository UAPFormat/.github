# UAPF | Unified Algorithmic Process Format

> Open standard for machine-executable enterprise processes.

Welcome to the GitHub organization for **UAPF (Unified Algorithmic Process Format)** — an open, machine-readable standard for expressing workflows, decision logic, case management, agent roles, and integration metadata in a single portable package.

UAPF is designed as the **algorithmization layer** for AI-driven enterprises:

- Reuses existing ISO/OMG standards (BPMN, DMN, CMMN).
- Adds agent-native concepts (roles, capabilities, MCP tools, A2A messaging).
- Produces version-controlled, machine-executable `.uapf` packages.

---

## Repository map

**Core specification**

- [`UAPF-spec`](https://github.com/UAPFormat/UAPF-spec)  
  Authoritative specification text and JSON Schemas for UAPF.

**Language SDKs**

- [`uapf-python`](https://github.com/UAPFormat/uapf-python)  
  Official Python parser & validator for `.uapf` packages.
- [`uapf-typescript`](https://github.com/UAPFormat/uapf-typescript)  
  Official TypeScript/Node parser & validator.

**Examples & quickstarts**

- [`uapf-examples`](https://github.com/UAPFormat/uapf-examples)  
  Canonical `.uapf` example packages for multiple industries (gov, RUP, etc.).
- [`uapf-quickstarts`](https://github.com/UAPFormat/uapf-quickstarts)  
  Minimal “hello UAPF” templates and boilerplate projects.

**Quality & tooling**

- [`uapf-conformance`](https://github.com/UAPFormat/uapf-conformance)  
  Conformance tests / fixtures for UAPF implementations.
- [`uapf-viewer`](https://github.com/UAPFormat/uapf-viewer)  
  Web UI playground for uploading and inspecting `.uapf` packages.

**Execution & MCP integration**

- [`uapf-engine`](https://github.com/UAPFormat/uapf-engine)  
  Reference execution engine for UAPF packages (HTTP API).
- [`uapf-mcp`](https://github.com/UAPFormat/uapf-mcp)  
  Reference MCP server exposing `uapf-engine` as Model Context Protocol tools.

> **Status**  
> UAPF is currently in **Draft / v0.9** status. The specification and schemas may change in minor, backwards-aware ways prior to v1.0.

---

## Getting started

1. **Read the spec**  
   Start with [`UAPF-spec`](https://github.com/UAPFormat/UAPF-spec) to understand the package structure, schemas, and design principles.

2. **Explore examples**  
   Browse [`uapf-examples`](https://github.com/UAPFormat/uapf-examples) to see complete `.uapf` packages for real-world scenarios.

3. **Use a parser**  
   - Python: [`uapf-python`](https://github.com/UAPFormat/uapf-python)  
   - TypeScript/Node: [`uapf-typescript`](https://github.com/UAPFormat/uapf-typescript)

4. **Try the viewer**  
   Use [`uapf-viewer`](https://github.com/UAPFormat/uapf-viewer) to upload and inspect your own `.uapf` files.

---

## Contributing

Issues, discussions, and pull requests are very welcome:

- Propose schema changes or clarifications in **UAPF-spec**.
- Add new examples or industry patterns in **uapf-examples**.
- Improve SDKs and tooling in **uapf-python / uapf-typescript / uapf-viewer**.

Standardization direction is coordinated under the **Algomation / UAPF working group**.

---

## License

All UAPF repositories in this organization are released under the **MIT License**, unless stated otherwise.
