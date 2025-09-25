<!DOCTYPE html>
<html lang="pt-BR">
<!-- Proposta Comercial White Bebidas - Otimizada para GitHub Pages -->
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Proposta Comercial para White Bebidas - Estratégia de Crescimento Digital">
    <meta name="author" content="LOC INSIGHTS">
    <title>Proposta Comercial - White Bebidas</title>
    <!-- Favicon -->
    <link rel="icon" href="data:image/svg+xml,<svg xmlns=%22http://www.w3.org/2000/svg%22 viewBox=%220 0 100 100%22><text y=%22.9em%22 font-size=%2290%22>🥂</text></svg>">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f8f9fa;
            -webkit-font-smoothing: antialiased;
            -moz-osx-font-smoothing: grayscale;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            background: white;
            box-shadow: 0 0 20px rgba(0,0,0,0.1);
            overflow-x: hidden;
        }
        
        .header {
            background: linear-gradient(135deg, #000 0%, #333 100%);
            color: white;
            padding: 40px;
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        
        .header::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><defs><pattern id="grain" width="100" height="100" patternUnits="userSpaceOnUse"><circle cx="25" cy="25" r="1" fill="%23ffffff" opacity="0.05"/><circle cx="75" cy="75" r="1" fill="%23ffffff" opacity="0.05"/><circle cx="50" cy="10" r="1" fill="%23ffffff" opacity="0.05"/></pattern></defs><rect width="100" height="100" fill="url(%23grain)"/></svg>');
            z-index: 1;
            pointer-events: none;
        }
        
        .header-content {
            position: relative;
            z-index: 2;
        }
        
        .logo-section {
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 20px;
            gap: 30px;
        }
        
        .logo {
            width: 80px;
            height: 80px;
            background: #000;
            border-radius: 50%;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            border: 3px solid #00BFFF;
            position: relative;
        }
        
        .logo .wb {
            font-size: 24px;
            font-weight: bold;
            color: white;
            letter-spacing: 1px;
        }
        
        .logo .brand {
            font-size: 8px;
            color: white;
            margin-top: 2px;
            letter-spacing: 0.5px;
        }
        
        .diamond {
            width: 12px;
            height: 12px;
            background: #00BFFF;
            transform: rotate(45deg);
            position: absolute;
            bottom: 8px;
        }
        
        .loc-insights {
            text-align: center;
        }
        
        .loc-insights h1 {
            font-size: 28px;
            margin-bottom: 5px;
            letter-spacing: 2px;
        }
        
        .loc-insights p {
            font-size: 14px;
            opacity: 0.9;
            letter-spacing: 1px;
        }
        
        .proposal-title {
            margin-top: 30px;
        }
        
        .proposal-title h2 {
            font-size: 36px;
            margin-bottom: 10px;
            color: #00BFFF;
        }
        
        .proposal-title h3 {
            font-size: 24px;
            font-weight: 300;
            opacity: 0.9;
        }
        
        .date {
            margin-top: 20px;
            font-size: 14px;
            opacity: 0.8;
        }
        
        .section {
            padding: 50px;
            border-bottom: 1px solid #eee;
        }
        
        .section:last-child {
            border-bottom: none;
        }
        
        .section h2 {
            font-size: 28px;
            color: #000;
            margin-bottom: 25px;
            border-left: 4px solid #00BFFF;
            padding-left: 20px;
            display: flex;
            align-items: center;
            gap: 15px;
        }
        
        .section-icon {
            width: 40px;
            height: 40px;
            background: #00BFFF;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-weight: bold;
            font-size: 18px;
        }
        
        .section p {
            font-size: 16px;
            margin-bottom: 20px;
            text-align: justify;
        }
        
        .metrics-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin: 30px 0;
        }
        
        .metric-card {
            background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
            padding: 25px;
            border-radius: 10px;
            text-align: center;
            border-left: 4px solid #00BFFF;
        }
        
        .metric-card h3 {
            font-size: 24px;
            color: #000;
            margin-bottom: 10px;
        }
        
        .metric-card p {
            font-size: 14px;
            color: #666;
            text-align: center;
        }
        
        .problem {
            background: #fff5f5;
            border-left: 4px solid #e53e3e;
        }
        
        .opportunity {
            background: #f0fff4;
            border-left: 4px solid #38a169;
        }
        
        .objectives-list {
            list-style: none;
        }
        
        .objectives-list li {
            padding: 15px;
            margin: 10px 0;
            background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
            border-radius: 8px;
            border-left: 4px solid #00BFFF;
            font-size: 16px;
        }
        
        .objectives-list li::before {
            content: "🎯";
            margin-right: 10px;
            font-size: 18px;
        }
        
        .strategy-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 25px;
            margin: 30px 0;
        }
        
        .strategy-card {
            background: white;
            border: 1px solid #ddd;
            border-radius: 10px;
            padding: 25px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }
        
        .strategy-card:hover {
            transform: translateY(-5px);
        }
        
        .strategy-card h3 {
            color: #000;
            margin-bottom: 15px;
            font-size: 20px;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .strategy-icon {
            font-size: 24px;
        }
        
        .timeline {
            display: grid;
            gap: 20px;
            margin: 30px 0;
        }
        
        .timeline-item {
            display: flex;
            align-items: center;
            padding: 20px;
            background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
            border-radius: 10px;
            border-left: 4px solid #00BFFF;
        }
        
        .timeline-number {
            background: #00BFFF;
            color: white;
            width: 40px;
            height: 40px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            margin-right: 20px;
            flex-shrink: 0;
        }
        
        .pricing-table {
            background: linear-gradient(135deg, #000 0%, #333 100%);
            color: white;
            border-radius: 15px;
            padding: 40px;
            text-align: center;
            margin: 30px 0;
        }
        
        .pricing-table h3 {
            font-size: 32px;
            margin-bottom: 20px;
            color: #00BFFF;
        }
        
        .price {
            font-size: 48px;
            font-weight: bold;
            margin: 20px 0;
            color: #00BFFF;
        }
        
        .price-details {
            font-size: 14px;
            opacity: 0.8;
            margin-bottom: 30px;
        }
        
        .benefits-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin: 30px 0;
        }
        
        .benefit-card {
            background: linear-gradient(135deg, #00BFFF 0%, #0099d4 100%);
            color: white;
            padding: 25px;
            border-radius: 10px;
            text-align: center;
        }
        
        .benefit-card h4 {
            font-size: 18px;
            margin-bottom: 15px;
        }
        
        .benefit-card p {
            font-size: 14px;
            text-align: center;
        }
        
        .cta-section {
            background: linear-gradient(135deg, #000 0%, #333 100%);
            color: white;
            padding: 50px;
            text-align: center;
        }
        
        .cta-button {
            background: #00BFFF;
            color: white;
            padding: 15px 30px;
            border: none;
            border-radius: 25px;
            font-size: 18px;
            font-weight: bold;
            cursor: pointer;
            transition: all 0.3s ease;
            display: inline-block;
            margin: 20px 10px;
            text-decoration: none;
        }
        
        .cta-button:hover {
            background: #0099d4;
            transform: translateY(-2px);
        }
        
        .footer {
            background: #f8f9fa;
            padding: 30px;
            text-align: center;
            color: #666;
            font-size: 14px;
        }
        
        @media (max-width: 768px) {
            .section {
                padding: 30px 20px;
            }
            
            .header {
                padding: 30px 20px;
            }
            
            .logo-section {
                flex-direction: column;
                gap: 20px;
            }
            
            .proposal-title h2 {
                font-size: 28px;
            }
            
            .metrics-grid,
            .strategy-grid,
            .benefits-grid {
                grid-template-columns: 1fr;
            }
            
            .timeline-item {
                flex-direction: column;
                text-align: center;
            }
            
            .timeline-number {
                margin: 0 auto 15px auto;
            }
            
            .cta-button {
                display: block;
                margin: 15px auto;
                max-width: 250px;
            }
        }
        
        @media (max-width: 480px) {
            .section h2 {
                font-size: 24px;
            }
            
            .logo {
                width: 70px;
                height: 70px;
            }
            
            .loc-insights h1 {
                font-size: 24px;
            }
            
            .proposal-title h2 {
                font-size: 24px;
            }
            
            .proposal-title h3 {
                font-size: 18px;
            }
            
            .price {
                font-size: 36px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Header -->
        <div class="header">
            <div class="header-content">
                <div class="logo-section">
                    <div class="logo">
                        <div class="wb">WB</div>
                        <div class="brand">WHITE BEBIDAS</div>
                        <div class="diamond"></div>
                    </div>
                    <div class="loc-insights">
                        <h1>LOC INSIGHTS</h1>
                        <p>Digital Marketing & Growth Strategy</p>
                    </div>
                </div>
                <div class="proposal-title">
                    <h2>PROPOSTA COMERCIAL</h2>
                    <h3>Estratégia de Crescimento Digital</h3>
                </div>
                <div class="date">
                    Setembro 2025 | Proposta Confidencial
                </div>
            </div>
        </div>

        <!-- Apresentação e Diagnóstico -->
        <div class="section">
            <h2>
                <div class="section-icon">📊</div>
                APRESENTAÇÃO E DIAGNÓSTICO
            </h2>
            
            <div style="background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%); padding: 30px; border-radius: 15px; margin-bottom: 30px;">
                <h3 style="color: #000; margin-bottom: 20px; text-align: center;">🏆 QUEM É A WHITE BEBIDAS HOJE</h3>
                
                <div class="metrics-grid">
                    <div class="metric-card">
                        <h3>4.785</h3>
                        <p>Seguidores Fiéis</p>
                    </div>
                    <div class="metric-card">
                        <h3>5 anos</h3>
                        <p>De História e Credibilidade</p>
                    </div>
                    <div class="metric-card problem">
                        <h3>0.88%</h3>
                        <p>Engajamento Atual<br><small>(Grande oportunidade!)</small></p>
                    </div>
                    <div class="metric-card problem">
                        <h3>Baixa</h3>
                        <p>Frequência de Posts<br><small>(Potencial inexplorado)</small></p>
                    </div>
                </div>
            </div>

            <p><strong>A White Bebidas já possui:</strong> ✅ Base sólida de seguidores • ✅ Marca reconhecida localmente • ✅ Credibilidade de 5 anos • ✅ Diferenciais claros (cerveja gelada + gelo cortesia)</p>
            <p><strong>Oportunidades identificadas:</strong> 🎯 Seguidores prontos para comprar mas pouco ativados • 🎯 Potencial de alcance local inexplorado • 🎯 Conversão de seguidores em vendas diretas</p>
        </div>

        <!-- Objetivos -->
        <div class="section">
            <h2>
                <div class="section-icon">🎯</div>
                OBJETIVOS PRINCIPAIS DA PARCERIA
            </h2>
            
            <div class="objectives-list">
                <li><strong>🚀 Mais pedidos diretos pelo Instagram/WhatsApp</strong><br>
                <small>Converter seus 4.785 seguidores em clientes ativos através de estratégias direcionadas</small></li>
                
                <li><strong>❤️ Mais engajamento com seguidores atuais</strong><br>
                <small>Aumentar interação, comentários e compartilhamentos para criar uma comunidade ativa</small></li>
                
                <li><strong>📍 Mais alcance local em Caucaia + região</strong><br>
                <small>Expandir a presença digital para alcançar novos clientes na sua área de entrega</small></li>
            </div>
        </div>

        <!-- Proposta de Trabalho -->
        <div class="section">
            <h2>
                <div class="section-icon">🚀</div>
                MINHA PROPOSTA DE TRABALHO
            </h2>
            
            <div class="strategy-grid">
                <div class="strategy-card">
                    <h3><span class="strategy-icon">📈</span>Gestão de Tráfego (Meta Ads)</h3>
                    <p><strong>• Campanhas segmentadas locais</strong> (Caucaia e região)<br>
                    <strong>• Anúncios otimizados</strong> para conversão em WhatsApp<br>
                    <strong>• Remarketing</strong> para quem já visitou o perfil<br>
                    <strong>• Testes A/B</strong> para melhorar resultados</p>
                </div>
                
                <div class="strategy-card">
                    <h3><span class="strategy-icon">💡</span>Orientação de Estratégia no Instagram</h3>
                    <p><strong>• Dicas de frequência</strong> e melhores horários<br>
                    <strong>• Ideias de promoções</strong> que convertem<br>
                    <strong>• Melhores práticas</strong> para engajamento<br>
                    <strong>• Orientação de conteúdo</strong> que gera vendas</p>
                </div>
                
                <div class="strategy-card">
                    <h3><span class="strategy-icon">📊</span>Relatório Mensal de Resultados</h3>
                    <p><strong>• Alcance e impressões</strong> detalhados<br>
                    <strong>• Cliques no WhatsApp</strong> (lead tracking)<br>
                    <strong>• Pedidos gerados</strong> via Instagram<br>
                    <strong>• ROI das campanhas</strong> e otimizações</p>
                </div>
            </div>
        </div>

        <!-- Investimento -->
        <div class="section">
            <h2>
                <div class="section-icon">💰</div>
                INVESTIMENTO
            </h2>
            
            <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 30px; margin: 30px 0;">
                <div style="background: linear-gradient(135deg, #000 0%, #333 100%); color: white; border-radius: 15px; padding: 40px; text-align: center;">
                    <h3 style="color: #00BFFF; margin-bottom: 15px;">💼 SUA TAXA MENSAL DE GESTÃO</h3>
                    <div style="font-size: 42px; font-weight: bold; margin: 20px 0; color: #00BFFF;">R$ 1.200</div>
                    <p style="font-size: 14px; opacity: 0.9;">Gestão completa + Relatórios + Suporte</p>
                </div>
                
                <div style="background: linear-gradient(135deg, #00BFFF 0%, #0099d4 100%); color: white; border-radius: 15px; padding: 40px; text-align: center;">
                    <h3 style="margin-bottom: 15px;">💸 VERBA RECOMENDADA EM ANÚNCIOS</h3>
                    <div style="font-size: 42px; font-weight: bold; margin: 20px 0;">R$ 500</div>
                    <p style="font-size: 14px; opacity: 0.9;">Mínimo (pago direto ao Meta Ads)</p>
                </div>
            </div>
            
            <div style="background: #f8f9fa; border: 2px solid #00BFFF; border-radius: 10px; padding: 25px; text-align: center; margin-top: 30px;">
                <h4 style="color: #000; margin-bottom: 15px;">📋 RESUMO DO INVESTIMENTO MENSAL:</h4>
                <p style="font-size: 16px;"><strong>R$ 1.200</strong> (taxa de gestão) + <strong>R$ 500+</strong> (verba de anúncios) = <strong style="color: #00BFFF;">Total a partir de R$ 1.700/mês</strong></p>
                <p style="font-size: 14px; color: #666; margin-top: 10px;"><em>*A verba de anúncios é paga diretamente ao Meta/Facebook, não para mim</em></p>
            </div>
        </div>

        <!-- Benefícios -->
        <div class="section">
            <h2>
                <div class="section-icon">⭐</div>
                BENEFÍCIOS ESPERADOS
            </h2>
            
            <div class="benefits-grid">
                <div class="benefit-card">
                    <h4>📱 AUMENTO DE PEDIDOS VIA WHATSAPP</h4>
                    <p>Campanhas direcionadas para converter<br>seguidores em clientes reais<br>com mensagens otimizadas</p>
                </div>
                <div class="benefit-card">
                    <h4>🏆 MAIOR RECONHECIMENTO LOCAL</h4>
                    <p>Presença forte em Caucaia e região<br>através de anúncios segmentados<br>e engajamento constante</p>
                </div>
                <div class="benefit-card">
                    <h4>❤️ MAIS ENGAJAMENTO ESPONTÂNEO</h4>
                    <p>Stories e posts com mais curtidas,<br>comentários e compartilhamentos<br>através de estratégias testadas</p>
                </div>
                <div class="benefit-card">
                    <h4>📊 RESULTADOS MENSURÁVEIS</h4>
                    <p>Relatórios claros mostrando<br>quantos cliques, leads e vendas<br>cada campanha está gerando</p>
                </div>
            </div>
        </div>

        <!-- Próximos Passos -->
        <div class="section">
            <h2>
                <div class="section-icon">🚀</div>
                PRÓXIMOS PASSOS
            </h2>
            
            <div class="timeline">
                <div class="timeline-item">
                    <div class="timeline-number">1</div>
                    <div>
                        <h3>✅ APROVAÇÃO DA PROPOSTA</h3>
                        <p>Confirmação do interesse em seguir com a parceria</p>
                    </div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-number">2</div>
                    <div>
                        <h3>🔧 ALINHAMENTO INICIAL + CONFIGURAÇÕES</h3>
                        <p>Setup do Ads Manager, definição de metas e acessos necessários</p>
                    </div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-number">3</div>
                    <div>
                        <h3>🚀 LANÇAMENTO DAS PRIMEIRAS CAMPANHAS</h3>
                        <p>Início dos anúncios e acompanhamento diário dos resultados</p>
                    </div>
                </div>
            </div>
        </div>

        <!-- CTA -->
        <div class="cta-section">
            <h2 style="color: #00BFFF; margin-bottom: 20px;">PRONTO PARA ACELERAR O CRESCIMENTO?</h2>
            <p style="font-size: 18px; margin-bottom: 30px;">Vamos transformar seus 4.785 seguidores em uma máquina de vendas!</p>
            
            <a href="https://wa.me/5521976487628?text=Olá!%20Gostaria%20de%20aprovar%20a%20proposta%20para%20White%20Bebidas." target="_blank" class="cta-button">💬 APROVAR PROPOSTA</a>
            <a href="https://calendly.com/locinsights" target="_blank" class="cta-button">📞 AGENDAR REUNIÃO</a>
            
            <div style="margin-top: 30px; font-size: 16px;">
                <p><strong>📱 WhatsApp:</strong> <a href="https://wa.me/5521976487628" target="_blank" style="color: white; text-decoration: underline;">(21) 97648-7628</a></p>
                <p><strong>📧 Email:</strong> <a href="mailto:insights.loc@gmail.com" style="color: white; text-decoration: underline;">insights.loc@gmail.com</a></p>
                <p><strong>🌐 Website:</strong> <a href="https://www.locinsights.com.br" target="_blank" style="color: white; text-decoration: underline;">www.locinsights.com.br</a></p>
            </div>
        </div>

        <!-- Footer -->
        <div class="footer">
            <p><strong>LOC INSIGHTS</strong> - Digital Marketing & Growth Strategy</p>
            <p>Proposta válida por 15 dias • Confidencial e exclusiva para White Bebidas</p>
            <p style="margin-top: 10px; font-size: 12px;">
                Este documento é propriedade intelectual da LOC Insights e contém informações confidenciais.<br>
                Reprodução ou distribuição não autorizada é proibida.
            </p>
            <p style="margin-top: 15px; font-size: 12px;">
                © 2023 LOC Insights. Todos os direitos reservados.
            </p>
        </div>
    </div>
</body>
</html>
