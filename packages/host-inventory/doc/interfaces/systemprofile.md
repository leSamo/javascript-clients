[@redhat-cloud-services/host-inventory-client](../README.md) › [Globals](../globals.md) › [SystemProfile](systemprofile.md)

# Interface: SystemProfile

Representation of the system profile fields

**`export`** 

**`interface`** SystemProfile

## Hierarchy

* **SystemProfile**

## Index

### Properties

* [arch](systemprofile.md#optional-arch)
* [bios_release_date](systemprofile.md#optional-bios_release_date)
* [bios_vendor](systemprofile.md#optional-bios_vendor)
* [bios_version](systemprofile.md#optional-bios_version)
* [captured_date](systemprofile.md#optional-captured_date)
* [cloud_provider](systemprofile.md#optional-cloud_provider)
* [cores_per_socket](systemprofile.md#optional-cores_per_socket)
* [cpu_flags](systemprofile.md#optional-cpu_flags)
* [disk_devices](systemprofile.md#optional-disk_devices)
* [dnf_modules](systemprofile.md#optional-dnf_modules)
* [enabled_services](systemprofile.md#optional-enabled_services)
* [infrastructure_type](systemprofile.md#optional-infrastructure_type)
* [infrastructure_vendor](systemprofile.md#optional-infrastructure_vendor)
* [insights_client_version](systemprofile.md#optional-insights_client_version)
* [insights_egg_version](systemprofile.md#optional-insights_egg_version)
* [installed_packages](systemprofile.md#optional-installed_packages)
* [installed_products](systemprofile.md#optional-installed_products)
* [installed_services](systemprofile.md#optional-installed_services)
* [katello_agent_running](systemprofile.md#optional-katello_agent_running)
* [kernel_modules](systemprofile.md#optional-kernel_modules)
* [last_boot_time](systemprofile.md#optional-last_boot_time)
* [network_interfaces](systemprofile.md#optional-network_interfaces)
* [number_of_cpus](systemprofile.md#optional-number_of_cpus)
* [number_of_sockets](systemprofile.md#optional-number_of_sockets)
* [operating_system](systemprofile.md#optional-operating_system)
* [os_kernel_version](systemprofile.md#optional-os_kernel_version)
* [os_release](systemprofile.md#optional-os_release)
* [running_processes](systemprofile.md#optional-running_processes)
* [sap_instance_number](systemprofile.md#optional-sap_instance_number)
* [sap_sids](systemprofile.md#optional-sap_sids)
* [sap_system](systemprofile.md#optional-sap_system)
* [sap_version](systemprofile.md#optional-sap_version)
* [satellite_managed](systemprofile.md#optional-satellite_managed)
* [selinux_config_file](systemprofile.md#optional-selinux_config_file)
* [selinux_current_mode](systemprofile.md#optional-selinux_current_mode)
* [subscription_auto_attach](systemprofile.md#optional-subscription_auto_attach)
* [subscription_status](systemprofile.md#optional-subscription_status)
* [system_memory_bytes](systemprofile.md#optional-system_memory_bytes)
* [tuned_profile](systemprofile.md#optional-tuned_profile)
* [yum_repos](systemprofile.md#optional-yum_repos)

## Properties

### `Optional` arch

• **arch**? : *string*

*Defined in [packages/host-inventory/api.ts:682](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L682)*

**`memberof`** SystemProfile

___

### `Optional` bios_release_date

• **bios_release_date**? : *string*

*Defined in [packages/host-inventory/api.ts:652](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L652)*

**`memberof`** SystemProfile

___

### `Optional` bios_vendor

• **bios_vendor**? : *string*

*Defined in [packages/host-inventory/api.ts:640](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L640)*

**`memberof`** SystemProfile

___

### `Optional` bios_version

• **bios_version**? : *string*

*Defined in [packages/host-inventory/api.ts:646](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L646)*

**`memberof`** SystemProfile

___

### `Optional` captured_date

• **captured_date**? : *string*

*Defined in [packages/host-inventory/api.ts:766](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L766)*

**`memberof`** SystemProfile

___

### `Optional` cloud_provider

• **cloud_provider**? : *string*

*Defined in [packages/host-inventory/api.ts:730](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L730)*

**`memberof`** SystemProfile

___

### `Optional` cores_per_socket

• **cores_per_socket**? : *number*

*Defined in [packages/host-inventory/api.ts:604](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L604)*

**`memberof`** SystemProfile

___

### `Optional` cpu_flags

• **cpu_flags**? : *Array‹string›*

*Defined in [packages/host-inventory/api.ts:658](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L658)*

**`memberof`** SystemProfile

___

### `Optional` disk_devices

• **disk_devices**? : *Array‹[DiskDevice](diskdevice.md)›*

*Defined in [packages/host-inventory/api.ts:634](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L634)*

**`memberof`** SystemProfile

___

### `Optional` dnf_modules

• **dnf_modules**? : *Array‹[DnfModule](dnfmodule.md)›*

*Defined in [packages/host-inventory/api.ts:742](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L742)*

**`memberof`** SystemProfile

___

### `Optional` enabled_services

• **enabled_services**? : *Array‹string›*

*Defined in [packages/host-inventory/api.ts:784](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L784)*

**`memberof`** SystemProfile

___

### `Optional` infrastructure_type

• **infrastructure_type**? : *string*

*Defined in [packages/host-inventory/api.ts:616](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L616)*

**`memberof`** SystemProfile

___

### `Optional` infrastructure_vendor

• **infrastructure_vendor**? : *string*

*Defined in [packages/host-inventory/api.ts:622](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L622)*

**`memberof`** SystemProfile

___

### `Optional` insights_client_version

• **insights_client_version**? : *string*

*Defined in [packages/host-inventory/api.ts:754](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L754)*

**`memberof`** SystemProfile

___

### `Optional` insights_egg_version

• **insights_egg_version**? : *string*

*Defined in [packages/host-inventory/api.ts:760](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L760)*

**`memberof`** SystemProfile

___

### `Optional` installed_packages

• **installed_packages**? : *Array‹string›*

*Defined in [packages/host-inventory/api.ts:772](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L772)*

**`memberof`** SystemProfile

___

### `Optional` installed_products

• **installed_products**? : *Array‹[InstalledProduct](installedproduct.md)›*

*Defined in [packages/host-inventory/api.ts:748](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L748)*

**`memberof`** SystemProfile

___

### `Optional` installed_services

• **installed_services**? : *Array‹string›*

*Defined in [packages/host-inventory/api.ts:778](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L778)*

**`memberof`** SystemProfile

___

### `Optional` katello_agent_running

• **katello_agent_running**? : *boolean*

*Defined in [packages/host-inventory/api.ts:718](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L718)*

**`memberof`** SystemProfile

___

### `Optional` kernel_modules

• **kernel_modules**? : *Array‹string›*

*Defined in [packages/host-inventory/api.ts:688](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L688)*

**`memberof`** SystemProfile

___

### `Optional` last_boot_time

• **last_boot_time**? : *string*

*Defined in [packages/host-inventory/api.ts:694](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L694)*

**`memberof`** SystemProfile

___

### `Optional` network_interfaces

• **network_interfaces**? : *Array‹[NetworkInterface](networkinterface.md)›*

*Defined in [packages/host-inventory/api.ts:628](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L628)*

**`memberof`** SystemProfile

___

### `Optional` number_of_cpus

• **number_of_cpus**? : *number*

*Defined in [packages/host-inventory/api.ts:592](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L592)*

**`memberof`** SystemProfile

___

### `Optional` number_of_sockets

• **number_of_sockets**? : *number*

*Defined in [packages/host-inventory/api.ts:598](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L598)*

**`memberof`** SystemProfile

___

### `Optional` operating_system

• **operating_system**? : *[OperatingSystem](operatingsystem.md)*

*Defined in [packages/host-inventory/api.ts:664](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L664)*

**`memberof`** SystemProfile

___

### `Optional` os_kernel_version

• **os_kernel_version**? : *string*

*Defined in [packages/host-inventory/api.ts:676](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L676)*

**`memberof`** SystemProfile

___

### `Optional` os_release

• **os_release**? : *string*

*Defined in [packages/host-inventory/api.ts:670](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L670)*

**`memberof`** SystemProfile

___

### `Optional` running_processes

• **running_processes**? : *Array‹string›*

*Defined in [packages/host-inventory/api.ts:700](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L700)*

**`memberof`** SystemProfile

___

### `Optional` sap_instance_number

• **sap_instance_number**? : *string*

*Defined in [packages/host-inventory/api.ts:802](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L802)*

The instance number of the SAP HANA system

**`memberof`** SystemProfile

___

### `Optional` sap_sids

• **sap_sids**? : *Array‹string›*

*Defined in [packages/host-inventory/api.ts:796](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L796)*

List of SAP SIDs

**`memberof`** SystemProfile

___

### `Optional` sap_system

• **sap_system**? : *boolean*

*Defined in [packages/host-inventory/api.ts:790](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L790)*

Indicates if SAP is installed on the system

**`memberof`** SystemProfile

___

### `Optional` sap_version

• **sap_version**? : *string*

*Defined in [packages/host-inventory/api.ts:808](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L808)*

The version of the SAP HANA lifecycle management program

**`memberof`** SystemProfile

___

### `Optional` satellite_managed

• **satellite_managed**? : *boolean*

*Defined in [packages/host-inventory/api.ts:724](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L724)*

**`memberof`** SystemProfile

___

### `Optional` selinux_config_file

• **selinux_config_file**? : *[SystemProfileSelinuxConfigFileEnum](../enums/systemprofileselinuxconfigfileenum.md)*

*Defined in [packages/host-inventory/api.ts:826](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L826)*

The SELinux mode provided in the config file

**`memberof`** SystemProfile

___

### `Optional` selinux_current_mode

• **selinux_current_mode**? : *[SystemProfileSelinuxCurrentModeEnum](../enums/systemprofileselinuxcurrentmodeenum.md)*

*Defined in [packages/host-inventory/api.ts:820](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L820)*

The current SELinux mode, either enforcing, permissive, or disabled

**`memberof`** SystemProfile

___

### `Optional` subscription_auto_attach

• **subscription_auto_attach**? : *string*

*Defined in [packages/host-inventory/api.ts:712](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L712)*

**`memberof`** SystemProfile

___

### `Optional` subscription_status

• **subscription_status**? : *string*

*Defined in [packages/host-inventory/api.ts:706](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L706)*

**`memberof`** SystemProfile

___

### `Optional` system_memory_bytes

• **system_memory_bytes**? : *number*

*Defined in [packages/host-inventory/api.ts:610](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L610)*

**`memberof`** SystemProfile

___

### `Optional` tuned_profile

• **tuned_profile**? : *string*

*Defined in [packages/host-inventory/api.ts:814](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L814)*

Current profile resulting from command tuned-adm active

**`memberof`** SystemProfile

___

### `Optional` yum_repos

• **yum_repos**? : *Array‹[YumRepo](yumrepo.md)›*

*Defined in [packages/host-inventory/api.ts:736](https://github.com/leSamo/javascript-clients/blob/master/packages/host-inventory/api.ts#L736)*

**`memberof`** SystemProfile
