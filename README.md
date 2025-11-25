# Protótipo Mobile Dashboard Operacional

Um projeto Flutter projetado para web - dashboard operacional.

## Sobre o Projeto

Este é um protótipo de dashboard operacional desenvolvido com Flutter, otimizado para execução em navegadores web. O projeto fornece uma estrutura básica para um painel de controle operacional com interface moderna e responsiva.

## Estrutura do Projeto

```
prototipo-mobile-dashboard-operacional/
├── lib/
│   └── main.dart          # Ponto de entrada da aplicação
├── web/
│   ├── index.html         # HTML principal da aplicação web
│   ├── manifest.json      # Configurações PWA
│   ├── favicon.png        # Ícone do site
│   └── icons/             # Ícones para PWA
├── test/                  # Testes da aplicação
├── pubspec.yaml           # Dependências do projeto
└── analysis_options.yaml  # Configurações de análise de código

```

## Começando

### Pré-requisitos

- Flutter SDK (versão 3.0.0 ou superior)
- Navegador web moderno (Chrome, Firefox, Safari, Edge)

### Instalação

1. Clone o repositório:
```bash
git clone https://github.com/SamuelGFDias/prototipo-mobile-dashboard-operacional.git
cd prototipo-mobile-dashboard-operacional
```

2. Instale as dependências:
```bash
flutter pub get
```

### Executando o Projeto

Para executar o projeto em modo de desenvolvimento:

```bash
flutter run -d chrome
```

ou para executar em qualquer navegador disponível:

```bash
flutter run -d web-server
```

### Build para Produção

Para gerar os arquivos de build otimizados para produção:

```bash
flutter build web
```

Os arquivos compilados estarão disponíveis no diretório `build/web/`.

## Recursos

- Interface moderna com Material Design 3
- Suporte para Progressive Web App (PWA)
- Responsivo e otimizado para diferentes tamanhos de tela
- Estrutura organizada e escalável

## Tecnologias Utilizadas

- **Flutter**: Framework principal para desenvolvimento
- **Dart**: Linguagem de programação
- **Material Design 3**: Sistema de design para interface do usuário

## Desenvolvimento

### Estrutura de Código

O código segue as melhores práticas do Flutter e Dart, incluindo:
- Uso de widgets stateless e stateful apropriadamente
- Código limpo e bem organizado
- Análise estática com flutter_lints

### Linting

O projeto utiliza o pacote `flutter_lints` para garantir qualidade de código. Execute:

```bash
flutter analyze
```

## Licença

Este projeto é um protótipo para fins educacionais e de demonstração.

## Contato

Samuel G F Dias - [GitHub](https://github.com/SamuelGFDias)