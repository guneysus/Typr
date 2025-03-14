Typr, Typer, or Type-R
======================

# Typr: A DSL for Type-Driven Code Generation

**Typr** is a Domain-Specific Language (DSL) designed to provide a clear, concise way to define data and generate code. Unlike generic data serialization formats like YAML, JSON, and TOML, Typr is specifically tailored for expressing complex type systems and facilitating efficient code generation across multiple target languages.

## Why Typr?

* **Code Generation Focus:** Designed explicitly for code generation, Typr simplifies the process of creating data models and related code in various languages.
* **Readability and Maintainability:** Typr's syntax is designed to be intuitive and easy to understand, promoting maintainable codebases.
* **Extensibility:** Typr is built to be extensible, allowing for custom type definitions, code generation logic, and target language support.
* **Avoids YAML/JSON/TOML Limitations:** Addresses the lack of robust type definition capabilities in common data serialization formats.

## Key Features

* **Comprehensive Type System:**
    * Primitive types (integers, floats, strings, booleans).
    * Composite types (structures, records, classes).
    * Collections (lists, arrays, maps).
    * Enums and unions.
    * Generics.
* **Code Generation Directives:**
    * Target language specification.
    * Code generation options and customizations.
    * Template-based code generation.
* **Modularity:**
    * Namespaces and modules for organized type definitions.
    * Import/export mechanisms for code reuse.
* **Constraints and Validation:**
    * Value constraints (ranges, patterns).
    * Data validation during code generation and runtime.
* **Metadata and Annotations:**
    * Attach metadata to type definitions.
    * Utilize metadata for code generation.

## Example

```typr
Example {
    # Comment
    Id int,
    Name text,
    Bin bin,
    Guid uuid,
    Duration duration,
    BirthDate datetime
}
```
