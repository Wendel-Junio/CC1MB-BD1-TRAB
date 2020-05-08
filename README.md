Banco de dados para um hopital.

1.O hospital possui várias alas.
2. Cada ala possui uma enfermeira responsável.
3. Cada enfermeira se reporta a uma enfermeira-chefe.
4. Enfermeiras podem atender apenas uma ala.
5. O hospital atende (credencia) os planos de saúde A, B e C.
6. Para cada plano de saúde, é necessário saber os médicos credenciados no mesmo.
7. Cada médico tem CRM e cada enfermeira CRE que lhes são únicos.
8. Todo atendimento de um médico a um paciente deve ser registrado com a data e hora em que o
mesmo ocorreu.
9. Um mesmo paciente pode ser atendido por mais de um médico.
10. O hospital tem CNPJ.
11. Cada ala do hospital tem um identificador exclusivo.
12. Todos os planos de saúde tem um nome e telefone da operadora.
13. Médicos tem nome e especialidade.
14. Enfermeiras têm nome.
15. O nome de um plano de saúde é único.
16. Cada paciente deve ter registrado seu nome, CPF/CNPJ e endereço.
17. O CPF é único para cada paciente.

Formas normais:
1º forma: Se trata em evitar atributos multivalorados e compostos. Sendo assim a tabela deve possuir apenas valores atômicos (indivisiveis) não tendo grupos repetidos de atributos, ser constituido por uma chave primária.
2º forma: A tabela vai estar na 2FN se cada um dos atributos não chave dessa tabela for total e funcionalmente dependente da chave primaria. Os atributos não dependentes da chave primária devem ser movidos para uma nova tabela.
3º forma: Um atributo não chave, não pode ser determinado por outro atributo não chave, quando ocorre deve-se criar novas entidades para o atributo não chave e o atributo que ele depende.


