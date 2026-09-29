# Site acadêmico de Gustavo Martins

Esta pasta contém o site completo e editável. Não depende do Codex, de uma instalação de Python ou de um serviço de criação de sites para funcionar.

## Guardar e abrir em outro computador

1. Guarde uma cópia do ZIP completo em um local de sua escolha.
2. Extraia o ZIP em qualquer computador, mantendo as pastas internas.
3. Abra website/index.html no navegador para visualizar o site localmente.
4. Para editar, abra a pasta em um editor de texto/código, ou forneça a pasta completa ao assistente de sua escolha.

Não guarde apenas index.html: as fotos, os PDFs e os estilos também são necessários.
O endereço 127.0.0.1 usado durante a criação é apenas uma prévia local e não é o endereço público do site.

## Onde alterar cada parte

- index.html: apresentação, interesses, preprints, ensino e links.
- styles.css: cores, espaçamento, tamanhos, enquadramento e clareamento do retrato, paisagem desfocada no cabeçalho e adaptação para celular.
- script.js: ativa o fundo do cabeçalho após rolar a página.
- images/gustavo-martins.jpg: retrato original. O recorte e o brilho são aplicados na exibição, sem alterar o arquivo.
- images/autumn-landscape.jpg: paisagem original usada no rodapé e no cabeçalho.
- files/Gustavo-Martins-CV.pdf: CV público atualizado, sem data de nascimento nem endereço residencial.
- files/Josh-Johnson-DRP-Presentation.pdf: apresentação de Josh Johnson. Mentoria em Spring 2026; apresentação em October 2026, datas confirmadas.
- .nojekyll: arquivo vazio que deve ser mantido para a hospedagem estática.

## Atualizações comuns

Para atualizar o CV, substitua files/Gustavo-Martins-CV.pdf mantendo o mesmo nome. Os dois links do site continuarão funcionando.
Para acrescentar um artigo, edite a seção Preprints em index.html usando o artigo existente como modelo.
Para atualizar a posição acadêmica, edite o primeiro parágrafo da seção About e a descrição no início de index.html.

## Publicação no GitHub Pages

A conta de destino ainda deve ser confirmada com Gustavo. Não há publicação concluída nesta cópia.

1. Criar um repositório público chamado USUARIO.github.io na conta correta.
2. Enviar o conteúdo da pasta website à raiz do repositório, preservando as subpastas images e files.
3. Em Settings > Pages, escolher Deploy from a branch, branch main, pasta / (root), e salvar.
4. Aguardar a publicação e conferir o endereço https://USUARIO.github.io/.

Documentação: https://docs.github.com/en/pages/quickstart

## Manutenção depois da publicação

O repositório será a cópia principal online, com histórico de alterações. Em outro computador, você poderá baixar uma cópia em Code > Download ZIP ou editar os textos pelo próprio GitHub. Alterações locais só ficam públicas depois de enviadas ao repositório.

Antes de editar em outro computador, obtenha a versão mais recente do repositório para não sobrescrever mudanças anteriores. Depois de atualizar o site, guarde um novo ZIP se quiser manter um backup adicional.
