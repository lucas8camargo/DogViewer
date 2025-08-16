# Dog Viewer - Blazor WebAssembly

Um aplicativo web simples feito com **Blazor WebAssembly** que consome a API pública [Dog CEO](https://dog.ceo/dog-api/) para exibir imagens aleatórias de cachorros.

## Como Funciona
- Exibe uma imagem aleatória de cachorro no centro da tela.
- Botão **"Nova Imagem"** para gerar outra imagem.
- Botão **"Abrir imagem"** para abrir a imagem inteira em uma nova guia.
- Totalmente **frontend** (não há backend).

# Demonstração

Site hospedado no Azure utiilizando o Azure Static Web Apps (Plano Free)

https://agreeable-smoke-0871bb610.1.azurestaticapps.net/

## Tecnologias Utilizadas

- [.NET 8](https://dotnet.microsoft.com/) (Blazor WebAssembly)
- [Dog CEO API](https://dog.ceo/dog-api/)
- HTML5 / CSS3
- C#

## Como Executar

1. **Clonar o repositório**

```bash
git clone https://github.com/seuusuario/DogViewer.git

cd DogViewer
```

2. Restaurar dependências
```bash
dotnet restore
```

3. Rodar o projeto
```bash
dotnet run
```

