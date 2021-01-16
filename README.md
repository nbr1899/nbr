<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Site 02</title>
    <link rel="stylesheet" href="cards-time.css">
    <link rel="stylesheet" href="css-africa.css">
    <link rel="stylesheet" href="css-asia.css">
    <link rel="stylesheet" href="css-america-central.css">
    <link rel="stylesheet" href="css-america-sul.css">
    <link rel="stylesheet" href="css-europa.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins&display=swap" rel="stylesheet">

</head>
<style>
    body{
        background-color: rgba(0, 0, 0, 0.966);
    }
    #section-intro{
        margin-top: 35px;
        margin-bottom: 30px;
        padding: 0px 50px 25px 50px;

    }
    #section-intro p{
        font-size: 24px;
        text-align: justify;
        color: rgb(255, 255, 255);
        text-shadow: 1px 3px 2px black;
        font-family: 'Poppins';
    }
    #nav-clubes{
        border-right: 1px solid black;
        width: 300px;
        min-width: 290px;
        position: fixed;
        top: 0%;
        left: 0%;
        overflow-y: auto;
        height: 100%;
    }
    nav a{
        text-decoration: none;
        color: rgba(255, 255, 255, 0.815);
    }
    .nav-link:hover{
        color: rgb(13, 189, 13);
    }
    nav header{
        display: block;
        font-size: 20px;
        padding-bottom: 2px;
    }
    .nav-link{
        list-style-type: none;
        margin: 0;
        padding: 0;
    }
    #title-clubes{
        text-align: center;
        color: rgb(13, 189, 13);
        font-family: 'Trebuchet MS', sans-serif;
        text-shadow: 1px 2px 1px black;
    }
    #main-conteudo{
        position: absolute;
        margin-left: 292px;
        top: 0%;
        padding: 0px 30px 0 15px;
        background: url(imagens/campo.png);
        background-size: cover;
        background-repeat: no-repeat;
    }

    #title-section{
        text-align: center;
        font-size: 55px;
        color:  rgb(13, 231, 13);
        font-family: 'Trebuchet MS';
        text-shadow: 5px 5px 2px black;
    }
    #title-intro{
        font-size: 45px;
        text-align: center;
        font-family: 'Trebuchet MS';
        color: rgb(13, 231, 13);
        text-shadow: 5px 5px 2px black;
    }
    #nav-list ul{
        display: block;
        padding: 0px;
        margin: 0;
        list-style-type: none;
        font-family: 'Poppins';
    }
    #nav-list li{
        padding: 10px;
        text-align: center;
        font-size: 22px;
        background-color: rgb(13, 189, 13);
        border-top: 2px solid ;
    }
    #nav-list a{
        display: block;
        padding: 15px 0px 15px 30px;
        border-top: 1px solid rgb(13, 189, 13);
        font-size: 20px;
        font-family: 'Poppins';
    }
