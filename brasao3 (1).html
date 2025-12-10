
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Controle de Equipamentos</title>
    <style>
        
        :root {
            --cor-verde: #4CAF50;
            --cor-azul: #2196F3;
            --cor-amarela: #ffcc00;
            --cor-cinza: #f0f0f0;
            --cor-vermelho: #f44336;
            --borda-radius: 5px;
            --espacamento: 15px;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            padding: 10px;
            background-color: #fafafa;
            line-height: 1.4;
        }

        h1, h3 {
            color: #333;
            margin-bottom: 15px;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
        }

        .secao {
            background: white;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: var(--borda-radius);
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }

        .cabecalho {
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 20px;
        }

        /* NOVO: Container para logo e título */
        .logo-titulo {
            display: flex;
            align-items: center;
            gap: 15px;
        }

        /* NOVO: Estilo do brasão */
        .brasao-navio {
            width: 70px;
            height: 70px;
            object-fit: contain;
            border-radius: 8px;
        }

        .titulo-principal h1 {
            margin-bottom: 5px;
        }

        /* NOVO: Subtítulo do navio */
        .subtitulo {
            color: #666;
            font-size: 0.9em;
            font-style: italic;
        }

        .controles-data {
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .controles-data label {
            font-weight: bold;
            white-space: nowrap;
        }

        .controles-data input {
            padding: 8px 12px;
            border: 1px solid #ddd;
            border-radius: var(--borda-radius);
            font-size: 2em;
        }

        .equipamentos-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(140px, 1fr));
            gap: 10px;
            margin-top: 15px;
        }

        .equipamento-btn {
            padding: 12px 8px;
            border: none;
            border-radius: var(--borda-radius);
            cursor: pointer;
            font-weight: bold;
            transition: all 0.3s ease;
            background-color: var(--cor-cinza);
            font-size: 1.2em;
            min-height: 50px;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            word-break: break-word;
        }

        .equipamento-btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 4px 8px rgba(0,0,0,0.15);
        }

        .equipamento-btn.verde { background-color: var(--cor-verde); color: white; }
        .equipamento-btn.amarela { background-color: var(--cor-amarela); color: white; }
        .equipamento-btn.azul { background-color: var(--cor-azul); color: white; }
        .equipamento-btn.vermelho { background-color: var(--cor-vermelho); color: white; }

        .legenda-container, .combustiveis-container {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            align-items: center;
        }

        .legenda-item, .combustivel-item {
            display: flex;
            align-items: center;
            margin: 5px 0;
        }

        .cor-legenda {
            width: 20px;
            height: 20px;
            margin-right: 8px;
            border-radius: 3px;
            flex-shrink: 0;
        }

        .combustivel-item {
            margin: 0 5px 10px 0;
        }

        .combustivel-item label {
            margin-right: 8px;
            font-weight: bold;
            min-width: 50px;
            font-size: 16px;
        }

        .combustivel-item input {
            width: 100px;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 10px;
            text-align: center;
            font-size: 18px;
        }

        .unidade {
            margin-left: 5px;
            font-weight: bold;
        }

        @media (max-width: 768px) {
            .cabecalho {
                flex-direction: column;
                align-items: flex-start;
            }
            
            /* NOVO: Ajustes mobile para o logo */
            .logo-titulo {
                flex-direction: column;
                text-align: center;
                gap: 10px;
            }
            
            .brasao-navio {
                width: 60px;
                height: 60px;
            }
            
            .controles-data {
                width: 100%;
                justify-content: space-between;
            }
            
            .equipamentos-grid {
                grid-template-columns: repeat(auto-fill, minmax(120px, 1fr));
            }
            
            .legenda-container, .combustiveis-container {
                flex-direction: column;
                align-items: flex-start;
                gap: 10px;
            }
            
            .combustivel-item {
                margin-right: 0;
            }
        }

        .contador-estados {
            margin-top: 15px;
            padding: 10px;
            background: #e3f2fd;
            border-radius: var(--borda-radius);
            font-size: 0.9em;
        }

        .data-atual {
            font-weight: bold;
            color: #2196F3;
        }

        .loading {
            opacity: 0.7;
            pointer-events: none;
        }
    </style>
