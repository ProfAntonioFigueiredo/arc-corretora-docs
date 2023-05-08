<div align="left">

# Firewall

<div align="right">

### ⬅️ [Voltar](/README.md)

</div>

</div>

## Matriz

- ### Informações:

  - Fabricante: Fortinet
  - Modelo: Fortigate 40F
  - Serial Number: FGT40FTK2209AM3C
  - Hostname: ARCMTZFGTFW01
  - Acesso externo: https://mtz.arccorretora.fortiddns.com:8443
  - <details>
    <summary>Credenciais</summary>

    ```bash
    Login: supptec
    Senha: n5Yk7%Jg52ng
    ```

    </details>

- ### Mapa de interfaces

  | Interface | Descrição               | Observações                        |
  | --------- | ----------------------- | ---------------------------------- |
  | WAN       | Link Vivo               |                                    |
  | A         | Link Claro              |                                    |
  | LAN 1     | Management Interface    | Address: https://192.168.0.99:8443 |
  | LAN 2     | Switch Link Aggregation |                                    |
  | LAN 3     | Switch Link Aggregation |                                    |

  <br>

- ### Mapa de VLANs
  | VLAN Name       | VLAN ID | IP                | DHCP Range                  |
  | --------------- | ------- | ----------------- | --------------------------- |
  | Infra           | 1       | 172.16.1.254/24   | 172.16.1.1-172.16.1.200     |
  | Servidores      | 10      | 172.16.10.254/24  | 172.16.10.1-172.16.10.200   |
  | Impressoras     | 50      | 172.16.50.254/24  | 172.16.50.1-172.16.50.200   |
  | Estações        | 100     | 172.16.100.254/24 | 172.16.100.1-172.16.100.200 |
  | WiFi_MGMT       | 1000    | 10.0.0.254/24     | 10.0.0.1-10.0.0.200         |
  | WiFi_Internal   | 1001    | 10.0.1.254/24     | 10.0.1.1-10.0.1.200         |
  | WiFi_Colab      | 1100    | 10.0.100.254/24   | 10.0.100.1-10.0.100.200     |
  | WiFi_Visitantes | 1101    | 10.0.101.254/24   | 10.0.101.1-10.0.101.200     |

<br>

---

<br>

## Filial - XV de Novembro

- ### Informações:

  - Fabricante: Fortinet
  - Modelo: Fortigate 40F
  - Serial Number: FGT40FTK2209AMNV
  - Hostname: ARCXVNFGTFW01
  - Acesso externo: https://xvn.arccorretora.fortiddns.com:8443
  - <details>
    <summary>Credenciais</summary>

    ```bash
    Login: supptec
    Senha: n5Yk7%Jg52ng
    ```

    </details>

- ### Mapa de interfaces

  | Interface | Descrição               | Observações                        |
  | --------- | ----------------------- | ---------------------------------- |
  | WAN       | Link Vivo               |                                    |
  | LAN 1     | Management Interface    | Address: https://192.168.0.99:8443 |
  | LAN 2     | Switch Link Aggregation |                                    |
  | LAN 3     | Switch Link Aggregation |                                    |

- ### Mapa de VLANs

  | VLAN Name  | VLAN ID | IP               | DHCP Range                |
  | ---------- | ------- | ---------------- | ------------------------- |
  | Infra      | 1       | 172.16.2.254/24  | 172.16.2.1-172.16.1.200   |
  | Servidores | 10      | 172.16.20.254/24 | 172.16.20.1-172.16.20.200 |
