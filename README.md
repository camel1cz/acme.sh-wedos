# acme.sh-wedos

Umožňuje autorizaci SSL certifikátů pomocí DNS spravovaném v prostředí WEDOS.

## Založeno na kódu:
https://github.com/acmesh-official/acme.sh/pull/2980/commits

## Využívá WEDOS API:
https://github.com/acmesh-official/acme.sh/pull/2980/commits

### Nastavení přístupu:
https://kb.wedos.com/cs/wapi-api-interface/wapi-activation-and-settings/

### Spuštění
export WEDOS_User=xxx
export WEDOS_Pass=xxx
acme.sh ... --dns dns_wedos
