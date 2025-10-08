# Hackaton Project

Este repositório contém duas aplicações:
- **DotNetApp**: API Web ASP.NET Core (.NET 8)
- **ReactNativeApp**: Aplicação mobile React Native

## 🚀 GitHub Actions

O pipeline de CI/CD está configurado em `.github/workflows/build.yml` e executa automaticamente:
- Build da aplicação .NET
- Build da aplicação React Native

## 📦 Estrutura do Projeto

```
.
├── .github/
│   └── workflows/
│       └── build.yml          # Pipeline CI/CD
├── DotNetApp/                 # API .NET 8
│   ├── Program.cs
│   └── DotNetApp.csproj
├── ReactNativeApp/            # App React Native
│   ├── App.js
│   ├── index.js
│   └── package.json
└── Time_2.sln                 # Solution .NET
```

## 🛠️ Como Executar

### .NET API
```bash
cd DotNetApp
dotnet restore
dotnet run
```

### React Native
```bash
cd ReactNativeApp
npm install  # ou yarn install
npm start
```

## 📝 Requisitos

- .NET 8.0 SDK
- Node.js 18+
- npm ou yarn
