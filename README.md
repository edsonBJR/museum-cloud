# Museum Cloud
Arquitetura de Banco de Dados para acompanhar as informações relativas a todos os museus de artes do Brasil.

Projetar um banco de dados para acompanhar as informações relativas a todos os museus de artes do Brasil. 
Suponha que os seguintes requisitos foram coletados:

  O museu possui uma coleção de OBJETOS_DE_ARTE. Cada OBJETO_DE_ARTE possui uma única Identificação, um Artista (caso seja conhecido), um Ano (quando foi criado, caso seja conhecido), um Título e uma Descrição. Os objetos de arte são categorizados de diversas formas, conforme descrito a seguir.
  
  OBJETOS_DE_ARTE são categorizados com base no seu tipo. Existem três tipos principais: PINTURA, ESCULTURA e ESTÁTUA, além de outro tipo chamado OUTRO para
acomodar objetos que não se inserem em nenhum dos três tipos principais.

  Uma PINTURA possui um Tipo de Pintura (óleo, aquarela, etc.), o material no qual foi pintado (papel, tela, madeira, etc.) e Estilo (moderno, abstrato, etc.).
  
  Uma ESCULTURA possui um Material no qual foi criada (madeira, pedra, etc.), Altura, Peso e Estilo.
  
  Um objeto de arte da categoria OUTRO possui um Tipo (gravura, fotografia, etc.) e Estilo.
  
  OBJETOS_DE_ARTE também são categorizados como COLEÇÃO_PERMANENTE que são de propriedade do museu (que possui informações quanto à Data Aquisição, se está
exposto ou guardado e o Custo) ou EMPRESTADO, que possui as informações sobre a Coleção da qual foi emprestado), a Data Empréstimo e a Data Devolução.

  OBJETOS_DE_ARTE também possuem informações que descrevem seu país/cultura utilizando informações sobre país/cultura de Origem (italiana, egípcia, americana,
indiana, etc.) e Época (Renascentista, Moderno, Antigo, etc.).

  O museu acompanha informações sobre ARTISTAS, caso sejam conhecidas: Nome, Data Nascimento, Data Falecimento (caso não esteja mais vivo), País Origem, Época, Estilo Dominante e Descrição. O Nome é suposto como sendo único.
  
  Ocorrem diferentes EXPOSIÇÕES, cada uma com um Nome, Data Início, Data Encerramento e cada uma está vinculada a todos os objetos de arte que estiveram
expostos durante a exposição.

  As informações são mantidas em outras COLEÇÕES com as quais o museu interage, incluindo Nome (único), Tipo (museu, pessoal, etc.), Descrição, Endereço, Telefone e
Pessoa de Contato.
