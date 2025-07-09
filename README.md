
# Checklist de Implantação

Ferramenta desenvolvida para auxiliar no processo de implantação de sistemas em ambientes de varejo, padronizando as etapas técnicas e operacionais envolvidas. Permite acompanhar o progresso das tarefas por meio de um checklist interativo com gráfico de status em tempo real, além de recursos para impressão e envio por e-mail.

## Funcionalidades

- Checklist completo com mais de 50 etapas organizadas por categoria
- Salvamento automático do progresso no navegador
- Gráfico de progresso dinâmico
- Botões para imprimir ou enviar o checklist por e-mail
- Interface responsiva, compatível com desktop e dispositivos móveis

## Como usar

1. Abrir o arquivo `index.html` em qualquer navegador moderno ou acessar diretamente via GitHub Pages.
2. Preencher o campo “Nome do cliente” no topo da página.
3. Marcar os itens conforme forem sendo concluídos.
4. A barra de progresso será atualizada automaticamente com base no número de tarefas realizadas.
5. O progresso será salvo localmente no navegador, mesmo após recarregar a página.
6. Ao finalizar, você pode:
   - Clicar em “Imprimir” para gerar uma versão física
   - Ou clicar em “Enviar no e-mail” para disparar um resumo das atividades via EmailJS

## Personalização

- Logo: Substitua o arquivo `logo.png` pela identidade visual da sua empresa.
- Checklist: Os itens podem ser editados diretamente no HTML, seguindo o padrão utilizado nas tags `<ul>` e `<li>`.
- Envio por e-mail:
  - Configure seu próprio serviço e template no [EmailJS](https://www.emailjs.com/)
  - Substitua as chaves no trecho `emailjs.init(...)` e `emailjs.send(...)` com suas credenciais.

## Requisitos

- Navegador atualizado (Chrome, Firefox, Edge ou Safari)
- Conexão com a internet para utilizar o EmailJS e os recursos via CDN (Bootstrap, Chart.js)

## Observações

Este projeto pode ser adaptado livremente para outras realidades e equipes. A estrutura foi pensada para facilitar o dia a dia técnico de implantações, minimizando esquecimentos e otimizando o processo de documentação das atividades.
