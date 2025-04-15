
# 🚗 Simulador de Veículo

Este projeto é uma aplicação em TypeScript que simula o funcionamento básico de um veículo. Através de um menu interativo no terminal, é possível acelerar, frear, mudar de marcha e visualizar os dados do veículo.

---

## 📦 Funcionalidades

- Criação de um veículo com marca, modelo, potência e número de marchas
- Aceleração baseada na potência e marcha atual
- Subida e descida de marcha (em desenvolvimento)
- Impressão de dados do veículo
- Menu interativo no terminal

---

## ▶️ Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/simulador-veiculo.git
   ```

2. Instale as dependências:
   ```bash
   npm install
   ```

3. Execute o projeto:
   ```bash
   ts-node src/index.ts
   ```

> Certifique-se de ter o `ts-node` instalado globalmente ou como dependência de desenvolvimento.

---

## 📁 Estrutura do Projeto

```
src/
├── Veiculo.ts      # Classe que representa o veículo
└── index.ts        # Código principal com o menu interativo
```

---

## 🛠 Tecnologias Utilizadas

- TypeScript
- prompt-sync (entrada de dados no terminal)

---

## 📌 Notas

- Apenas a função de **acelerar** está implementada no momento.
- As demais opções do menu ainda estão pendentes de desenvolvimento.

---

## 📃 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

```

Se quiser, posso adicionar a parte da `classe Veiculo` também no README, ou ajudar a escrever um `package.json`. É só avisar!