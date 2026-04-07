# Repositorio Inicial.

## Atividades:

- 1 : Refatorar as paginas basquete e volley para ficar de acordo com o futebol.
- 2 : Todos os hyperlinks devem estar funcionais indo e voltando.
- 3 : A nomenclatura dos arquivos e primordial, obrigatorio seguir o padrao estabelecido. Nomes minusculos e caso existir nomes compostos utilizar (-) hifen.
- 4 : Ao final da confeccao de cada pagina realizar um commit
- 5 : Pesquisar os status code do HTTP da família 200 e colocar no README explicando cada um.

###Família 200

Os códigos da família 200 (ou série 2xx) são mensagens de sucesso que indicam que uma requisição feita por um navegador ou aplicação foi recebida, compreendida e aceite pelo servidor. No mundo da internet, eles funcionam como o "sinal verde".

200	OK - O mais comum de todos. Significa que a requisição foi bem-sucedida e o servidor entregou o que foi pedido (como carregar uma página ou imagem).
201	Created - Usado geralmente após um comando POST. Indica que a requisição teve sucesso e resultou na criação de um novo recurso no servidor.
202	Accepted - O servidor recebeu o pedido e vai processá-lo, mas a ação ainda não foi concluída. É comum em tarefas que demoram muito para serem finalizadas.
203 Non-Authoritative Information - O servidor está lhe dizendo: "Eu tenho os dados, mas pode não ser a versão original exata da fonte".
204	No Content - A requisição foi um sucesso, mas o servidor não precisa retornar nenhum conteúdo no corpo da mensagem (muito usado em APIs para confirmação de exclusão).
205	Reset Content - Indica que a solicitação foi bem-sucedida e o servidor instrui o cliente (navegador/aplicativo) a redefinir a visualização do documento, geralmente limpando campos de formulário ou estados da interface do usuário. É semelhante ao 204 No Content
206	Partial Content - Indica que o servidor processou com sucesso uma solicitação de intervalo (range request) e está retornando apenas parte do recurso solicitado, em vez do arquivo completo. É crucial para streaming de mídia, retomada de downloads interrompidos e eficiência de banda.
207	Multi-Status - indica que a resposta contém códigos de status separados para múltiplos recursos, comum no protocolo WebDAV. Ele é usado quando uma única solicitação afeta vários itens, e o resultado (sucesso, erro ou parcial) varia para cada um, listados em um corpo XML. 
208	Already Reported - é utilizado em operações WebDAV (Web Distributed Authoring and Versioning) para informar que os membros de uma coleção já foram listados em uma parte anterior da resposta. Ele evita duplicidade de dados e loops infinitos em solicitações, tornando a resposta mais concisa.
226	IM Used -  indica uma solicitação GET bem-sucedida, na qual o servidor retorna um delta (diferença) em vez do recurso completo, com base em umaA-IMO cabeçalho reduz o consumo de banda atualizando os dados em cache apenas com as alterações, conforme definido na RFC 3229.
