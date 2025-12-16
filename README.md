# Linguagem de Programação I

### Wagner Petronio de Sousa Abreu
### Universidade Estadual do Ceará
### Curso Computação Licenciatura

Apresentação

  Nós respiramos código. O código está nas nossas veias. Tudo começou em meados nos anos 90, a gente começou a descobrir que existia Clipper, Foxbase, Basic. Antes de chegar
  aos anos 2000, ainda respirávamos Clipper queriamos fazer alteração no relatório só pelo Sidekick, e fomos apresentados às primeiras macros feitas com VBA. 
  Então conhecemos o Delphi 3... através de livros. Aaaaa, que saudade do Interbase, e das tabelas de banco com extensão .dbf que eram muito fáceis de ficar corrompido ! 

Nós esperamos aprender ao máximo desse curso, para que possamos estar capacitados para ensinar as próximas gerações de profissionais de Tecnologia.

# Série de Fibonacci

A série de Fibonacci é uma sequência de números em que cada número é a soma dos dois números anteriores, começando com 0 e 1.

A sequência é assim:

0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144, ...

A fórmula é:

F(n) = F(n-1) + F(n-2)

Onde F(n) é o n-ésimo número da sequência.

A série de Fibonacci tem muitas aplicações em matemática, ciência, arte e natureza, como:

- Proporção áurea (phi)
- Crescimento de populações
- Estrutura de árvores e galhos
- Design de arte e arquitetura

# Um exemplo de série de Fibonacci em Pascal

```
program Fibonacci;

function fib(n: integer): integer;
begin
  if (n = 0) or (n = 1) then
    fib := n
  else
    fib := fib(n-1) + fib(n-2);
end;

var
  n: integer;

begin
  writeln('Digite um número: ');
  readln(n);
  writeln('O ', n, '-ésimo número de Fibonacci é: ', fib(n));
end.
```
