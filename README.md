# faculdade
Utilizando agora IDs, faça o gerenciamento das seguintes entidades:

Turno:
 nome
 inicio
 termino

Curso:
 nome
 horas_totais
 id_turno: relacionar com turno

Matéria:
 nome
 hora_totais
 id_curso: relacionar com curso
 
Aluno:
 nome
 id_curso: relacionar com curso

Professor:
 nome

Sala
 numero

Aula:
 id_professor: relacionar com professor
 id_materia: relacionar com matéria
 id_sala: relacionar com sala

Aluno_Aula:
 id_aula: relacionar com aula
 id_aluno: relacionar com aluno
