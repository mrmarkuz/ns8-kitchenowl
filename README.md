# ns8-kitchenowl

[KitchenOwl](https://kitchenowl.org/) is a smart grocery list and recipe manager.

## Install

Install via Software center:

- Add a Software repository pointing to `https://repo.mrmarkuz.com/ns8/updates/`, check out the [repo webpage](https://repo.mrmarkuz.com/) how to do it.

Install via CLI:

    add-module ghcr.io/nethserver/kitchenowl:0.0.0 1

## Configure

Configure the FQDN an browse to `https://<FQDN>`

## Uninstall

To uninstall the instance:

    remove-module --no-preserve kitchenowl1
