# 🖥️ Script Profissional de Suporte N1 com Logs

![PowerShell](https://img.shields.io/badge/PowerShell-5%2B-blue?logo=powershell)
![Status](https://img.shields.io/badge/Status-Ativo-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow)

> 🔧 Automação completa para **Suporte N1** no Windows, com logs organizados e funções essenciais para diagnóstico e manutenção.

---

## 📺 Demonstração Visual

### Menu Interativo (simulação em ASCII)

```text
=========================================
   Suporte N1 Profissional - Menu Interativo
=========================================
1. Limpar arquivos temporários
2. Limpar cache do Power BI
3. Limpar navegadores (Chrome, Edge, Firefox)
4. Verificar integridade do Windows
5. Testar conexão de rede
6. Atualizar Windows
7. Reiniciar máquina
8. Relatório de hardware e software
9. Resetar rede
10. Backup rápido (zip) de Documentos e Desktop
11. Verificar serviços essenciais
12. Scan rápido Windows Defender
13. Inventário de processos pesados
14. Sair
=========================================
✨ Funcionalidades

🧹 Limpeza de arquivos temporários

📊 Limpeza de cache Power BI

🌐 Limpeza de cache e histórico de navegadores (Chrome, Edge, Firefox)

🛠️ Verificação de integridade do Windows (sfc /scannow)

📡 Teste e diagnóstico de rede

🔄 Reset de rede (release/renew + flush DNS)

💾 Backup rápido e compactado de Documentos e Desktop

🖥️ Relatório de hardware e software

🧩 Verificação de serviços essenciais (Windows Update, Spooler, Firewall)

🛡️ Scan rápido do Windows Defender

📈 Inventário de processos pesados (CPU)

🔁 Atualização do Windows via PSWindowsUpdate

🖲️ Opção de reinício imediato da máquina

📝 Geração de logs únicos por sessão em C:\SuporteN1_Logs

📋 Pré-requisitos

Windows 10 ou superior

PowerShell 5.1+ ou PowerShell Core

Permissões de administrador 👨‍💻


🚀 Como usar

Clone este repositório:

git clone https://github.com/SeuUsuario/SuporteN1.git


Acesse a pasta do projeto:

cd SuporteN1


Execute o script como Administrador:

.\SuporteN1.ps1

📂 Estrutura de Logs

Todos os relatórios ficam em:

C:\SuporteN1_Logs\
│── Log_SuporteN1_20250914_103500.txt
│── Verificacao_Integridade_20250914_103600.txt
│── Teste_Rede_20250914_104200.txt
│── Relatorio_HW_SW_20250914_104800.txt
│── ...
