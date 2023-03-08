# Attributes

[Attributes] are used to customize the `FromIt`
implementations produced by Serde's derive. They require a Rust compiler version
1.15 or newer.

[Attributes]: https://doc.rust-lang.org/book/attributes.html

There are three categories of attributes:

- [**Container attributes**] — apply to a struct or enum declaration.
- [**Variant attributes**] — apply to a variant of an enum.
- [**Field attributes**] — apply to one field in a struct or in an enum variant.

[**Container attributes**]: container-attrs.md
[**Variant attributes**]: variant-attrs.md
[**Field attributes**]: field-attrs.md