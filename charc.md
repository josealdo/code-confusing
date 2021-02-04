<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
<html>
  <head>
      <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
      <meta name="generator" content="PhpSpreadsheet, https://github.com/PHPOffice/PhpSpreadsheet">
      <meta name="author" content="Rafael Mello" />
    <style type="text/css">
      html { font-family:Calibri, Arial, Helvetica, sans-serif; font-size:11pt; background-color:white }
      a.comment-indicator:hover + div.comment { background:#ffd; position:absolute; display:block; border:1px solid black; padding:0.5em }
      a.comment-indicator { background:red; display:inline-block; border:1px solid black; width:0.5em; height:0.5em }
      div.comment { display:none }
      table { border-collapse:collapse; page-break-after:always }
      .gridlines td { border:1px dotted black }
      .gridlines th { border:1px dotted black }
      .b { text-align:center }
      .e { text-align:center }
      .f { text-align:right }
      .inlineStr { text-align:left }
      .n { text-align:right }
      .s { text-align:left }
      td.style0 { vertical-align:bottom; border-bottom:none #000000; border-top:none #000000; border-left:none #000000; border-right:none #000000; color:#000000; font-family:'Calibri'; font-size:11pt; background-color:white }
      th.style0 { vertical-align:bottom; border-bottom:none #000000; border-top:none #000000; border-left:none #000000; border-right:none #000000; color:#000000; font-family:'Calibri'; font-size:11pt; background-color:white }
      td.style1 { vertical-align:middle; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:1px solid #000000 !important; color:#000000; font-family:'Calibri'; font-size:12pt; background-color:white }
      th.style1 { vertical-align:middle; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:1px solid #000000 !important; color:#000000; font-family:'Calibri'; font-size:12pt; background-color:white }
      td.style2 { vertical-align:bottom; border-bottom:none #000000; border-top:none #000000; border-left:none #000000; border-right:none #000000; color:#000000; font-family:'Calibri'; font-size:11pt; background-color:white }
      th.style2 { vertical-align:bottom; border-bottom:none #000000; border-top:none #000000; border-left:none #000000; border-right:none #000000; color:#000000; font-family:'Calibri'; font-size:11pt; background-color:white }
      td.style3 { vertical-align:bottom; text-align:left; padding-left:0px; border-bottom:none #000000; border-top:none #000000; border-left:none #000000; border-right:none #000000; font-weight:bold; color:#000000; font-family:'Calibri'; font-size:11pt; background-color:white }
      th.style3 { vertical-align:bottom; text-align:left; padding-left:0px; border-bottom:none #000000; border-top:none #000000; border-left:none #000000; border-right:none #000000; font-weight:bold; color:#000000; font-family:'Calibri'; font-size:11pt; background-color:white }
      td.style4 { vertical-align:middle; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:1px solid #000000 !important; color:#000000; font-family:'Calibri'; font-size:12pt; background-color:white }
      th.style4 { vertical-align:middle; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:1px solid #000000 !important; color:#000000; font-family:'Calibri'; font-size:12pt; background-color:white }
      td.style5 { vertical-align:middle; text-align:left; padding-left:0px; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:1px solid #000000 !important; color:#000000; font-family:'Calibri'; font-size:11pt; background-color:white }
      th.style5 { vertical-align:middle; text-align:left; padding-left:0px; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:1px solid #000000 !important; color:#000000; font-family:'Calibri'; font-size:11pt; background-color:white }
      td.style6 { vertical-align:bottom; border-bottom:none #000000; border-top:none #000000; border-left:none #000000; border-right:none #000000; color:#000000; font-family:'Calibri'; font-size:11pt; background-color:white }
      th.style6 { vertical-align:bottom; border-bottom:none #000000; border-top:none #000000; border-left:none #000000; border-right:none #000000; color:#000000; font-family:'Calibri'; font-size:11pt; background-color:white }
      td.style7 { vertical-align:bottom; text-align:left; padding-left:0px; border-bottom:none #000000; border-top:none #000000; border-left:none #000000; border-right:none #000000; color:#000000; font-family:'Calibri'; font-size:11pt; background-color:white }
      th.style7 { vertical-align:bottom; text-align:left; padding-left:0px; border-bottom:none #000000; border-top:none #000000; border-left:none #000000; border-right:none #000000; color:#000000; font-family:'Calibri'; font-size:11pt; background-color:white }
      td.style8 { vertical-align:middle; text-align:left; padding-left:0px; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:1px solid #000000 !important; font-weight:bold; color:#000000; font-family:'Calibri'; font-size:12pt; background-color:#FFFF00 }
      th.style8 { vertical-align:middle; text-align:left; padding-left:0px; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:1px solid #000000 !important; font-weight:bold; color:#000000; font-family:'Calibri'; font-size:12pt; background-color:#FFFF00 }
      td.style9 { vertical-align:middle; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:1px solid #000000 !important; font-weight:bold; color:#000000; font-family:'Calibri'; font-size:12pt; background-color:#FFFF00 }
      th.style9 { vertical-align:middle; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:1px solid #000000 !important; font-weight:bold; color:#000000; font-family:'Calibri'; font-size:12pt; background-color:#FFFF00 }
      td.style10 { vertical-align:bottom; text-align:center; border-bottom:none #000000; border-top:none #000000; border-left:none #000000; border-right:none #000000; color:#000000; font-family:'Calibri'; font-size:11pt; background-color:white }
      th.style10 { vertical-align:bottom; text-align:center; border-bottom:none #000000; border-top:none #000000; border-left:none #000000; border-right:none #000000; color:#000000; font-family:'Calibri'; font-size:11pt; background-color:white }
      td.style11 { vertical-align:middle; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:1px solid #000000 !important; color:#000000; font-family:'Calibri'; font-size:11pt; background-color:white }
      th.style11 { vertical-align:middle; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:1px solid #000000 !important; color:#000000; font-family:'Calibri'; font-size:11pt; background-color:white }
      td.style12 { vertical-align:middle; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:1px solid #000000 !important; font-weight:bold; color:#000000; font-family:'Calibri'; font-size:12pt; background-color:#FFFF00 }
      th.style12 { vertical-align:middle; text-align:center; border-bottom:1px solid #000000 !important; border-top:1px solid #000000 !important; border-left:1px solid #000000 !important; border-right:1px solid #000000 !important; font-weight:bold; color:#000000; font-family:'Calibri'; font-size:12pt; background-color:#FFFF00 }
      td.style13 { vertical-align:bottom; text-align:center; border-bottom:1px solid #000000 !important; border-top:none #000000; border-left:none #000000; border-right:none #000000; font-weight:bold; color:#000000; font-family:'Calibri'; font-size:16pt; background-color:white }
      th.style13 { vertical-align:bottom; text-align:center; border-bottom:1px solid #000000 !important; border-top:none #000000; border-left:none #000000; border-right:none #000000; font-weight:bold; color:#000000; font-family:'Calibri'; font-size:16pt; background-color:white }
      table.sheet0 col.col0 { width:51.51111052pt }
      table.sheet0 col.col1 { width:90.82222118pt }
      table.sheet0 col.col2 { width:223.6666641pt }
      table.sheet0 col.col3 { width:141.65555393pt }
      table.sheet0 col.col4 { width:72.52222139pt }
      table.sheet0 col.col5 { width:72.52222139pt }
      table.sheet0 col.col6 { width:72.52222139pt }
      table.sheet0 col.col7 { width:72.52222139pt }
      table.sheet0 col.col8 { width:72.52222139pt }
      table.sheet0 col.col9 { width:72.52222139pt }
      table.sheet0 col.col10 { width:41.34444397pt }
      table.sheet0 tr { height:15pt }
      table.sheet0 tr.row0 { height:21pt }
      table.sheet0 tr.row1 { height:66pt }
      table.sheet0 tr.row2 { height:31.5pt }
      table.sheet0 tr.row3 { height:63pt }
      table.sheet0 tr.row4 { height:31.5pt }
      table.sheet0 tr.row5 { height:45pt }
      table.sheet0 tr.row6 { height:60pt }
      table.sheet0 tr.row7 { height:47.25pt }
      table.sheet0 tr.row8 { height:31.5pt }
      table.sheet0 tr.row9 { height:38.1pt }
      table.sheet0 tr.row10 { height:45pt }
      table.sheet0 tr.row11 { height:135pt }
      table.sheet0 tr.row12 { height:31.5pt }
      table.sheet0 tr.row13 { height:30pt }
      table.sheet0 tr.row14 { height:45pt }
      table.sheet0 tr.row15 { height:45pt }
      table.sheet0 tr.row16 { height:45pt }
      table.sheet0 tr.row17 { height:78.75pt }
      table.sheet0 tr.row18 { height:45pt }
      table.sheet0 tr.row19 { height:15.75pt }
      table.sheet0 tr.row20 { height:45pt }
      table.sheet0 tr.row21 { height:15.75pt }
      table.sheet0 tr.row22 { height:45pt }
      table.sheet0 tr.row23 { height:60pt }
      table.sheet0 tr.row24 { height:90pt }
      table.sheet0 tr.row25 { height:31.5pt }
      table.sheet0 tr.row26 { height:15.75pt }
      table.sheet0 tr.row27 { height:31.5pt }
      table.sheet0 tr.row28 { height:135pt }
      table.sheet0 tr.row29 { height:15.75pt }
      table.sheet0 tr.row30 { height:75pt }
      table.sheet0 tr.row31 { height:75pt }
      table.sheet0 tr.row32 { height:31.5pt }
      table.sheet0 tr.row33 { height:45pt }
    </style>
  </head>

  <body>
<style>
@page { margin-left: 0.25in; margin-right: 0.25in; margin-top: 0.75in; margin-bottom: 0.75in; }
body { margin-left: 0.25in; margin-right: 0.25in; margin-top: 0.75in; margin-bottom: 0.75in; }
</style>
    <table border="0" cellpadding="0" cellspacing="0" id="sheet0" class="sheet0 gridlines">
        <col class="col0">
        <col class="col1">
        <col class="col2">
        <col class="col3">
        <col class="col4">
        <col class="col5">
        <col class="col6">
        <col class="col7">
        <col class="col8">
        <col class="col9">
        <col class="col10">
        <tbody>
          <tr class="row0">
            <td class="column0 style13 s style13" colspan="10">LTE- Characterization Data</td>
            <td class="column10">&nbsp;</td>
          </tr>
          <tr class="row1">
            <td class="column0 style8 s">Dev. ID</td>
            <td class="column1 style8 s">Highest Academic Degree</td>
            <td class="column2 style8 s">Brief description of the professional experience (in Portuguese)</td>
            <td class="column3 style9 s">Programming languages worked with</td>
            <td class="column4 style8 s">Self-perceived experience in software development</td>
            <td class="column5 style8 s">Self-perceived experience in code reviews</td>
            <td class="column6 style8 s">Software development experience (in years)</td>
            <td class="column7 style8 s">Number of projects developing software</td>
            <td class="column8 style8 s">Code review experience (in years)</td>
            <td class="column9 style8 s">Number of projects reviewing code</td>
            <td class="column10">&nbsp;</td>
          </tr>
          <tr class="row2">
            <td class="column0 style4 s">A</td>
            <td class="column1 style4 s">Master</td>
            <td class="column2 style5 s">Desenvolvedor Python Desktop, Java Web back-end, C# desktop.</td>
            <td class="column3 style1 s">C, C#, Java, Python, Javascript, Swift</td>
            <td class="column4 style4 s">High</td>
            <td class="column5 style4 s">Low</td>
            <td class="column6 style4 n">8</td>
            <td class="column7 style4 n">8</td>
            <td class="column8 style4 n">1</td>
            <td class="column9 style4 n">1</td>
            <td class="column10">&nbsp;</td>
          </tr>
          <tr class="row3">
            <td class="column0 style4 s">B</td>
            <td class="column1 style4 s">Master</td>
            <td class="column2 style5 s">Comecei a programar com 15 anos de idade em Pascal. Logo depois aprendi C e C++, entrei num curso de computação e hoje eu sou desenvolvedor profissionalmente há 8 anos.</td>
            <td class="column3 style1 s">Pascal, C, C++, Python, Ruby, OCaml, Rust, Lua, Scheme, Haskell, Java, C#, Swift, JS, etc.</td>
            <td class="column4 style4 s">Very High</td>
            <td class="column5 style4 s">Very High</td>
            <td class="column6 style4 n">12</td>
            <td class="column7 style4 n">8</td>
            <td class="column8 style4 n">8</td>
            <td class="column9 style4 n">3</td>
            <td class="column10">&nbsp;</td>
          </tr>
          <tr class="row4">
            <td class="column0 style4 s">C</td>
            <td class="column1 style4 s">Undergraduate</td>
            <td class="column2 style11 s">-</td>
            <td class="column3 style1 s">Java, C, C++, Python, R, Javascript, Julia, Assembly</td>
            <td class="column4 style4 s">High</td>
            <td class="column5 style4 s">Low</td>
            <td class="column6 style4 n">4</td>
            <td class="column7 style4 n">5</td>
            <td class="column8 style4 n">1</td>
            <td class="column9 style4 n">1</td>
            <td class="column10">&nbsp;</td>
          </tr>
          <tr class="row5">
            <td class="column0 style4 s">D</td>
            <td class="column1 style4 s">Master</td>
            <td class="column2 style5 s">Tenho cursado disciplinas de desenvolvimento de software na graduação e no mestrado. Tenho feito alguns sistemas simples como freelancer</td>
            <td class="column3 style1 s">Java, C, python</td>
            <td class="column4 style4 s">High</td>
            <td class="column5 style4 s">Low</td>
            <td class="column6 style4 n">2</td>
            <td class="column7 style4 n">3</td>
            <td class="column8 style4 n">0</td>
            <td class="column9 style4 n">0</td>
            <td class="column10">&nbsp;</td>
          </tr>
          <tr class="row6">
            <td class="column0 style4 s">E</td>
            <td class="column1 style4 s">Doctorate</td>
            <td class="column2 style5 s">Ao longo de quase 30 anos, sempre trabalhei com desenvolvimento de sistemas desempenhando diferentes funções e utilizando diferentes linguagens de programação.</td>
            <td class="column3 style1 s">C, C++, Pascoal, Basic, Mumps, Smalltalk, Lua, Java e Python</td>
            <td class="column4 style4 s">Very High</td>
            <td class="column5 style4 s">High</td>
            <td class="column6 style4 n">25</td>
            <td class="column7 style4 n">15</td>
            <td class="column8 style4 n">15</td>
            <td class="column9 style4 n">10</td>
            <td class="column10">&nbsp;</td>
          </tr>
          <tr class="row7">
            <td class="column0 style4 s">F</td>
            <td class="column1 style4 s">Undergraduate</td>
            <td class="column2 style5 s">27 anos de experiência com desenvolvimento de sistemas</td>
            <td class="column3 style1 s">Cobol, RPG, Easytrieve, Python, PHP, Cold Fusion, PL1, Pascal</td>
            <td class="column4 style4 s">Very High</td>
            <td class="column5 style4 s">High</td>
            <td class="column6 style4 n">27</td>
            <td class="column7 style4 n">50</td>
            <td class="column8 style4 n">15</td>
            <td class="column9 style4 n">30</td>
            <td class="column10">&nbsp;</td>
          </tr>
          <tr class="row8">
            <td class="column0 style4 s">G</td>
            <td class="column1 style4 s">Master</td>
            <td class="column2 style5 s">Experiência em backend, sistemas distribuídos e programação paralela</td>
            <td class="column3 style1 s">C/C++, C#, Lua, Erlang, Java, Python</td>
            <td class="column4 style4 s">Very High</td>
            <td class="column5 style4 s">High</td>
            <td class="column6 style4 n">10</td>
            <td class="column7 style4 n">50</td>
            <td class="column8 style4 n">5</td>
            <td class="column9 style4 n">20</td>
            <td class="column10">&nbsp;</td>
          </tr>
          <tr class="row9">
            <td class="column0 style4 s">H</td>
            <td class="column1 style4 s">Master</td>
            <td class="column2 style11 s">-</td>
            <td class="column3 style1 s">Java, Python, JavaScript, C#, C, C++</td>
            <td class="column4 style4 s">High</td>
            <td class="column5 style4 s">High</td>
            <td class="column6 style4 n">5</td>
            <td class="column7 style4 n">6</td>
            <td class="column8 style4 n">3</td>
            <td class="column9 style4 n">5</td>
            <td class="column10">&nbsp;</td>
          </tr>
          <tr class="row10">
            <td class="column0 style4 s">I</td>
            <td class="column1 style4 s">Master</td>
            <td class="column2 style5 s">Desenvolvo software desde antes de entrar na faculdade, vendi meu primeiro sistema no ensino médio.</td>
            <td class="column3 style1 s">Angular, Java, C/C++, Python, Delphi, Visual Basic, Ruby, ...</td>
            <td class="column4 style4 s">Very High</td>
            <td class="column5 style4 s">Very High</td>
            <td class="column6 style4 n">30</td>
            <td class="column7 style4 n">50</td>
            <td class="column8 style4 n">20</td>
            <td class="column9 style4 n">30</td>
            <td class="column10">&nbsp;</td>
          </tr>
          <tr class="row11">
            <td class="column0 style4 s">J</td>
            <td class="column1 style4 s">Undergraduate</td>
            <td class="column2 style5 s">tenho experiência em desenvolver aplicações web em que os front-end foram desenvolvidos em Angular+Material e Javascript e aplicações em que os back-end foram desenvolvidos utilizando Python+Flask, Java+Spring MVC+Spring Boot. Além , disso possuo experiência em criar modelos de machine learning para aplicar em diferentes domínios, tais como: visão computacional, PNL, Mercado financeiro.</td>
            <td class="column3 style1 s">Python, C, C++, Haskell, Prolog, Java, Julia, Angular, Javascript</td>
            <td class="column4 style4 s">High</td>
            <td class="column5 style4 s">None</td>
            <td class="column6 style4 n">6</td>
            <td class="column7 style4 n">7</td>
            <td class="column8 style4 n">0</td>
            <td class="column9 style4 n">0</td>
            <td class="column10">&nbsp;</td>
          </tr>
          <tr class="row12">
            <td class="column0 style4 s">K</td>
            <td class="column1 style4 s">Master</td>
            <td class="column2 style5 s">Muitos anos de carreira</td>
            <td class="column3 style1 s">C, C++, Java, JS, TypeScript, Lua, Dart, Python</td>
            <td class="column4 style4 s">Very High</td>
            <td class="column5 style4 s">Very High</td>
            <td class="column6 style4 n">26</td>
            <td class="column7 style4 n">50</td>
            <td class="column8 style4 n">20</td>
            <td class="column9 style4 n">40</td>
            <td class="column10">&nbsp;</td>
          </tr>
          <tr class="row13">
            <td class="column0 style4 s">L</td>
            <td class="column1 style4 s">Master</td>
            <td class="column2 style5 s">Trabalho mais com análise e especificação de requisitos e análise de ux e usabilidade.</td>
            <td class="column3 style1 s">C, Java, Java script, C#</td>
            <td class="column4 style4 s">Very Low</td>
            <td class="column5 style4 s">None</td>
            <td class="column6 style4 n">1</td>
            <td class="column7 style4 n">12</td>
            <td class="column8 style4 n">0</td>
            <td class="column9 style4 n">0</td>
            <td class="column10">&nbsp;</td>
          </tr>
          <tr class="row14">
            <td class="column0 style4 s">M</td>
            <td class="column1 style4 s">Undergraduate</td>
            <td class="column2 style5 s">4 anos e meio como desenvolvedora de sistemas em sistema web PHP. 2 meses como desenvolvedora de sistemas em Java.</td>
            <td class="column3 style1 s">PHP, Java, C#, React, Javascript.</td>
            <td class="column4 style4 s">High</td>
            <td class="column5 style4 s">Very Low</td>
            <td class="column6 style4 n">4</td>
            <td class="column7 style4 n">4</td>
            <td class="column8 style4 n">0</td>
            <td class="column9 style4 n">0</td>
            <td class="column10">&nbsp;</td>
          </tr>
          <tr class="row15">
            <td class="column0 style4 s">N</td>
            <td class="column1 style4 s">Master</td>
            <td class="column2 style5 s">Trabalhei em torno de 8 anos com analise e desenvolvimento de software em diversas linguagens de programação.</td>
            <td class="column3 style1 s">Java / Javascript / PHP / C# / C++ / C / Python / Lua</td>
            <td class="column4 style4 s">Very High</td>
            <td class="column5 style4 s">High</td>
            <td class="column6 style4 n">8</td>
            <td class="column7 style4 n">20</td>
            <td class="column8 style4 n">5</td>
            <td class="column9 style4 n">8</td>
            <td class="column10">&nbsp;</td>
          </tr>
          <tr class="row16">
            <td class="column0 style4 s">O</td>
            <td class="column1 style4 s">Undergraduate</td>
            <td class="column2 style5 s">Sou programador Java desde 2013, tive experiência em projetos acadêmicos e em aplicações mobile (Android).</td>
            <td class="column3 style1 s">C, Java, Python, R, PROLOG, JavaScript e SWIFT.</td>
            <td class="column4 style4 s">Very High</td>
            <td class="column5 style4 s">High</td>
            <td class="column6 style4 n">7</td>
            <td class="column7 style4 n">10</td>
            <td class="column8 style4 n">4</td>
            <td class="column9 style4 n">6</td>
            <td class="column10">&nbsp;</td>
          </tr>
          <tr class="row17">
            <td class="column0 style4 s">P</td>
            <td class="column1 style4 s">Master</td>
            <td class="column2 style5 s">Ao todo, tenho aproximadamente cinco anos de experiência. Isso inclui o desenvolvimento de três sistemas de porte médio para a indústria e incontáveis sistemas pequenos no contexto acadêmico.</td>
            <td class="column3 style1 s">Java (Web e Android), HTML, PHP, VB, VB.NET, C/C++, Java e Python, Perl, Assembly, AspectJ, AHEAD/FeatureHouse</td>
            <td class="column4 style4 s">Low</td>
            <td class="column5 style4 s">Very Low</td>
            <td class="column6 style4 n">5</td>
            <td class="column7 style4 n">9</td>
            <td class="column8 style4 n">1</td>
            <td class="column9 style4 n">0</td>
            <td class="column10">&nbsp;</td>
          </tr>
          <tr class="row18">
            <td class="column0 style4 s">Q</td>
            <td class="column1 style4 s">Master</td>
            <td class="column2 style5 s">comecei automatizando planilhas com visual Basic e no mestrado comecei a ter contato com python e Julia</td>
            <td class="column3 style1 s">VB, Python, Julia</td>
            <td class="column4 style4 s">Very Low</td>
            <td class="column5 style4 s">Very Low</td>
            <td class="column6 style4 n">0</td>
            <td class="column7 style4 n">0</td>
            <td class="column8 style4 n">0</td>
            <td class="column9 style4 n">0</td>
            <td class="column10">&nbsp;</td>
          </tr>
          <tr class="row19">
            <td class="column0 style4 s">R</td>
            <td class="column1 style4 s">Doctorate</td>
            <td class="column2 style5 s">10 anos (dev, teste, requisitos, Scrum master)</td>
            <td class="column3 style1 s">C, C++, Java, PHP, Python</td>
            <td class="column4 style4 s">High</td>
            <td class="column5 style4 s">Low</td>
            <td class="column6 style4 n">10</td>
            <td class="column7 style4 n">5</td>
            <td class="column8 style4 n">0</td>
            <td class="column9 style4 n">0</td>
            <td class="column10">&nbsp;</td>
          </tr>
          <tr class="row20">
            <td class="column0 style4 s">S</td>
            <td class="column1 style4 s">Master</td>
            <td class="column2 style5 s">8 anos de desenvolvimento com a linguagem Java em sistemas para web. 1 ano trabalhando com revisão de códigos em C e C++.</td>
            <td class="column3 style1 s">Java, C, Python, C++, Pascal, Delphi</td>
            <td class="column4 style4 s">High</td>
            <td class="column5 style4 s">High</td>
            <td class="column6 style4 n">9</td>
            <td class="column7 style4 n">20</td>
            <td class="column8 style4 n">1</td>
            <td class="column9 style4 n">5</td>
            <td class="column10">&nbsp;</td>
          </tr>
          <tr class="row21">
            <td class="column0 style4 s">T</td>
            <td class="column1 style4 s">Master</td>
            <td class="column2 style5 s">10 anos de experiência, aplicações Web e BPMs</td>
            <td class="column3 style1 s">Java</td>
            <td class="column4 style4 s">Very High</td>
            <td class="column5 style4 s">Low</td>
            <td class="column6 style4 n">10</td>
            <td class="column7 style4 n">8</td>
            <td class="column8 style4 n">2</td>
            <td class="column9 style4 n">1</td>
            <td class="column10">&nbsp;</td>
          </tr>
          <tr class="row22">
            <td class="column0 style4 s">U</td>
            <td class="column1 style4 s">Doctorate</td>
            <td class="column2 style5 s">Trabalho a mais de 15 anos na área de desenvolvimento de softwares e servidores FreeBSD</td>
            <td class="column3 style1 s">C, C++, Python, Java, JavaScript, Pascal, Pearl</td>
            <td class="column4 style4 s">High</td>
            <td class="column5 style4 s">Low</td>
            <td class="column6 style4 n">15</td>
            <td class="column7 style4 n">10</td>
            <td class="column8 style4 n">5</td>
            <td class="column9 style4 n">5</td>
            <td class="column10">&nbsp;</td>
          </tr>
          <tr class="row23">
            <td class="column0 style4 s">V</td>
            <td class="column1 style4 s">Master</td>
            <td class="column2 style5 s">Desenvolvimento de sistemas científicos aplicados à aea de petróleo. Linguagem de programação: Fortran, C++ e Python. Interface Grafica: API 32 Widows; Motif X-Windows; Qt.</td>
            <td class="column3 style1 s">Assemble ibm /370, assemble 8088; Fortran; C++ e Python.</td>
            <td class="column4 style4 s">High</td>
            <td class="column5 style4 s">Very High</td>
            <td class="column6 style4 n">40</td>
            <td class="column7 style4 n">20</td>
            <td class="column8 style4 n">10</td>
            <td class="column9 style4 n">5</td>
            <td class="column10">&nbsp;</td>
          </tr>
          <tr class="row24">
            <td class="column0 style4 s">W</td>
            <td class="column1 style4 s">Master</td>
            <td class="column2 style5 s">Desenvolvimento, teste e manutenção de sistema industrial na área de óleo e gás. Além de sistemas de natureza científica para apoio a obtenção de dados de repositório público (e.g: GitHub) e na construção de ferramentas de apoio a desenvolvedores.</td>
            <td class="column3 style1 s">Java, C, Python.</td>
            <td class="column4 style4 s">Low</td>
            <td class="column5 style4 s">High</td>
            <td class="column6 style4 n">6</td>
            <td class="column7 style4 n">3</td>
            <td class="column8 style4 n">2</td>
            <td class="column9 style4 n">1</td>
            <td class="column10">&nbsp;</td>
          </tr>
          <tr class="row25">
            <td class="column0 style4 s">X</td>
            <td class="column1 style4 s">Undergraduate</td>
            <td class="column2 style5 s">Sou recém formado na PUC, estagiei por 2 anos e meio como desenvolvedor</td>
            <td class="column3 style1 s">C, C++, Python, JavaScript, Java, Lua, Go</td>
            <td class="column4 style4 s">Low</td>
            <td class="column5 style4 s">Low</td>
            <td class="column6 style4 n">2</td>
            <td class="column7 style4 n">4</td>
            <td class="column8 style4 n">2</td>
            <td class="column9 style4 n">3</td>
            <td class="column10">&nbsp;</td>
          </tr>
          <tr class="row26">
            <td class="column0 style4 s">Y</td>
            <td class="column1 style4 s">Doctorate</td>
            <td class="column2 style5 s">4 anos de experiência</td>
            <td class="column3 style1 s">C, C+, lua, c#</td>
            <td class="column4 style4 s">High</td>
            <td class="column5 style4 s">Very High</td>
            <td class="column6 style4 n">4</td>
            <td class="column7 style4 n">4</td>
            <td class="column8 style4 n">4</td>
            <td class="column9 style4 n">4</td>
            <td class="column10">&nbsp;</td>
          </tr>
          <tr class="row27">
            <td class="column0 style4 s">Z</td>
            <td class="column1 style4 s">Master</td>
            <td class="column2 style5 s">Experiência na industria e academia.</td>
            <td class="column3 style1 s">Java, Python, C, C++, javascript</td>
            <td class="column4 style4 s">Very High</td>
            <td class="column5 style4 s">Very High</td>
            <td class="column6 style4 n">6</td>
            <td class="column7 style4 n">5</td>
            <td class="column8 style4 n">5</td>
            <td class="column9 style4 n">5</td>
            <td class="column10">&nbsp;</td>
          </tr>
          <tr class="row28">
            <td class="column0 style4 s">AA</td>
            <td class="column1 style4 s">Undergraduate</td>
            <td class="column2 style5 s">Estudei Engenharia Eletrônica. Já na universidade, cursei algumas disciplinas de programação como C, C++ e Pascal. Ainda durante a graduação, trabalhei com Java na iniciação científica e depois Java, aplicado a um contexto de desenvolvimento Android no estágio. Conheci também um pouco de Ruby por conta de outro estágio e hoje utilizo basicamente Python na minha pesquisa no mestrado.</td>
            <td class="column3 style1 s">C, C++, Ruby, Java e Python</td>
            <td class="column4 style4 s">High</td>
            <td class="column5 style4 s">Low</td>
            <td class="column6 style4 n">4</td>
            <td class="column7 style4 n">6</td>
            <td class="column8 style4 n">0</td>
            <td class="column9 style4 n">0</td>
            <td class="column10">&nbsp;</td>
          </tr>
          <tr class="row29">
            <td class="column0 style4 s">AB</td>
            <td class="column1 style4 s">Master</td>
            <td class="column2 style5 s">Desenvolvedor focado machine learning</td>
            <td class="column3 style1 s">Python</td>
            <td class="column4 style4 s">High</td>
            <td class="column5 style4 s">Low</td>
            <td class="column6 style4 n">4</td>
            <td class="column7 style4 n">10</td>
            <td class="column8 style4 n">0</td>
            <td class="column9 style4 n">0</td>
            <td class="column10">&nbsp;</td>
          </tr>
          <tr class="row30">
            <td class="column0 style4 s">AC</td>
            <td class="column1 style4 s">Undergraduate</td>
            <td class="column2 style5 s">Meu desenvolvimento de software se resume a scripts e pequenas ferramentas usadas especificamente para (1) facilitar meu trabalho na graduação/mestrado, e (2) como resultados da própria graduação/mestrado.</td>
            <td class="column3 style1 s">C, C++, Java, Python, JavaScript, Ruby, R, Haskell</td>
            <td class="column4 style4 s">High</td>
            <td class="column5 style4 s">High</td>
            <td class="column6 style4 n">1</td>
            <td class="column7 style4 n">2</td>
            <td class="column8 style4 n">1</td>
            <td class="column9 style4 n">2</td>
            <td class="column10">&nbsp;</td>
          </tr>
          <tr class="row31">
            <td class="column0 style4 s">AD</td>
            <td class="column1 style4 s">Master</td>
            <td class="column2 style5 s">Sou desenvolvedora a 8 anos, já trabalhei como backend, frontend em cerca de 40 projetos de domínios diferentes. Recentemente, também fui gerente de qualidade de processo de desenvolvimento de uma empresa.</td>
            <td class="column3 style1 s">Java, Python, C, C++, C#</td>
            <td class="column4 style4 s">High</td>
            <td class="column5 style4 s">Low</td>
            <td class="column6 style4 n">8</td>
            <td class="column7 style4 n">40</td>
            <td class="column8 style4 n">2</td>
            <td class="column9 style4 n">5</td>
            <td class="column10">&nbsp;</td>
          </tr>
          <tr class="row32">
            <td class="column0 style4 s">AE</td>
            <td class="column1 style4 s">Undergraduate</td>
            <td class="column2 style5 s">Desenvolvimento web com implementação de web scraping</td>
            <td class="column3 style1 s">Java, Python, Javascript, C/C++,</td>
            <td class="column4 style4 s">High</td>
            <td class="column5 style4 s">Low</td>
            <td class="column6 style4 n">1</td>
            <td class="column7 style4 n">2</td>
            <td class="column8 style4 n">0</td>
            <td class="column9 style4 n">0</td>
            <td class="column10">&nbsp;</td>
          </tr>
          <tr class="row33">
            <td class="column0 style4 s">AF</td>
            <td class="column1 style4 s">Master</td>
            <td class="column2 style5 s">1 ano como SCRUM Master (Junior). 1 ano como desenvolvedor android. 3 anos em projetos de pesquisa e desenvolvimento</td>
            <td class="column3 style1 s">Java, java para android, python, c++, c</td>
            <td class="column4 style4 s">High</td>
            <td class="column5 style4 s">High</td>
            <td class="column6 style4 n">5</td>
            <td class="column7 style4 n">6</td>
            <td class="column8 style4 n">2</td>
            <td class="column9 style4 n">3</td>
            <td class="column10">&nbsp;</td>
          </tr>
        </tbody>
    </table>
  </body>
</html>
