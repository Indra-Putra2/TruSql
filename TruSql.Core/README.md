# TruSql.Core

Core components and abstractions for TruSql.

This project contains the foundational types used throughout TruSql, including the tokenization, parsing, abstract syntax tree (AST), and expression structures used to represent SQL query expressions.

It provides the building blocks for parsing and analyzing expressions before they are translated into SQL.

## Responsibilities

- **Tokenization** — Represents tokens produced from expression input.
- **Parsing** — Defines the structures and components used to parse expressions.
- **Abstract Syntax Tree (AST)** — Represents parsed expressions as structured nodes.
- **Expression types** — Provides the types and operators used to describe expressions.
- **Shared abstractions** — Contains common types and enums used by other TruSql components.

## Design

TruSql.Core is intended to remain independent of database execution and query-builder integrations. Higher-level TruSql components build upon these foundational types.