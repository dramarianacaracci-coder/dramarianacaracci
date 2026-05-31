# Security Policy (Política de Segurança)

Este documento define a nossa política para a comunicação e resolução de vulnerabilidades de segurança encontradas no código do nosso site e sistemas de automação integrados.

## Versões Suportadas (Supported Versions)

Atualmente, fornecemos atualizações de segurança e correções de bugs apenas para a versão ativa e em produção do nosso ecossistema.

| Versão | Suportada | Notas |
| :--- | :---: | :--- |
| Produção (Main branch) | :white_check_mark: | Versão estável rodando no site atual. |
| Desenvolvimento / Testes | :warning: | Apenas vulnerabilidades críticas serão avaliadas. |
| Versões Anteriores | :x: | Não são mais suportadas. |

## Como Reportar uma Vulnerabilidade (Reporting a Vulnerability)

**Por favor, não abra uma Issue pública para relatar uma falha de segurança.** Isso expõe o site e os sistemas a riscos desnecessários antes que possamos corrigi-lo.

### Método Recomendado: Reporte Privado do GitHub
A forma mais segura de nos contactar é utilizando o recurso nativo de **Private Vulnerability Reporting** do próprio GitHub:
1. Vá até a aba **Security** (Segurança) deste repositório.
2. Clique em **Vulnerabilities** na barra lateral.
3. Clique em **Report a vulnerability** para enviar os detalhes de forma privada e segura diretamente para a nossa equipe.

### Método Alternativo: E-mail direto
Se preferir, ou se encontrar problemas na plataforma, envie um e-mail detalhado para:
👉 **dramarianacaracci@gmail.com**

### O que incluir no seu relatório:
- Uma descrição clara da vulnerabilidade encontrada.
- Passos detalhados para reproduzir o problema (Proof of Concept - PoC), incluindo scripts, prints ou payloads, se aplicável.
- O impacto potencial que essa falha pode gerar no site ou nos dados coletados.

### O que você pode esperar de nós:
- **Confirmação:** Responderemos em até 48 horas úteis confirmando o recebimento do seu relatório.
- **Atualizações:** Manteremos você informado sobre o progresso da investigação e da correção a cada 3 a 5 dias.
- **Resolução:** Assim que a falha for validada e corrigida, faremos o deploy imediatamente.
