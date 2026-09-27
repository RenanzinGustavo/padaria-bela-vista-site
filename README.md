# Padaria Bela Vista

Site institucional desenvolvido para a "Padaria e Conveniência Bela Vista" como projeto acadêmico.

O projeto tem como objetivo apresentar as principais informações do estabelecimento de forma simples e organizada, incluindo horários de funcionamento, cardápios, localização e formas de contato.

## 📋 Visão geral

O site foi desenvolvido utilizando HTML5 e CSS3, com foco na criação de uma página institucional responsiva.

Por meio do site, o usuário pode consultar:

- Informações sobre a padaria;
- Horários de funcionamento;
- Cardápios;
- Localização;
- Telefone;
- WhatsApp;
- Instagram;
- E-mail.

## 🛠️ Tecnologias utilizadas

- **HTML5** — estruturação do conteúdo da página;
- **CSS3** — estilização, layout e responsividade;
- **Google Maps** — integração do mapa de localização;
- **PDF** — disponibilização dos cardápios.

## 📋 Requisitos

Para executar o projeto, é necessário apenas:

- Um navegador web atualizado;
- Git, caso queira clonar o repositório;
- Visual Studio Code, caso queira editar o projeto.

Não é necessário instalar bibliotecas, frameworks ou banco de dados.

## 📁 Estrutura do projeto

```text
padaria-bela-vista-site/
├── README.md
├── index.html
├── css/
│   └── style.css
└── public/
    ├── images/
    │   ├── bread.png
    │   ├── email (1).png
    │   ├── instagram.png
    │   ├── logo.png
    │   ├── loja.png
    │   ├── padaria.jpeg
    │   ├── ramo.png
    │   ├── relogio.png
    │   ├── sobre.png
    │   ├── sobre1.png
    │   ├── telefone.png
    │   └── whatsapp.png
    │
    └── pdf/
        ├── 5.pdf
        ├── espetinho.pdf
        ├── jantinha.pdf
        ├── pasteis.pdf
        └── porções.pdf
```

## 🚀 Instalação

### Clonando o repositório

Para baixar o projeto utilizando Git:

```bash
git clone https://github.com/erickhlnascimento-ops/padaria-bela-vista-site.git
```

Depois, entre na pasta:

```bash
cd padaria-bela-vista-site
```

Não é necessária nenhuma instalação adicional.

## ▶️ Como executar

Após baixar o projeto, abra o arquivo:

```text
index.html
```

em um navegador web.

Outra opção é abrir a pasta do projeto no **Visual Studio Code** e utilizar a extensão **Live Server**.

## 💻 Utilização

Ao abrir o site, o usuário pode navegar pelas diferentes seções utilizando o menu principal.

Entre as opções disponíveis estão:

- **Início:** apresentação inicial do estabelecimento;
- **Sobre:** informações sobre a Padaria Bela Vista;
- **Cardápios:** acesso aos diferentes cardápios em PDF;
- **Contato:** informações para entrar em contato com o estabelecimento;
- **Localização:** endereço e mapa integrado.

Os cardápios podem ser acessados pelos respectivos botões disponíveis na seção de cardápios.

## 🕐 Horário de funcionamento

O site apresenta os seguintes horários:

- **Segunda a sábado:** 6:00 às 22:00;
- **Domingos e feriados:** 6:00 às 14:00.

## 📍 Localização

**R. José Facciolla, 180 - Parque Xangrilá - Campinas**

A página também possui um mapa integrado do Google Maps para auxiliar o usuário a encontrar o estabelecimento.

## 📱 Responsividade

O site possui regras de CSS para adaptar a apresentação da página a diferentes tamanhos de tela.

São considerados diferentes formatos de dispositivos, incluindo:

- Computadores;
- Tablets;
- Celulares.

## 🐛 Solução de problemas

### As imagens não aparecem

Verifique se a pasta `public/images` foi baixada junto com o projeto e se os arquivos permanecem nos mesmos diretórios.

### Os cardápios não abrem

Verifique se os arquivos PDF estão presentes na pasta:

```text
public/pdf/
```

Também é importante não alterar os nomes dos arquivos ou seus caminhos sem atualizar os links presentes no `index.html`.

### O layout não aparece corretamente

Verifique se o arquivo:

```text
css/style.css
```

está presente e se o caminho utilizado no `index.html` está correto.

### O mapa não aparece

O mapa depende do conteúdo incorporado do Google Maps e de uma conexão com a internet. Verifique sua conexão caso o mapa não seja carregado.

## 📚 Referências e recursos

- [Google Maps](https://www.google.com/maps/)
- [MDN Web Docs - HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
- [MDN Web Docs - CSS](https://developer.mozilla.org/pt-BR/docs/Web/CSS)

## 🎓 Projeto acadêmico

Este projeto foi desenvolvido para fins acadêmicos, com o objetivo de aplicar conhecimentos de desenvolvimento web, estruturação de páginas HTML, estilização com CSS, organização de arquivos e criação de uma interface responsiva.

## 📄 Licença

Projeto desenvolvido para fins acadêmicos.
