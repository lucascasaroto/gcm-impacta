Lucas de Souza Casaroto – 1600220 – ADS 3 Semestre.

Exercício Extra entrega 2017-02-14

Histórico de Versões Apache HTTP Server:
•	(1995): 0.6.2;
•	(1995): 0.8.8;
•	(1995): Apache 1.0;
•	Apache Version 2.0;
•	Apache Version 2.2;
•	Apache Version 2.4;

Principais alterações entre as versões 2.2 e 2.4 do Apache HTTP Server.

Melhorias no Núcleo como:
•	MPMs carregáveis em tempo de execução
•	Uso reduzido de memória
•	Melhor suporte para leitura / escrita assíncrona para suporte a MPMs e plataformas.
•	Agora é possível KeepAliveTimeoutespecificar em milissegundos.

Novos Módulos:
•	mod_proxy_fcgi
o	FastCGI Protocolo backend para mod_proxy
•	mod_proxy_scgi
o	Protocolo SCGI backend para mod_proxy
•	mod_proxy_express
o	Fornece proxies reversos de massa configurados dinamicamente para mod_proxy
•	mod_remoteip
o	Substitui o aparente endereço IP e nome de host do cliente para a solicitação com a lista de endereços IP apresentada por um proxies ou um balanceador de carga por meio dos cabeçalhos de solicitação.
•	mod_heartmonitor, mod_lbmethod_heartbeat
o	Permitir mod_proxy_balancerbasear decisões de balanceamento de carga no número de conexões ativas nos servidores back-end.
•	mod_proxy_html
o	Anteriormente um módulo de terceiros, isso suporta a fixação de links HTML em uma situação de proxy reverso, onde o back-end gera URLs que não são válidos para os clientes do proxy.
•	mod_sed
o	Uma substituição avançada de mod_substitute, permite editar o corpo de resposta com o poder cheio de sed.
•	mod_auth_form
o	Ativa a autenticação baseada em formulários.
•	mod_session
o	Permite o uso do estado de sessão para clientes, usando o armazenamento de cookie ou de banco de dados.
•	mod_allowmethods
o	Novo módulo para restringir certos métodos HTTP sem interferir com a autenticação ou autorização.
•	mod_lua
o	Incorpora o Lua língua para httpd, para as funções de configuração e lógica das pequenas empresas. (Experimental)
•	mod_log_debug
o	Permite a adição de log de depuração personalizável em diferentes fases do processamento da solicitação.
•	mod_buffer
o	Fornece buffering as pilhas de filtro de entrada e saída
•	mod_data
o	Converta o corpo da resposta em um URL de dados RFC2397
•	mod_ratelimit
o	Fornece limite de largura de banda para clientes
•	mod_request
o	Fornece Filtros para manipular e disponibilizar os corpos de solicitação HTTP
•	mod_reflector
o	Fornece reflexão de um corpo de solicitação como uma resposta através da pilha de filtro de saída.
•	mod_slotmem_shm
o	Fornece um provedor de memória compartilhada baseado em Slot (ala o placar).
•	mod_xml2enc
o	Anteriormente um módulo de terceiros, isso suporta a internacionalização em módulos de filtros baseados em libxml2 (com marca registrada).
•	mod_macro (Disponível desde 2.4.5)
o	Forneça macros dentro de arquivos de configuração.
•	mod_proxy_wstunnel (Disponível desde 2.4.5)
o	Suporte web-soquete túneis.
•	mod_authnz_fcgi (Disponível a partir de 2.4.10)
o	Ativar aplicativos autorizadores FastCGI para autenticar e / ou autorizar clientes.
•	mod_http2 (Disponível a partir de 2.4.17)
o	Suporte para a camada de transporte HTTP / 2.


Histórico de Versões NGINX:

Mainline version
CHANGES
nginx-1.11.10  pgp
nginx/Windows-1.11.10  pgp

Stable version
CHANGES-1.10
nginx-1.10.3  pgp
nginx/Windows-1.10.3  pgp

Legacy versions
CHANGES-1.8
nginx-1.8.1  pgp
nginx/Windows-1.8.1  pgp

CHANGES-1.6
nginx-1.6.3  pgp
nginx/Windows-1.6.3  pgp

CHANGES-1.4
nginx-1.4.7  pgp
nginx/Windows-1.4.7  pgp

CHANGES-1.2
nginx-1.2.9  pgp
nginx/Windows-1.2.9  pgp

CHANGES-1.0
nginx-1.0.15  pgp
nginx/Windows-1.0.15  pgp

CHANGES-0.8
nginx-0.8.55  pgp
nginx/Windows-0.8.55  pgp

CHANGES-0.7
nginx-0.7.69  pgp
nginx/Windows-0.7.69  pgp

CHANGES-0.6
nginx-0.6.39  pgp

CHANGES-0.5


nginx-0.5.38  pgp


Principais mudanças para 1.11.10:

•	Alteração: o formato do cabeçalho do cache foi alterado, previamente armazenado em cache
o	As respostas serão invalidadas.

•	Recurso: suporte de "stale-while-revalidate" e "stale-if-error"
o	Extensões na linha de cabeçalho de resposta do back-end "Cache-Control".

•	Recurso: o "proxy_cache_background_update",
o	"Fastcgi_cache_background_update", "scgi_cache_background_update",
o	E "uwsgi_cache_background_update" diretivas.

•	Recurso: nginx agora é capaz de cache respostas com o "Vary" cabeçalho
o	Até 128 caracteres (em vez de 42 caracteres em caracteres
o	Versões).

•	Recurso: o parâmetro "build" da diretiva "server_tokens".
o	Graças a Tom Thorogood.

•	Bugfix: "[crit] SSL_write () falhou" mensagens podem aparecer em logs
o	Ao tratar solicitações com o cabeçalho de solicitação "Expect: 100-continue"
o	linha.

•	Bugfix: o ngx_http_slice_module não funcionou em locais nomeados.

•	Bugfix: uma falha de segmentação pode ocorrer em um processo de
o	Usando AIO após um redirecionamento "X-Accel-Redirect".

•	Bugfix: consumo reduzido de memória para pedidos de longa duração usando
o	Gzipping


Histórico de Versões WordPress:

•	Versão mais recente
•	4.7.2	26-01-2017	zip (md5)	tar.gz (md5)
•	Ramo 4.7
•	Ramo 4.6
•	Ramo 4.5
•	Ramo 4.4
•	Ramo 4.3
•	Ramo 4.2
•	Ramo 4.1
•	Ramo 4.0
•	Ramo 3.9
•	Ramo 3.8
•	Ramo 3.7
•	Ramo 3.6
•	Ramo 3.5
•	Ramo 3.4
•	Ramo 3.3
•	Ramo 3.2
•	Ramo 3.1
•	Ramo 3.0
•	Ramo 2.9
•	Ramo 2.8
•	Ramo 2.7
•	Ramo 2.6
•	Ramo 2.5
•	Versões Beta & RC
•	2.6-RC1	13-07-2008	zip (md5)	tar.gz (md5)
