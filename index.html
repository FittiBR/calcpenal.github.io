
<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculadora Penal GTA RP</title>
    <style>
        body {
            background-color: black;
            color: white;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            min-height: 100vh;
        }
        

        .header {
            width: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
            margin-bottom: 20px;
        }

        .header img {
            max-width: 300px;
            height: auto;
        }

        .container {
            width: 90%;
            max-width: 900px;
            padding: 20px;
            border-radius: 10px;
            background: #121212;
            box-shadow: 0 0 15px rgba(92, 158, 255, 0.5);
            border: 2px solid #5C9EFF;
            
        }

        h2 {
            text-align: center;
            color: #8A2BE2;
            margin-bottom: 20px;
        }

        .main-container {
            display: flex;
            flex-direction: column;
            gap: 20px;
        }

        .top-section {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            gap: 20px;
        }

        .form-section,
        .report-section {
            flex: 1;
            min-width: 300px;
            padding: 15px;
            background: #1E1E1E;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(92, 158, 255, 0.3);
            border: 2px solid #5C9EFF;
        }

        .crime-section {
            width: 100%;
            padding: 15px;
            background: #1E1E1E;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(92, 158, 255, 0.3);
            border: 2px solid #5C9EFF;
        }

        .crime-container {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 10px;
            max-height: 250px;
            overflow-y: auto;
            padding: 10px;
            border: 2px solid #5C9EFF;
            background: #222;
            border-radius: 5px;
        }

        .crime {
            background: #333;
            color: white;
            border-radius: 5px;
            padding: 10px;
            text-align: left;
            font-size: 14px;
            transition: 0.3s;
        }

        .crime:hover {
            background: #444;
        }

        .atenuantes-section {
            width: 100%;
            margin-top: 20px;
            padding: 10px;
            background: #1E1E1E;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(92, 158, 255, 0.3);
            max-height: 120px;
            overflow-y: auto;
            border: 2px solid #5C9EFF;
        }

        #resultado,
        #relatorioDados {
            width: 95%;
            height: 80px;
            margin-top: 10px;
            resize: vertical;
            font-size: 14px;
            padding: 15px;
            background: #222;
            color: white;
            border: 2px solid #5C9EFF;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(92, 158, 255, 0.3);
            line-height: 1.5;
        }

        .input-group {
            display: flex;
            flex-direction: column;
            gap: 5px;
            margin-bottom: 15px;
        }

        .input-group label {
            font-size: 14px;
            font-weight: bold;
            color: #5C9EFF;
        }

        .input-group input {
            padding: 10px;
            border: 2px solid #5C9EFF;
            border-radius: 5px;
            background: #121212;
            color: white;
            outline: none;
            font-size: 14px;
        }

        button {
            width: 100%;
            padding: 10px;
            margin-top: 10px;
            border: none;
            background: #8A2BE2;
            color: white;
            font-size: 16px;
            font-weight: bold;
            border-radius: 5px;
            cursor: pointer;
            transition: 0.3s;
        }

        button:hover {
            background: #6a1bbd;
        }

        /* Responsividade */
        @media (max-width: 768px) {
            .top-section {
                flex-direction: column;
                gap: 15px;
            }

            .crime-container {
                grid-template-columns: repeat(2, 1fr);
            }
        }
    </style>
    <div>
        <div class="header">
            <img src="OAB_BC_SEM_FUNDO.png" alt="OAB Santa Catarina">
        </div>
    </div>

    <div class="container">
        <h2 style="font-family:cursive;">Calculadora Penal - OAB SC</h2>
        <div class="main-container">
            <div class="top-section">
                <div class="crime-section">
                    <h3>Crimes</h3>
                    <input type="text" id="searchCrime" placeholder="Pesquisar crime..." oninput="filtrarCrimes()"
                        style="width: 100%; padding: 10px; border: 2px solid #5C9EFF; border-radius: 5px; background: #121212; color: white; margin-bottom: 10px;">
                    <div class="crime-container" id="crimes"></div>
                </div>
                
                
                <div class="crime-section">
                    <h3>Atenuantes</h3>
                    <div class="checkbox-group">
                        <input type="checkbox" id="advogado"> <label for="advogado">Advogado Constituído
                            (-30%)</label><br>
                        <input type="checkbox" id="reuPrimario"> <label for="reuPrimario">Réu Primário
                            (-20%)</label><br>
                        <input type="checkbox" id="reuConfesso"> <label for="reuConfesso">Réu Confesso
                            (-20%)</label><br>
                        <input type="checkbox" id="delacao10"> <label for="delacao10">Delação Premiada
                            (-10%)</label><br>
                        <input type="checkbox" id="delacao15"> <label for="delacao15">Delação Premiada
                            (-15%)</label><br>
                    </div>
                    <button onclick="calcularPena()">Calcular Pena</button>
                    <textarea id="resultado" readonly>Pena Final: -- Meses | Multa: -- | Fiança: --</textarea>
                </div>
                <div class="report-section">
                    <h2>Relatório - OAB</h2>
                    <div class="form-section">
                        <div class="input-group">
                            <label for="advogadoNome">Nome do Advogado</label>
                            <input type="text" id="advogadoNome" placeholder="Digite o nome do advogado">
                        </div>
                        <div class="input-group">
                            <label for="rgAdvogado">RG do Advogado</label>
                            <input type="text" id="rgAdvogado" placeholder="Digite o RG do advogado">
                        </div>
                        <div class="input-group">
                            <label for="rgAcompanhante">RG do Acompanhante</label>
                            <input type="text" id="rgAcompanhante" placeholder="Digite o RG do acompanhante">
                        </div>
                        <div class="input-group">
                            <label for="cliente">Nome do Cliente</label>
                            <input type="text" id="cliente" placeholder="Digite o nome do cliente">
                        </div>
                        <div class="input-group">
                            <label for="RGcliente">RG do Cliente</label>
                            <input type="text" id="RGcliente" placeholder="Digite o RG do cliente">
                        </div>
                        <div class="input-group">
                            <label for="Nomeoficial">Nome do Oficial</label>
                            <input type="text" id="Nomeoficial" placeholder="Digite o nome do oficial">
                        </div>
                        <div class="input-group">
                            <label for="rgOficial">RG do Oficial</label>
                            <input type="text" id="rgOficial" placeholder="Digite o RG do cliente">
                        </div>

                        <div class="input-group" style="display: flex; align-items: left; gap: 10px; text-align: left;">
                            <label for="Porte">Porte de armas:</label>
                            <div style="display: flex; flex-direction: column; gap: 5px;">
                                <label for="PorteSim" style="display: flex; align-items: center; gap: 5px;">
                                    <input type="radio" id="PorteSim" name="Porte" value="Sim"> Sim
                                </label>
                                <label for="PorteNao" style="display: flex; align-items: center; gap: 5px;">
                                    <input type="radio" id="PorteNao" name="Porte" value="Nao"> Não
                                </label>
                            </div>
                        </div>

                        <div class="input-group" style="display: flex; align-items: left; gap: 10px; text-align: left;">
                            <label for="Fianca">Pagou a fiança:</label>
                            <div style="display: flex; flex-direction: column; gap: 5px;">
                                <label for="FiancaSim" style="display: flex; align-items: center; gap: 5px;">
                                    <input type="radio" id="FiancaSim" name="Fianca" value="Sim"> Sim
                                </label>
                                <label for="FiancaNao" style="display: flex; align-items: center; gap: 5px;">
                                    <input type="radio" id="FiancaNao" name="Fianca" value="Nao"> Não
                                </label>
                            </div>

                        </div>





                        <div class="input-group">
                            <label for="relatorioDados">Relatório Gerado</label>
                            <textarea id="relatorioDados" readonly></textarea>
                        </div>
                        <button onclick="gerarRelatorio()">Gerar Relatório</button>
                        <button onclick="copiarRelatorio()">Copiar Relatório</button>
            


                    </div>
                </div>
            </div>
        </div>
    </div>


    <script>
        const crimes = [
            { artigo: 1, nome: "Azaralhamento", pena: 100, multa: 100000, fianca: 150000 },
            { artigo: 2, nome: "Prisão Militar", pena: 100, multa: 0, fianca: 0 },
            { artigo: 3, nome: "Prevaricação", pena: 100, multa: 100000, fianca: 150000 },
            { artigo: 4, nome: "Invasão de Departamento Policial", pena: 100, multa: 100000, fianca: 150000 },
            { artigo: 5, nome: "Tentativa de Homicídio", pena: 40, multa: 100000, fianca: 0 },
            { artigo: 6, nome: "Homicídio Culposo", pena: 15, multa: 100000, fianca: 150000 },
            { artigo: 7, nome: "Homicídio Doloso", pena: 15, multa: 120000, fianca: 0 },
            { artigo: 8, nome: "Homicídio Doloso Qualificado", pena: 40, multa: 100000, fianca: 0 },
            { artigo: 9, nome: "Omissão de Socorro", pena: 15, multa: 40000, fianca: 60000 },
            { artigo: 10, nome: "Lesão Corporal", pena: 40, multa: 50000, fianca: 75000 },
            { artigo: 11, nome: "Sequestro", pena: 50, multa: 200000, fianca: 0 },
            { artigo: 12, nome: "Assédio", pena: 500, multa: 1000000, fianca: 0 },
            { artigo: 13, nome: "Calúnia", pena: 15, multa: 30000, fianca: 45000 },
            { artigo: 14, nome: "Injúria", pena: 15, multa: 30000, fianca: 45000 },
            { artigo: 15, nome: "Difamação", pena: 15, multa: 30000, fianca: 45000 },
            { artigo: 16, nome: "Invasão de Propriedade", pena: 15, multa: 40000, fianca: 60000 },
            { artigo: 17, nome: "Perturbação do Sossego Alheio", pena: 10, multa: 30000, fianca: 45000 },
            { artigo: 18, nome: "Ameaça", pena: 50, multa: 100000, fianca: 150000 },
            { artigo: 19, nome: "Extorsão", pena: 40, multa: 50000, fianca: 75000 },
            { artigo: 20, nome: "Peculato", pena: 60, multa: 100000, fianca: 150000 },
            { artigo: 21, nome: "Falsidade Ideológica", pena: 30, multa: 90000, fianca: 135000 },
            { artigo: 22, nome: "Tráfico de Influência", pena: 10, multa: 30000, fianca: 45000 },
            { artigo: 23, nome: "Abuso de Autoridade", pena: 100, multa: 50000, fianca: 75000 },
            { artigo: 24, nome: "Falsa Comunicação de Crime", pena: 5, multa: 20000, fianca: 30000 },
            { artigo: 25, nome: "Tentativa de Suborno", pena: 25, multa: 50000, fianca: 75000 },
            { artigo: 26, nome: "Uso Indevido do Sistema de Emergência", pena: 20, multa: 50000, fianca: 75000 },
            { artigo: 27, nome: "Desacato", pena: 10, multa: 50000, fianca: 0 },
            { artigo: 28, nome: "Desobediência" , pena: 50, multa: 80000, fianca: 120000 },
            { artigo: 29, nome: "Obstrução da Justiça", pena: 20, multa: 50000, fianca: 75000 },
            { artigo: 30, nome: "Ocultação de Provas", pena: 15, multa: 50000, fianca: 75000 },
            { artigo: 31, nome: "Resistência a Prisão", pena: 20, multa: 50000, fianca: 75000 },
            { artigo: 32, nome: "Dano ao Patrimônio Público", pena: 25, multa: 100000, fianca: 150000 },
            { artigo: 33, nome: "Atentado ao Pudor", pena: 50, multa: 50000, fianca: 75000 },
            { artigo: 34, nome: "Associação Criminosa", pena: 30, multa: 65000, fianca: 97500 },
            { artigo: 35, nome: "Apologia ao Crime", pena: 5, multa: 20000, fianca: 30000 },
            { artigo: 36, nome: "Posse de Arma em Público", pena: 40, multa: 70000, fianca: 105500 },
            { artigo: 37, nome: "Ocultação Facial", pena: 1, multa: 15000, fianca: 0 },
            { artigo: 38, nome: "Uso de Equipamentos Restritos", pena: 10, multa: 50000, fianca: 75000 },
            { artigo: 39, nome: "Vadiagem", pena: 50, multa: 150000, fianca: 225000 },
            { artigo: 40, nome: "Vandalismo", pena: 20, multa: 50000, fianca: 75000 },
            { artigo: 41, nome: "Réu Reincidente", pena: 10, multa: 15000, fianca: 22500 },
            { artigo: 42, nome: "Cúmplice", pena: 5, multa: 15000, fianca: 22500 },
            { artigo: 43, nome: "Tráfico de Armas (3 ou mais)", pena: 60, multa: 300000, fianca: 450000 },
            { artigo: 44, nome: "Tráfico de Itens Ilegais", pena: 20, multa: 100000, fianca: 150000 },
            { artigo: 45, nome: "Tráfico de Munições (+ de 100)", pena: 60, multa: 100000, fianca: 150000 },
            { artigo: 46, nome: "Tráfico de Drogas (+ de 100)", pena: 50, multa: 100000, fianca: 150000 },
            { artigo: 47, nome: "Porte de Arma Pesada", pena: 45, multa: 200000, fianca: 300000 },
            { artigo: 48, nome: "Porte de Arma Leve", pena: 35, multa: 100000, fianca: 150000 },
            { artigo: 49, nome: "Porte de Arma Branca", pena: 1, multa: 30000, fianca: 0 },
            { artigo: 50, nome: "Posse de Peças de Armas", pena: 35, multa: 50000, fianca: 75000 },
            { artigo: 51, nome: "Posse de Cápsulas", pena: 35, multa: 50000, fianca: 75000 },
            { artigo: 52, nome: "Posse de Munição (- de 100)", pena: 40, multa: 50000, fianca: 75000 },
            { artigo: 53, nome: "Posse de Itens Ilegais", pena: 35, multa: 50000, fianca: 75000 },
            { artigo: 54, nome: "Aviãozinho (6 à 100)", pena: 35, multa: 70000, fianca: 105000 },
            { artigo: 55, nome: "Posse de Componentes Narcóticos", pena: 35, multa: 50000, fianca: 75000 },
            { artigo: 56, nome: "Posse de Drogas (1 a 5)", pena: 1, multa: 30000, fianca: 0 },
            { artigo: 57, nome: "Posse de Dinheiro Sujo", pena: 30, multa: 60000, fianca: 90000 },
            { artigo: 58, nome: "Desmanche de Veículos", pena: 25, multa: 50000, fianca: 75000 },
            { artigo: 59, nome: "Roubo", pena: 40, multa: 100000, fianca: 150000 },
            { artigo: 60, nome: "Furto a Caixa Eletrônico", pena: 35, multa: 50000, fianca: 75000 },
            { artigo: 61, nome: "Furto", pena: 35, multa: 50000, fianca: 75000 },
            { artigo: 62, nome: "Receptação de Veículos", pena: 35, multa: 50000, fianca: 75000 },
            { artigo: 63, nome: "Roubo de Veículos", pena: 40, multa: 100000, fianca: 150000 },
            { artigo: 64, nome: "Tentativa de Furto", pena: 10, multa: 20000, fianca: 30000 },
            { artigo: 65, nome: "Furto de Veículos", pena: 15, multa: 40000, fianca: 60000 },
            { artigo: 66, nome: "Condução Imprudente", pena: 15, multa: 50000, fianca: 75000 },
            { artigo: 67, nome: "Dirigir na Contra Mão", pena: 1, multa: 30000, fianca: 0 },
            { artigo: 68, nome: "Alta Velocidade", pena: 1, multa: 50000, fianca: 0 },
            { artigo: 69, nome: "Poluição Sonora", pena: 10, multa: 50000, fianca: 75000 },
            { artigo: 70, nome: "Corridas Ilegais", pena: 1, multa: 50000, fianca: 0 },
            { artigo: 71, nome: "Uso Excessivo de Insulfilm", pena: 1, multa: 25000, fianca: 0 },
            { artigo: 72, nome: "Direção sem Habilitação", pena: 1, multa: 25000, fianca: 0 },
            { artigo: 73, nome: "Estacionar em Área Proibida", pena: 1, multa: 25000, fianca: 0 },
            { artigo: 74, nome: "Não Ceder Passagem a Viaturas", pena: 1, multa: 25000, fianca: 0 },
            { artigo: 75, nome: "Impedir o Fluxo do Tráfego", pena: 1, multa: 50000, fianca: 0 },
            { artigo: 76, nome: "Veículo Muito Danificado", pena: 1, multa: 30000, fianca: 0 }
        ]


        function filtrarCrimes() {
    let input = document.getElementById("searchCrime").value.toLowerCase();
    let crimesLista = document.getElementsByClassName("crime");

    for (let crime of crimesLista) {
        let nomeCrime = crime.innerText.toLowerCase();
        if (nomeCrime.includes(input)) {
            crime.style.display = "block";
        } else {
            crime.style.display = "none";
        }
    }
}

        function copiarRelatorio() {
    let relatorio = document.getElementById("relatorioDados").value;
    let textoFormatado = `\
\
${relatorio}\n\
\
`;

    navigator.clipboard.writeText(textoFormatado).then(() => {
        alert("Relatório copiado com formatação!");
    }).catch(err => {
        console.error("Erro ao copiar:", err);
    });
}

