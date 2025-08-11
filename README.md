
// Classe mãe (Abstração)
class Funcionario {
constructor (nome) {
this.nome = nome;
}
executar Tarefa() {
console.log($(this.nome} está executando uma
tarefa no restaurante. );
}
// Classes filhas (Herança + Polimorfismo)
class Garcom extends Funcionario {
executar Tarefal) {
console.log(${this.rafaela}está servindo os
clientes. );
}
class Cozinheiro extends Funcionario {
executar Tarefa() 1
console.log(*$(this.Jose) está preparando os pratos. );
}
class Caixa extends Funcionario {
executar tarefas(retitando dinheiro){
console.log(*$(this.rafael) está contando notas. );
}
const equipe = [
new Garcom ("rafaela"),
new Cozinheiro (jose),
new Caixa ("rafael")
];
equipe.forEach(func=>func.executarTarefa());
