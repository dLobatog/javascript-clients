[@redhat-cloud-services/cost-management-client](../README.md) > [ProviderOut](../interfaces/providerout.md)

# Interface: ProviderOut

*__export__*: 

*__interface__*: ProviderOut

## Hierarchy

**ProviderOut**

## Index

### Properties

* [active](providerout.md#active)
* [authentication](providerout.md#authentication)
* [billingSource](providerout.md#billingsource)
* [costModels](providerout.md#costmodels)
* [createdBy](providerout.md#createdby)
* [customer](providerout.md#customer)
* [infrastructure](providerout.md#infrastructure)
* [name](providerout.md#name)
* [stats](providerout.md#stats)
* [type](providerout.md#type)
* [uuid](providerout.md#uuid)

---

## Properties

<a id="active"></a>

### `<Optional>` active

**● active**: *`boolean`*

*Defined in [api.ts:864](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/cost-management/api.ts#L864)*

Flag to indicate when the provider is configured correctly

*__type__*: {boolean}

*__memberof__*: ProviderOut

___
<a id="authentication"></a>

###  authentication

**● authentication**: *[ProviderAuthenticationOut](providerauthenticationout.md)*

*Defined in [api.ts:828](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/cost-management/api.ts#L828)*

*__type__*: {ProviderAuthenticationOut}

*__memberof__*: ProviderOut

___
<a id="billingsource"></a>

###  billingSource

**● billingSource**: *[ProviderBillingSourceOut](providerbillingsourceout.md)*

*Defined in [api.ts:834](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/cost-management/api.ts#L834)*

*__type__*: {ProviderBillingSourceOut}

*__memberof__*: ProviderOut

___
<a id="costmodels"></a>

### `<Optional>` costModels

**● costModels**: *`Array`<`any`>*

*Defined in [api.ts:870](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/cost-management/api.ts#L870)*

List of cost model name and UUIDs associated with this provider.

*__type__*: {Array}

*__memberof__*: ProviderOut

___
<a id="createdby"></a>

###  createdBy

**● createdBy**: *[UserOut](userout.md)*

*Defined in [api.ts:846](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/cost-management/api.ts#L846)*

*__type__*: {UserOut}

*__memberof__*: ProviderOut

___
<a id="customer"></a>

###  customer

**● customer**: *[CustomerOut](customerout.md)*

*Defined in [api.ts:840](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/cost-management/api.ts#L840)*

*__type__*: {CustomerOut}

*__memberof__*: ProviderOut

___
<a id="infrastructure"></a>

### `<Optional>` infrastructure

**● infrastructure**: *`string`*

*Defined in [api.ts:858](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/cost-management/api.ts#L858)*

OpenShift foundational infrastructure type.

*__type__*: {string}

*__memberof__*: ProviderOut

___
<a id="name"></a>

###  name

**● name**: *`string`*

*Defined in [api.ts:810](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/cost-management/api.ts#L810)*

*__type__*: {string}

*__memberof__*: ProviderOut

___
<a id="stats"></a>

### `<Optional>` stats

**● stats**: *`any`*

*Defined in [api.ts:852](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/cost-management/api.ts#L852)*

Dictionary key is the start of a billing month. Value is report processing statistics.

*__type__*: {any}

*__memberof__*: ProviderOut

___
<a id="type"></a>

###  type

**● type**: *`string`*

*Defined in [api.ts:816](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/cost-management/api.ts#L816)*

*__type__*: {string}

*__memberof__*: ProviderOut

___
<a id="uuid"></a>

###  uuid

**● uuid**: *`string`*

*Defined in [api.ts:822](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/cost-management/api.ts#L822)*

*__type__*: {string}

*__memberof__*: ProviderOut

___
