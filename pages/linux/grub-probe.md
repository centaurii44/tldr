# grub-probe

> Retrieve info about a drive or partition.
> More information: <http://manned.org/grub-probe.8>.

- Find what filesystem is installed on a specific partition:

`sudo grub-probe --target=fs --device {{/dev/sda1}}`

- Find the UUID of a partition:

`sudo grub-probe --target=partuuid --device {{/dev/sda1}}`
