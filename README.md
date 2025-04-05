# Landing Page - Curso DNC

Este repositório contém uma landing page desenvolvida como parte do curso da **Escola de Tecnologia DNC**. O objetivo do projeto é criar uma página de captura simples e responsiva, utilizando **HTML5**, **CSS3**, e integrando com o serviço **[Sheet Monkey](https://sheetmonkey.io/)** para envio dos dados de formulário diretamente para uma planilha.

## 🚀 Tecnologias Utilizadas

- HTML5
- CSS3
- Sheet Monkey (integração para submissão de dados)

## 💡 Funcionalidades

- Estrutura de página moderna com HTML5 semântica
- Estilização com CSS3 responsivo
- Formulário de captura de leads com campos personalizados
- Integração com o Sheet Monkey para armazenar os dados enviados

## 📸 Preview

![image](https://github.com/user-attachments/assets/8ca7a224-0e24-4fa3-b1a6-23028e75791e)

## ✉️ Como funciona a integração com o Sheet Monkey

1. Foi criado um formulário HTML com campos de nome, email, etc.
2. O atributo `action` do formulário aponta para a URL gerada pelo Sheet Monkey.
3. Os dados são enviados diretamente para uma planilha conectada ao serviço.

Exemplo de código do formulário:

```html
<form action="https://api.sheetmonkey.io/form/SEU_ID_UNICO" method="POST">
  <input type="text" name="Nome" placeholder="Digite seu nome" required />
  <input type="email" name="Email" placeholder="Digite seu email" required />
  <button type="submit">Enviar</button>
</form>


