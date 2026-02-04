# Diário de Analise de Incidentes( Laboratório )

## 📖 Cenário

Uma pequena clínica de saúde dos EUA, especializada na prestação de serviços de cuidados primários, sofreu um incidente de segurança em uma manhã de terça-feira, aproximadamente às 9h00. 

Vários funcionários relataram que não conseguiam usar seus computadores para acessar arquivos de computador, como registros médicos. As operações comerciais foram interrompidas porque os funcionários não conseguiram acessar os arquivos e o software necessários para realizar seu trabalho.

Além disso, os funcionários também relataram que um bilhete de resgate foi exibido em seus computadores. A nota de resgate informava que todos os arquivos da empresa haviam sido criptografados por um grupo organizado de hackers antiéticos, conhecidos por atacar organizações dos setores de saúde e transporte. Em troca de restaurar o acesso aos arquivos criptografados, a nota de resgate exigia uma grande soma de dinheiro em troca da chave de descriptografia.

Os atacantes conseguiram obter acesso à rede da empresa usando e-mails de phishing direcionados, que foram enviados a vários funcionários da empresa. Os e-mails de phishing continham um anexo malicioso que instalava malware no computador do funcionário depois de baixado.

Depois que os invasores obtiveram acesso, eles implantaram o ransomware, que criptografou arquivos essenciais. A empresa não conseguiu acessar os dados críticos dos pacientes, causando grandes interrupções em suas operações comerciais. A empresa foi forçada a desligar seus sistemas de computador e entrar em contato com várias organizações para relatar o incidente e receber assistência técnica.

---

## 📋 Diário de Análise de Incidentes

**Data:** 04, Fevereiro de 2026  
**Numeração:** 01  
**Descrição:** Incidente de Segurança 0900-T: Interrupção de Operações Comerciais - Setor de Saúde

### Ferramentas Utilizadas
- Logs do FG
- Splunk
- CrowdStrike

### Padrão 5W

**● Quem causou o Incidente?**  
Um grupo organizado de hackers antiéticos.

**● O que aconteceu?**  
Implantação de um ransomware que criptografou os dados.

**● Quando ocorreu?**  
Na terça-feira dia 03 de Fevereiro de 2026, às 09:00 no horário de Brasília.

**● Onde ocorreu o Incidente?**  
Clínica de Saúde localizada nos EUA (Estados Unidos da América).

**● Por quê ocorreu?**  
Vetor de entrada via Engenharia Social (Phishing), resultando na execução de código arbitrário e implantação de Ransomware.

### Notas

**Isolamento:** Recomendado o isolamento imediato da máquina infectada da rede local para impedir a propagação do Ransomware para outros servidores.

**Backup:** Verificação da integridade dos backups offline, já que os dados locais foram criptografados e estão inacessíveis.
