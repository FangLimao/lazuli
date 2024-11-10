[**@lazuli/api v2.1.0**](../README.md) • **Docs**

***

[@lazuli/api v2.1.0](../globals.md) / Article

# Class: Article

Create an article.

## Extended by

- [`ChapterArticle`](ChapterArticle.md)

## Constructors

### new Article()

> **new Article**(`id`, `title`, `body`, `iconPath`?, `needUnlock`?): [`Article`](Article.md)

#### Parameters

• **id**: `string`

Article`s id.

• **title**: `string` \| `RawMessage`

Title of the article.

• **body**: `string` \| `RawMessage`

Body of the article, support RawMessage.

• **iconPath?**: `string`

Icon path of the article.

• **needUnlock?**: `boolean` = `true`

If true, articles will be unlocked in the [ArticleCollection](ArticleCollection.md) after reading it.

#### Returns

[`Article`](Article.md)

#### Defined in

article.ts:17

## Properties

### body

> **body**: `string` \| `RawMessage`

Body of the article, support RawMessage.

#### Defined in

article.ts:20

***

### iconPath?

> `optional` **iconPath**: `string`

Icon path of the article.

#### Defined in

article.ts:21

***

### id

> `readonly` **id**: `string`

Article`s id.

#### Defined in

article.ts:18

***

### needUnlock

> **needUnlock**: `boolean` = `true`

If true, articles will be unlocked in the [ArticleCollection](ArticleCollection.md) after reading it.

#### Defined in

article.ts:22

***

### title

> **title**: `string` \| `RawMessage`

Title of the article.

#### Defined in

article.ts:19

## Methods

### checkUnlock()

> **checkUnlock**(`player`): `boolean`

Check the article whether it is unlocked or not to article collection.

#### Parameters

• **player**: `Player`

#### Returns

`boolean`

#### Defined in

article.ts:50

***

### display()

> **display**(`player`): `void`

Display the reading to a player.

#### Parameters

• **player**: `Player`

#### Returns

`void`

#### Defined in

article.ts:27

***

### unlock()

> **unlock**(`player`): `void`

Unlock the article to article collection.

#### Parameters

• **player**: `Player`

#### Returns

`void`

#### Defined in

article.ts:43
