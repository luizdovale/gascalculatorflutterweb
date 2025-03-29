# Calculadora de Gases Flutter Web

![Licença](https://img.shields.io/badge/license-MIT-blue.svg)

## Índice

- [Descrição](#descrição)
- [Funcionalidades](#funcionalidades)
- [Instalação](#instalação)
- [Como Usar](#como-usar)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Contribuição](#contribuição)
- [Licença](#licença)

## Descrição

A *Calculadora de Gases* é um aplicativo desenvolvido em **Flutter** que permite calcular o peso líquido e o volume em metros cúbicos (m³) de gases do ar, como Nitrogênio, Oxigênio e Argônio, com base nas polegadas descarregadas. O projeto foi criado para facilitar o processo de cálculo após o descarregamento dos produtos, oferecendo uma interface intuitiva e eficiente.

## Funcionalidades

- Cálculo de peso líquido e volume (em m³) para Nitrogênio, Oxigênio e Argônio.
- Interface simples e amigável com campos para nível inicial, nível final e fator.
- Botão de limpeza rápida dos campos e dos resultados.
- Modo escuro para melhor experiência do usuário.
- Responsivo e acessível em diferentes dispositivos.

## Instalação

1. Clone este repositório para sua máquina local:

    ```bash
    git clone https://github.com/seu-usuario/nome-do-repositorio.git
    ```

2. Navegue até o diretório do projeto:

    ```bash
    cd nome-do-repositorio
    ```

3. Instale as dependências do Flutter:

    ```bash
    flutter pub get
    ```

4. Execute o aplicativo:

    ```bash
    flutter run
    ```

Se desejar gerar a versão para Web, utilize:

```bash
flutter build web
```

E acesse a pasta `build/web` para obter os arquivos da aplicação.

## Como Usar

1. Insira o **fator** do gás que deseja calcular no campo correspondente.
2. Preencha os campos de **Nível Inicial** e **Nível Final**.
3. Selecione o gás que deseja calcular (Nitrogênio, Oxigênio ou Argônio) pressionando o respectivo botão.
4. O resultado será exibido nos campos de **Peso Líquido** e **M³**.
5. Use o botão **Limpar** para resetar todos os campos e realizar novos cálculos.

## Tecnologias Utilizadas

- **Flutter**: Framework principal para o desenvolvimento do aplicativo.
- **Dart**: Linguagem de programação utilizada no desenvolvimento.
- **Provider** (ou outro gerenciador de estado, caso aplicável).
- **Material Design** para estilização e componentes.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para fazer um **fork** deste repositório, criar uma nova branch com suas alterações e enviar um **pull request**.

1. Faça o **fork** do projeto
2. Crie uma **branch** para sua feature:

    ```bash
    git checkout -b feature/nome-da-feature
    ```

3. Faça **commit** das suas alterações:

    ```bash
    git commit -m 'Adicionei nova feature'
    ```

4. Envie para o repositório remoto:

    ```bash
    git push origin feature/nome-da-feature
    ```

5. Abra um **pull request**

## Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais informações.

---

Feito por Luiz Fernando (https://github.com/luizdovale)

