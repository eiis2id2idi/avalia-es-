<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minhas Avaliações</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 20px;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            background: white;
            border-radius: 20px;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
            overflow: hidden;
        }

        .header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 40px;
            text-align: center;
        }

        .header h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.2);
        }

        .header p {
            font-size: 1.1em;
            opacity: 0.9;
        }

        .content {
            padding: 40px;
        }

        .section-title {
            font-size: 1.8em;
            color: #667eea;
            margin-bottom: 30px;
            padding-bottom: 10px;
            border-bottom: 3px solid #667eea;
        }

        .avaliacao {
            background: #f8f9fa;
            padding: 25px;
            border-radius: 15px;
            margin-bottom: 20px;
            border-left: 5px solid #667eea;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .avaliacao:hover {
            transform: translateX(10px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }

        .avaliacao-user {
            font-size: 1.3em;
            font-weight: bold;
            color: #333;
            margin-bottom: 10px;
            display: flex;
            align-items: center;
        }

        .avaliacao-user::before {
            content: "👤";
            margin-right: 10px;
            font-size: 1.2em;
        }

        .avaliacao-texto {
            color: #555;
            font-size: 1.1em;
            line-height: 1.6;
        }

        .badge {
            display: inline-block;
            background: #28a745;
            color: white;
            padding: 5px 15px;
            border-radius: 20px;
            font-size: 0.9em;
            margin-top: 10px;
            font-weight: bold;
        }

        .estrelas {
            color: #ffc107;
            font-size: 1.2em;
            margin-top: 10px;
        }

        .cta-section {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 30px;
            border-radius: 15px;
            text-align: center;
            margin-top: 30px;
        }

        .cta-section h3 {
            font-size: 1.5em;
            margin-bottom: 10px;
        }

        .cta-section p {
            font-size: 1.1em;
            opacity: 0.9;
        }

        .form-avaliacao {
            margin-top: 20px;
        }

        .input-field {
            width: 100%;
            padding: 15px;
            margin-bottom: 15px;
            border: none;
            border-radius: 10px;
            font-size: 1em;
            font-family: inherit;
        }

        .textarea-field {
            min-height: 100px;
            resize: vertical;
        }

        .estrelas-select {
            font-size: 2em;
            margin: 15px 0;
            cursor: pointer;
        }

        .estrela {
            color: #ffc107;
            margin: 0 5px;
            transition: transform 0.2s;
        }

        .estrela:hover {
            transform: scale(1.2);
        }

        .btn-enviar {
            background: white;
            color: #667eea;
            border: none;
            padding: 15px 40px;
            font-size: 1.1em;
            font-weight: bold;
            border-radius: 10px;
            cursor: pointer;
            transition: all 0.3s;
        }

        .btn-enviar:hover {
            background: #f0f0f0;
            transform: scale(1.05);
        }

        @keyframes slideIn {
            from {
                opacity: 0;
                transform: translateX(-50px);
            }
            to {
                opacity: 1;
                transform: translateX(0);
            }
        }

        @media (max-width: 600px) {
            .header h1 {
                font-size: 1.8em;
            }
            
            .content {
                padding: 20px;
            }
            
            .section-title {
                font-size: 1.4em;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>✨ Minhas Avaliações e Referências ✨</h1>
            <p>Confira o que nossos clientes dizem</p>
        </div>

        <div class="content">
            <h2 class="section-title">📋 Vai tê Referências</h2>

            <div class="avaliacao">
                <div class="avaliacao-user">Lucas8272js (Discord)</div>
                <div class="estrelas">⭐⭐⭐⭐⭐</div>
                <div class="avaliacao-texto">
                    Confiável dms slk deu dinheiro certinho
                </div>
                <span class="badge">✓ Verificado</span>
            </div>

            <div class="avaliacao">
                <div class="avaliacao-user">Samuel_ripkk</div>
                <div class="estrelas">⭐⭐⭐⭐⭐</div>
                <div class="avaliacao-texto">
                    Slkkkkkkkk confiável tropa kkkk
                </div>
                <span class="badge">✓ Verificado</span>
            </div>

            <div class="avaliacao">
                <div class="avaliacao-user">Thzin.xp</div>
                <div class="estrelas">⭐⭐⭐⭐⭐</div>
                <div class="avaliacao-texto">
                    Mnnn confiável dms confiem tropa
                </div>
                <span class="badge">✓ Verificado</span>
            </div>

            <div class="avaliacao">
                <div class="avaliacao-user">Julio67kk</div>
                <div class="estrelas">⭐⭐⭐⭐⭐</div>
                <div class="avaliacao-texto">
                    Mnn obg
                </div>
                <span class="badge">✓ Verificado</span>
            </div>

            <div class="avaliacao">
                <div class="avaliacao-user">Bobuz86.p</div>
                <div class="estrelas">⭐⭐⭐⭐⭐</div>
                <div class="avaliacao-texto">
                    Slk 100% confiável
                </div>
                <span class="badge">✓ Verificado</span>
            </div>

            <div class="cta-section">
                <h3>💬 Faça sua Avaliação Também!</h3>
                <p>Deixe seu feedback abaixo</p>
                
                <div class="form-avaliacao">
                    <input type="text" id="nomeUsuario" placeholder="Seu nome/usuário" class="input-field">
                    
                    <div class="estrelas-select">
                        <span class="estrela" data-valor="1">☆</span>
                        <span class="estrela" data-valor="2">☆</span>
                        <span class="estrela" data-valor="3">☆</span>
                        <span class="estrela" data-valor="4">☆</span>
                        <span class="estrela" data-valor="5">☆</span>
                    </div>
                    
                    <textarea id="textoAvaliacao" placeholder="Escreva sua avaliação..." class="input-field textarea-field"></textarea>
                    
                    <button onclick="adicionarAvaliacao()" class="btn-enviar">Enviar Avaliação</button>
                </div>
            </div>
        </div>
    </div>

    <script>
        let avaliacaoSelecionada = 5;

        // Sistema de estrelas clicáveis
        const estrelas = document.querySelectorAll('.estrela');
        estrelas.forEach(estrela => {
            estrela.addEventListener('click', function() {
                avaliacaoSelecionada = parseInt(this.getAttribute('data-valor'));
                atualizarEstrelas();
            });
            
            estrela.addEventListener('mouseover', function() {
                const valor = parseInt(this.getAttribute('data-valor'));
                estrelas.forEach((e, index) => {
                    if (index < valor) {
                        e.textContent = '★';
                    } else {
                        e.textContent = '☆';
                    }
                });
            });
        });

        document.querySelector('.estrelas-select').addEventListener('mouseout', atualizarEstrelas);

        function atualizarEstrelas() {
            estrelas.forEach((estrela, index) => {
                if (index < avaliacaoSelecionada) {
                    estrela.textContent = '★';
                } else {
                    estrela.textContent = '☆';
                }
            });
        }

        function adicionarAvaliacao() {
            const nome = document.getElementById('nomeUsuario').value.trim();
            const texto = document.getElementById('textoAvaliacao').value.trim();

            if (!nome || !texto) {
                alert('Por favor, preencha todos os campos!');
                return;
            }

            const novaAvaliacao = document.createElement('div');
            novaAvaliacao.className = 'avaliacao';
            novaAvaliacao.style.animation = 'slideIn 0.5s ease';
            
            const estrelasHtml = '⭐'.repeat(avaliacaoSelecionada);
            
            novaAvaliacao.innerHTML = `
                <div class="avaliacao-user">${nome}</div>
                <div class="estrelas">${estrelasHtml}</div>
                <div class="avaliacao-texto">${texto}</div>
                <span class="badge">✓ Verificado</span>
            `;

            const secaoAvaliacoes = document.querySelector('.content');
            const ctaSection = document.querySelector('.cta-section');
            secaoAvaliacoes.insertBefore(novaAvaliacao, ctaSection);

            // Limpar formulário
            document.getElementById('nomeUsuario').value = '';
            document.getElementById('textoAvaliacao').value = '';
            avaliacaoSelecionada = 5;
            atualizarEstrelas();

            // Scroll suave para a nova avaliação
            novaAvaliacao.scrollIntoView({ behavior: 'smooth', block: 'center' });
        }
    </script>
</body>
</html>
