### Especificação de Produto (PRD): Ecossistema SOL-Jobs (MVP v0.1)

##### 1\. Visão Estratégica e Proposta de Valor

O  **SOL-Jobs**  é uma resposta disruptiva à fricção crônica do mercado de freelancing, onde a insegurança de pagamento e a diluição da autoridade limitam o potencial da  *Gig Economy* . Como Arquiteto de Produto, a estratégia central foca na convergência entre o  **Social Commerce**  e o  **Trustless Finance** . Não estamos construindo apenas um marketplace, mas um protocolo de identidade profissional que utiliza  **loops de dopamina**  (feedback social) para reduzir drasticamente o Custo de Aquisição de Clientes (CAC).A combinação de um  **Discovery Feed**  (estilo TikTok), segurança via  **Smart Escrow**  e reputação via  **Soulbound NFTs (SBTs)**  resolve o "Trust Gap" (lacuna de confiança) no mercado brasileiro. Ao humanizar o portfólio com provas de trabalho em vídeo e garantir o capital via blockchain, eliminamos o medo do calote e a subjetividade da competência. A interface viciante serve como porta de entrada para uma infraestrutura técnica potente e invisível, transformando o "trabalho" em um ativo líquido e verificável on-chain.

##### 2\. Arquitetura da Experiência do Usuário (UX/UI Mobile-Driven)

Para alcançar o patamar de  *Consumer Crypto* , a abordagem é estritamente  **Mobile-First** , hibridizando comportamentos de redes sociais com transações B2B de alta velocidade.

* **Discovery Feed (TikTok Style):**  O coração da plataforma. Vídeos curtos atuam como Provas de Trabalho (PoW) dinâmicas. O algoritmo não entrega apenas perfis, mas competência visual, permitindo que o cliente avalie o "vibe-check" e a qualidade técnica em segundos.  
* **Match B2B (Tinder Style):**  Utiliza a lógica de "Swipe" para conexões imediatas. O sistema de filtragem é baseado no binômio  **Valor vs. Prazo** . O cliente visualiza o custo e a disponibilidade em tempo real, permitindo contratações sob demanda para necessidades urgentes de terceirização.  
* **Interface "Fricção Zero" (Abstração de Carteira):**  
* **Login Social (Privy):**  Acesso via e-mail ou redes sociais, gerando uma  *Smart Wallet*  em segundo plano sem a necessidade de gerenciar  *seed phrases* .  
* **Experiência Gasless:**  Através de  *Paymasters*  e  *Account Abstraction*  (ERC-4337 na Base), o usuário nunca vê taxas de rede ou transações de "Sign", sentindo uma fluidez de Web2.

##### 3\. Protocolos de Confiança e Engenharia de Blockchain

A arquitetura utiliza um stack dual:  **Solana**  para micro-transações de ultra-velocidade e  **Base**  para integração profunda com o ecossistema da Coinbase e liquidez global.

1. **Lógica de Smart Escrow & Cálculo de Danos:**  
2. **Lock-in:**  O capital é travado no contrato inteligente (on-chain).  
3. **Caução Inteligente (Damage Calculation):**  Para aluguéis de equipamentos ou serviços físicos, o contrato prevê uma trava de garantia que pode ser executada ou devolvida com base no estado do ativo.  
4. **Execução & Entrega:**  O prestador é notificado e realiza o upload das provas de entrega.  
5. **Arbitragem Descentralizada (Kleros):**  Em caso de disputa ou divergência no "cálculo de danos", o protocolo integra-se ao Kleros para uma resolução via jurados descentralizados, eliminando o viés da plataforma.  
6. **Release:**  Liberação instantânea dos fundos após aprovação.  
7. **Solana Actions & Blinks:**  Permite que serviços sejam contratados e pagos diretamente em redes sociais como o Twitter/X. Um "trampo" vira um link executável (Blink), onde o cliente trava o pagamento sem sair do seu feed social original.  
8. **Reputação Imutável (Soulbound NFTs \- SBT):**  Ao concluir o serviço, o sistema emite automaticamente um  **SBT** . Por serem não-transferíveis, esses tokens garantem que a reputação pertença exclusivamente àquele profissional, criando um currículo on-chain inalterável.

