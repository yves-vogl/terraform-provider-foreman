
# foreman_operatingsystem


Foreman representation of an operating system.


## Example Usage

```
# Autogenerated example with required keys
resource "foreman_operatingsystem" "example" {
  major = "7"
  minor = "4"
  name = "CentOS"
}
```


## Argument Reference

The following arguments are supported:

- `architectures` - (Optional) Identifiers of attached architectures
- `description` - (Optional) Additional operating system information.
- `family` - (Optional) Operating system family. Values include: `"AIX"`, `"Altlinux"`, `"Archlinux"`, `"Coreos"`, `"Debian"`, `"Freebsd"`, `"Gentoo"`, `"Junos"`, `"NXOS"`, `"Redhat"`, `"Solaris"`, `"Suse"`, `"Windows"`.
- `major` - (Required) Major release version.
- `media` - (Optional) Identifiers of attached media
- `minor` - (Optional) Minor release version.
- `name` - (Required) Operating system name.
- `parameters` - (Optional) A map of parameters that will be saved as operating system parameters in the os config.
- `partitiontables` - (Optional) Identifiers of attached partition tables
- `password_hash` - (Optional) Root password hash function to use. Valid values include: `"MD5"`, `"SHA256"`, `"SHA512"`, `"Base64"`.
- `provisioning_templates` - (Optional) Identifiers of attached provisioning templates
- `release_name` - (Optional) Code name or release name for the specific operating system version.


## Attributes Reference

The following attributes are exported:

- `architectures` - Identifiers of attached architectures
- `description` - Additional operating system information.
- `family` - Operating system family. Values include: `"AIX"`, `"Altlinux"`, `"Archlinux"`, `"Coreos"`, `"Debian"`, `"Freebsd"`, `"Gentoo"`, `"Junos"`, `"NXOS"`, `"Redhat"`, `"Solaris"`, `"Suse"`, `"Windows"`.
- `major` - Major release version.
- `media` - Identifiers of attached media
- `minor` - Minor release version.
- `name` - Operating system name.
- `parameters` - A map of parameters that will be saved as operating system parameters in the os config.
- `partitiontables` - Identifiers of attached partition tables
- `password_hash` - Root password hash function to use. Valid values include: `"MD5"`, `"SHA256"`, `"SHA512"`, `"Base64"`.
- `provisioning_templates` - Identifiers of attached provisioning templates
- `release_name` - Code name or release name for the specific operating system version.
- `title` - The operating system's title is a concatentation of the OS name, major, and minor versions to get a full operating system release.

