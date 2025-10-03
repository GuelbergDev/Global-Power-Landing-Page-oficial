 Global Power - Landing Page de Pré-Treino
Este projeto é uma landing page interativa para a marca fictícia Global Power, que apresenta diferentes sabores de pré-treinos inspirados em culturas ao redor do mundo.
 O site foi construído utilizando HTML, TailwindCSS e JavaScript puro, com integração opcional à API Google Gemini para gerar rotinas de treino personalizadas.

 Como Rodar o Projeto

Clone o repositório ou copie os arquivos para uma pasta no seu computador.

 git clone https://github.com/seu-usuario/global-power-landing.git

Abra o arquivo index.html diretamente no navegador.
 Não é necessário servidor local, mas recomenda-se usar a extensão Live Server do VS Code para melhor experiência.




Configuração opcional da API Gemini:


Dentro do código, procure a seção // --- LÓGICA DA API GEMINI ---.


Substitua a constante apiKey pela sua chave de API do Google AI Studio:

 const apiKey = "SUA_CHAVE_AQUI";


Assim, ao abrir os detalhes de um produto, você poderá gerar uma rotina de treino temática.


Deploy no Vercel
Este projeto pode ser hospedado facilmente no Vercel:
Crie uma conta no Vercel (se ainda não tiver).


Conecte seu repositório GitHub/GitLab/Bitbucket.


O Vercel detectará automaticamente que é um projeto estático e fará o deploy sem precisar de configuração de build.


Após a conclusão, você terá um link público para acessar sua landing page.


 Atenção: certifique-se de que a pasta /imagens esteja incluída no repositório, pois o Vercel só renderiza corretamente arquivos que estão versionados.



 Estrutura do Projeto
/projeto
│── index.html        # Página principal
│── /imagens          # Pasta com imagens usadas no layout
│── /README.md        # Documentação


 Tecnologias Utilizadas
HTML5 – Estrutura da página


TailwindCSS – Estilização rápida e responsiva


Lucide Icons – Ícones em SVG


JavaScript Vanilla – Funcionalidades interativas (carrossel, modal, API, animações)


Google Fonts (Poppins) – Tipografia


Google Gemini API (opcional) – Geração de rotinas de treino



 Funcionalidades
  Cabeçalho Responsivo
Menu adaptável (desktop e mobile).


Botão "Compre Já" em destaque.


 Carrossel de Imagens
Rotação automática a cada 5 segundos.


Botões de navegação próximo/anterior.


Texto de destaque sobre cada slide.


 Catálogo de Produtos
Cards interativos com efeitos de hover.


Cada produto tem:


Nome


País de origem


Imagem


Descrição


Preço


 Modal de Detalhes
Ao clicar em um produto, abre-se um pop-up com:


Imagem ampliada


Descrição completa


Lista de utilidades


Botão "Adicionar ao Carrinho"


Integração com Gemini para criar rotinas de treino


 API Gemini (opcional)
Gera uma rotina curta de treino personalizada com base no país do sabor selecionado.


Exibe o resultado formatado dentro do modal.


 Animação de Scroll
Elementos aparecem suavemente conforme o usuário rola a página.


  Rodapé
Links de redes sociais.


Termos de uso e política de privacidade.





 Observações
O projeto funciona apenas com HTML + CSS + JS, não há backend.


Para que a funcionalidade de geração de treino funcione, é necessário configurar a API Gemini com uma chave válida.


Pode ser facilmente hospedado no GitHub Pages, Netlify ou Vercel.


 Autor
Nícolas Duarte Guelberg
Processo seletivo CIMATEC JR 2025.2
ETAPA TÉCNICA DO NÚCLEO DE PROJETOS DE COMPUTAÇÃO
