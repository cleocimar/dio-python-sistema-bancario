# dio-python-sistema-bancario
simulação de um sisema bancário com as seguintes operações: saque, deposito e extrato

=============
1 - DEPÓSITO:
=============
a) Aceitar apenas valores postitivos e inteiros;
b) Podem ser feitos quantos depósitos forem necessários;
c) Os depósitos devem ser refletidos no extrato formatado com duas decimais
   e para identificar um dpósito, será utilizado o prefixo "C";
d) O sistema deve registrar a data e hora do depósito;

=========
2 - SAQUE
=========
a) Permitir apenas 03 (três) saques diários sendo que cada saque não deve
   ultrapassar R$ 500,00;
b) Emitir mensagem caso o usuário não possua saldo para o saques solicitado;
c) Os saques devem ser refletidos no extrato formatado com duas decimais
   e para identificar o saque, será utilizado o prefixo "D";
d) O sistema deve registrar a data e hora do saque;

===========
3 - EXTRATO
===========
a) O estrato deve refletir todos os depósitos e saques realizados com data
   e hora além dos valores serem formatados da seguinte forma R$ 9999999.00;
b) O sistema deve assumir o sitema monetário americado (ponto no lugar da vígula)
c) A separação de milhar deve ser omitida;
d) Colunas do extrato:
     i) Data no formato dd/mm/aaaa;
    ii) Hora no formato hh:mm:ss;
   iii) Descrição "DEPOSITO" ou "SAQUE";
    iv) Valor no formato 9999999.99 podendo suportar até um milhão de reais;
     v) Operação: 
        "D" identificando os SAQUES;
        "C" identificando os DEPÓSITOS;
     v) Ao final do extrato deve ser exibido a mensagem "SALDO ATUAL" seguido do
        do símbolo da moeda o valor do saldo atual da conta;
e) Deverá ser utilizado uma constante para simbolizar a moeda utilizada;

     
    