function carregarCrimes() {
    let divCrimes = document.getElementById("crimes");
    divCrimes.innerHTML = crimes.map(crime => `
        <div class="crime">
            <input type="checkbox" id="crime${crime.artigo}" value="${crime.artigo}">
            <label for="crime${crime.artigo}">Art. ${crime.artigo} - ${crime.nome}</label>
        </div>
    `).join('');
}

function gerarRelatorio() {
    let nomeAdvogado = document.getElementById("advogadoNome").value || "Não informado";
    let rgAdvogado = document.getElementById("rgAdvogado").value || "Não informado";
    let nomeCliente = document.getElementById("cliente").value || "Não informado";
    let rgCliente = document.getElementById("RGcliente").value || "Não informado";
    let nomeOficial = document.getElementById("Nomeoficial").value || "Não informado";
    let rgOficial = document.getElementById("rgOficial").value || "Não informado";
    let rgAcompanhante = document.getElementById("rgAcompanhante").value || "Não informado";

    let porteArma = document.querySelector('input[name="Porte"]:checked');
    porteArma = porteArma ? porteArma.value : "Não informado";

    let fianca = document.querySelector('input[name="Fianca"]:checked');
    fianca = fianca ? fianca.value : "Não informado";

    let crimesSelecionados = [];
    document.querySelectorAll("#crimes input:checked").forEach(input => {
        const artigoSelecionado = parseInt(input.value);
        const crimeObj = crimes.find(crime => crime.artigo === artigoSelecionado);
        if (crimeObj) {
            crimesSelecionados.push(`📌 Art. ${crimeObj.artigo} - ${crimeObj.nome}`);
        }
    });
    let listaCrimes = crimesSelecionados.length ? crimesSelecionados.join("\n") : "Nenhum crime registrado";

    let atenuantes = [];
    if (document.getElementById("advogado").checked) atenuantes.push("📉 Advogado Constituído (-30%)");
    if (document.getElementById("reuPrimario").checked) atenuantes.push("📉 Réu Primário (-20%)");
    if (document.getElementById("reuConfesso").checked) atenuantes.push("📉 Réu Confesso (-20%)");
    if (document.getElementById("delacao10").checked) atenuantes.push("📉 Delação premiada (-10%)");
    if (document.getElementById("delacao15").checked) atenuantes.push("📉 Delação premiada (-15%)");
    let listaAtenuantes = atenuantes.length ? atenuantes.join("\n") : "Nenhuma atenuante aplicada";

    let relatorioTexto = `
\`\`\`
NOME: ${nomeCliente}
RG: ${rgCliente}
RG Acompanhante: ${rgAcompanhante}

📋 ARTIGOS INFRINGIDOS:
${listaCrimes}

⚖️ ATENUANTES APLICADAS:
${listaAtenuantes}

📋 PORTE DE ARMA: ${porteArma}
💰 FIANÇA: ${fianca}

👮‍♂️ NOME DO OFICIAL: ${nomeOficial} | RG: ${rgOficial}

📝 ADVOGADO: ${nomeAdvogado} | RG: ${rgAdvogado}
\`\`\`
`.trim();


    document.getElementById("relatorioDados").value = relatorioTexto;
}

