# 🛡️ Projeto SF Cyber | Academia CiberSegurança e Redes

### 📡 Simulador do Switch Cisco para criação de VLANs

![Simulador de VLANs](https://github.com/user-attachments/assets/d4a11aad-0e1f-4a38-a375-e183a9e93ce4)

Simulador **interativo e educativo** de um switch Cisco 🖥️ para ensinar **VLANs (Virtual Local Area Networks)** de forma prática e divertida. Ideal para alunos de **CiberSegurança e Redes** que querem aprender a configurar switches usando comandos Cisco reais, sem precisar de equipamentos físicos!

---

## ✨ Funcionalidades

- 🖱️ **Terminal Cisco realista** digite comandos como `configure terminal`, `vlan 10`, `switchport mode access` e veja o resultado em tempo real.
- 🧭 **6 níveis progressivos** do básico (criar VLAN) até a configuração completa do switch.
- 🤖 **Assistente virtual (SF Bot)** acompanha o aluno, dá dicas e mostra o próximo passo.
- 💡 **Dicas e revisão teórica** modal de conceitos para reforçar o aprendizado.
- 🗺️ **Mapa de níveis** visualize seu progresso.
- 🧪 **Teste de conectividade (Ping)** simule ping entre PCs e descubra se estão na mesma VLAN.
- 📝 **Prova final** questionário com 6 perguntas para testar o conhecimento.
- 🎓 **Certificado de conclusão** com nome do aluno, pontuação e data (pronto para imprimir).
- 💾 **Salvamento automático** seu progresso fica salvo no navegador (localStorage) e pode ser retomado.
- ⌨️ **Autocomplete** sugestões de comandos conforme você digita.
- 🌐 **Totalmente em português** (pt-BR).

---

## 🚀 Como usar

1. Acesse o site 🌐 https://redevirtual.projetosdisruptivos.com.br/ ou baixe o arquivo `index.html`.
2. Abra o arquivo no navegador (Google Chrome, Edge, Firefox, etc.) — **não precisa instalar nada!** 🎉
3. Digite seu **nome do aluno** na tela inicial e clique em **🚀 Começar!**
4. Leia as instruções, digite os comandos no terminal e complete os 6 níveis.

> 💡 **Dica:** use o botão **📚 Revisão** para consultar os conceitos a qualquer momento e o painel **📖 Referência de Comandos** para não esquecer a sintaxe!

---

## 🗺️ Os 6 Níveis do Jogo

| Nível | Objetivo | Conteúdo |
|:---:|:---|:---|
| 1 | **Criando sua primeira VLAN** | Criar a VLAN 10 (`vlan 10`) |
| 2 | **Nomeando a VLAN** | Dar nome à VLAN (`name TI`) |
| 3 | **Criando múltiplas VLANs** | Criar novas VLANs para separar as redes da empresa |
| 4 | **Atribuindo portas às VLANs** | Configurar portas como access e associá-las às VLANs |
| 5 | **Portas Trunk** | Configurar porta trunk para transportar várias VLANs |
| 6 | **Configuração Completa** | Finalizar e **salvar** a configuração (`copy running-config startup-config`) |

Após o nível 6, você faz a **📝 Prova Final** e, ao concluir, recebe seu **🎓 Certificado**!

---

## ⌨️ Comandos Disponíveis

| Comando | Descrição |
|:---|:---|
| `clear` / `cls` | Limpar a tela do terminal |
| `configure terminal` | Entrar no modo de configuração |
| `copy running-config startup-config` | Salvar a configuração |
| `description <texto>` | Descrever a porta |
| `exit` | Sair do modo atual |
| `hostname <nome>` | Definir o nome do switch |
| `interface <porta>` | Selecionar uma interface |
| `name <nome>` | Nomear a VLAN |
| `show interfaces status` | Ver o status das portas |
| `show running-config` | Ver a configuração atual |
| `show vlan brief` | Ver o resumo das VLANs |
| `switchport access vlan <id>` | Atribuir a porta a uma VLAN |
| `switchport mode access` | Definir a porta como **access** |
| `switchport mode trunk` | Definir a porta como **trunk** |
| `switchport trunk allowed vlan` | Permitir VLANs em uma porta trunk |
| `vlan <id>` | Criar/selecionar uma VLAN |

Digite `ajuda` no terminal para ver todos os comandos.

---

## 🧪 Teste de Conectividade (Ping)

Após configurar as VLANs, você pode:

1. Selecionar os PCs de **origem** e **destino** no painel **Teste de Conectividade**.
2. Clicar em **📨 Enviar Ping** e ver a animação do pacote no canvas. 🎬
3. Usar o botão **➕ Colocar PCs nas VLANs** para associar os PCs (PC1 a PC4) às VLANs criadas e testar diferentes cenários.

**Resultado:** PCs na **mesma VLAN** → ping com sucesso ✅. PCs em **VLANs diferentes** → tráfego bloqueado (domínios de broadcast separados) ❌.

---

## 📚 Conceitos Teóricos (Revisão)

- 🌐 **VLAN** — divide um switch físico em redes lógicas independentes, como se fossem switches separados.
- 📡 **Domínio de broadcast** o tráfego (ex.: ARP) só é entregue dentro da própria VLAN, reduzindo tráfego e aumentando a segurança.
- 🔌 **Porta Access** pertence a uma única VLAN; usada para PCs, impressoras e servidores.
- 🔗 **Porta Trunk** carrega várias VLANs entre switches usando **tags 802.1Q** (uplink entre switches).
- 🏷️ **Tag 802.1Q** rótulo inserido no quadro Ethernet para identificar a VLAN no link trunk.
- 💾 **Salvar configuração** "copy running-config startup-config" grava na NVRAM, mantendo as configurações após reiniciar o switch.

---

## 🏆 Pontuação

- Complete cada nível para ganhar pontos (quanto menos tentativas, mais pontos!).
- Responda a prova final corretamente para ganhar **pontos bônus**.
- No final, veja sua **pontuação total** no certificado. 🎓

---

## 📜 Licença

**Gratuito para uso educacional** Professores e Instituições podem utilizar e adaptar o projeto para suas atividades de ensino. 🎓✨
