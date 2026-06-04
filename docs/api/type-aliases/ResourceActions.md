# Type Alias: ResourceActions

> **ResourceActions** = `object`

Defined in: [requestInterceptor/interceptorActions.ts:68](https://github.com/bouwe77/temba/blob/6cf83f6030587f43dbcde01143a958210eaee651/packages/temba/src/requestInterceptor/interceptorActions.ts#L68)

## Properties

### response()

> **response**: (`options?`) => [`ResponseAction`](ResponseAction.md)

Defined in: [requestInterceptor/interceptorActions.ts:70](https://github.com/bouwe77/temba/blob/6cf83f6030587f43dbcde01143a958210eaee651/packages/temba/src/requestInterceptor/interceptorActions.ts#L70)

#### Parameters

##### options?

###### body?

`unknown`

###### status?

`number`

#### Returns

[`ResponseAction`](ResponseAction.md)

***

### setRequestBody()

> **setRequestBody**: (`body`) => [`SetRequestBodyAction`](SetRequestBodyAction.md)

Defined in: [requestInterceptor/interceptorActions.ts:69](https://github.com/bouwe77/temba/blob/6cf83f6030587f43dbcde01143a958210eaee651/packages/temba/src/requestInterceptor/interceptorActions.ts#L69)

#### Parameters

##### body

`unknown`

#### Returns

[`SetRequestBodyAction`](SetRequestBodyAction.md)
