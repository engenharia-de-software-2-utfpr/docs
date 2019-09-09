# Requisitos

## Usuário
- Autenticação (O sistema deve permitir que o usuário se autentique):
  - O usuário pode se autenticar via Facebook.
  - O usuário pode se autenticar via número de telefone.
  - O usuário deve estar cadastrado para realizar qualquer ação no sistema.
- Ocorrências:
  - Visualização:
    - O sistema deve exibir as ocorrências aprovadas e não resolvidas através de pontos no mapa.
    - Ao usuário clicar na ocorrência, o sistema deve exibir os detalhes da mesma.

  - Cadastro (O sistema deve permitir que o usuário cadastre ocorrências):
    - Pode-se fazer upload de fotos, vídeos e áudio.
    - Pode-se incluir descrição da ocorrência em forma de texto.
    - Pode-se classificar o nível de criticidade da ocorrência.
    - Deve-se categorizar a ocorrência.
    - O sistema deve permitir que o usuário cadastre ocorrências mesmo sem internet, devendo sincronizar ao conectar com a internet.
    - A localização da ocorrência será feita utilizando as coordenadas locais do dispositivo.
    
- Informações e coletas de dados:
  - Exibir os pontos de descartes.
  - Exibir dados de pesquisas/ações/conscientização.
  - Exibir dados de análise de água e sedimentos da bacia.
  - Permitir que os usuários respondam questionários feitos pelos administradores.
  - O sistema deve exibir links externos para jogos educativos.

- Eventos:
  - O sistema deve exibir calendário de eventos cadastrados pelos administradores.
    
## Administradores
- Autenticação (O sistema deve permitir que o administrador se autentique):
  - Pode-se autenticar por nome de usuário e senha.
  
  - Para realizar qualquer ação no sistema o administrador deve estar autenticado.
 
- Gerência de usuários e admnistradores:
  - Deve-se ter um super administrador
  - O super administrador pode adicionar/remover/visualizar outros admnistradores.
  - O super administrador pode transferir a função para um administrador normal.
  - O administrador pode visualizar em uma lista os usuários do sistema.
  - A administrador pode remover usuários do sistema.
  
- Ocorrências:
  - Gerência de ocorrências:
    - Visualização do mapa com heatmap.
    - O sistema deve exibir as ocorrências aprovadas e não resolvidas através de pontos no mapa.
    - Deve-se ter uma lista para visualização de todas as ocorrências.
    - Aprovar/Negar ocorrências.
    - Visualizar todas as ocorrências já aprovadas e exclui-las.
    
- Informações e coletas de dados:
  - CRUD pontos de descartes.
  - CRUD de pesquisas/ações/conscientização.
  - CRUD água e sedimentos da bacia.
  - CRUD de formulários.
  - CRUD de link para jogos.
  
- Relatórios:
  - Gerência de relatórios.

- Eventos:
  - CRUD de eventos.
