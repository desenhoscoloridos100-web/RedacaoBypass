# Redação Bypass

**Redação Bypass** é uma ferramenta avançada de automação que utiliza Inteligência Artificial para gerar e digitar redações automaticamente em plataformas de ensino, simulando comportamento humano e contornando validações de sistema.

## 🚀 Funcionalidades

  * **IA Integrada (Gpt-4o-mini)**: Gera redações completas ou títulos criativos baseados no tema proposto
  * **Contexto Inteligente**: Detecta automaticamente se o campo é um título ou o corpo da redação
  * **Digitação Humanizada**: Simula a digitação tecla por tecla com velocidade variável
  * **Dark Mode Automático**: Injeta proteção visual para uso noturno
  * **Interface Flutuante**: Painel arrastável e minimizável (Modo Bolha ⛈️)

## ⚙️ Instalação

### 1\. Como Userscript (Tampermonkey/Violentmonkey)

1.  Instale o [Tampermonkey](https://www.tampermonkey.net/) no seu navegador

2.  Acesse o seguinte link para instalar o script (exemplo):

    ```
    [https://cdn.jsdelivr.net/gh/desenhoscoloridos100-web/RedacaoBypass@patch-1/script.js]
    ```

3.  O gerenciador detectará o script e solicitará a instalação

4.  Confirme e o script abrirá automaticamente ao acessar a página de redação (`/student-write-essay`)

### 2\. Como Bookmarklet (Favoritos)

1.  Crie um novo favorito no seu navegador

2.  No campo de URL do favorito, cole o seguinte código:

    ```javascript
    javascript:(function(){var s=document.createElement('script');s.src='https://cdn.jsdelivr.net/gh/desenhoscoloridos100-web/RedacaoBypass@patch-1/script.js?t='+Date.now();s.crossOrigin='anonymous';s.onload=function(){console.log('RedacaoBypass loaded (no-cache)')};document.head.appendChild(s)})();

    ```

3.  Acesse a página da redação

4.  Clique no favorito para injetar o painel

## 🔧 Configuração e Uso

### Configurando a IA (Gemini)

Para usar a geração automática de texto, você precisa configurar sua chave de API uma única vez:

1.  Gere sua chave gratuita no [OoenRouter](https://openrouter.ai/workspaces/default/keys)
2.  Cole a chave no campo **OpenRout API Key** dentro do painel do script
3.  A chave será salva automaticamente nos cookies do navegador

### Controles do Painel

  * **✨ Gerar com IA**: Lê o tema e cria o texto automaticamente
  * **Digitar**: Começa a escrever o texto no campo selecionado
  * **Velocidade**: Escolha entre *Lento*, *Normal*, *Flash* 
  * **Minimizar (–)**: Transforma o painel em uma bolha flutuante para não atrapalhar a visão

## 📄 Licença

Este projeto está licenciado sob a [MIT License](https://www.google.com/search?q=LICENSE).

-----

*Nota: Este script é fornecido para fins educacionais e de teste de segurança (PenTest). O uso em ambientes acadêmicos reais pode violar as diretrizes da sua instituição.*
