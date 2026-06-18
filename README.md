# Computa-o-em-Nuvem-e-Arquitetura-B-sica.-
 1. O que é Cloud Computing (Computação em Nuvem)?
Computação em nuvem é a entrega de serviços de computação — incluindo servidores, armazenamento, bancos de dados, redes, software e análise — pela Internet ("a nuvem").
Em vez de comprar e manter servidores físicos locais, as empresas contratam esses recursos sob demanda de provedores de nuvem (como AWS, Google Cloud ou Microsoft Azure), pagando apenas pelo que utilizam.
 Principais Benefícios:
 Redução de Custos: Elimina o gasto com infraestrutura física (hardware, energia, refrigeração).
 Escalabilidade: Permite aumentar ou diminuir a capacidade de recursos instantaneamente conforme a demanda.
 Disponibilidade: Infraestrutura global com redundância, garantindo que os sistemas fiquem sempre online.
 2. Modelos de Serviço (IaaS, PaaS, SaaS)
A computação em nuvem é dividida em três modelos principais, que definem o nível de controle e responsabilidade entre o cliente e o provedor.
  IaaS (Infrastructure as a Service - Infraestrutura como Serviço)
Você aluga a infraestrutura bruta de hardware (servidores virtuais, rede e armazenamento). O provedor cuida da parte física, mas você é responsável por instalar, configurar e manter o sistema operacional, bancos de dados e aplicações.
 Exemplos: AWS EC2, Google Compute Engine (GCE), DigitalOcean Droplets.
 Analogia: Alugar uma casa vazia. A estrutura é sua, mas os móveis e a organização interna são de sua responsabilidade.
  PaaS (Platform as a Service - Plataforma como Serviço)
O provedor gerencia o sistema operacional, a rede, os servidores e o armazenamento. Você se preocupa exclusivamente com o desenvolvimento e o código da sua aplicação. É ideal para equipes focarem apenas em programar.
 Exemplos: Heroku, AWS Elastic Beanstalk, Google App Engine, Vercel.
 Analogia: Morar em um hotel. Você não se preocupa com a manutenção ou estrutura, apenas usa o quarto.
  SaaS (Software as a Service - Software como Serviço)
O provedor entrega um produto completo e pronto para o uso final através da internet, geralmente via navegador web ou aplicativo. Você não gerencia nada da infraestrutura ou do código.
 Exemplos: Google Drive, Netflix, Microsoft 365, Slack.
 Analogia: Pegar um táxi ou Uber. Você só consome o serviço para se deslocar, sem se preocupar com a manutenção ou direção do carro.
 3. O que é um Deploy Simples?
Deploy (ou implantação) é o processo de colocar um sistema, site ou funcionalidade no ar, tornando-o acessível para os usuários finais.
    Deploy Simples geralmente envolve enviar o código que foi desenvolvido localmente no seu computador para um servidor na nuvem (geralmente usando uma plataforma PaaS para automatizar e simplificar o processo).
 Fluxo básico de um Deploy Simples:
 1. Desenvolvimento: O programador escreve o código na sua máquina local.
 2. Versionamento: O código é enviado para um repositório remoto (como o GitHub).
 3. Publicação (Deploy): Uma plataforma (como Vercel, Netlify ou Render) se conecta ao GitHub, puxa o código atualizado e o distribui em um servidor.
 4. Acesso: O site ou sistema ganha uma URL pública (ex: meusite.com) e fica disponível na internet.
 3. *Versionamento:* O código é enviado para um repositório remoto (como o GitHub).
 4. *Publicação (Deploy):* Uma plataforma (como Vercel, Netlify ou Render) se conecta ao GitHub, puxa o código atualizado e o distribui em um servidor.
 5. *Acesso:* O site ou sistema ganha uma URL pública (ex: meusite.com) e fica disponível na internet.
