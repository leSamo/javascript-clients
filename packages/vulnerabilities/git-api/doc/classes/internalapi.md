[@redhat-cloud-services/vulnerabilities-client](../README.md) › [Globals](../globals.md) › [InternalApi](internalapi.md)

# Class: InternalApi

InternalApi - object-oriented interface

**`export`** 

## Hierarchy

* [BaseAPI](baseapi.md)

  ↳ **InternalApi**

## Index

### Constructors

* [constructor](internalapi.md#constructor)

### Properties

* [axios](internalapi.md#protected-axios)
* [basePath](internalapi.md#protected-basepath)
* [configuration](internalapi.md#protected-configuration)

### Methods

* [refreshAccount](internalapi.md#refreshaccount)
* [refreshAccountCve](internalapi.md#refreshaccountcve)
* [refreshCve](internalapi.md#refreshcve)
* [refreshSystem](internalapi.md#refreshsystem)

## Constructors

###  constructor

\+ **new InternalApi**(`configuration?`: [Configuration](configuration.md), `basePath`: string, `axios`: AxiosInstance): *[InternalApi](internalapi.md)*

*Inherited from [BaseAPI](baseapi.md).[constructor](baseapi.md#constructor)*

*Defined in [packages/vulnerabilities/git-api/base.ts:49](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/base.ts#L49)*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`configuration?` | [Configuration](configuration.md) | - |
`basePath` | string | BASE_PATH |
`axios` | AxiosInstance | globalAxios |

**Returns:** *[InternalApi](internalapi.md)*

## Properties

### `Protected` axios

• **axios**: *AxiosInstance*

*Inherited from [BaseAPI](baseapi.md).[axios](baseapi.md#protected-axios)*

*Defined in [packages/vulnerabilities/git-api/base.ts:51](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/base.ts#L51)*

___

### `Protected` basePath

• **basePath**: *string*

*Inherited from [BaseAPI](baseapi.md).[basePath](baseapi.md#protected-basepath)*

*Defined in [packages/vulnerabilities/git-api/base.ts:51](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/base.ts#L51)*

___

### `Protected` configuration

• **configuration**: *[Configuration](configuration.md) | undefined*

*Inherited from [BaseAPI](baseapi.md).[configuration](baseapi.md#protected-configuration)*

*Defined in [packages/vulnerabilities/git-api/base.ts:49](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/base.ts#L49)*

## Methods

###  refreshAccount

▸ **refreshAccount**(`accountId`: string, `options?`: any): *AxiosPromise‹void›*

*Defined in [packages/vulnerabilities/git-api/api.ts:4768](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L4768)*

Refresh cached counts for given account ID. Admin interface, available only to internal users.

**`summary`** Refresh cached counts for given account ID.

**`throws`** {RequiredError}

**`memberof`** InternalApi

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`accountId` | string | Account ID of user. |
`options?` | any | - |

**Returns:** *AxiosPromise‹void›*

___

###  refreshAccountCve

▸ **refreshAccountCve**(`accountId`: string, `cveId`: string, `options?`: any): *AxiosPromise‹void›*

*Defined in [packages/vulnerabilities/git-api/api.ts:4781](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L4781)*

Refresh cached counts for given account ID and CVE. Admin interface, available only to internal users.

**`summary`** Refresh cached counts for given account ID and CVE.

**`throws`** {RequiredError}

**`memberof`** InternalApi

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`accountId` | string | Account ID of user. |
`cveId` | string | CVE id. |
`options?` | any | - |

**Returns:** *AxiosPromise‹void›*

___

###  refreshCve

▸ **refreshCve**(`cveId`: string, `options?`: any): *AxiosPromise‹void›*

*Defined in [packages/vulnerabilities/git-api/api.ts:4793](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L4793)*

Refresh cached counts for given CVE. Admin interface, available only to internal users.

**`summary`** Refresh cached counts for given CVE.

**`throws`** {RequiredError}

**`memberof`** InternalApi

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`cveId` | string | CVE id. |
`options?` | any | - |

**Returns:** *AxiosPromise‹void›*

___

###  refreshSystem

▸ **refreshSystem**(`inventoryId`: string, `options?`: any): *AxiosPromise‹void›*

*Defined in [packages/vulnerabilities/git-api/api.ts:4805](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L4805)*

Refresh cached counts for given inventory ID. Admin interface, available only to internal users.

**`summary`** Refresh cached counts for given inventory ID.

**`throws`** {RequiredError}

**`memberof`** InternalApi

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`inventoryId` | string | Inventory ID. |
`options?` | any | - |

**Returns:** *AxiosPromise‹void›*
