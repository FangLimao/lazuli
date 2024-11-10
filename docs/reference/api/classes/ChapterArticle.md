[**@lazuli/api v2.2.0**](../README.md) • **Docs**

***

[@lazuli/api v2.2.0](../globals.md) / ChapterArticle

# Class: ChapterArticle

Create an article with chapters.

## Extends

- [`Article`](Article.md)

## Constructors

### new ChapterArticle()

> **new ChapterArticle**(`id`, `title`, `body`, `chapters`, `iconPath`?, `needUnlock`?): [`ChapterArticle`](ChapterArticle.md)

#### Parameters

• **id**: `string`

Article`s id.

• **title**: `string` \| `RawMessage`

Title of the article.

• **body**: `string` \| `RawMessage`

Body of the article, support RawMessage.

• **chapters**: [`ChapterData`](../interfaces/ChapterData.md)[]

Chapters of the article.

• **iconPath?**: `string`

Icon path of the article.

• **needUnlock?**: `boolean` = `true`

If true, articles will be unlocked in the [ArticleCollection](ArticleCollection.md) after reading it.

#### Returns

[`ChapterArticle`](ChapterArticle.md)

#### Overrides

[`Article`](Article.md).[`constructor`](Article.md#constructors)

#### Defined in

article.ts:77

## Properties

### body

> **body**: `string` \| `RawMessage`

Body of the article, support RawMessage.

#### Inherited from

[`Article`](Article.md).[`body`](Article.md#body)

#### Defined in

article.ts:80

***

### chapters

> **chapters**: [`ChapterData`](../interfaces/ChapterData.md)[]

Chapters of the article.

#### Defined in

article.ts:81

***

### iconPath?

> `optional` **iconPath**: `string`

Icon path of the article.

#### Inherited from

[`Article`](Article.md).[`iconPath`](Article.md#iconpath)

#### Defined in

article.ts:82

***

### id

> `readonly` **id**: `string`

Article`s id.

#### Inherited from

[`Article`](Article.md).[`id`](Article.md#id)

#### Defined in

article.ts:78

***

### needUnlock

> **needUnlock**: `boolean` = `true`

If true, articles will be unlocked in the [ArticleCollection](ArticleCollection.md) after reading it.

#### Inherited from

[`Article`](Article.md).[`needUnlock`](Article.md#needunlock)

#### Defined in

article.ts:83

***

### title

> **title**: `string` \| `RawMessage`

Title of the article.

#### Inherited from

[`Article`](Article.md).[`title`](Article.md#title)

#### Defined in

article.ts:79

## Methods

### checkUnlock()

> **checkUnlock**(`player`): `boolean`

Check the article whether it is unlocked or not to article collection.

#### Parameters

• **player**: `Player`

#### Returns

`boolean`

#### Inherited from

[`Article`](Article.md).[`checkUnlock`](Article.md#checkunlock)

#### Defined in

article.ts:55

***

### display()

> **display**(`player`): `void`

Display the reading to a player.

#### Parameters

• **player**: `Player`

#### Returns

`void`

#### Overrides

[`Article`](Article.md).[`display`](Article.md#display)

#### Defined in

article.ts:90

***

### unlock()

> **unlock**(`player`): `void`

Unlock the article to article collection.

#### Parameters

• **player**: `Player`

#### Returns

`void`

#### Inherited from

[`Article`](Article.md).[`unlock`](Article.md#unlock)

#### Defined in

article.ts:48
