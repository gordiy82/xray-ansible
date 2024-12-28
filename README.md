# Xray

```173.39.70.213``` - fake server for examples

## 1. Configure server with ansible

Run [xray](https://github.com/XTLS/Xray-core) in docker on the server:

```sh
ansible-playbook -i 173.39.70.213, xray.yml --ask-become-pass --diff
```

## 2. Configure client by QR-code

Copy client code:

```sh
scp user:pass@173.39.70.213:/etc/xray/qr_code.png .
```

MacOS + iOS client: [V2Box - V2ray Client](https://apps.apple.com/ru/app/v2box-v2ray-client/id6446814690)
