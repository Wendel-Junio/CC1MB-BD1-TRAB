Banco de dados para um hopital.

1. O hospital possui várias alas.
2. Cada ala possui uma enfermeira responsável.
3. Cada enfermeira se reporta a uma enfermeira-chefe.
4. Enfermeiras podem atender apenas uma ala.
5. O hospital atende (credencia) os planos de saúde A, B e C.
6. Para cada plano de saúde, é necessário saber os médicos credenciados no mesmo.
7. Cada médico tem CRM e cada enfermeira CRE que lhes são únicos.
8. Todo atendimento de um médico a um paciente deve ser registrado com a data e hora em que o
mesmo ocorreu.
9. Um mesmo paciente pode ser atendido por mais de um médico.
10. Uma enfermeira-chefe pode atender a mais de uma enfermeira
11. O hospital tem CNPJ.
12. Cada ala do hospital tem um identificador exclusivo.
13. Todos os planos de saúde tem um nome e telefone da operadora.
14. Médicos tem nome e especialidade.
15. Enfermeiras têm nome.
16. O nome de um plano de saúde é único.
17. Cada paciente deve ter registrado seu nome, CPF/CNPJ e endereço.
18. O CPF é único para cada paciente.

Modelo Lógico:https://drive.google.com/open?id=1c5hcfnE9zsbgv89YB2sjy0VisSE5OZuD

Perguntas:
1- Quais médicos atendem aos planos A, B, C?
2- Que horas o paciente "A" foi atendido pelo médico "B"?
3- A que plano de saúde o paciente "C" está relacionado?
4- Qual enfermeira está responsável pela ala "A"?
5- A enfermeira "C" está relacionada a qual enfermeira-chefe?

Formas normais:
1º forma: Se trata em evitar atributos multivalorados e compostos. Sendo assim a tabela deve possuir apenas valores atômicos (indivisiveis) não tendo grupos repetidos de atributos, ser constituido por uma chave primária.
2º forma: A tabela vai estar na 2FN se cada um dos atributos não chave dessa tabela for total e funcionalmente dependente da chave primaria. Os atributos não dependentes da chave primária devem ser movidos para uma nova tabela.
3º forma: Um atributo não chave, não pode ser determinado por outro atributo não chave, quando ocorre deve-se criar novas entidades para o atributo não chave e o atributo que ele depende.

Modelo lógico na FN: https://drive.google.com/open?id=1dnz2P_Us0Lx0NDphjeilMOERjTJJpmRn

