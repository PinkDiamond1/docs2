# Namespace: Encryption

## Table of contents

### Functions

- [decrypt](Encryption.md#decrypt)
- [encrypt](Encryption.md#encrypt)

## Functions

### decrypt

▸ **decrypt**(`__namedParameters`, `privateKey`): [`Field`](../classes/Field.md)[]

Decrypts a CipherText using a [PrivateKey](../classes/PrivateKey.md).^

#### Parameters

| Name | Type |
| :------ | :------ |
| `__namedParameters` | `CipherText` |
| `privateKey` | [`PrivateKey`](../classes/PrivateKey.md) |

#### Returns

[`Field`](../classes/Field.md)[]

#### Defined in

[lib/encryption.ts:44](https://github.com/o1-labs/snarkyjs/blob/b5e7c38/src/lib/encryption.ts#L44)

___

### encrypt

▸ **encrypt**(`message`, `otherPublicKey`): `Object`

Public Key Encryption, using a given array of [Field](../classes/Field.md) elements and encrypts it using a [PublicKey](../README.md#publickey).

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | [`Field`](../classes/Field.md)[] |
| `otherPublicKey` | [`PublicKey`](../classes/Types.PublicKey.md) |

#### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `cipherText` | [`Field`](../classes/Field.md)[] |
| `publicKey` | [`Group`](../classes/Group.md) |

#### Defined in

[lib/encryption.ts:15](https://github.com/o1-labs/snarkyjs/blob/b5e7c38/src/lib/encryption.ts#L15)
