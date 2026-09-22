# Ansible Playbooks

Repositório destinado ao armazenamento e versionamento de playbooks Ansible.

## Estrutura

- `linux/`: playbooks para servidores Linux
- `windows/`: playbooks para servidores Windows
- `inventories/`: inventários dos ambientes
- `group_vars/`: variáveis por grupo
- `host_vars/`: variáveis específicas por servidor

- Limpeza de filas de impressao no AWX
- Adaptacao de Limpeza_Filas_printers_Zabbix_Script.ps1. Remove trabalhos pendentes de impressao e arquivos dos logs SAPSprint, preservando .dbg (sem diferenciar maiusculas). Nao remove pastas nem percorre subpastas. Inclui arquivos ocultos.

- Diagnostico Windows / WinRM no AWX
- O alerta da imagem informa porta 6791 indisponivel, associada a APP - SAP BW. Ele nao identifica o processo ou servico Windows responsavel. Este playbook coleta evidencias e classifica o problema sem presumir uma causa-raiz.

- 
