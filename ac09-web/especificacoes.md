# Aluno
Campos:
-nome: (varchar (50), not null)
-rg; (varchar(9), not null)
-cpf: (varchar(11) – int*-validador, not null)
-data nasc.: (varchar(10)– 1900/2100)
-endereço: (varchar (200), not null)
-número-endereço: (varchar (6), not null)
-uf:(varchar(2), not null)
-cep: (varchar (8), not null)
-disciplinas: (varchar (2), checkbox)
-matrícula: (varchar (10),not null )

# Professor 
Campos:
-nome: (varchar (50), not null)
-rg; (varchar(9), not null)
-cpf: (varchar(11) – int*-validador, not null)
-datanasc.: (varchar(10)– 1900/2100)
-endereço: (varchar (200), not null) 
-número_endereço: (varchar (6), not null)
-uf:(varchar(2), not null)
-cep: (varchar (8), not null)
-matérias lecionadas: (varchar(50), checkbox)
-matrícula: (varchar (10),not null )

# Disciplina
Campos:
-nome: (varchar(15), not null)
-coordenador: (varchar(50), not null)
-código: (varchar(10),not null)
-carga_horária: (int, not null)
-cursos: (varchar(200), checkbox)
-professor: (varchar(50), not null)
-substituto: (varchar(50) – se houver– default: N/C 
