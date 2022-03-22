<h1 align="center">Testes Unitários - Intersystems</h1>

Tabela de conteúdos
=================
<!--ts-->
   * [Sobre](#sobre)
   * [Instalação](#instalação)
   * [Como Usar](#como-usar)
      * [Pre Requisitos](#pre-requisitos)
      * [Executar Testes](#executar-testes)
   * [Tecnologias](#tecnologias)
   * [Features](#features)
<!--te-->

## Sobre
<p align="center">Desenvolvimento de um framework de testes que facilite o desenvolvimento de novos testes, e facilite a execução dos testes unitários</p>

## Instalação
<p>Importar o projeto TESTES-UNITARIOS.xml pelo Studio ou pelo portal de Administração do Cache/Ensemble/Iris</p>

## Como Usar

### Pre Requisitos
<p>As classes de testes desenvolvidas precisam estender a classe Desenvolvimento.utils.testesUnitarios</p>
<p>A nova classe de teste desenvolvida precisa do Parameter PACOTECOLECAOTESTES com o caminho dos testes que deverão ser executados. Conforme exemplo da classe Desenvolvimento.testesUnitarios.CalculadoraTest</p>
<p>O nome do método de teste precisa iniciar com a palavra Test</p>

### Executar Testes
<p>Executar o método ExecutarTestes da classe Desenvolvimento.testesUnitarios.CalculadoraTest</p>

## Tecnologias
<p align="center">
  <kbd>
    <img id="docslogo" src="https://docs.intersystems.com/irislatest/csp/docbook/doc-logo.svg" alt="Logotipo da empresa Intersystems, com tom azul predominante" height="71" width="263">
  </kbd>
</p>
https://docs.intersystems.com/

## Features
- [x] Execução de testes gerando arquivos em pastas temporárias
- [ ] Execução de testes sem gerar arquivos
- [ ] Framework de testes de integração

<h4 align="center"> 
	🚧  Projeto em construção...  🚧
</h4>
