
# 📸 Feed-Insta

Este é um aplicativo mobile construído com **React Native** que simula o **feed do Instagram**. Você verá postagens com imagens, nomes de usuários, descrições e poderá **curtir ou descurtir** as publicações — exatamente como no Instagram real, mas em versão simplificada.

![React Native](https://img.shields.io/badge/react--native-mobile--app-blueviolet)

## ✨ Funcionalidades

- Exibição de postagens com:
  - Foto de perfil
  - Nome do usuário
  - Imagem da publicação
  - Descrição
  - Número de curtidas
- Ação de "curtir/descurtir" com troca dinâmica de ícone
- Scroll de feed com `FlatList`
- Interface inspirada na estrutura do Instagram

---

## 🚀 Como rodar o projeto

> **Nota:** Certifique-se de seguir o guia oficial de configuração do ambiente React Native:  
> 👉 [Set up Your Environment](https://reactnative.dev/docs/environment-setup)

### 1. Clone o repositório

```bash
git clone https://github.com/jefferson-barroso/Feed-Insta.git
cd Feed-Insta
````

### 2. Instale as dependências

```bash
# Usando npm
npm install

# ou Yarn
yarn
```

---

### 3. Inicie o servidor Metro

```bash
# npm
npm start

# ou Yarn
yarn start
```

---

### 4. Execute o app no emulador ou dispositivo

#### Android

```bash
npm run android
# ou
yarn android
```

#### iOS (Mac apenas)

> Antes de tudo, instale os pods com:

```bash
cd ios
pod install
```

Depois, execute:

```bash
npm run ios
# ou
yarn ios
```

---

## 🛠️ Estrutura de Componentes

* `App.tsx`: Componente principal que renderiza o feed
* `src/lista/index.jsx`: Componente que representa cada item da lista (post)
* `src/img/`: Imagens locais como ícones de like e botão de envio

---

## 🖼️ Imagens de exemplo

As imagens e perfis são carregados de forma remota a partir do site [sujeitoprogramador.com](https://sujeitoprogramador.com).

---

## ♻️ Fast Refresh

O app suporta **Fast Refresh**, ou seja, atualiza automaticamente quando você salva alterações nos arquivos.

### Recarga manual

* **Android**: Pressione <kbd>R</kbd> duas vezes no terminal ou use <kbd>Ctrl</kbd> + <kbd>M</kbd> para abrir o menu de desenvolvedor.
* **iOS**: Pressione <kbd>Cmd ⌘</kbd> + <kbd>R</kbd> no simulador.

---

## 🧪 Testado em

* ✅ React Native CLI
* ✅ Dispositivo Android físico
* ✅ Emulador Android
* (iOS não testado, mas suportado)

---

## 📚 Saiba mais

* [Documentação Oficial](https://reactnative.dev/docs/getting-started)
* [Integração com apps existentes](https://reactnative.dev/docs/integration-with-existing-apps)
* [Fast Refresh](https://reactnative.dev/docs/fast-refresh)

---

## 🐛 Suporte e Problemas

Se você tiver qualquer dificuldade, consulte:

* [React Native Troubleshooting](https://reactnative.dev/docs/troubleshooting)
* [Issues no GitHub](https://github.com/jefferson-barroso/Feed-Insta/issues)

---

## 🎉 Parabéns!

Você está usando e modificando um app React Native funcional. Aproveite para praticar e evoluir!

---

> Projeto criado para fins de estudo e prática com React Native.

```

