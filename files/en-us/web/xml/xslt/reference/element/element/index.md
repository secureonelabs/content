---
title: <xsl:element>
slug: Web/XML/XSLT/Reference/Element/element
page-type: xslt-element
sidebar: xmlsidebar
---

The `<xsl:element>` element creates an element in the output document.

## Syntax

```xml
<xsl:element name=NAME namespace=URI use-attribute-sets=LIST-OF-NAMES >
  TEMPLATE
</xsl:element>
```

### Required Attributes

- `name`
  - : Specifies the desired name of the output element. The name must be a valid QName.

### Optional Attributes

- `namespace`
  - : Specifies the namespace of the output element.
- `use-attribute-sets`
  - : A whitespace‐separated list of [`attribute-set` element](/en-US/docs/Web/XML/XSLT/Reference/Element/attribute-set) names to be applied to the `element` element's output element. Applied attributes can be overridden via nested `attribute` elements.

### Type

Instruction, appears within a template.

## Specifications

XSLT, section 7.1.2.

## Gecko support

Supported.
