<!DOCTYPE html>
<html lang="pt-br">
   <head>
       <meta charset="utf-8">
       <title> Minha Page </title>
      <link rel="stylesheet" type="text/css" href="css/style.css">
   </head>
   
    <body>
        <nav>
                <p> Coisas </p>
            <ul>
                <li><a href="#Serviços">Serviços</a></li>
                <li><a href="#Contato">Contato</a></li>
                <li><a href="#Parcerios">Parcerios</a></li>
            </ul>
        </nav>
                <p>Pagina da Sofia </p>

       <header>
           <h2>MY NEW PAGE</h2>
           <p>Sofia Mara dos Reis</p>
       </header>
       <form action="processa.php" method="post">
             <label>Textt</label>
             <input type="text" name="Texto1" placeholders="Text">

             <br>

             <label>Senha</label>
             <input type="password" name="senhaa">

             <br>

             <label>Oculto</label>
             <input type="hidden" name="info_
             oculta" value="Mensagem_ocultaa">

             <br>

             <label>Select</label>
             <select>
                 <option value="1">Opção 01</option>
                 <option value="2">Opção 02</option>
             </select>

         <br>

            <label>Radio</label>
            <input type="radio" name="radio01" value="1">Valor01
            <input type="radio" name="radio01" value="2">Valor02

         <br>

            <label>Checkbox</label>
            <input type="checkbox" name="ck1" value="1" checked>Valor 1
            <input type="checkbox" name="ck1" value="2" >Valor 2
            <input type="checkbox" name="ck1" value="3" >Valor 3

         <br>

            <input type="submit">


        </form>

       <section id="Serviços">
        <H2> Serviços</H2>
        <p>Designer digital é um profissional que usa a criatividade e a técnica para desenvolver interfaces digitais interativas, atrativas e eficazes.

            Essa especialização da área de design visual é necessária para atender as necessidades geradas pelo surgimento (e rápida evolução) da mídia digital.
             O profissional dessa área concilia os conhecimentos da programação visual - 
             criatividade, senso estético, embasamento visual cultural, estudo da forma voltados aos variados tipos de suporte da mídia digital - 
             com a técnica destinada ao uso das ferramentas adequadas do meio de produção digital para criar soluções para mídia digital e interativa
            </p>
       </section>

       <section id="Contato">
        <H2>Contato </H2>
        <div>
          <a href="https://www.linkedin.com/in/sofia-mara-994978191/" target="_blank">
              <img src="img/sofi.jpeg.jpg" width="300p"> 
          </a>
          <p><a href="mailto:sofiamara09@gmail.com">sofiamara09@gmail.com </a></p>    
        </div> 

        <div> 
            <p><a href="Tel:1199999999">
               Telefone:1199999999
               </a>
            </p>
        </div>

        <div>
            <img src="img/gg.jpeg.jpg" width="300px">
        </div>
      </section> 

        <section id="Parcerios">
            <H2>Parcerioss</H2>
            <p>
                Nenhuma no momento ;-;
            </p>
     
        </section>

       <footer>
          <p>Desenvolvido por sofiaa</p>
       </footer>

    </body>
    
</html> 
