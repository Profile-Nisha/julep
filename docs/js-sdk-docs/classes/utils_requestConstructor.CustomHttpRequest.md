[@julep/sdk](../README.md) / [Modules](../modules.md) / [utils/requestConstructor](../modules/utils_requestConstructor.md) / CustomHttpRequest

# Class: CustomHttpRequest

[utils/requestConstructor](../modules/utils_requestConstructor.md).CustomHttpRequest

## Hierarchy

- `AxiosHttpRequest`

  ↳ **`CustomHttpRequest`**

## Table of contents

### Constructors

- [constructor](utils_requestConstructor.CustomHttpRequest.md#constructor)

### Properties

- [config](utils_requestConstructor.CustomHttpRequest.md#config)

### Methods

- [request](utils_requestConstructor.CustomHttpRequest.md#request)

## Constructors

### constructor

• **new CustomHttpRequest**(`config`): [`CustomHttpRequest`](utils_requestConstructor.CustomHttpRequest.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `config` | [`OpenAPIConfig`](../modules/api.md#openapiconfig) |

#### Returns

[`CustomHttpRequest`](utils_requestConstructor.CustomHttpRequest.md)

#### Overrides

AxiosHttpRequest.constructor

#### Defined in

[src/utils/requestConstructor.ts:16](https://github.com/julep-ai/julep/blob/16b6a16e058c745243b863c8672ca43b8658d9c8/sdks/ts/src/utils/requestConstructor.ts#L16)

## Properties

### config

• `Readonly` **config**: [`OpenAPIConfig`](../modules/api.md#openapiconfig)

#### Inherited from

AxiosHttpRequest.config

#### Defined in

[src/api/core/BaseHttpRequest.ts:10](https://github.com/julep-ai/julep/blob/16b6a16e058c745243b863c8672ca43b8658d9c8/sdks/ts/src/api/core/BaseHttpRequest.ts#L10)

## Methods

### request

▸ **request**\<`T`\>(`options`): [`CancelablePromise`](api.CancelablePromise.md)\<`T`\>

#### Type parameters

| Name |
| :------ |
| `T` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | `ApiRequestOptions` |

#### Returns

[`CancelablePromise`](api.CancelablePromise.md)\<`T`\>

#### Overrides

AxiosHttpRequest.request

#### Defined in

[src/utils/requestConstructor.ts:21](https://github.com/julep-ai/julep/blob/16b6a16e058c745243b863c8672ca43b8658d9c8/sdks/ts/src/utils/requestConstructor.ts#L21)