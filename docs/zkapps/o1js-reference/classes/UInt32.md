[o1js](../README.md) / [Modules](../modules.md) / UInt32

# Class: UInt32

A 32 bit unsigned integer with values ranging from 0 to 4,294,967,295.

## Hierarchy

- [`CircuitValue`](CircuitValue.md)

  ↳ **`UInt32`**

## Table of contents

### Constructors

- [constructor](UInt32.md#constructor)

### Properties

- [value](UInt32.md#value)
- [NUM\_BITS](UInt32.md#num_bits)

### Accessors

- [one](UInt32.md#one)
- [zero](UInt32.md#zero)

### Methods

- [add](UInt32.md#add)
- [assertEquals](UInt32.md#assertequals)
- [assertGreaterThan](UInt32.md#assertgreaterthan)
- [assertGreaterThanOrEqual](UInt32.md#assertgreaterthanorequal)
- [assertGt](UInt32.md#assertgt)
- [assertGte](UInt32.md#assertgte)
- [assertLessThan](UInt32.md#assertlessthan)
- [assertLessThanOrEqual](UInt32.md#assertlessthanorequal)
- [assertLt](UInt32.md#assertlt)
- [assertLte](UInt32.md#assertlte)
- [div](UInt32.md#div)
- [divMod](UInt32.md#divmod)
- [equals](UInt32.md#equals)
- [greaterThan](UInt32.md#greaterthan)
- [greaterThanOrEqual](UInt32.md#greaterthanorequal)
- [gt](UInt32.md#gt)
- [gte](UInt32.md#gte)
- [isConstant](UInt32.md#isconstant)
- [lessThan](UInt32.md#lessthan)
- [lessThanOrEqual](UInt32.md#lessthanorequal)
- [lt](UInt32.md#lt)
- [lte](UInt32.md#lte)
- [mod](UInt32.md#mod)
- [mul](UInt32.md#mul)
- [sub](UInt32.md#sub)
- [toBigint](UInt32.md#tobigint)
- [toConstant](UInt32.md#toconstant)
- [toFields](UInt32.md#tofields)
- [toJSON](UInt32.md#tojson)
- [toString](UInt32.md#tostring)
- [toUInt64](UInt32.md#touint64)
- [MAXINT](UInt32.md#maxint)
- [check](UInt32.md#check)
- [checkConstant](UInt32.md#checkconstant)
- [from](UInt32.md#from)
- [fromFields](UInt32.md#fromfields)
- [fromJSON](UInt32.md#fromjson)
- [fromObject](UInt32.md#fromobject)
- [sizeInFields](UInt32.md#sizeinfields)
- [toAuxiliary](UInt32.md#toauxiliary)
- [toConstant](UInt32.md#toconstant-1)
- [toFields](UInt32.md#tofields-1)
- [toInput](UInt32.md#toinput)
- [toJSON](UInt32.md#tojson-1)

## Constructors

### constructor

• **new UInt32**(`...props`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `...props` | `any`[] |

#### Inherited from

[CircuitValue](CircuitValue.md).[constructor](CircuitValue.md#constructor)

#### Defined in

[lib/circuit_value.ts:72](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/circuit_value.ts#L72)

## Properties

### value

• **value**: [`Field`](Field.md)

#### Defined in

[lib/int.ts:379](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/int.ts#L379)

___

### NUM\_BITS

▪ `Static` **NUM\_BITS**: `number` = `32`

#### Defined in

[lib/int.ts:380](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/int.ts#L380)

## Accessors

### one

• `Static` `get` **one**(): [`UInt32`](UInt32.md)

Static method to create a [UInt32](UInt32.md) with value `0`.

#### Returns

[`UInt32`](UInt32.md)

#### Defined in

[lib/int.ts:392](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/int.ts#L392)

___

### zero

• `Static` `get` **zero**(): [`UInt32`](UInt32.md)

Static method to create a [UInt32](UInt32.md) with value `0`.

#### Returns

[`UInt32`](UInt32.md)

#### Defined in

[lib/int.ts:385](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/int.ts#L385)

## Methods

### add

▸ **add**(`y`): [`UInt32`](UInt32.md)

Addition with overflow checking.

#### Parameters

| Name | Type |
| :------ | :------ |
| `y` | `number` \| [`UInt32`](UInt32.md) |

#### Returns

[`UInt32`](UInt32.md)

#### Defined in

[lib/int.ts:532](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/int.ts#L532)

___

### assertEquals

▸ **assertEquals**(`x`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `x` | [`UInt32`](UInt32.md) |

#### Returns

`void`

#### Inherited from

[CircuitValue](CircuitValue.md).[assertEquals](CircuitValue.md#assertequals)

#### Defined in

[lib/circuit_value.ts:160](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/circuit_value.ts#L160)

___

### assertGreaterThan

▸ **assertGreaterThan**(`y`, `message?`): `void`

Asserts that a [UInt32](UInt32.md) is greater than another one.

#### Parameters

| Name | Type |
| :------ | :------ |
| `y` | [`UInt32`](UInt32.md) |
| `message?` | `string` |

#### Returns

`void`

#### Defined in

[lib/int.ts:675](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/int.ts#L675)

___

### assertGreaterThanOrEqual

▸ **assertGreaterThanOrEqual**(`y`, `message?`): `void`

Asserts that a [UInt32](UInt32.md) is greater than or equal to another one.

#### Parameters

| Name | Type |
| :------ | :------ |
| `y` | [`UInt32`](UInt32.md) |
| `message?` | `string` |

#### Returns

`void`

#### Defined in

[lib/int.ts:708](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/int.ts#L708)

___

### assertGt

▸ **assertGt**(`y`, `message?`): `void`

**`Deprecated`**

Use [assertGreaterThan](UInt32.md#assertgreaterthan) instead.

Asserts that a [UInt32](UInt32.md) is greater than another one.

#### Parameters

| Name | Type |
| :------ | :------ |
| `y` | [`UInt32`](UInt32.md) |
| `message?` | `string` |

#### Returns

`void`

#### Defined in

[lib/int.ts:668](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/int.ts#L668)

___

### assertGte

▸ **assertGte**(`y`, `message?`): `void`

**`Deprecated`**

Use [assertGreaterThanOrEqual](UInt32.md#assertgreaterthanorequal) instead.

Asserts that a [UInt32](UInt32.md) is greater than or equal to another one.

#### Parameters

| Name | Type |
| :------ | :------ |
| `y` | [`UInt32`](UInt32.md) |
| `message?` | `string` |

#### Returns

`void`

#### Defined in

[lib/int.ts:701](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/int.ts#L701)

___

### assertLessThan

▸ **assertLessThan**(`y`, `message?`): `void`

Asserts that a [UInt32](UInt32.md) is less than another one.

#### Parameters

| Name | Type |
| :------ | :------ |
| `y` | [`UInt32`](UInt32.md) |
| `message?` | `string` |

#### Returns

`void`

#### Defined in

[lib/int.ts:643](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/int.ts#L643)

___

### assertLessThanOrEqual

▸ **assertLessThanOrEqual**(`y`, `message?`): `void`

Asserts that a [UInt32](UInt32.md) is less than or equal to another one.

#### Parameters

| Name | Type |
| :------ | :------ |
| `y` | [`UInt32`](UInt32.md) |
| `message?` | `string` |

#### Returns

`void`

#### Defined in

[lib/int.ts:601](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/int.ts#L601)

___

### assertLt

▸ **assertLt**(`y`, `message?`): `void`

**`Deprecated`**

Use [assertLessThan](UInt32.md#assertlessthan) instead.

Asserts that a [UInt32](UInt32.md) is less than another one.

#### Parameters

| Name | Type |
| :------ | :------ |
| `y` | [`UInt32`](UInt32.md) |
| `message?` | `string` |

#### Returns

`void`

#### Defined in

[lib/int.ts:636](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/int.ts#L636)

___

### assertLte

▸ **assertLte**(`y`, `message?`): `void`

**`Deprecated`**

Use [assertLessThanOrEqual](UInt32.md#assertlessthanorequal) instead.

Asserts that a [UInt32](UInt32.md) is less than or equal to another one.

#### Parameters

| Name | Type |
| :------ | :------ |
| `y` | [`UInt32`](UInt32.md) |
| `message?` | `string` |

#### Returns

`void`

#### Defined in

[lib/int.ts:594](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/int.ts#L594)

___

### div

▸ **div**(`y`): [`UInt32`](UInt32.md)

Integer division.

`x.div(y)` returns the floor of `x / y`, that is, the greatest
`z` such that `x * y <= x`.

#### Parameters

| Name | Type |
| :------ | :------ |
| `y` | `number` \| [`UInt32`](UInt32.md) |

#### Returns

[`UInt32`](UInt32.md)

#### Defined in

[lib/int.ts:509](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/int.ts#L509)

___

### divMod

▸ **divMod**(`y`): `Object`

Integer division with remainder.

`x.divMod(y)` returns the quotient and the remainder.

#### Parameters

| Name | Type |
| :------ | :------ |
| `y` | `string` \| `number` \| [`UInt32`](UInt32.md) |

#### Returns

`Object`

| Name | Type |
| :------ | :------ |
| `quotient` | [`UInt32`](UInt32.md) |
| `rest` | [`UInt32`](UInt32.md) |

#### Defined in

[lib/int.ts:467](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/int.ts#L467)

___

### equals

▸ **equals**(`x`): [`Bool`](Bool.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `x` | [`UInt32`](UInt32.md) |

#### Returns

[`Bool`](Bool.md)

#### Inherited from

[CircuitValue](CircuitValue.md).[equals](CircuitValue.md#equals)

#### Defined in

[lib/circuit_value.ts:156](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/circuit_value.ts#L156)

___

### greaterThan

▸ **greaterThan**(`y`): [`Bool`](Bool.md)

Checks if a [UInt32](UInt32.md) is greater than another one.

#### Parameters

| Name | Type |
| :------ | :------ |
| `y` | [`UInt32`](UInt32.md) |

#### Returns

[`Bool`](Bool.md)

#### Defined in

[lib/int.ts:659](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/int.ts#L659)

___

### greaterThanOrEqual

▸ **greaterThanOrEqual**(`y`): [`Bool`](Bool.md)

Checks if a [UInt32](UInt32.md) is greater than or equal to another one.

#### Parameters

| Name | Type |
| :------ | :------ |
| `y` | [`UInt32`](UInt32.md) |

#### Returns

[`Bool`](Bool.md)

#### Defined in

[lib/int.ts:691](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/int.ts#L691)

___

### gt

▸ **gt**(`y`): [`Bool`](Bool.md)

**`Deprecated`**

Use [greaterThan](UInt32.md#greaterthan) instead.

Checks if a [UInt32](UInt32.md) is greater than another one.

#### Parameters

| Name | Type |
| :------ | :------ |
| `y` | [`UInt32`](UInt32.md) |

#### Returns

[`Bool`](Bool.md)

#### Defined in

[lib/int.ts:652](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/int.ts#L652)

___

### gte

▸ **gte**(`y`): [`Bool`](Bool.md)

**`Deprecated`**

Use [greaterThanOrEqual](UInt32.md#greaterthanorequal) instead.

Checks if a [UInt32](UInt32.md) is greater than or equal to another one.

#### Parameters

| Name | Type |
| :------ | :------ |
| `y` | [`UInt32`](UInt32.md) |

#### Returns

[`Bool`](Bool.md)

#### Defined in

[lib/int.ts:684](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/int.ts#L684)

___

### isConstant

▸ **isConstant**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CircuitValue](CircuitValue.md).[isConstant](CircuitValue.md#isconstant)

#### Defined in

[lib/circuit_value.ts:164](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/circuit_value.ts#L164)

___

### lessThan

▸ **lessThan**(`y`): [`Bool`](Bool.md)

Checks if a [UInt32](UInt32.md) is less than another one.

#### Parameters

| Name | Type |
| :------ | :------ |
| `y` | [`UInt32`](UInt32.md) |

#### Returns

[`Bool`](Bool.md)

#### Defined in

[lib/int.ts:627](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/int.ts#L627)

___

### lessThanOrEqual

▸ **lessThanOrEqual**(`y`): [`Bool`](Bool.md)

Checks if a [UInt32](UInt32.md) is less than or equal to another one.

#### Parameters

| Name | Type |
| :------ | :------ |
| `y` | [`UInt32`](UInt32.md) |

#### Returns

[`Bool`](Bool.md)

#### Defined in

[lib/int.ts:571](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/int.ts#L571)

___

### lt

▸ **lt**(`y`): [`Bool`](Bool.md)

**`Deprecated`**

Use [lessThan](UInt32.md#lessthan) instead.

Checks if a [UInt32](UInt32.md) is less than another one.

#### Parameters

| Name | Type |
| :------ | :------ |
| `y` | [`UInt32`](UInt32.md) |

#### Returns

[`Bool`](Bool.md)

#### Defined in

[lib/int.ts:620](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/int.ts#L620)

___

### lte

▸ **lte**(`y`): [`Bool`](Bool.md)

**`Deprecated`**

Use [lessThanOrEqual](UInt32.md#lessthanorequal) instead.

Checks if a [UInt32](UInt32.md) is less than or equal to another one.

#### Parameters

| Name | Type |
| :------ | :------ |
| `y` | [`UInt32`](UInt32.md) |

#### Returns

[`Bool`](Bool.md)

#### Defined in

[lib/int.ts:550](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/int.ts#L550)

___

### mod

▸ **mod**(`y`): [`UInt32`](UInt32.md)

Integer remainder.

`x.mod(y)` returns the value `z` such that `0 <= z < y` and
`x - z` is divisble by `y`.

#### Parameters

| Name | Type |
| :------ | :------ |
| `y` | `number` \| [`UInt32`](UInt32.md) |

#### Returns

[`UInt32`](UInt32.md)

#### Defined in

[lib/int.ts:518](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/int.ts#L518)

___

### mul

▸ **mul**(`y`): [`UInt32`](UInt32.md)

Multiplication with overflow checking.

#### Parameters

| Name | Type |
| :------ | :------ |
| `y` | `number` \| [`UInt32`](UInt32.md) |

#### Returns

[`UInt32`](UInt32.md)

#### Defined in

[lib/int.ts:524](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/int.ts#L524)

___

### sub

▸ **sub**(`y`): [`UInt32`](UInt32.md)

Subtraction with underflow checking.

#### Parameters

| Name | Type |
| :------ | :------ |
| `y` | `number` \| [`UInt32`](UInt32.md) |

#### Returns

[`UInt32`](UInt32.md)

#### Defined in

[lib/int.ts:540](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/int.ts#L540)

___

### toBigint

▸ **toBigint**(): `bigint`

Turns the [UInt32](UInt32.md) into a BigInt.

#### Returns

`bigint`

#### Defined in

[lib/int.ts:404](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/int.ts#L404)

___

### toConstant

▸ **toConstant**(): [`UInt32`](UInt32.md)

#### Returns

[`UInt32`](UInt32.md)

#### Inherited from

[CircuitValue](CircuitValue.md).[toConstant](CircuitValue.md#toconstant)

#### Defined in

[lib/circuit_value.ts:152](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/circuit_value.ts#L152)

___

### toFields

▸ **toFields**(): [`Field`](Field.md)[]

#### Returns

[`Field`](Field.md)[]

#### Inherited from

[CircuitValue](CircuitValue.md).[toFields](CircuitValue.md#tofields)

#### Defined in

[lib/circuit_value.ts:144](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/circuit_value.ts#L144)

___

### toJSON

▸ **toJSON**(): `any`

#### Returns

`any`

#### Inherited from

[CircuitValue](CircuitValue.md).[toJSON](CircuitValue.md#tojson)

#### Defined in

[lib/circuit_value.ts:148](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/circuit_value.ts#L148)

___

### toString

▸ **toString**(): `string`

Turns the [UInt32](UInt32.md) into a string.

#### Returns

`string`

#### Defined in

[lib/int.ts:398](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/int.ts#L398)

___

### toUInt64

▸ **toUInt64**(): [`UInt64`](UInt64.md)

Turns the [UInt32](UInt32.md) into a [UInt64](UInt64.md).

#### Returns

[`UInt64`](UInt64.md)

#### Defined in

[lib/int.ts:410](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/int.ts#L410)

___

### MAXINT

▸ `Static` **MAXINT**(): [`UInt32`](UInt32.md)

Creates a [UInt32](UInt32.md) with a value of 4,294,967,295.

#### Returns

[`UInt32`](UInt32.md)

#### Defined in

[lib/int.ts:458](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/int.ts#L458)

___

### check

▸ `Static` **check**(`x`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `x` | [`UInt32`](UInt32.md) |

#### Returns

`void`

#### Overrides

[CircuitValue](CircuitValue.md).[check](CircuitValue.md#check)

#### Defined in

[lib/int.ts:415](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/int.ts#L415)

___

### checkConstant

▸ `Static` `Private` **checkConstant**(`x`): [`Field`](Field.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `x` | [`Field`](Field.md) |

#### Returns

[`Field`](Field.md)

#### Defined in

[lib/int.ts:436](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/int.ts#L436)

___

### from

▸ `Static` **from**(`x`): [`UInt32`](UInt32.md)

Creates a new [UInt32](UInt32.md).

#### Parameters

| Name | Type |
| :------ | :------ |
| `x` | `string` \| `number` \| `bigint` \| [`Field`](Field.md) \| [`UInt32`](UInt32.md) |

#### Returns

[`UInt32`](UInt32.md)

#### Defined in

[lib/int.ts:451](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/int.ts#L451)

___

### fromFields

▸ `Static` **fromFields**<`T`\>(`this`, `xs`): `InstanceType`<`T`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `AnyConstructor` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `this` | `T` |
| `xs` | [`Field`](Field.md)[] |

#### Returns

`InstanceType`<`T`\>

#### Inherited from

[CircuitValue](CircuitValue.md).[fromFields](CircuitValue.md#fromfields)

#### Defined in

[lib/circuit_value.ts:168](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/circuit_value.ts#L168)

___

### fromJSON

▸ `Static` **fromJSON**<`T`\>(`x`): `InstanceType`<`T`\>

Decodes a JSON-like object into this structure.

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `AnyConstructor` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `x` | `string` |

#### Returns

`InstanceType`<`T`\>

#### Overrides

[CircuitValue](CircuitValue.md).[fromJSON](CircuitValue.md#fromjson)

#### Defined in

[lib/int.ts:432](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/int.ts#L432)

___

### fromObject

▸ `Static` **fromObject**<`T`\>(`this`, `value`): `InstanceType`<`T`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `AnyConstructor` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `this` | `T` |
| `value` | `NonMethods`<`InstanceType`<`T`\>\> |

#### Returns

`InstanceType`<`T`\>

#### Inherited from

[CircuitValue](CircuitValue.md).[fromObject](CircuitValue.md#fromobject)

#### Defined in

[lib/circuit_value.ts:89](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/circuit_value.ts#L89)

___

### sizeInFields

▸ `Static` **sizeInFields**(): `number`

#### Returns

`number`

#### Inherited from

[CircuitValue](CircuitValue.md).[sizeInFields](CircuitValue.md#sizeinfields)

#### Defined in

[lib/circuit_value.ts:96](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/circuit_value.ts#L96)

___

### toAuxiliary

▸ `Static` **toAuxiliary**(): []

#### Returns

[]

#### Inherited from

[CircuitValue](CircuitValue.md).[toAuxiliary](CircuitValue.md#toauxiliary)

#### Defined in

[lib/circuit_value.ts:118](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/circuit_value.ts#L118)

___

### toConstant

▸ `Static` **toConstant**<`T`\>(`this`, `t`): `InstanceType`<`T`\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `AnyConstructor` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `this` | `T` |
| `t` | `InstanceType`<`T`\> |

#### Returns

`InstanceType`<`T`\>

#### Inherited from

[CircuitValue](CircuitValue.md).[toConstant](CircuitValue.md#toconstant-1)

#### Defined in

[lib/circuit_value.ts:207](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/circuit_value.ts#L207)

___

### toFields

▸ `Static` **toFields**<`T`\>(`this`, `v`): [`Field`](Field.md)[]

#### Type parameters

| Name | Type |
| :------ | :------ |
| `T` | extends `AnyConstructor` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `this` | `T` |
| `v` | `InstanceType`<`T`\> |

#### Returns

[`Field`](Field.md)[]

#### Inherited from

[CircuitValue](CircuitValue.md).[toFields](CircuitValue.md#tofields-1)

#### Defined in

[lib/circuit_value.ts:101](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/circuit_value.ts#L101)

___

### toInput

▸ `Static` **toInput**(`x`): `HashInput`

#### Parameters

| Name | Type |
| :------ | :------ |
| `x` | [`UInt32`](UInt32.md) |

#### Returns

`HashInput`

#### Overrides

[CircuitValue](CircuitValue.md).[toInput](CircuitValue.md#toinput)

#### Defined in

[lib/int.ts:419](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/int.ts#L419)

___

### toJSON

▸ `Static` **toJSON**(`x`): `string`

Encodes this structure into a JSON-like object.

#### Parameters

| Name | Type |
| :------ | :------ |
| `x` | [`UInt32`](UInt32.md) |

#### Returns

`string`

#### Overrides

[CircuitValue](CircuitValue.md).[toJSON](CircuitValue.md#tojson-1)

#### Defined in

[lib/int.ts:425](https://github.com/o1-labs/o1js/blob/5ca4368/src/lib/int.ts#L425)
