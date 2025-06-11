# calc_ipv6
Calculadora IPv6 
Calculadora IPv6 Moderna e Completa
Esta é uma Calculadora IPv6 robusta e intuitiva, desenvolvida inteiramente com HTML, CSS (moderno e responsivo) e JavaScript puro. Ela foi criada para simplificar o trabalho com endereços IPv6, oferecendo um conjunto de funcionalidades essenciais para profissionais de rede, estudantes e entusiastas.

Cansado de lidar com a complexidade dos endereços IPv6 e seus prefixos? Esta ferramenta visa eliminar essa dor de cabeça, proporcionando uma experiência de cálculo eficiente e precisa diretamente no seu navegador.

🌟 Funcionalidades Principais
Design Intuitivo e Responsivo: Uma interface de usuário limpa e moderna, otimizada para funcionar perfeitamente em desktops, tablets e smartphones. A experiência do usuário é prioridade, tornando a navegação e o uso da calculadora simples e agradável.
Compactação e Expansão de Endereços: Alterne facilmente entre a forma compactada de um endereço IPv6 (utilizando :: para sequências de zeros) e sua representação completa, com todos os 8 hextetos preenchidos. Essencial para padronização e análise.
Identificação Detalhada do Tipo de Endereço: Insira qualquer IPv6 e a calculadora identificará automaticamente seu tipo. Reconhece e classifica endereços como:
Global Unicast (Público): Endereços roteáveis globalmente.
Link-Local: Utilizados apenas no segmento de rede local.
Loopback: O endereço para teste local da interface de rede (::1).
Endereço Não Especificado: O endereço que indica a ausência de um endereço (::).
Unique Local Address (ULA): Equivalente aos endereços privados do IPv4.
Multicast: Usados para comunicação de um-para-muitos.
E outros tipos, fornecendo uma visão clara da finalidade do endereço.
Validação Inteligente de Prefixo para ISP: Uma funcionalidade única que analisa o comprimento do prefixo (/xx) inserido e fornece um feedback sobre sua adequação para diferentes cenários de delegação de endereços por ISPs. Isso inclui indicações para prefixos comuns para usuários finais (/56, /60), sub-redes padrão (/64) e grandes organizações (/48).
Cálculo Preciso do Endereço de Rede: Insira um endereço IPv6 e o comprimento do prefixo, e a calculadora determinará o endereço de rede base da sub-rede, zerando os bits da porção de host.
Contagem de Hosts Possíveis: Calcule rapidamente o número total de hosts que podem ser atribuídos a uma sub-rede específica, com base no comprimento do prefixo.
💻 Como Usar
Clone o Repositório (ou baixe o arquivo calc_ipv6.html)

Abra o Arquivo: Simplesmente abra o arquivo calculadora_ipv6.html em qualquer navegador web moderno (Chrome, Firefox, Edge, Safari, etc.).
A calculadora está pronta para ser utilizada! Basta inserir um endereço IPv6 e o comprimento do prefixo, e clicar em "Calcular" para obter os resultados.

🤝 Contribuição e Feedback
Este projeto é de código aberto e adoraria a sua contribuição! Sinta-se à vontade para:

Reportar Bugs: Encontrou algum problema? Abra uma issue para me avisar.
Sugerir Melhorias: Tem ideias para novas funcionalidades ou como tornar a calculadora ainda melhor? Suas sugestões são muito bem-vindas!
Enviar Pull Requests: Se você implementou uma melhoria ou corrigiu um bug, envie um pull request.
Se você achou esta calculadora útil, por favor, deixe uma estrela neste repositório! ⭐ Seu apoio me incentiva a criar mais ferramentas e a continuar aprimorando esta.

Tecnologias Utilizadas:

HTML5: Estrutura da página.
CSS3: Estilização moderna e responsividade.
JavaScript: Lógica de cálculo e manipulação do DOM.
Espero que esta ferramenta seja um recurso valioso para a sua jornada no mundo do IPv6!
