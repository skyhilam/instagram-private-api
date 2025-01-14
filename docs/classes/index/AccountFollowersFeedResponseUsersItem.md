[instagram-private-api](../../README.md) / [index](../../modules/index.md) / AccountFollowersFeedResponseUsersItem

# Class: AccountFollowersFeedResponseUsersItem

[index](../../modules/index.md).AccountFollowersFeedResponseUsersItem

## Hierarchy

- [`ProfileEntity`](ProfileEntity.md)

  ↳ **`AccountFollowersFeedResponseUsersItem`**

## Table of contents

### Constructors

- [constructor](AccountFollowersFeedResponseUsersItem.md#constructor)

### Properties

- [full\_name](AccountFollowersFeedResponseUsersItem.md#full_name)
- [has\_anonymous\_profile\_picture](AccountFollowersFeedResponseUsersItem.md#has_anonymous_profile_picture)
- [is\_private](AccountFollowersFeedResponseUsersItem.md#is_private)
- [is\_verified](AccountFollowersFeedResponseUsersItem.md#is_verified)
- [latest\_reel\_media](AccountFollowersFeedResponseUsersItem.md#latest_reel_media)
- [pk](AccountFollowersFeedResponseUsersItem.md#pk)
- [profile\_pic\_id](AccountFollowersFeedResponseUsersItem.md#profile_pic_id)
- [profile\_pic\_url](AccountFollowersFeedResponseUsersItem.md#profile_pic_url)
- [username](AccountFollowersFeedResponseUsersItem.md#username)

### Methods

- [checkFollow](AccountFollowersFeedResponseUsersItem.md#checkfollow)
- [checkUnfollow](AccountFollowersFeedResponseUsersItem.md#checkunfollow)

## Constructors

### constructor

• **new AccountFollowersFeedResponseUsersItem**(`client`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `client` | [`IgApiClient`](IgApiClient.md) |

#### Inherited from

[ProfileEntity](ProfileEntity.md).[constructor](ProfileEntity.md#constructor)

#### Defined in

[src/core/repository.ts:7](https://github.com/Nerixyz/instagram-private-api/blob/0e0721c/src/core/repository.ts#L7)

## Properties

### full\_name

• **full\_name**: `string`

#### Defined in

[src/responses/account-followers.feed.response.ts:14](https://github.com/Nerixyz/instagram-private-api/blob/0e0721c/src/responses/account-followers.feed.response.ts#L14)

___

### has\_anonymous\_profile\_picture

• **has\_anonymous\_profile\_picture**: `boolean`

#### Defined in

[src/responses/account-followers.feed.response.ts:19](https://github.com/Nerixyz/instagram-private-api/blob/0e0721c/src/responses/account-followers.feed.response.ts#L19)

___

### is\_private

• **is\_private**: `boolean`

#### Defined in

[src/responses/account-followers.feed.response.ts:15](https://github.com/Nerixyz/instagram-private-api/blob/0e0721c/src/responses/account-followers.feed.response.ts#L15)

___

### is\_verified

• **is\_verified**: `boolean`

#### Defined in

[src/responses/account-followers.feed.response.ts:18](https://github.com/Nerixyz/instagram-private-api/blob/0e0721c/src/responses/account-followers.feed.response.ts#L18)

___

### latest\_reel\_media

• `Optional` **latest\_reel\_media**: `number`

#### Defined in

[src/responses/account-followers.feed.response.ts:20](https://github.com/Nerixyz/instagram-private-api/blob/0e0721c/src/responses/account-followers.feed.response.ts#L20)

___

### pk

• **pk**: `number`

#### Overrides

[ProfileEntity](ProfileEntity.md).[pk](ProfileEntity.md#pk)

#### Defined in

[src/responses/account-followers.feed.response.ts:12](https://github.com/Nerixyz/instagram-private-api/blob/0e0721c/src/responses/account-followers.feed.response.ts#L12)

___

### profile\_pic\_id

• `Optional` **profile\_pic\_id**: `string`

#### Defined in

[src/responses/account-followers.feed.response.ts:17](https://github.com/Nerixyz/instagram-private-api/blob/0e0721c/src/responses/account-followers.feed.response.ts#L17)

___

### profile\_pic\_url

• **profile\_pic\_url**: `string`

#### Defined in

[src/responses/account-followers.feed.response.ts:16](https://github.com/Nerixyz/instagram-private-api/blob/0e0721c/src/responses/account-followers.feed.response.ts#L16)

___

### username

• **username**: `string`

#### Defined in

[src/responses/account-followers.feed.response.ts:13](https://github.com/Nerixyz/instagram-private-api/blob/0e0721c/src/responses/account-followers.feed.response.ts#L13)

## Methods

### checkFollow

▸ **checkFollow**(): `Promise`<[`FriendshipRepositoryChangeResponseFriendship_status`](../../interfaces/index/FriendshipRepositoryChangeResponseFriendship_status.md)\>

#### Returns

`Promise`<[`FriendshipRepositoryChangeResponseFriendship_status`](../../interfaces/index/FriendshipRepositoryChangeResponseFriendship_status.md)\>

#### Inherited from

[ProfileEntity](ProfileEntity.md).[checkFollow](ProfileEntity.md#checkfollow)

#### Defined in

[src/entities/profile.entity.ts:5](https://github.com/Nerixyz/instagram-private-api/blob/0e0721c/src/entities/profile.entity.ts#L5)

___

### checkUnfollow

▸ **checkUnfollow**(): `Promise`<[`FriendshipRepositoryChangeResponseFriendship_status`](../../interfaces/index/FriendshipRepositoryChangeResponseFriendship_status.md)\>

#### Returns

`Promise`<[`FriendshipRepositoryChangeResponseFriendship_status`](../../interfaces/index/FriendshipRepositoryChangeResponseFriendship_status.md)\>

#### Inherited from

[ProfileEntity](ProfileEntity.md).[checkUnfollow](ProfileEntity.md#checkunfollow)

#### Defined in

[src/entities/profile.entity.ts:10](https://github.com/Nerixyz/instagram-private-api/blob/0e0721c/src/entities/profile.entity.ts#L10)