##### 4\. Fluxo Financeiro e On-ramp (A Experiência Pix-to-Crypto)

O sucesso no Brasil exige a sublimação do Pix. O SOL-Jobs atua como um tradutor de liquidez invisível.

* **O Fluxo "Zero Fricção":**  
* **Entrada:**  Cliente paga via Pix. O sistema converte automaticamente para  **USDC**  via gateway de on-ramp e trava no Escrow.  
* **Estabilidade:**  O valor permanece em Stablecoin, protegendo ambas as partes da volatilidade.  
* **Saque (Off-ramp):**  O prestador recebe o valor e, com um clique, converte o USDC de volta para Pix em sua conta bancária.  
* **Vantagem de Liquidez:**  Enquanto plataformas Web2 (como Upwork ou Hotmart) retêm fundos por 7 a 14 dias para "segurança", o SOL-Jobs oferece  **liquidez imediata** . O dinheiro é liberado no milissegundo da aprovação, eliminando o custo de oportunidade financeira para o freelancer.

##### 5\. Flywheel de Educação e Qualificação Condicional

A educação não é um extra, mas o  *gatekeeper*  de qualidade do ecossistema e uma ferramenta de retenção estratégica ligada ao  **Rabelus Lab** .

* **Badges de Especialista:**  Determinadas categorias (ex: "Editor de Reels Virais") são bloqueadas. O prestador deve completar um micro-curso e um desafio técnico para desbloquear o direito de dar "bid" nesses jobs.  
* **Funil de SaaS & Afiliados:**  Durante os cursos, o profissional é introduzido a ferramentas de IA e produtividade proprietárias do  **Rabelus Lab** . O curso funciona como um tutorial de integração (onboarding) para ferramentas pagas, criando uma receita recorrente para o ecossistema enquanto qualifica a entrega do prestador.

##### 6\. Estratégia de Monetização Subliminar e Sustentabilidade

O modelo de negócios é desenhado para ser imperceptível, capturando valor da eficiência da rede em vez de sobrecarregar o usuário.

* **Yield de Escrow (Primary Revenue):**  O capital parado em Escrow (USDC) é alocado em protocolos DeFi de baixo risco (Aave ou Kamino). O rendimento gerado durante o período de execução do serviço é capturado pela plataforma, permitindo taxas de transação extremamente baixas ou zeradas.  
* **Promoted Slots & Algorithm Boost:**  Profissionais podem pagar para que seus vídeos de portfólio tenham maior alcance no feed de descoberta, similar ao modelo de anúncios do Instagram.  
* **Marketplace de Ferramentas:**  Venda de créditos de IA e ferramentas de produtividade necessárias para a execução dos serviços qualificados.

##### 7\. Roadmap de Captação e Desenvolvimento (Funding & Grants)

O posicionamento do SOL-Jobs foca em  **Consumer Crypto**  e  **Real World Assets (RWA)** , onde o ativo é o talento humano brasileiro.

* **Funding & Ecosystem:**  
* **Colosseum (Renaissance Hackathon):**  Foco em vencer a trilha de pagamentos/consumo para aceleração imediata.  
* **Base Ecosystem Fund:**  Candidatura focada em trazer usuários brasileiros para a rede Base através do On-ramp via Pix.  
* **Solana Foundation Grants:**  Foco na inovação de pagamentos sociais via Blinks.  
* **Roadmap Técnico Simplificado (Lançamento MVP):**  
* **Sprint 1:**  Smart Contract de Escrow com lógica de cálculo de danos e integração de Smart Wallets (Privy).  
* **Sprint 2:**  Launch do Feed Vertical (Mobile) e sistema de reputação via SBTs.  
* **Sprint 3:**  Foco total no nicho de  **Editores de Conteúdo**  para dominar o SEO de ferramentas de criação e lançar o flywheel de educação.Este PRD estabelece o SOL-Jobs não apenas como uma ferramenta, mas como a infraestrutura definitiva para o patrimônio de reputação e a soberania financeira do profissional moderno. \#