</head>
<body>
    <div class="container">
        <header class="secao">
            <div class="cabecalho">
                <!-- NOVO: Container do logo e título -->
                <div class="logo-titulo">
                    <!-- BRASÃO DO NAVIO - Substitua pela imagem real do seu navio -->
                    <img src="NAM_Atlântico_Badge.jpg" 
                         alt="Brasão do Navio" 
                         class="brasao-navio"
                         id="brasaoNavio">
                    <div class="titulo-principal">
                        <h1>Controle de Equipamentos</h1>
                        <div class="subtitulo" id="nomeNavio">Nome do Navio</div>
                    </div>
                </div>
                <div class="controles-data">
                    <label for="dataSelecionada">Data do Controle:</label>
                    <input type="date" id="dataSelecionada" name="dataSelecionada">
                    <span class="data-atual" id="dataExibicao"></span>
                </div>
            </div>
        </header>

        <section class="secao">
            <h3>Status dos Equipamentos</h3>
            <div class="equipamentos-grid" id="equipamentos">
                <!-- Botões gerados via JavaScript -->
            </div>
            
        </section>

        <section class="secao">
            <h3>Legenda de Status</h3>
            <div class="legenda-container">
                <div class="legenda-item">
                    <div class="cor-legenda" style="background-color: var(--cor-verde);"></div>
                    <span>Equipamento na linha</span>
                </div>
                <div class="legenda-item">
                    <div class="cor-legenda" style="background-color: var(--cor-azul);"></div>
                    <span>Equipamento de Serviço</span>
                </div>
                <div class="legenda-item">
                    <div class="cor-legenda" style="background-color: var(--cor-amarela);"></div>
                    <span>Operando com Restrição</span>
                </div>
                <div class="legenda-item">
                    <div class="cor-legenda" style="background-color: var(--cor-cinza);"></div>
                    <span>Equipamento disponível</span>
                </div>
                <div class="legenda-item">
                    <div class="cor-legenda" style="background-color: var(--cor-vermelho);"></div>
                    <span>Equipamento indisponível</span>
                </div>
            </div>
        </section>

        <section class="secao">
            <h3>Carga Líquida</h3>
            <div class="combustiveis-container">
                <div class="combustivel-item">
                    <label for="agua">Aguada:</label>
                    <input type="number" value="555" step="0.001" min="0" id="agua">
                    <span class="unidade">m³</span>
                </div>
                <div class="combustivel-item">
                    <label for="oleo_lub">Óleo lub:</label>
                    <input type="number" value="98" step="0.001" min="0" id="oleo_lub">
                    <span class="unidade">m³</span>
                </div>
                <div class="combustivel-item">
                    <label for="oleo_comb">Óleo comb:</label>
                    <input type="number" value="100" step="0.001" min="0" id="oleo_comb">
                    <span class="unidade">m³</span>
                </div>
                <div class="combustivel-item">
                    <label for="jp5">JP5:</label>
                    <input type="number" value="150" step="0.001" min="0" id="jp5">
                    <span class="unidade">m³</span>
                </div>
            </div>
        </section>
    </div>

    <script>
        // Configurações centralizadas
        const CONFIG = {
            estados: [
                { classe: "verde", texto: "Na linha", cor: "#4CAF50" },
                { classe: "amarela", texto: "com Restrição", cor: "#ffcc00" },
                { classe: "azul", texto: "de Serviço", cor: "#2196F3" },
                { classe: "", texto: "Disponível", cor: "#f0f0f0" },
                { classe: "vermelho", texto: "Indisponível", cor: "#f44336" }
            ],
            equipamentos: [
                "MCP BB", "MCP BE", "MCA 1", "MCA 2", "MCA 3", "MCA 4", " Gerador de Emerg", 
                "URA 1", "URA 2", "URA 3", "URA 4", "URA 5", "URA 6",
                "GOR 1", "GOR 2", "GOR 3", "GOR 4", "DEMIN",
                "Maquina do Leme BE 1", "Maquina do Leme BE 2", 
                "Maquina do Leme BB 1", "Maquina do Leme BB 2",
                "HPSW 1", "HPSW 2", "HPSW 3", "HPSW 4", "HPSW 5",
                "LPSW 1", "LPSW 2", "LPSW 3", "LPSW 4",
                "Bomba de Serviço 1", "Bomba de Serviço 2", "Bomba de Serviço 3",
                "MotoBomba 1", "MotoBomba 2", "MotoBomba 3", "MotoBomba 4",
                "CAP 1", "CAP 2", "CAP 3", "CMP 1", "CMP 2", "CMP de Emergência",
                "CBP 1", "CBP 2", "CBP 3", "CBP 4",
                "Planta Frigorífica 1", "Planta Frigorífica 2",
                "Estabilizador BB", "Estabilizador BE", 
                "BAG 1", "BAG 2", "BAG 3", "BAG 4",
                "BOILER 1", "BOILER 2", "BOILER 3", "BOILER 4",
                "Bomba de Água Quente 1", "Bomba de Água Quente 2",
                "Separador de Óleo/Água",
                "Purificador Óleo Comb 1", "Purificador Óleo Comb 2",
                "Purificador Óleo Lub 1", "Purificador Óleo Lub 2",
                "Purificador Redutora 1", "Purificador Redutora 2",
                "Purificador Óleo Lub GER Diesel",
                "Elevador de Aeronaves AV", "Elevador de Aeronaves AR",
                "Guindaste", "Container 1", "Container 2", "Container 3",
                "Proteção Catódica AV", "Proteção Catódica AR"
            ],
            // NOVO: Configuração do navio
            navio: {
                nome: "NAM ATLÂNTICO - A140", // Altere para o nome do seu navio
                brasao: "NAM_Atlântico_Badge.jpg"
            }
        };

        class GerenciadorEquipamentos {
            constructor() {
                this.initialized = false;
                this.dataAtual = this.getDataAtualFormatada();
                this.estadosAtuais = {};
                this.init();
            }

            async init() {
                try {
                    // Adiciona classe de loading
                    document.body.classList.add('loading');
                    
                    // NOVO: Configurar informações do navio
                    this.configurarNavio();
                    
                    await this.configurarData();
                    await this.carregarDadosDaData();
                    await this.criarBotoesEquipamentos();
                    this.configurarCombustiveis();
                    this.configurarAutoSave();
                    
                    this.initialized = true;
                    console.log('Sistema inicializado com sucesso');
                } catch (error) {
                    console.error('Erro na inicialização:', error);
                } finally {
                    document.body.classList.remove('loading');
                }
            }

            // NOVO: Método para configurar informações do navio
            configurarNavio() {
                // Configurar nome do navio
                document.getElementById('nomeNavio').textContent = CONFIG.navio.nome;
                
                // Configurar brasão - você pode substituir por uma imagem real
                const brasao = document.getElementById('brasaoNavio');
                
                // Se você tiver uma imagem real, substitua esta linha:
                // brasao.src = 'brasao_navio.png'; // ou .jpg, .svg
                // brasao.alt = `Brasão do ${CONFIG.navio.nome}`;
            }

            getDataAtualFormatada() {
                const hoje = new Date();
                return hoje.toISOString().split('T')[0];
            }

            async configurarData() {
                return new Promise((resolve) => {
                    const dataInput = document.getElementById('dataSelecionada');
                    const dataExibicao = document.getElementById('dataExibicao');
                    
                    // Tenta carregar data salva
                    const dataSalva = localStorage.getItem('dataControle');
                    this.dataAtual = dataSalva || this.dataAtual;
                    
                    // Configurar data atual
                    dataInput.value = this.dataAtual;
                    dataExibicao.textContent = this.formatarData(this.dataAtual);
                    
                    // Event listener para mudança de data
                    dataInput.addEventListener('change', async (e) => {
                        if (!this.initialized) return;
                        
                        document.body.classList.add('loading');
                        try {
                            // Salva estados atuais antes de mudar
                            await this.salvarEstado();
                            
                            this.dataAtual = e.target.value;
                            dataExibicao.textContent = this.formatarData(this.dataAtual);
                            
                            await this.carregarDadosDaData();
                            await this.atualizarInterface();
                            this.salvarData();
                        } catch (error) {
                            console.error('Erro ao mudar data:', error);
                        } finally {
                            document.body.classList.remove('loading');
                        }
                    });
                    
                    resolve();
                });
            }

            // ... o resto dos métodos permanece igual
            formatarData(dataString) {
                try {
                    const data = new Date(dataString + 'T00:00:00');
                    return data.toLocaleDateString('pt-BR', {
                        weekday: 'long',
                        year: 'numeric',
                        month: 'long',
                        day: 'numeric'
                    });
                } catch (error) {
                    console.error('Erro ao formatar data:', error);
                    return dataString;
                }
            }

            async carregarDadosDaData() {
                return new Promise((resolve) => {
                    try {
                        // Carrega os estados específicos para a data selecionada
                        const dadosSalvos = localStorage.getItem(`estados_${this.dataAtual}`);
                        
                        if (dadosSalvos) {
                            const parsed = JSON.parse(dadosSalvos);
                            // Valida se os dados são um objeto válido
                            if (parsed && typeof parsed === 'object') {
                                this.estadosAtuais = parsed;
                            } else {
                                this.estadosAtuais = {};
                            }
                        } else {
                            this.estadosAtuais = {};
                        }
                        
                        console.log(`Dados carregados para ${this.dataAtual}:`, this.estadosAtuais);
                        resolve();
                    } catch (error) {
                        console.error('Erro ao carregar dados:', error);
                        this.estadosAtuais = {};
                        resolve();
                    }
                });
            }

            async criarBotoesEquipamentos() {
                const container = document.getElementById("equipamentos");
                
                // Limpa container de forma segura
                while (container.firstChild) {
                    container.removeChild(container.firstChild);
                }
                
                // Cria botões com timeout para não travar a UI
                for (let i = 0; i < CONFIG.equipamentos.length; i++) {
                    const equipamento = CONFIG.equipamentos[i];
                    
                    // Inicializa estado se não existir
                    if (this.estadosAtuais[equipamento] === undefined) {
                        this.estadosAtuais[equipamento] = 3; // Estado padrão: Disponível
                    }
                    
                    const btn = this.criarBotaoEquipamento(equipamento);
                    container.appendChild(btn);
                    
                    // Pequeno delay para não travar a UI com muitos elementos
                    if (i % 10 === 0) {
                        await new Promise(resolve => setTimeout(resolve, 0));
                    }
                }
                
                this.atualizarContadorEstados();
            }

            criarBotaoEquipamento(equipamento) {
                const btn = document.createElement("button");
                btn.className = "equipamento-btn";
                btn.textContent = equipamento;
                
                this.atualizarAparenciaBotao(btn, equipamento);
                
                btn.addEventListener("click", () => this.alternarEstado(equipamento, btn));
                btn.addEventListener("contextmenu", (e) => {
                    e.preventDefault();
                    this.resetarEstado(equipamento, btn);
                });

                return btn;
            }

            alternarEstado(equipamento, elemento) {
                if (!this.initialized) return;
                
                this.estadosAtuais[equipamento] = 
                    (this.estadosAtuais[equipamento] + 1) % CONFIG.estados.length;
                
                this.atualizarAparenciaBotao(elemento, equipamento);
                this.atualizarContadorEstados();
                
                console.log(`${equipamento}: ${CONFIG.estados[this.estadosAtuais[equipamento]].texto}`);
            }

            resetarEstado(equipamento, elemento) {
                if (!this.initialized) return;
                
                this.estadosAtuais[equipamento] = 3; // Volta para "Disponível"
                this.atualizarAparenciaBotao(elemento, equipamento);
                this.atualizarContadorEstados();
                
                console.log(`${equipamento}: resetado para Disponível`);
            }

            atualizarAparenciaBotao(botao, equipamento) {
                const estadoIndex = this.estadosAtuais[equipamento];
                const estado = CONFIG.estados[estadoIndex];
                
                if (estado) {
                    botao.className = `equipamento-btn ${estado.classe}`;
                    botao.setAttribute("aria-label", `${equipamento} - ${estado.texto}`);
                }
            }

            async atualizarInterface() {
                await this.criarBotoesEquipamentos();
            }

            atualizarContadorEstados() {
                const contador = document.getElementById("contadorEstados");
                if (!contador) return;
                
                const counts = {};
                
                // Inicializa contadores
                CONFIG.estados.forEach((_, index) => {
                    counts[index] = 0;
                });

                // Conta os estados
                Object.values(this.estadosAtuais).forEach(estado => {
                    if (estado !== undefined && counts[estado] !== undefined) {
                        counts[estado] = (counts[estado] || 0) + 1;
                    }
                });

                const texto = CONFIG.estados.map((estado, index) => 
                    `${estado.texto}: ${counts[index] || 0}`
                ).join(" | ");

                contador.textContent = `Resumo: ${texto} | Data: ${this.dataAtual}`;
            }

            async salvarEstado() {
                return new Promise((resolve) => {
                    try {
                        localStorage.setItem(`estados_${this.dataAtual}`, JSON.stringify(this.estadosAtuais));
                        console.log('Estados salvos com sucesso');
                        resolve(true);
                    } catch (error) {
                        console.error('Erro ao salvar estados:', error);
                        resolve(false);
                    }
                });
            }

            salvarData() {
                try {
                    localStorage.setItem('dataControle', this.dataAtual);
                } catch (error) {
                    console.error('Erro ao salvar data:', error);
                }
            }

            configurarAutoSave() {
                // Salva a cada 3 segundos quando houver mudanças
                setInterval(async () => {
                    if (this.initialized && Object.keys(this.estadosAtuais).length > 0) {
                        await this.salvarEstado();
                    }
                }, 3000);
            }

            configurarCombustiveis() {
                document.querySelectorAll('.combustivel-item input').forEach(input => {
                    // Carregar valor salvo para a data atual
                    const carregarCombustivel = () => {
                        try {
                            const salvo = localStorage.getItem(`combustivel_${input.id}_${this.dataAtual}`);
                            if (salvo !== null) {
                                input.value = salvo;
                            }
                        } catch (error) {
                            console.error('Erro ao carregar combustível:', error);
                        }
                    };

                    // Event listener para mudanças
                    input.addEventListener('change', function() {
                        try {
                            localStorage.setItem(`combustivel_${this.id}_${this.dataAtual}`, this.value);
                        } catch (error) {
                            console.error('Erro ao salvar combustível:', error);
                        }
                    });

                    // Carregar ao inicializar
                    carregarCombustivel();
                    
                    // Recarregar quando mudar a data
                    document.getElementById('dataSelecionada').addEventListener('change', carregarCombustivel);
                });
            }
        }

        // Inicializar quando a página carregar
        document.addEventListener('DOMContentLoaded', () => {
            new GerenciadorEquipamentos();
        });

        // Prevenir perda de dados ao recarregar a página
        window.addEventListener('beforeunload', (event) => {
            // Opcional: pode adicionar uma confirmação aqui se necessário
        });
    </script>
</body>
</html>
