[**@lazuli/api v2.2.0**](../README.md) • **Docs**

***

[@lazuli/api v2.2.0](../globals.md) / ArticleCollection

# Class: ArticleCollection

Create an article collection.
It likes [ChapterArticle](ChapterArticle.md), but support article unlock.

## Constructors

### new ArticleCollection()

> **new ArticleCollection**(`id`, `title`, `body`, `displayCondition`, `articles`): [`ArticleCollection`](ArticleCollection.md)

#### Parameters

• **id**: `string`

Collection`s id.

• **title**: `string` \| `RawMessage`

Title of the collection.

• **body**: `string` \| `RawMessage`

Body of the collection.

• **displayCondition**: `DisplayCondition`

Control when collection is displayed.

• **articles**: ([`Article`](Article.md) \| [`ChapterArticle`](ChapterArticle.md))[]

Articles in the collection.

#### Returns

[`ArticleCollection`](ArticleCollection.md)

#### Defined in

article.ts:126

## Properties

### articles

> **articles**: ([`Article`](Article.md) \| [`ChapterArticle`](ChapterArticle.md))[]

Articles in the collection.

#### Defined in

article.ts:131

***

### body

> **body**: `string` \| `RawMessage`

Body of the collection.

#### Defined in

article.ts:129

***

### displayCondition

> **displayCondition**: `DisplayCondition`

Control when collection is displayed.

#### Defined in

article.ts:130

***

### id

> `readonly` **id**: `string`

Collection`s id.

#### Defined in

article.ts:127

***

### title

> **title**: `string` \| `RawMessage`

Title of the collection.

#### Defined in

article.ts:128

## Methods

### display()

> **display**(`player`): `void`

Display the reading to a player.

#### Parameters

• **player**: `Player`

#### Returns

`void`

#### Defined in

article.ts:137
