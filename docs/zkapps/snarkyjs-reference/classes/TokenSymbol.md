# Class: TokenSymbol

## Hierarchy

- { `field`: [`Field`](Field.md) ; `symbol`: `string`  }

  ↳ **`TokenSymbol`**

## Table of contents

### Constructors

- [constructor](TokenSymbol.md#constructor)

### Properties

- [field](TokenSymbol.md#field)
- [symbol](TokenSymbol.md#symbol)
- [check](TokenSymbol.md#check)
- [fromFields](TokenSymbol.md#fromfields)
- [fromJSON](TokenSymbol.md#fromjson)
- [toAuxiliary](TokenSymbol.md#toauxiliary)
- [toFields](TokenSymbol.md#tofields)
- [toInput](TokenSymbol.md#toinput)
- [toJSON](TokenSymbol.md#tojson)

### Accessors

- [empty](TokenSymbol.md#empty)

### Methods

- [from](TokenSymbol.md#from)
- [sizeInFields](TokenSymbol.md#sizeinfields)

## Constructors

### constructor

• **new TokenSymbol**(`value`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | `Object` |
| `value.field` | [`Field`](Field.md) |
| `value.symbol` | `string` |

#### Inherited from

Struct(TokenSymbolPure).constructor

#### Defined in

[lib/circuit_value.ts:728](https://github.com/o1-labs/snarkyjs/blob/b5e7c38/src/lib/circuit_value.ts#L728)

## Properties

### field

• **field**: [`Field`](Field.md)

#### Inherited from

Struct(TokenSymbolPure).field

#### Defined in

[lib/hash.ts:122](https://github.com/o1-labs/snarkyjs/blob/b5e7c38/src/lib/hash.ts#L122)

___

### symbol

• **symbol**: `string`

#### Inherited from

Struct(TokenSymbolPure).symbol

#### Defined in

[lib/hash.ts:122](https://github.com/o1-labs/snarkyjs/blob/b5e7c38/src/lib/hash.ts#L122)

___

### check

▪ `Static` **check**: (`x`: { `field`: [`Field`](Field.md) ; `symbol`: `string`  }) => `void`

#### Type declaration

▸ (`x`): `void`

##### Parameters

| Name | Type |
| :------ | :------ |
| `x` | `Object` |
| `x.field` | [`Field`](Field.md) |
| `x.symbol` | `string` |

##### Returns

`void`

#### Inherited from

Struct(TokenSymbolPure).check

#### Defined in

[snarky.d.ts:29](https://github.com/o1-labs/snarkyjs/blob/b5e7c38/src/snarky.d.ts#L29)

___

### fromFields

▪ `Static` **fromFields**: (`x`: [`Field`](Field.md)[], `aux`: `any`[]) => { `field`: [`Field`](Field.md) ; `symbol`: `string`  }

#### Type declaration

▸ (`x`, `aux`): `Object`

##### Parameters

| Name | Type |
| :------ | :------ |
| `x` | [`Field`](Field.md)[] |
| `aux` | `any`[] |

##### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `field` | [`Field`](Field.md) |
| `symbol` | `string` |

#### Inherited from

Struct(TokenSymbolPure).fromFields

#### Defined in

[snarky.d.ts:27](https://github.com/o1-labs/snarkyjs/blob/b5e7c38/src/snarky.d.ts#L27)

___

### fromJSON

▪ `Static` **fromJSON**: (`x`: `string`) => { `field`: [`Field`](Field.md) ; `symbol`: `string`  }

#### Type declaration

▸ (`x`): `Object`

##### Parameters

| Name | Type |
| :------ | :------ |
| `x` | `string` |

##### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `field` | [`Field`](Field.md) |
| `symbol` | `string` |

#### Inherited from

Struct(TokenSymbolPure).fromJSON

#### Defined in

[lib/circuit_value.ts:735](https://github.com/o1-labs/snarkyjs/blob/b5e7c38/src/lib/circuit_value.ts#L735)

___

### toAuxiliary

▪ `Static` **toAuxiliary**: (`x?`: { `field`: [`Field`](Field.md) ; `symbol`: `string`  }) => `any`[]

#### Type declaration

▸ (`x?`): `any`[]

##### Parameters

| Name | Type |
| :------ | :------ |
| `x?` | `Object` |
| `x.field` | [`Field`](Field.md) |
| `x.symbol` | `string` |

##### Returns

`any`[]

#### Inherited from

Struct(TokenSymbolPure).toAuxiliary

#### Defined in

[snarky.d.ts:26](https://github.com/o1-labs/snarkyjs/blob/b5e7c38/src/snarky.d.ts#L26)

___

### toFields

▪ `Static` **toFields**: (`x`: { `field`: [`Field`](Field.md) ; `symbol`: `string`  }) => [`Field`](Field.md)[]

#### Type declaration

▸ (`x`): [`Field`](Field.md)[]

##### Parameters

| Name | Type |
| :------ | :------ |
| `x` | `Object` |
| `x.field` | [`Field`](Field.md) |
| `x.symbol` | `string` |

##### Returns

[`Field`](Field.md)[]

#### Inherited from

Struct(TokenSymbolPure).toFields

#### Defined in

[snarky.d.ts:25](https://github.com/o1-labs/snarkyjs/blob/b5e7c38/src/snarky.d.ts#L25)

___

### toInput

▪ `Static` **toInput**: (`x`: { `field`: [`Field`](Field.md) ; `symbol`: `string`  }) => { `fields?`: [`Field`](Field.md)[] ; `packed?`: [[`Field`](Field.md), `number`][]  }

#### Type declaration

▸ (`x`): `Object`

##### Parameters

| Name | Type |
| :------ | :------ |
| `x` | `Object` |
| `x.field` | [`Field`](Field.md) |
| `x.symbol` | `string` |

##### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `fields?` | [`Field`](Field.md)[] |
| `packed?` | [[`Field`](Field.md), `number`][] |

#### Inherited from

Struct(TokenSymbolPure).toInput

#### Defined in

[lib/circuit_value.ts:730](https://github.com/o1-labs/snarkyjs/blob/b5e7c38/src/lib/circuit_value.ts#L730)

___

### toJSON

▪ `Static` **toJSON**: (`x`: { `field`: [`Field`](Field.md) ; `symbol`: `string`  }) => `string`

#### Type declaration

▸ (`x`): `string`

##### Parameters

| Name | Type |
| :------ | :------ |
| `x` | `Object` |
| `x.field` | [`Field`](Field.md) |
| `x.symbol` | `string` |

##### Returns

`string`

#### Inherited from

Struct(TokenSymbolPure).toJSON

#### Defined in

[lib/circuit_value.ts:734](https://github.com/o1-labs/snarkyjs/blob/b5e7c38/src/lib/circuit_value.ts#L734)

## Accessors

### empty

• `Static` `get` **empty**(): `Object`

#### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `field` | [`Field`](Field.md) |
| `symbol` | `string` |

#### Defined in

[lib/hash.ts:153](https://github.com/o1-labs/snarkyjs/blob/b5e7c38/src/lib/hash.ts#L153)

## Methods

### from

▸ `Static` **from**(`symbol`): [`TokenSymbol`](TokenSymbol.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `symbol` | `string` |

#### Returns

[`TokenSymbol`](TokenSymbol.md)

#### Defined in

[lib/hash.ts:157](https://github.com/o1-labs/snarkyjs/blob/b5e7c38/src/lib/hash.ts#L157)

___

### sizeInFields

▸ `Static` **sizeInFields**(): `number`

#### Returns

`number`

#### Inherited from

Struct(TokenSymbolPure).sizeInFields

#### Defined in

[snarky.d.ts:28](https://github.com/o1-labs/snarkyjs/blob/b5e7c38/src/snarky.d.ts#L28)
