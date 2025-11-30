<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>🚀 Igreen Telecom: Internet que Acumula e 1 Mês Grátis!</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700;900&display=swap" rel="stylesheet">
    <style>
        /* Documentação CSS: Variáveis e Reset */
        :root {
            --cor-fundo-principal: #121212; /* Fundo preto escuro */
            --cor-neon-verde: #39ff14;     /* Verde Neon para destaque e bordas */
            --cor-texto-claro: #f0f0f0;    /* Texto principal claro */
            --cor-texto-secundario: #aaa;  /* Texto menor cinza claro */
            --sombra-neon: 0 0 10px var(--cor-neon-verde), 0 0 20px rgba(57, 255, 20, 0.5);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Montserrat', sans-serif;
            line-height: 1.6;
            color: var(--cor-texto-claro);
            background-color: var(--cor-fundo-principal);
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        /* Documentação CSS: Cabeçalho e Destaque */
        header {
            text-align: center;
            padding: 60px 20px 40px;
        }

        .titulo-principal {
            font-size: 3em;
            font-weight: 900;
            margin-bottom: 10px;
            color: var(--cor-neon-verde);
            text-shadow: var(--sombra-neon);
        }

        .subtitulo {
            font-size: 1.2em;
            font-weight: 400;
            color: var(--cor-texto-secundario);
            margin-bottom: 40px;
        }

        /* Destaque Principal - Internet Acumulativa */
        .destaque-acumula {
            background-color: #222;
            padding: 20px;
            margin: 30px auto;
            border-radius: 8px;
            max-width: 700px;
            border: 2px solid var(--cor-neon-verde);
            box-shadow: var(--sombra-neon);
            animation: pulse 1.5s infinite alternate; /* Animação leve */
        }

        .destaque-acumula h2 {
            font-size: 1.8em;
            font-weight: 700;
            color: var(--cor-neon-verde);
            margin-bottom: 5px;
        }

        .destaque-acumula p {
            font-size: 1.1em;
            color: var(--cor-texto-claro);
        }

        @keyframes pulse {
            from { box-shadow: 0 0 8px var(--cor-neon-verde); }
            to { box-shadow: 0 0 25px var(--cor-neon-verde); }
        }

        /* Documentação CSS: Seção de Planos */
        .planos-secao {
            padding: 50px 0;
            text-align: center;
        }

        .planos-secao h2 {
            font-size: 2.5em;
            margin-bottom: 40px;
            color: var(--cor-texto-claro);
        }

        .planos-grid {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 30px;
        }

        /* Estilização do Cartão de Plano */
        .plano-card {
            background-color: #000;
            border: 3px solid var(--cor-neon-verde);
            border-radius: 12px;
            padding: 30px 20px;
            width: 100%;
            max-width: 250px;
            box-shadow: 0 0 15px rgba(57, 255, 20, 0.7);
            transition: transform 0.3s, box-shadow 0.3s;
            position: relative;
        }

        .plano-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 0 30px var(--cor-neon-verde);
        }

        .plano-nome {
            font-size: 1.8em;
            font-weight: 900;
            color: var(--cor-neon-verde);
            margin-bottom: 10px;
            text-shadow: 0 0 5px var(--cor-neon-verde);
        }

        .plano-preco {
            font-size: 2.2em;
            font-weight: 700;
            margin: 15px 0;
            color: var(--cor-texto-claro);
        }

        .plano-preco small {
            font-size: 0.5em;
            font-weight: 400;
            color: var(--cor-neon-verde);
        }

        .plano-beneficios {
            list-style: none;
            text-align: left;
            margin-top: 20px;
        }
        
        /* Ajuste para o texto de Portabilidade fora da UL */
        .plano-card li {
            padding: 8px 0;
            border-top: 1px dashed #333;
            font-size: 0.9em;
            color: var(--cor-texto-secundario);
            list-style-type: none; /* Garante que o item da portabilidade não tenha bullet */
        }

        .plano-beneficios li {
            padding: 8px 0;
            border-top: 1px dashed #333;
            font-size: 0.9em;
            color: var(--cor-texto-secundario);
        }

        .plano-beneficios li:first-child {
            border-top: none;
        }
        
        /* Botão de Ação do Plano */
        .btn-plano {
            display: block;
            margin-top: 25px;
            padding: 10px;
            background-color: var(--cor-neon-verde);
            color: #121212;
            text-decoration: none;
            border-radius: 5px;
            font-weight: 700;
            transition: background-color 0.3s;
        }

        .btn-plano:hover {
            background-color: #5eff47;
        }

        /* Documentação CSS: Lista de Vantagens Abaixo dos Planos */
        .vantagens-extra {
            padding: 50px 0;
            text-align: center;
        }

        .vantagens-extra ul {
            list-style: none;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }

        .vantagens-extra li {
            background-color: #222;
            padding: 20px;
            border-radius: 8px;
            width: 200px;
            font-weight: 700;
            color: var(--cor-neon-verde);
            border: 1px solid #333;
        }

        /* Documentação CSS: Formulário de Portabilidade (NOVO) */
        .form-portabilidade-area {
            background-color: #000;
            padding: 30px;
            border-radius: 8px;
            max-width: 600px;
            margin: 30px auto;
            border: 1px solid var(--cor-neon-verde);
            box-shadow: 0 0 15px rgba(57, 255, 20, 0.5);
        }

        .form-portabilidade-area h3 {
            color: var(--cor-neon-verde);
            text-align: center;
            margin-bottom: 25px;
            font-size: 1.5em;
            text-shadow: 0 0 5px var(--cor-neon-verde);
        }

        .form-portabilidade-area .form-group label {
            color: var(--cor-texto-claro);
            font-weight: 700;
            margin-bottom: 5px;
            display: block;
        }

        .form-portabilidade-area .form-group input,
        .form-portabilidade-area .form-group select {
            width: 100%;
            padding: 12px;
            border: 1px solid #333;
            border-radius: 4px;
            background-color: #1a1a1a;
            color: var(--cor-texto-claro);
            font-size: 1em;
            transition: border-color 0.3s, box-shadow 0.3s;
        }

        .form-portabilidade-area .form-group input:focus,
        .form-portabilidade-area .form-group select:focus {
            outline: none;
            border-color: var(--cor-neon-verde);
            box-shadow: 0 0 8px var(--cor-neon-verde);
        }

        .btn-portabilidade {
            background-color: var(--cor-neon-verde);
            color: #121212;
            font-size: 1.4em;
            font-weight: 900;
            padding: 15px;
            border: none;
            border-radius: 6px;
            cursor: pointer;
            width: 100%;
            margin-top: 20px;
            text-transform: uppercase;
            box-shadow: 0 0 10px rgba(57, 255, 20, 0.7);
            transition: transform 0.2s;
        }

        .btn-portabilidade:hover {
            transform: translateY(-2px);
            box-shadow: 0 0 20px var(--cor-neon-verde);
        }

        /* Documentação CSS: FAQ (NOVO) */
        .faq-secao {
            padding: 50px 0;
            text-align: left;
            max-width: 800px;
            margin: 0 auto;
        }

        .faq-secao h2 {
            text-align: center;
            font-size: 2.2em;
            margin-bottom: 30px;
            color: var(--cor-neon-verde);
        }

        .faq-item {
            margin-bottom: 20px;
            border: 1px solid #333;
            border-radius: 8px;
            background-color: #000;
            padding: 15px;
        }

        .faq-pergunta {
            font-size: 1.1em;
            font-weight: 700;
            color: var(--cor-texto-claro);
            cursor: pointer;
            position: relative;
            padding-right: 30px;
        }

        .faq-pergunta::after {
            content: '+';
            position: absolute;
            right: 0;
            font-size: 1.5em;
            color: var(--cor-neon-verde);
            transition: transform 0.3s;
        }

        .faq-pergunta.ativo::after {
            content: '-';
            transform: rotate(180deg);
        }

        .faq-resposta {
            font-size: 0.9em;
            color: var(--cor-texto-secundario);
            margin-top: 10px;
            padding-top: 10px;
            border-top: 1px dashed #333;
            display: none;
        }

        .faq-resposta.mostrar {
            display: block;
        }

        .faq-resposta a {
            color: var(--cor-neon-verde);
            text-decoration: none;
        }
        /* Documentação CSS: Rodapé */
        footer {
            background-color: #000;
            color: #555;
            padding: 20px;
            text-align: center;
            font-size: 0.8em;
            border-top: 1px solid #222;
        }

        /* Media Query para Responsividade */
        @media (max-width: 768px) {
            .titulo-principal {
                font-size: 2em;
            }

            .planos-grid {
                flex-direction: column;
                align-items: center;
            }

            .plano-card {
                max-width: 90%;
            }
            
            .vantagens-extra ul {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>

    <header>
        <div class="container">
            <h1 class="titulo-principal">🚀 Igreen Telecom: Internet que Acumula e 1 Mês Grátis!</h1>
            <p class="subtitulo">Mude hoje! Portabilidade Gratuita, Sem Fidelidade e Cobertura Nacional.</p>
            
            <div class="destaque-acumula">
                <h2>O MELHOR BENEFÍCIO: INTERNET ACUMULATIVA!</h2>
                <p>Não usou todos os seus dados este mês? Eles **ACUMULAM** automaticamente para o próximo mês! Você nunca perde o que pagou.</p>
            </div>
        </div>
    </header>

    <section class="planos-secao">
        <div class="container">
            <h2>Escolha Seu Plano - Ative 1 Mês Grátis! Sem fidelidade</h2>
            
            <div class="planos-grid">
                
                <div class="plano-card">
                    <div class="plano-nome">Plano START 11Gb</div>
                    <div class="plano-preco">R$ 54,90<small>/mês</small></div>
                    <li>✅ 6Gb + 5Gb na portabilidade</li>
                    <ul class="plano-beneficios">
                        <li>✅ Igreen Club</li>
                        <li>✅ Ligações ILIMITADAS</li>
                        <li>✅ Internet Acumulada</li>
                        <li>✅ WhatsApp ILIMITADO</li>
                        <li>✅ sem portabilidade R$59,90/mês com 6Gb de dados.</li>
                    </ul>
                    <a href="#" class="btn-plano">ESCOLHER PLANO START</a>
                </div>

                <div class="plano-card">
                    <div class="plano-nome">PLANO MEGA 15Gb</div>
                    <div class="plano-preco">R$ 59,90<small>/mês</small></div>
                    <li>✅ 10Gb + 5Gb na portabilidade</li>
                    <ul class="plano-beneficios">
                        <li>✅ Igreen Club</li>
                        <li>✅ Ligações ILIMITADAS</li>
                        <li>✅ Internet Acumulada</li>
                        <li>✅ WhatsApp ILIMITADO</li>
                        <li>✅ sem portabilidade R$ 64,90/mês com 10Gb de dados.</li>
                    </ul>
                    <a href="#" class="btn-plano">ESCOLHER PLANO MEGA</a>
                </div>

                <div class="plano-card">
                    <div class="plano-nome">PLANO GIGA 20Gb</div>
                    <div class="plano-preco">R$ 69,90<small>/mês</small></div>
                    <li>✅15Gb + 5Gb na portabilidade</li>
                    <ul class="plano-beneficios">
                        <li>✅ Igreen Club</li>
                        <li>✅ Ligações ILIMITADAS</li>
                        <li>✅ Internet Acumulada</li>
                        <li>✅ WhatsApp ILIMITADO</li>
                        <li>✅ sem portabilidade R$ 74,90/mês com 15Gb de dados.</li>
                    </ul>
                    <a href="#" class="btn-plano">ESCOLHER PLANO GIGA</a>
                </div>
                
                <div class="plano-card">
                    <div class="plano-nome">Plano Ultra 28Gb</div>
                    <div class="plano-preco">R$ 79,90<small>/mês</small></div>
                    <li>✅23Gb +5Gb na portabilidade</li>
                    <ul class="plano-beneficios">
                        <li>✅ Igreen Club</li>
                        <li>✅ Ligações ILIMITADAS</li>
                        <li>✅ Internet Acumulada</li>
                        <li>✅ WhatsApp ILIMITADO</li>
                        <li>✅ sem portabilidade:R$ 84,90/mês com 23Gb de dados</li>
                    </ul>
                    <a href="#" class="btn-plano">ESCOLHER PLANO Ultra</a>
                </div>

                <div class="plano-card">
                    <div class="plano-nome">Plano Infinity 50Gb</div>
                    <div class="plano-preco">R$ 99,90<small>/mês</small></div>
                    <li>✅ 45 + 5Gb na portabilidade</li>
                    <ul class="plano-beneficios">
                        <li>✅ Igreen Club</li>
                        <li>✅ Ligações ILIMITADAS</li>
                        <li>✅ Internet Acumulada</li>
                        <li>✅ WhatsApp ILIMITADO</li>
                        <li>✅ sem portabilidade: R$ 104,90/mês com 45Gb de dados</li>
                    </ul>
                    <a href="#" class="btn-plano">ESCOLHER PLANO Infinity</a>
                </div>

            </div>
        </div>
    </section>
    
    <section class="vantagens-extra">
        <div class="container">
            <h2>Por que mudar para a Igreen Telecom?</h2>
            <ul>
                <li>✅ 1 MÊS TOTALMENTE GRÁTIS</li>
                <li>✅ PORTABILIDADE FÁCIL (MANTENHA SEU NÚMERO)</li>
                <li>✅ SEM FIDELIDADE OU MULTA</li>
                <li>✅ COBERTURA 4G E 5G</li>
            </ul>
        </div>
    </section>

    <section class="cta-final">
        <div class="container">
            <div class="form-portabilidade-area">
                <h3>Portabilidade Simples: Mantenha Seu Número Agora!</h3>
                
                <form action="#" method="POST"> 
                    
                    <div class="form-group">
                        <label for="operadora">Qual a sua operadora atual? *</label>
                        <select id="operadora" name="operadora_atual" required>
                            <option value="" disabled selected>Selecione sua operadora</option>
                            <option value="claro">Claro</option>
                            <option value="tim">TIM</option>
                            <option value="vivo">Vivo</option>
                            <option value="algar">Algar Telecom</option>
                            <option value="correios">Correios Celular</option>
                            <option value="surpreenda">Surpreenda</option>
                            <option value="datora">Outra MVNO/Virtual</option>
                            <option value="outro">Outra</option>
                        </select>
                    </div>
                    
                    <div class="form-group">
                        <label for="nome_port">Seu Nome *</label>
                        <input type="text" id="nome_port" name="nome" required>
                    </div>

                    <div class="form-group">
                        <label for="telefone_port">Telefone para Contato *</label>
                        <input type="tel" id="telefone_port" name="telefone" placeholder="(XX) XXXXX-XXXX" required>
                    </div>

                    <button type="submit" class="btn-portabilidade">
                        SOLICITAR PORTABILIDADE E ATIVAR 1 MÊS GRÁTIS!
                    </button>
                </form>
            </div>
        </div>
    </section>
    
        <section class="faq-secao">
        <div class="container">
            <h2>Perguntas Frequentes (FAQ)</h2>
            
            <div class="faq-item">
                <div class="faq-pergunta">Como adquirir um plano iGreen Telecom?</div>
                <div class="faq-resposta">Para adquirir um plano, basta escolher uma das opções acima e clicar no botão "ESCOLHER PLANO". Você será direcionado para o processo de ativação e poderá optar pela portabilidade ou por um novo número.</div>
            </div>

            <div class="faq-item">
                <div class="faq-pergunta">Existe fidelidade nos planos?</div>
                <div class="faq-resposta">Não! Nossos planos são **SEM FIDELIDADE**, permitindo que você cancele ou altere o plano a qualquer momento, sem multas. A flexibilidade é total: adapte o plano às suas necessidades sempre que quiser.</div>
            </div>

            <div class="faq-item">
                <div class="faq-pergunta">Há diferença entre os planos para clientes PJ e PF?</div>
                <div class="faq-resposta">Não, os planos são os mesmos para ambos os perfis de cliente, garantindo as mesmas condições e benefícios.</div>
            </div>

            <div class="faq-item">
                <div class="faq-pergunta">O cliente iGreen Telecom tem direito aos benefícios do iGreen Club?</div>
                <div class="faq-resposta">Sim, os clientes iGreen Telecom também terão acesso a mais de 30 mil lojas com descontos exclusivos, basta acessar o aplicativo "**iGreen Club**" para adquirir os descontos (<a href="#">Saiba mais</a>).</div>
            </div>
            
            <div class="faq-item">
                <div class="faq-pergunta">Existe diferença entre planos com e sem portabilidade?</div>
                <div class="faq-resposta">Sim! Oferecemos duas opções: planos **COM PORTABILIDADE** e **SEM PORTABILIDADE**. A principal diferença está na quantidade de internet e nos valores mensais, para que você escolha o que melhor atende às suas necessidades.</div>
            </div>

            <div class="faq-item">
                <div class="faq-pergunta">Como falar no Suporte ao Cliente?</div>
                <div class="faq-resposta">O nosso atendimento é 100% digital, basta clicar no ícone de "**Suporte**" no aplicativo iGreen Club e em breve você será atendido por um especialista. O atendimento funciona 24h. (<a href="#">Clique aqui para falar no Suporte</a>) Tel WhatsApp: **0800 183 0080**</div>
            </div>

            <div class="faq-item">
                <div class="faq-pergunta">Qual aplicativo baixar para gerenciar o plano?</div>
                <div class="faq-resposta">Após o cadastro feito por um licenciado autorizado iGreen, o cliente deverá baixar o aplicativo "**iGreen Club**" para ativar o plano e realizar o pagamento do mesmo. Neste mesmo aplicativo será possível acompanhar as faturas e ter benefícios exclusivos (<a href="#">Saiba mais aqui</a>).</div>
            </div>

            <div class="faq-item">
                <div class="faq-pergunta">O cliente pode ativar o pagamento automático e recorrente no cartão de crédito?</div>
                <div class="faq-resposta">Sim, agora ficou mais fácil ativar um chip e programar a recarga automática no cartão de crédito! Escolha a opção de pagamento com cartão, e um link será gerado para configurar a recorrência de forma rápida e prática. Após o pagamento, o cliente recebe a confirmação na tela, um SMS, e pronto: a recarga automática no cartão de crédito estará ativada!</div>
            </div>

            <div class="faq-item">
                <div class="faq-pergunta">O cliente pode cancelar a qualquer momento com a iGreen Telecom?</div>
                <div class="faq-resposta">Sim! Para cancelar o plano, basta solicitar pelo nosso atendimento. Realizaremos uma análise da conta para verificar possíveis pendências ou faturas em aberto, e, após essa verificação, o cancelamento será processado sem cobrança de multas.</div>
            </div>

            <div class="faq-item">
                <div class="faq-pergunta">Posso acumular GB sem limites?</div>
                <div class="faq-resposta">O máximo de GB acumulado é sempre o **dobro do plano atual contratado**, o que passar disso, não será contabilizado.</div>
            </div>
        </div>
    </section>
    
    <footer>
        <div class="container">
            <p>Igreen Telecom - Sua conexão com o futuro. *Oferta de 1 Mês Grátis válida para novos clientes.</p>
        </div>
    </footer>

    <script>
        // Funções de Máscara de Telefone (Mantidas)
        const aplicarMascara = (campo, mascara) => {
            const valorOriginal = campo.value.replace(/\D/g, '');
            let valorMascara = '';
            let k = 0;
            
            for (let i = 0; i < mascara.length; i++) {
                if (k >= valorOriginal.length) {
                    break;
                }
                if (mascara[i] === '#') {
                    valorMascara += valorOriginal[k];
                    k++;
                } else {
                    valorMascara += mascara[i];
                }
            }
            campo.value = valorMascara;
        };

        const mascaraTelefone = (campo) => {
            let mascara;
            const valorLimpo = campo.value.replace(/\D/g, '');
            
            if (valorLimpo.length > 10) { 
                mascara = '(##) #####-####'; // (XX) 9XXXX-XXXX
            } else {
                mascara = '(##) ####-####';  // (XX) XXXX-XXXX
            }

            aplicarMascara(campo, mascara);
        };

        // Script de Toggle do FAQ (NOVO)
        const setupFaq = () => {
            const faqItems = document.querySelectorAll('.faq-item');

            faqItems.forEach(item => {
                const pergunta = item.querySelector('.faq-pergunta');
                const resposta = item.querySelector('.faq-resposta');

                pergunta.addEventListener('click', () => {
                    // Fecha todos os outros
                    faqItems.forEach(i => {
                        const otherPergunta = i.querySelector('.faq-pergunta');
                        const otherResposta = i.querySelector('.faq-resposta');
                        
                        if (i !== item && otherResposta.classList.contains('mostrar')) {
                            otherResposta.classList.remove('mostrar');
                            otherPergunta.classList.remove('ativo');
                        }
                    });

                    // Abre ou fecha o item clicado
                    resposta.classList.toggle('mostrar');
                    pergunta.classList.toggle('ativo');
                });
            });
        };

        document.addEventListener('DOMContentLoaded', () => {
            // Referência ao campo de portabilidade
            const inputTelefonePort = document.getElementById('telefone_port'); 

            if (inputTelefonePort) {
                inputTelefonePort.addEventListener('keyup', () => mascaraTelefone(inputTelefonePort));
                inputTelefonePort.maxLength = 15;
            }
            
            // Chama a função do FAQ
            setupFaq();
        });
    </script>

</body>
</html>
