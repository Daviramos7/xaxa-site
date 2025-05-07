# Cartão de Aniversário Especial

Este projeto implementa um cartão de aniversário interativo em formato de site, com contagem de tempo desde o início de um relacionamento, slides de fotos e mensagens, animações de virada de carta e player de música ambiente.

Link: https://xaxa-site-davi-ramos-ferreiras-projects.vercel.app/

## Estrutura

* **index.html**: Arquivo principal com toda a marcação HTML, estilos em `<style>` e scripts em `<script>`.
* **CSS**: Estilos embutidos para:

  * Layout responsivo.
  * Animações de virada de carta e pulsar corações.
  * Contagem regressiva em tempo real.
  * Estilização de slides e contracapa.
* **JavaScript**: Lógica para:

  * Gerar dinamicamente slides a partir de um array de fotos e textos.
  * Controlar navegação entre slides (botões `Anterior` e `Próximo`).
  * Animar a capa ao clicar para abrir a carta.
  * Atualizar contador de tempo desde 24 de fevereiro de 2023.
  * Inserir player de música local (autoplay, botão mute/unmute).

## Funcionalidades

1. **Contador de tempo**: Mostra anos, dias, horas, minutos e segundos desde 24/02/2023.
2. **Cartão interativo**: Ao clicar na capa, a carta abre com efeito 3D, revelando slides.
3. **Slides dinamicamente gerados**: Fotos, datas e textos são carregados de um array JS.
4. **Navegação**: Botões para avançar e retornar nos slides.
5. **Contracapa estilizada**: Mensagem e ícones de coração com animação.
6. **Player de música**: Toca automaticamente `Clair de Lune` de Debussy, com controle de volume e mute.

## Como usar

1. **Clone o repositório**:

   ```bash
   git clone https://seu-repositorio.git
   ```

2. **Estrutura de pastas**:

   ```plaintext
   /
   ├─ index.html
   ├─ img/                # Imagens usadas nos slides
   ├─ music/              # Arquivos de música (ex: Clair de Lune.mp3)
   └─ README.md
   ```

3. **Executar**:

   * Abra `index.html` em um navegador moderno (Chrome, Firefox, Edge).

4. **Personalização**:

   * **Fotos**: No `index.html`, seção `const fotos = [...]`, ajuste caminhos e textos.
   * **Música**: Substitua o arquivo em `music/` e altere o caminho em `inserirPlayerMusicaLocal('music/Arquivo.mp3')`.
   * **Estilos**: Edite o `<style>` conforme desejar cores, tamanhos e animações.

## Dependências

* Não há dependências externas. Tudo é implementado em HTML, CSS e JavaScript puros.
* Fonte Google Fonts: `Dancing Script` e `Montserrat`.

## Licença

Este projeto é livre para uso e modificação.

---

#### Autor

* Criado por Zizico para Xaxa. Obrigado por conferir!
