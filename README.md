# Plugins QGIS da Norte Agro (fase de teste)

Repositório de plugins do QGIS da Norte Agro Projetos: **Norte Agro - Uso do Solo** e **NorteAgro Layout de plantas**.
O QGIS lê a lista `plugins.xml`, avisa quando sai uma versão nova e os vídeos da Ajuda chegam junto com a atualização.

## Para usar no QGIS (uma vez)
1. Complementos > Gerenciar e instalar complementos > Configurações > **Adicionar...**
2. Nome: `Norte Agro Projetos` · URL: `https://raw.githubusercontent.com/lipe83555-cyber/norteagro-plugins-qgis/main/plugins.xml` > OK
3. Aba **Todos** > procure **Norte Agro** > escolha o plugin > **Instalar complemento**.

Daí em diante: Complementos > Gerenciar e instalar complementos > **Atualizar** quando o QGIS avisar. Os vídeos novos
da Ajuda baixam sozinhos, em segundo plano, depois da atualização.

## Conteúdo
- `plugins.xml`: a lista que o QGIS lê.
- `zips/`: um ZIP por plugin (só a versão atual).
- `videos/<plugin>/`: os vídeos da Ajuda, em partes de até 20 MB (o plugin junta as partes).
- `icones/`: ícones dos plugins.

Publicado pelo `publicar_repositorio.py` da Norte Agro. Não colocar aqui chaves, senhas ou dados de clientes.