</style>
<body>
    <nav id="nav-clubes">
            <header id="title">
                <h1 id="title-clubes"><a id="title-clubes" href="#title-intro">Clubes de Futebol</a></h1>
            </header>

            <div id="nav-list">
                <ul>
                    <li>África</li>
                            <a class="nav-link" href="#title-al-ahly">Al Ahly-EGY</a>
                            <a class="nav-link" href="#title-esperance">Esperance Tunis</a>
                            <a class="nav-link" href="#title-zamalek">Zamalek</a>
                            <a class="nav-link" href="#title-wydad">Wydad</a>
                            <a class="nav-link" href="#title-etoile">Etoile du Sahel</a>
                </ul>
            </div>

            <div id="nav-list">
                <ul>
                    <li>Ásia</li>
                        <a class="nav-link"  href="#title-jeonbuk">Jeonbuk</a>
                        <a class="nav-link"  href="#title-kashima">Kashima Antlers</a>
                        <a class="nav-link"  href="#title-guang">Guangzhou Evergrande</a>
                        <a class="nav-link"  href="#title-persepolis">Persepolis</a>
                        <a class="nav-link"  href="#title-al-hilal">Al-Hilal</a>
                </ul>
            </div>

            <div id="nav-list">
                <ul>
                    <li>América Central</li>
                        <a class="nav-link" href="#title-saprissa">Deportivo Saprissa</a>
                        <a class="nav-link" href="#title-herediano">Herediano</a>
                        <a class="nav-link" href="#title-club-america">Club América</a>
                        <a class="nav-link" href="#title-monterrey">Monterrey</a>
                        <a class="nav-link" href="#title-toluca">Deportivo Toluca</a>
                </ul>
            </div>

            <div id="nav-list">
                <ul>
                    <li>América do Sul</li>
                        <a class="nav-link" href="#title-boca">Boca Juniors</a>
                        <a class="nav-link" href="#title-river">River Plate</a>
                        <a class="nav-link" href="#title-vitoria">Vitória</a>
                        <a class="nav-link" href="#title-santos">Santos</a>
                        <a class="nav-link" href="#title-nacional">Nacional-URU</a>
                </ul>
            </div>

            <div id="nav-list">
                <ul>
                    <li>Europa</li>
                        <a class="nav-link" href="#title-manutd">Manchester United</a>
                        <a class="nav-link" href="#title-real-madrid">Real Madrid</a>
                        <a class="nav-link" href="#title-bayern">Bayern München</a>
                        <a class="nav-link" href="#title-chelsea">Chelsea</a>
                        <a class="nav-link" href="#title-dortmund">Borussia Dortmund</a>
                </ul>
            </div>
    </nav>
    <main id="main-conteudo">
        <section class="main-section" id="section-intro">
            <header>
                <h1 id="title-intro">INTRODUÇÃO</h1>
            </header>
            <article id="article-intro">
                <p>Neste site você irá encontrar informações sobre alguns clubes de cada continente. Listei os cinco clubes de cada continente que mais tenho afinidade. Espero que goste.</p>
                <p>As informações sobre os clubes foram retiradas do <strong>Wikipédia</strong>.</p>
            </article>
        </section>

        <section class="main-section" id="section-africa">
            <header>
                <h1 id="title-section">ÁFRICA</h1>
            </header>

            <section class="class-al-ahly">  
                <div id="section-al-ahly">
                    <article id="article-al-ahly">
                        <header>
                            <h2 id="title-al-ahly">Al Ahly-EGY</h2>
                        </header>
                        <div id="img-al-ahly">
                            <img class="img-al-ahly" src="imagens/logoclubes/al-ahly2.png" alt="Ahly-EGY" height="300px">
                        </div>
                            <p>
                                Al-Ahly Sporting Club (em árabe النادي الأهلي) é um clube de futebol da cidade do Cairo no Egito que disputa a Egyptian Premier League. Al-Ahly, que significa "nacional" em português, é o clube mais coroado no Egito, depois de ter ganho a Liga egípcia 42 vezes e a Taça egípcia 37 vezes. Al-Ahly foi nomeado em 2000 pela Confederação Africana de Futebol (CAF) como o "clube africano do século".
                            </p>
                            <p>
                                Al-Ahly tem uma disputa acirrada com o rival Zamalek que se manifesta no Al-Ahly versus Al Zamalek.
                            </p>
                            <p>
                                O Al-Ahly é um dos clubes mais populares do mundo. A FIFA estima entre 30 a 39 milhões de torcedores.
                            </p>
                    </article>
                </div>
            </section>

            <section id="section-esperance">
                    <article id="article-esperance">
                        <header>
                            <h2 id="title-esperance">Espérance Sportive</h2>
                        </header>
                        <div id="img-esperance">
                            <img src="imagens/logoclubes/esperance.png" alt="Esperance Sportive">
                        </div>
                            <p>Espérance Sportive de Tunis (em árabe: الترجي الرياضي التونسي‎) é um clube poliesportivo sediado em Tunis, Tunísia. O clube tem como principal desporto o futebol.
            
                            É um dos quatro clubes mais populares e bem-sucedidos da Tunísia. Foi fundado em 15 de Janeiro de 1919. O clube manda seus jogos no Estádio Olympique d'El Menzah.</p>
                            
                            <p>É o clube que mais disputou finais na Liga dos Campeões Árabes, foram 4 finais, nas quais conquistou o título em 1993 e 2009 e ficou com o vice em 1986 e 1995.</p>
            
                            <p>Venceu a Liga dos Campeões da África na temporada 2011, o que lhe deu o direito de disputar - pela primeira vez em sua história - o Campeonato Mundial de Clubes da FIFA de 2011 no qual ficou em 6º lugar.</p>
                    </article>
            </section>

            <section class="class-zamalek">
                <div class="main-section" id="section-zamalek">
                    <article id="article-zamalek">
                        <header>
                            <h2 id="title-zamalek">Zamalek</h2>
                        </header>
                        <div id=img-zamalek>
                            <img src="imagens/logoclubes/zamalek.png" alt="Zamalek">
                        </div>
                        <p>
                            Zamalek Sports Club (em árabe: نادي الزمالك للألعاب الرياضية) é um clube de futebol egípcio, sediado na cidade de Gizé, região metropolitana de Cairo, onde manda seus jogos
                        </p>
                        <p>
                            Fundado em 1911 como Qasr El-Neel Club, foi rebatizado para El-Mokhtalat Club dois anos depois e para King Farouk Club - em referência ao Rei Faruk em 1940 - até adotar o seu nome atual após a Revolução Egípcia de 1952.
                        </p>
                        <p>
                            É um dos maiores clubes do futebol local, tendo já conquistado 12 títulos nacionais, 26 da Copa do Egito e 2 da Supercopa Egípcia. Também é uma das mais bem-sucedidas equipes da África, somando 5 títulos da Liga dos Campeões da CAF, 4 da Supercopa Africana, 2 da Copa das Confederações da CAF e ainda duas conquistas da extinta Campeonato Afro-Asiático de Clubes.
                        </p>
                    </article>
                </div>
            </section>

            <section class="class-wydad">
                <div id="section-wydad">
                    <article id="article-wydad">
                        <header>
                            <h2 id="title-wydad">Wydad</h2>
                        </header>
                        <div id="img-wydad">
                            <img src="imagens/logoclubes/wydad.png" alt="Wydad" height="250px">
                        </div>
                        <p>
                            O Wydad Athletic Club, mais conhecido como Wydad Casablanca, é um dos principais clubes de Futebol de Marrocos.
                        </p>
                        <p>
                            Formado em 08 de maio de 1937, manda seus jogos no Estádio Mohammed V, com capacidade para 67.000 pessoas, o clube e o maior campeão do Marrocos,mcom 20 ligas e 9 copas, ainda possui 2 Liga dos Campeões da CAF, 1 Taça das Confederações da CAF, seu maior rival é o Raja Casablanca.
                        </p>
                    </article>
                </div>
            </section>

            <section class="class-etoile">
                <div id="section-etoile">
                    <article id="article-etoile">
                        <header>
                            <h2 id="title-etoile">Etoile du Sahel</h2>
                        </header>
                        <div id="img-etoile">
                            <img src="imagens/logoclubes/etoile.png" alt="Etoile du Sahel" height="220px">
                        </div>
                        <p>
                            Étoile Sportive du Sahel (árabe: النـجـم الرياضي الساحلي) é um clube de futebol tunisiano da cidade de Sousse, região do Sahel. A equipe foi fundada em 1925 e além do futebol, conta com times de handebol, voleibol, basquete, judô e luta olímpica.
                        </p>
                        <p>
                            É uma das equipes mais vitoriosas do futebol africano, tendo já conquistado 1 Liga dos Campeões da CAF, 2 Taça das Confederações da CAF, 1 Liga dos Campeões Árabes, 2 Copa da CAF, 2 Recopa Africana e 2 Supercopa da CAF, 10 Campeonatos Tunisianos , 10 Taças da Tunísia, 1 Taça da Liga.
                        </p>
                    </article>
                </div>
            </section>
        </section>

        <section class="main-section" id="section-asia">
            <header>
                <h1 id="title-section">ÁSIA</h1>
            </header>
        
            <section id="section-jeonbuk">
                    <article id="article-jeonbuk">
                        <header>
                            <h2 id="title-jeonbuk">Jeonbuk Hyundai</h2>
                        </header>
                        <div id="img-jeonbuk">
                            <img src="imagens/logoclubes/jeonbuk.png" alt="Jeonbuk Hyundai">
                        </div>
                        <p>
                            O Jeonbuk Hyundai Motors Football Club é um clube de futebol sul-coreano com sede na cidade de Jeonju e administrado pela empresa automobilística sul-coreana Hyundai. Joga na K-League.
                        </p>
                        <p>
                            Seu estádio foi uma das sedes da Copa do Mundo de 2002. No ano de 2006 conquistou a Liga dos Campeões da Ásia, em cima do Al-Karamah da Síria, e qualificado para disputar a Copa do Mundo de Clubes da FIFA representando o continente asiático em dezembro. Em 2016 conquistou seu segundo título da Liga dos Campeões da Ásia ao vencer o Al Ain dos Emirados Árabes Unidos.
                        </p>
                    </article>
            </section>

            <section class="class-kashima">
                <div id="section-kashima">
                    <article id="article-kashima">
                        <header>
                            <h2 id="title-kashima">Kashima Antlers</h2>
                        </header>
                        <div id="img-kashima">
                            <img src="imagens/logoclubes/kashima.png" alt="Kashima Antlers">
                        </div>
                        <p>
                            O Kashima Antlers F.C. (em japonês: 鹿島アントラーズ, transl. Kashima Antorāzu) é um clube de futebol japonês. A equipe participa da primeira divisão japonesa, e é o clube mais vezes campeão da J-League, tendo conquistado oito títulos.
                        </p>
                        <p>
                            Em 2016, tornou-se o primeiro time asiático a disputar uma final do Mundial de Clubes da FIFA, ao ganhar do Atlético Nacional, no jogo da semifinal, por 3 a 0. Na grande final disputada em Yokohama, o Kashima Antlers foi vice-campeão ao ser derrotado pelo Real Madrid por 4 a 2 na prorrogação.
                        </p>
                    </article>
                </div>
            </section>
            
            <section class="class-guang">
                <div id="section-guang">
                    <article id="article-guang">
                        <header>
                            <h2 id="title-guang">Guangzhou Evergrande</h2>
                        </header>
                        <div id="img-guang">
                            <img src="imagens/logoclubes/guang.png" alt="Guangzhou Evergrande">
                        </div>
                        <p>
                            Guangzhou Evergrande Taobao Futebol Clube (em chinês: 广州恒大淘宝足球俱乐部), é um clube de futebol da cidade de Guangzhou, província de Cantão na China. A equipe foi fundada em 1954, mas sofreu algumas alterações de nome até chegar ao atual, que se refere ao nome da cidade e a proprietária do time, a Evergrande Real Estate Group. Guangzhou Evergrande Football Club é campeão da CSL (Chinese Super League). A casa do Guangzhou é o Tianhe Stadium, localizado na cidade de Guangzhou.
                        </p>
                        <p>
                            Em 2015, o clube passou a ser dirigido pelo capitão da Itália na conquista da copa do mundo em 2006 e melhor jogador do mundo no mesmo ano Fabio Cannavaro.
    
                            Seis meses depois, o clube foi atrás de Luiz Felipe Scolari para o comando técnico. Após conquistar a Super Liga Chinesa de 2015, 2016 e 2017, além da Champions League da Ásia em 2015 e da Copa da China em 2016, o técnico brasileiro deixou a sua marca no clube. 
                        </p>
                        <p>
                            Em novembro de 2017, Fabio Cannavaro retornou ao clube para substituir Luiz Felipe Scolari.
                        </p>
                    </article>
                </div>
            </section>

            <section class="class-persepolis">
                <div id="section-persepolis">
                    <article id="article-persepolis">
                        <header>
                            <h2 id="title-persepolis">Persepolis</h2>
                        </header>
                        <div id="img-persepolis">
                            <img src="imagens/logoclubes/persepolis.png" alt="Persepolis">
                        </div>
                        <p>
                            O Persepolis Football Club (em farsi: باشگاه فوتبال پرسپولیس) é um clube de futebol do Irã, da cidade de Teerã. Suas cores são vermelho e branco.
    
                            Foi fundado em 1963 por Ali Abdo e está na primeira divisão iraniana desde 1968. O clube também possuía equipes de boliche, basquete e voleibol em seus primeiros anos.
                        </p>
                        <p>
                            É também conhecido como Piruzi, que, em persa, significa "vitória".
    
                            Seu maior rival é o Esteghlal Football Club, clube também de Teerã, com quem disputa o Sorkhabi Derby.
                        </p>
                    </article>
                </div>
            </section>

            <section class="class-al-hilal">
                <div id="section-al-hilal">
                    <article id="article-al-hilal">
                        <header>
                            <h2 id="title-al-hilal">Al Hilal</h2>
                        </header>
                        <div id="img-al-hilal">
                            <img src="imagens/logoclubes/al-hilal.png" alt="Al-Hilal">
                        </div>
                        <p>
                            Al Hilal Al Saudi Club, ou como simplesmente Al-Hilal (árabe: الهلال) é um clube de futebol masculino de Riyadh, Arábia Saudita.
                            É o clube de maior torcida do país, considerado como o "clube dos príncipes". O nome Al-Hilal significa "lua crescente".
                        </p>
                        <p>
                            No geral, ganhou 56 títulos oficiais no cenário nacional e internacional. Nas competições nacionais, ganharam 44 troféus: um recorde de 14 títulos da Liga Profissional, um recorde de 13 títulos da Copa da Coroa do Príncipe, um recorde de 7 títulos da Federação, 8 títulos da Copa do Rei.
                        </p>
                        <p>
                            A nível internacional, Al-Hilal tem um recorde de 6 troféus da Confederação de Futebol Asiático - a Liga dos Campeões da AFC, em 1991,2000 e 2019, além de 4 vices em 1986, 1987, 2014, 2017; foi também campeão da Recopa Asiática em 1997 e 2002, e da Supercopa da Ásia em 1997, 2000 e vice-campeão em 2002.
                        </p>
                    </article>
                </div>
            </section>
        </section>

        <section class="main-section" id="section-america-central">
            <header>
                <h2 id="title-section">AMÉRICA CENTRAL</h2>
            </header>

            <section class="class-saprissa">
                <div id="section-saprissa">
                    <article id="article-saprissa">
                        <header>
                            <h2 id="title-saprissa">Deportivo Saprissa</h2>
                        </header>
                        <div id="img-saprissa">
                            <img src="imagens/logoclubes/saprissa.png" alt="Deportivo Saprissa">
                        </div>
                        <p>
                            O Deportivo Saprissa é um dos maiores e mais tradicionais clubes costarriquenho de futebol. Pois junto com seus maiores rivais, o Herediano, Alajuelense, e Cartaginés são os chamados 'equipes grandes' do futebol da Costa Rica.
        
                            O Saprissa atualmente joga na Primera División nacional, onde é o maior campeão com 35 títulos conquistados.
                        </p>
                        <p>
                            Eles jogaram como representantes da CONCACAF na Copa do Mundo de Clubes da FIFA de 2005. Na sua estréia, contra o FC Sydney, da Austrália, o Saprissa venceu por 1 a 0, gol de Bolaños. Nas semi-finais do torneio, o adversário foi o Liverpool, da Inglaterra. Os ingleses dominaram o jogo e venceram por 3 a 0.
                        </p>
                        <p>
                            Com essa derrota, o time foi para a decisão de 3º lugar, contra o Al Ittihad, da Arábia Saudita. Neste jogo, os costarriquenhos venceram de virada por 3 a 2 com um gol de falta no final do jogo.
                        </p>
                    </article>
                </div>
            </section>

            <section id="section-herediano">
                <article id="article-herediano">
                    <header>
                        <h2 id="title-herediano">Herediano</h2>
                    </header>
                    <div id="img-herediano">
                        <img src="imagens/logoclubes/herediano.png" alt="Herediano">
                    </div>
                    <p>
                        O Club Sport Herediano é uma das maiores e mais tradicionais equipes de futebol da Costa Rica. Sua sede fica na cidade de Heredia, e junto com o Saprissa, Alajuelense, e Cartaginés são os chamados "equipes grandes" do futebol costarriquenho.
                    </p>
                    <p>
                        O Herediano é o terceiro maior campeão da primeira divisão nacional, com 25 conquistas, sendo a primeira equipe da Costa Rica a superar a quantidade de 20 títulos.
                    </p>
                </article>
            </section>

            <section id="section-club-america">
                <article id="article-club-america">
                    <header>
                        <h2 id="title-club-america">Club América</h2>
                    </header>
                    <div id="img-club-america">
                        <img src="imagens/logoclubes/americamex.png" alt="Club América">
                    </div>
                    <p>
                        O Club De Fútbol América, mais conhecido como América, Club América ou ainda América do México (em países de língua portuguesa) é um clube de futebol profissional mexicano. Fundado em 12 de outubro de 1916 na Cidade do México, disputa suas partidas como mandante no Estadio Azteca e suas cores tradicionais são o creme, o azul e alguns detalhes em vermelho.
                    </p>
                    <p>
                        O clube pertence à Televisa, gigante mexicana do setor de mídia. O América do México possui a terceira maior torcida do mundo com 26,4 milhões de torcedores, superando Boca Juniors, Juventus e Milan, segundo ranking divulgado pela FIFA em 2018.
                    </p>
                    <p>
                        Um dos clubes mais tradicionais do México, é um dos dois únicos (ao lado do Guadalajara) que participaram de todos as edições da Primeira Divisão mexicana. Com 13 conquistas, é o maior vencedor da liga mexicana. Soma também 5 Copas México e 5 Supercopas do México. Também é uma das equipes mexicanas mais bem sucedidas internacionalmente, tendo vencido 7 vezes a Copa dos Campeões da CONCACAF, 1 vez a Copa Gigantes da CONCACAF e 2 vezes a Copa Interamericana.
                    </p>
                </article>
            </section>

            <section class="class-monterrey">  
                <div id="section-monterrey">
                    <article id="article-monterrey">
                        <header>
                            <h2 id="title-monterrey">Monterrey</h2>
                        </header>
                        <div id="img-monterrey">
                            <img src="imagens/logoclubes/monterrey.png" alt="Monterrey">
                        </div>
                        <p>
                            O Club de Fútbol Monterrey é um clube mexicano de futebol de Monterrey, Nuevo León, no nordeste do país. Ele pertence a FEMSA, maior empresa Mexicana de bebidas. O time é popularmente conhecido como "Os Rajados" , foi fundado em 1945. Seu maior adversário é o UANL Tigres, com que disputa o chamado "Clássico Regiomontano". Suas cores são azul e branco.
                        </p>
                        <p>
                            Venceu a Liga dos Campeões da CONCACAF por três temporadas consecutivas 2010-11, 2011-12 e 2012-13 o que lhe deu o direito de disputar o Campeonato Mundial de Clubes da FIFA. Durante os três anos sua melhor campanha foi em 2012 no qual ficou em 3º lugar.
                        </p>
                    </article>
                </div>
            </section>

            <section class="class-toluca">
                <div id="section-toluca">
                    <article id="article-toluca">
                        <header>
                            <h2 id="title-toluca">Deportivo Toluca</h2>
                        </header>
                        <div id="img-toluca">
                            <img src="imagens/logoclubes/toluca.png" alt="Toluca">
                        </div>
                        <p>
                            Deportivo Toluca Futbol Club, ou simplesmente Toluca, é um clube profissional mexicano de futebol. Fundado em 12 de fevereiro de 1917, é uma das equipes mais antigas do México, embora tenha se profissionalizado apenas no início da década de 1950.
                        </p>
                        <p>
                            Ao longo de sua história, já conquistou em dez oportunidades o Campeonato Mexicano, sendo a terceira equipe mais bem sucedida nessa competição, atrás somente do Chivas e do América. Também conquistou em duas ocasiões a Copa dos Campeões da CONCACAF.
                        </p>
                        <p>
                            É o terceiro clube com mais participações na divisão principal do Campeonato Mexicano e, juntamente com o Jaguares, o Pumas, o Cruz Azul e o Santos Laguna, jamais foi rebaixado desde que conquistou o acesso.
                        </p>
                    </article>
                </div>
            </section>
        </section>
        
        <section class="main-section" id="section-america-sul">
            <header>
                <h1 id="title-section">AMÉRICA DO SUL</h1>
            </header>

            <section id="section-boca">
                <article id="article-boca">
                    <header>
                        <h2 id="title-boca">Boca Juniors</h2>
                    </header>
                    <div id="img-boca">
                        <img src="imagens/logoclubes/america-sul/boca.png" alt="Boca Juniors">
                    </div>
                    <p>
                        O Club Atlético Boca Juniors, conhecido simplesmente como Boca Juniors, é o segundo clube mais bem-sucedido no futebol argentino da cidade de Buenos Aires.
                    </p>
                    <p>
                        Seu nome provém do bairro de La Boca, e é um dos clubes com o maior número de conquistas relevantes, com destaque para seus 6 títulos da Copa Libertadores da América e para os seus 3 títulos da Copa Intercontinental e sendo ainda um dos clubes com mais conquistas internacionais, 18, ao lado do Milan e Independiente, atrás somente do Al-Ahly com 20 títulos e do Real Madrid com 26 títulos.
                    </p>
                    <p>
                        O Boca tem uma tradicionalíssima rivalidade com o Club Atlético River Plate, e os jogos entre as equipes, além de serem muito disputados, atraem a atenção de muitos fãs do futebol na Argentina e no resto do mundo. O clássico é conhecido como Boca x River ou "El Superclásico"
                    </p>
                </article>
            </section>

            <section id="section-river">
                <article id="article-river">
                    <header>
                        <h2 id="title-river">River Plate</h2>
                    </header>
                    <div id="img-river">
                        <img src="imagens/logoclubes/america-sul/river.png" alt="River Plate">
                    </div>
                    <p>
                        O Club Atlético River Plate, simplesmente conhecido como River Plate, é um clube de futebol da Argentina, fundado no dia 25 de maio de 1901. O River Plate faz com o Boca Juniors o maior clássico da Argentina, Boca versus River, também conhecido como El Superclásico.
                    </p>
                    <p>
                        Devido a compra do ponta-direita Carlos Desiderio Peucelle por 10 mil pesos, em 1932, o River ganhou a alcunha de Los Millonarios.
                    </p>
                    <p>
                       Em termos de título, o River Plate conquistou a Copa Intercontinental em 1986, a Copa Libertadores da América em 1986, 1996, 2015 e 2018 e venceu 36 vezes o Campeonato Argentino.
                    </p>
                </article>
            </section>
            
            <section id="section-vitoria">
                <article id="article-vitoria">
                    <header>
                        <h2 id="title-vitoria">Vitória</h2>
                    </header>
                    <div id="img-vitoria">
                        <img src="imagens/logoclubes/america-sul/vitoria.png" alt="Esporte Clube Vitória">
                    </div>
                    <p>
                        O Esporte Clube Vitória (conhecido como Vitória e cujo acrônimo é ECV) é um clube multiesportivo brasileiro, sediado na cidade de Salvador, no estado da Bahia. Foi fundado em 13 de maio de 1899 com o nome de Club de Cricket Victoria, mudado para Sport Club Victoria, em 1902, e, finalmente, para o atual nome em 1946. Sendo o clube mais velho do nordeste e um dos mais antigo do Brasil. Suas cores são o vermelho e o preto, seu mascote é o Leão.
                    </p>
                    <p>
                        Foi o primeiro clube social nacional ser fundado apenas por brasileiros (antes dele, a grande maioria tinha sido fundado por estrangeiros residentes no Brasil) e um dos primeiros clubes do Brasil a praticar o futebol, esporte no qual obtém maior destaque.
                    </p>
                    <p>
                        O clube rubro-negro conquistou cinco títulos da Copa do Nordeste, tornando-se pentacampeão e maior vencedor deste torneio regional. No total, o Vitória possui atualmente 29 títulos baianos, sendo o último deles conquistado na edição de 2017. Destacam-se também as campanhas do "Leão da Barra" nos Brasileirões de 1993 e 1999, competições em que terminou em 2° e 3° colocado, respectivamente, e nas edições da Copa do Brasil de 2004 e 2010, onde foi quarto colocado e vice-campeão, respectivamente, tornando-se o único clube do estado a avançar às semifinais e chegar à final deste torneio.
                    </p>
                    <p>
                        A divisão de base do clube é uma das mais bem sucedidas do mundo, mantendo-se, entre 1995 e 2000, no seu auge, pelo menos 21 títulos mundiais.
                    </p>
                </article>
            </section>

            <section id="section-santos">
                <article id="article-santos">
                    <header>
                        <h2 id="title-santos">Santos</h2>
                    </header>
                    <div id="img-santos">
                        <img src="imagens/logoclubes/america-sul/santos.png" alt="Santos">
                    </div>
                    <p>
                        O Santos Futebol Clube, popularmente conhecido como Santos, é um clube poliesportivo brasileiro da cidade de Santos, litoral do estado de São Paulo.
                    </p>
                    <p>
                        O Santos tornou-se no futebol um dos clubes mais bem-sucedidos do Brasil e reconhecidos mundialmente. Ficou famoso na década de 60 pelos vários títulos internacionais e nacionais conquistados e por ter revelado Pelé, considerado o melhor jogador do século pela FIFA e também o maior artilheiro da história do Santos e da Seleção Brasileira
                    </p>
                    <p>
                        Ao longo de sua história, o Santos conquistou um grande número de títulos internacionais, com destaque para os Mundiais de 1962 e 1963, as Copas Libertadores de 1962, 1963 e 2011 (recordista brasileiro ao lado de Grêmio e São Paulo), a Copa Conmebol de 1998, a Supercopa dos Campeões Intercontinentais de 1968, a Supercopa Sul-Americana de 1968 e a Recopa Sul-Americana de 2012. 
                    </p>
                    <p>
                        No cenário nacional é octacampeão brasileiro, somando cinco Taças Brasil conquistadas consecutivamente de 1961 a 1965, o Torneio Roberto Gomes Pedrosa de 1968 e os Campeonatos Brasileiros de 2002 e 2004. Ainda no âmbito nacional, o clube possui uma Copa do Brasil vencida em 2010, totalizando nove conquistas nacionais. 
                    </p>
                </article>
            </section>

            <section id="section-nacional">
                <article id="article-nacional">
                    <header>
                        <h2 id="title-nacional">Club Nacional</h2>
                    </header>
                    <div id="img-nacional">
                        <img src="imagens/logoclubes/america-sul/nacional-uru.png" alt="Club Nacional">
                    </div>
                    <p>
                        O Club Nacional de Football é um clube de futebol do Uruguai, fundado em 14 de maio de 1899, após a fusão, por iniciativa de jovens universitários da época, dos clubes Uruguay Athletic Club e Montevideo Football Club.
                    </p>
                    <p>
                        O clube pratica diversas modalidades esportivas, mas o futebol se destaca, no qual tem obtido importantes vitórias em nível nacional e internacional, ganhando assim um considerável reconhecimento em nível mundial. Foi três vezes campeão da Copa Libertadores da América, e nas três vezes que foi ao Mundial de Clubes, não perdeu nenhuma.
                    </p>
                    <p>
                        O Nacional faz com o seu rival tradicional, Peñarol, um dos maiores clássicos do futebol mundial. O time possuí a maior torcida de seu país, levando uma leve vantagem sobre seu rival Peñarol.
                    </p>
                </article>
            </section>
        </section>
        
        <section class="main-section" id="section-europa">
            <header>
                <h1 id="title-section">EUROPA</h1>
            </header>

            <section id="section-manutd">
                <article id="article-manutd">
                    <header>
                        <h2 id="title-manutd">Manchester United</h2>
                    </header>
                    <div id="img-manutd">
                        <img src="imagens/logoclubes/europa/manutd.png" alt="Manchester United">
                    </div>
                    <p>
                        O Manchester United Football Club é um clube inglês, sediado em Trafford, na região metropolitana de Manchester, sendo um dos times mais populares e mais bem sucedidos da Inglaterra e do mundo. O Manchester United é o clube de maior sucesso na Inglaterra, tendo ganho 38 títulos importantes desde que Sir Alex Ferguson tornou-se treinador em 6 de novembro de 1986
                    </p>
                    <p>
                        É conhecido como "Diabos Vermelhos", bem como por abreviações de seu nome, como Manchester Utd, Man United, Man Utd e United. Em muitos lugares, é referido como "o Manchester" ou apenas como o "UNITED" assim referido pela grande maioria dos fãs, devido grande projeção mundial de seu rival Manchester City.
                    </p>
                    <p>
                        Desde a década de 1990, o clube tem sido um dos mais ricos do mundo e com a maior receita entre todos os clubes de futebol, em fevereiro de 2012 foi classificado como o clube mais rico e valioso em qualquer esporte, com um valor estimado de € 490 milhões (R$ 1,1 bilhão).
                    </p>
                </article>
            </section>
            
            <section id="section-real-madrid">
                <article id="article-real-madrid">
                    <header>
                        <h2 id="title-real-madrid">Real Madrid</h2>
                    </header>
                    <div id="img-real-madrid">
                        <img src="imagens/logoclubes/europa/real-madrid.png" alt="Real Madrid">
                    </div>
                    <p>
                        O Real Madrid Club de Fútbol, mais conhecido como Real Madrid ou simplesmente Real, é um clube polidesportivo espanhol, com sede em Madrid. Foi fundado oficialmente no dia 6 de março de 1902 pelos irmãos Juan Padrós e Carlos Padrós.
                    </p>
                    <p>
                        Disputa suas partidas como mandante desde 1947 no Estádio Santiago Bernabéu, anteriormente chamado Novo Estádio de Chamartín, que conta com uma capacidade de 81.044 espectadores, o terceiro maior em capacidade da Europa.
                    </p>
                    <p>
                        É uma das entidades mais premiadas e reconhecidas do mundo, recebendo no futebol o título de melhor clube do Século XX pela FIFA, em dezembro de 2000 e o primeiro entre todos clubes espanhóis, e o título de melhor clube europeu do Século XX pela IFFHS, em maio de 2010.
                    </p>
                    <p>
                        Entre suas maiores conquistas, o clube detém de 34 títulos da La Liga (um recorde), 19 títulos da Copa del Rey, 11 títulos da Supercopa da Espanha, 1 título da Copa da Liga Espanhola, 1 título da Copa Eva Duarte. Em nível internacional o clube venceu 13 títulos europeus da Taça dos Clubes Campeões Europeus/Liga dos Campeões da UEFA sendo o maior campeão do torneio, 2 títulos da Liga Europa da UEFA, 4 títulos da Supercopa da UEFA, 3 títulos da Copa Intercontinental e 4 títulos da Copa do Mundo de Clubes da FIFA.
                    </p>
                </article>
            </section>

            <section id="section-bayern">
                <article id="article-bayern">
                    <header>
                        <h2 id="title-bayern">Bayern München</h2>
                    </header>
                    <div id="img-bayern">
                        <img src="imagens/logoclubes/europa/bayern.png" alt="Bayern München">
                    </div>
                    <p>
                        Futball-Club Bayern München, comumente referido como Bayern ou Bayern de Munique, é um clube alemão multidesportivo sediado na cidade de Munique, no estado da Baviera. O estado e a cidade, que em alemão, respectivamente, se denominam Bayern e München, dão nome ao time. O "FC Bayern" foi fundado em 1900.
                    </p>
                    <p>
                        No futebol, o Bayern já conquistou 30 títulos do Campeonato Alemão e 20 da Copa da Alemanha. Em nível internacional, o Bayern venceu 6 edições da Taça dos Clubes Campeões Europeus/Liga dos Campeões da UEFA, 1 da Liga da Europa da UEFA, 1 da Recopa Europeia e 1 da Supercopa Europeia, sendo um dos cinco únicos times a ganhar as três principais competições da Europa (Liga dos Campeões, Liga Europa, e a Recopa Europeia). Somam-se a sua galeria 2 Taças Intercontinentais e 1 Campeonato do Mundo de Clubes da FIFA.
                    </p>
                    <p>
                        Seu período de maior sucesso foi em meados da década de 1970, quando, sob a capitania de Franz Beckenbauer, ganhou por três vezes seguidas a Liga dos campeões da UEFA (entre 1974 e 1976). Aquele time é reconhecido até hoje como uma das maiores equipes de todos os tempos do futebol mundial. Em 2013, o clube conquistou uma tríplice coroa (venceu a Liga dos Campeões da UEFA, a Bundesliga e a Copa da Alemanha) e em 2020 conquistou novamente tornando-se o primeiro clube alemão e o sétimo da Europa a conquistar esse feito.
                    </p>
                </article>
            </section>

            <section id="section-chelsea">
                <article id="article-chelsea">
                    <header>
                        <h2 id="title-chelsea">Chelsea</h2>
                    </header>
                    <div id="img-chelsea">
                        <img src="imagens/logoclubes/europa/chelsea.png" alt="Chelsea">
                    </div>
                    <p>
                        O Chelsea Football Club é um dos maiores clubes do futebol inglês, sediado na cidade de Londres, fundado em 10 de março de 1905.
                    </p>
                    <p>
                        O clube conquistou a nível continental, a Liga dos Campeões da UEFA de 2011-12, a Liga Europa da UEFA de 2012-13 e 2018-19, a Recopa Europeia de 1970-71 e 1997-98 e a Supercopa da UEFA de 1998. A nível nacional, venceu seis vezes o Campeonato Inglês, oito vezes a Copa da Inglaterra, cinco vezes a Copa da Liga Inglesa, quatro vezes a Supercopa da Inglaterra e duas vezes a Copa dos Membros Ingleses.
                    </p>
                    <p>
                        O Chelsea joga os seus jogos em casa no estádio Stamford Bridge, com capacidade para 41.663 espectadores, e que fica localizado em Fulham Road. O clube não está localizado no bairro de Chelsea, mas sim no bairro vizinho de Fulham, próximo ao limite entre os bairros. O clube foi comprado em 2003 pelo magnata do petróleo russo Roman Abramovich.
                    </p>
                </article>
            </section>

            <section id="section-dortmund">
                <article id="article-dortmund">
                    <header>
                        <h2 id="title-dortmund"> Borussia Dortmund</h2>
                    </header>
                    <div id="img-dortmund">
                        <img src="imagens/logoclubes/europa/dortmund.png" alt="Borussia Dortmund">
                    </div>
                    <p>
                        O Ballspielverein Borussia 09 e. V. Dortmund, conhecido como Borussia Dortmund, BVB, ou simplesmente Dortmund, é um clube desportivo alemão sediado em Dortmund, Renânia do Norte-Vestefália. O Dortmund joga na Bundesliga, a primeira divisão do sistema do campeonato alemão de futebol. As cores do clube são pretas e amarelas, dando ao clube o apelido de Schwarzgelben.
                    </p>
                    <p>
                        O Borussia Dortmund venceu oito campeonatos alemães, sete DFB-Pokals, seis DFL-Supercups, uma Liga dos Campeões, uma Taça dos Clubes Vencedores de Taças e uma Copa Intercontinental. A conquista da Taça dos Clubes Vencedores de Taças em 1966 fez deles o primeiro clube alemão a conquistar um título europeu.
                    </p>
                    <p>
                        Desde 1974, o Dortmund tem jogado em seus jogos em casa no Westfalenstadion. O estádio é o maior da Alemanha e o Dortmund tem a maior média de público no mundo. O clube tem uma longa rivalidade com o vizinho do Ruhr, o Schalke 04, com quem disputa o clássico conhecido como Revierderby.
                    </p>
                </article>
            </section>
        </section>
    </main>
</body>
</html>
