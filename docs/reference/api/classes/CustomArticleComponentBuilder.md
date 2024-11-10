[**@lazuli/api v2.2.0**](../README.md) • **Docs**

***

[@lazuli/api v2.2.0](../globals.md) / CustomArticleComponentBuilder

# Class: CustomArticleComponentBuilder

Build a simple article item component, it doesn't support [ArticleCollection](ArticleCollection.md).

## Example

```ts
new CustomArticleComponentBuilder("ldk:example_component", "Title", "Some text...").build();
```

## Constructors

### new CustomArticleComponentBuilder()

> **new CustomArticleComponentBuilder**(`typeId`, `title`, `body`): [`CustomArticleComponentBuilder`](CustomArticleComponentBuilder.md)

#### Parameters

• **typeId**: `string`

The id that represents this custom component. Must have a
namespace. This id can be specified in an item's JSON
configuration under the `minecraft:custom_components` item
component.

• **title**: `string` \| `RawMessage`

Title of the article.

• **body**: `string` \| `RawMessage`

Body of the article, support RawMessage.

#### Returns

[`CustomArticleComponentBuilder`](CustomArticleComponentBuilder.md)

#### Defined in

component.ts:298

## Properties

### body

> **body**: `string` \| `RawMessage`

Body of the article, support RawMessage.

#### Defined in

component.ts:301

***

### title

> **title**: `string` \| `RawMessage`

Title of the article.

#### Defined in

component.ts:300

***

### typeId

> `readonly` **typeId**: `string`

The id that represents this custom component. Must have a
namespace. This id can be specified in an item's JSON
configuration under the `minecraft:custom_components` item
component.

#### Defined in

component.ts:299

## Methods

### build()

> **build**(): `void`

#### Returns

`void`

#### Defined in

component.ts:303
