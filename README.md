<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfólio de Dados | Bruno</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        :root {
            --primary: #003366;
            --secondary: #cc0000;
            --light: #f4f7f6;
            --dark: #333;
        }
        body { font-family: 'Segoe UI', sans-serif; margin: 0; background: var(--light); color: var(--dark); }
        
        /* Header */
        header { background: var(--primary); color: white; padding: 60px 20px; text-align: center; border-bottom: 5px solid var(--secondary); }
        header h1 { margin: 0; font-size: 2.5em; }
        header p { font-size: 1.2em; opacity: 0.9; }

        /* Container */
        .container { max-width: 1000px; margin: 40px auto; padding: 0 20px; }

        /* Grid de Projetos */
        .project-card { 
            background: white; 
            border-radius: 10px; 
            overflow: hidden; 
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            margin-bottom: 30px;
            display: flex;
            flex-wrap: wrap;
        }
        .project-img { flex: 1; min-width: 300px; background: #ddd; display: flex; align-items: center; justify-content: center; }
        .project-img img { width: 100%; height: auto; display: block; }
        
        .project-content { flex: 1.5; padding: 30px; min-width: 300px; }
        .project-content h2 { color: var(--primary); margin-top: 0; }
        .tags { margin: 15px 0; }
        .tag { background: #e1ecf4; color: #39739d; padding: 5px 12px; border-radius: 15px; font-size: 0.85em; font-weight: bold; margin-right: 5px; }

        /* Links */
        .btn { 
            display: inline-block; 
            background: var(--primary); 
            color: white; 
            text-decoration: none; 
            padding: 10px 20px; 
            border-radius: 5px; 
            transition: 0.3s;
        }
        .btn:hover { background: var(--secondary); }

        footer { text-align: center; padding: 40px; color: #777; }
    </style>
</head>
<body>

<header>
    <h1>Bruno | Analista de Dados</h1>
    <p>Especialista em Business Intelligence, SQL e Python</p>
</header>

<div class="container">
    <h2>📊 Projetos em Destaque</h2>

    <div class="project-card">
        <div class="project-img">
            <img src="screenshots/seu-grafico.png" alt="Análise Futebol">
        </div>
        <div class="project-content">
            <h2>Análise Financeira: Clubes de Futebol</h2>
            <p>Dashboard interativo analisando a relação entre ticket médio, capacidade de estádios e folha salarial dos principais clubes brasileiros.</p>
            <div class="tags">
                <span class="tag">Power BI</span>
                <span class="tag">DAX</span>
                <span class="tag">Análise Financeira</span>
            </div>
            <a href="https://github.com/SEU-USUARIO/SEU-REPOSITORIO" class="btn">Ver Repositório</a>
        </div>
    </div>

    </div>

<footer>
    <p>© 2026 Bruno - Desenvolvido com foco em Dados</p>
</footer>

</body>
</html>