function calcularPena() {
    const artigosInafiançaveis = [5, 7, 8, 11, 12, 27];

    let penaBase = crimes.filter(crime =>
        document.getElementById(`crime${crime.artigo}`).checked
    ).reduce((total, crime) => total + crime.pena, 0);

    let multaTotal = crimes.filter(crime =>
        document.getElementById(`crime${crime.artigo}`).checked
    ).reduce((total, crime) => total + crime.multa, 0);

    let possuiFianca = crimes.filter(crime =>
        document.getElementById(`crime${crime.artigo}`).checked
    ).some(crime => artigosInafiançaveis.includes(crime.artigo));

    let fiancaTotal = possuiFianca ? "Inafiançável" : `R$ ${(multaTotal * 1.5).toLocaleString()}`;

    let reducao = 0;
    if (document.getElementById("advogado").checked) reducao += 30;
    if (document.getElementById("reuPrimario").checked) reducao += 20;
    if (document.getElementById("reuConfesso").checked) reducao += 20;
    if (document.getElementById("delacao10").checked) reducao += 10;
    if (document.getElementById("delacao15").checked) reducao += 15;

    let penaFinal = penaBase * (1 - (reducao / 100));

    document.getElementById("resultado").value =
        `Pena Final: ${Math.max(0, penaFinal.toFixed(2))} Meses | Multa: R$ ${multaTotal.toLocaleString()} | Fiança: ${fiancaTotal}`;
}

document.addEventListener("DOMContentLoaded", carregarCrimes);

    </script>
    </body>

</html>
