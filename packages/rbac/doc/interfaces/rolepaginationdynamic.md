[@redhat-cloud-services/rbac-client](../README.md) › [Globals](../globals.md) › [RolePaginationDynamic](rolepaginationdynamic.md)

# Interface: RolePaginationDynamic

**`export`** 

**`interface`** RolePaginationDynamic

## Hierarchy

* [ListPagination](listpagination.md)

  ↳ **RolePaginationDynamic**

## Index

### Properties

* [data](rolepaginationdynamic.md#data)
* [links](rolepaginationdynamic.md#optional-links)
* [meta](rolepaginationdynamic.md#optional-meta)

## Properties

###  data

• **data**: *Array‹[RoleOutDynamic](roleoutdynamic.md)›*

*Defined in [packages/rbac/api.ts:1226](https://github.com/leSamo/javascript-clients/blob/master/packages/rbac/api.ts#L1226)*

**`memberof`** RolePaginationDynamic

___

### `Optional` links

• **links**? : *[PaginationLinks](paginationlinks.md)*

*Inherited from [AccessPagination](accesspagination.md).[links](accesspagination.md#optional-links)*

*Defined in [packages/rbac/api.ts:460](https://github.com/leSamo/javascript-clients/blob/master/packages/rbac/api.ts#L460)*

**`memberof`** ListPagination

___

### `Optional` meta

• **meta**? : *[PaginationMeta](paginationmeta.md)*

*Inherited from [AccessPagination](accesspagination.md).[meta](accesspagination.md#optional-meta)*

*Defined in [packages/rbac/api.ts:454](https://github.com/leSamo/javascript-clients/blob/master/packages/rbac/api.ts#L454)*

**`memberof`** ListPagination
