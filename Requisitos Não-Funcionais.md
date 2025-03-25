
> explicar diferença entre site e web app. 

As interfaces tanto do site quanto do web app do Cordes devem ser intuitivas para facilitar o uso por parte do usuário, incluindo menus de navegação concisos, fontes facilmente legíveis, botões claramente visíveis e funcionais, para que o usuário possa encontrar o que deseja com o mínimo de cliques.

As interfaces do site da Cordes deverão ser responsivas, se adaptando a diferentes tipos de dispositivos (computadores, celulares, tablets, etc...)

Todas as informações fornecidas pelo usuário (tanto para o sistema quanto armazenadas em nuvem no software) serão protegidas com criptografia de ponta a ponta.

Tanto o site, quanto o web app em si serão desenvolvidos utilizando o seguinte stack: Next.JS (typescript), Tailwind CSS, Shadcn, Vercel, Supabase.

O web app e o acesso aos dados em nuvem devem estar disponíveis 99.9% (0.01% para manutenção e tratamento de erros) do tempo. O serviço de suporte e implementação estará disponível durante o horário comercial (08:00 até às 18:00, horário de Brasília) em dias úteis.

A arquitetura do projeto deve estar preparada para um aumento no volume de operações sem comprometer a performance.

De modo a obter carregamentos mais rápidos e tempos de resposta reduzidos, as requisições ao banco de dados devem ser feitas dinamicamente, ou seja, as informações devem ser obtidas conforme a necessidade, em oposição a obter a base de dados inteira no carregamento inicial. (?)

O projeto deve utilizar padrões de documentação e código para permitir manutenções e atualizações mais fáceis e estáveis.

O app deve ser facilmente implantado em difrerentes ambientes de infraestrutura, além de poder ser operado independentemente da plataforma (Windows, Linux, MacOS etc.).