# Search Central with AIs

## Introdução

Este projeto, contém um repositório HTML ainda em desenvolvimento, com o objetivo de criar um site onde possa ser acessado todos os meios de busca da web (com IA ou sem IA) em um único lugar, sem precisar acessar outras guias, janelas ou inserir URLs no seu navegador.

O site foi pensado para ser prático e direto, diminuindo o número de cliques e escritas no navegador.

Até o momento, o site foi construído apenas com acesso direto ao Microsoft Copilot, Google Gemini e Claude. Suporte para acessar outras IAs e campos de busca (Google e Bing) poderão ser implementados em um futuro próximo.

## Para apoio | Como realizar commits do seu repositório e enviar ao GitHub?

Como podem ver, no momento, deve haver uns 5 commits do meu repositório (se incluir o commit deste markdown).

Para quem está começando a enviar os arquivos para o GitHub, segue um pequeno passo a passo simples.

O método é rápido, e não exige muito tempo (leva em torno de 10 minutos no máximo).

**Detalhe importante: Entre as etapas 4 e 5, crie o repositório no GitHub pelo site na interface gráfica!!!**

|**Comandos (Terminal)**|**Função**|
|-|-|
|**1. git status**|Antes de atualizar, verifique os arquivos que foram modificados.|
|**2. git add "nome do arquivo"** ou **git add -A**|Comando para adicionar arquivos novos/modificados ao repositório local novamente. O parâmetro "-A" adiciona todos os modificados sem precisar digitar arquivo por arquivo.|
|**3. git commit -m "nome do commit"**|Cria um novo commit (versão) do seu repositório.|
|**4. git log**|Verifica os commits do seu repositório. Executar este comando é importante, para verificar se o nome do commit está correto.|
|**5. git remote add origin "link do GitHub"**|Adiciona e conecta seu repositório local ao GitHub, criando um repositório remoto.|
|**6. git branch -m "novo nome da branch"**|Quando iniciamos um repositório local, ele vem com uma branch (área de desenvolvimento) chamada (master). No momento de enviar o repositório para o GitHub, será preciso executar este comado e renomear o (master) para (main).|
|**7. git push -u origin "nome da branch"**|Envia os commits do repositório para o GitHub. Normalmente, em "nome da branch", se usa o main (área de desenvolvimento principal) para quem está iniciando.|