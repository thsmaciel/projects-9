[1.txt](https://github.com/user-attachments/files/15780384/1.txt)# projects-9
NoSQL

 -ETAPA 1

Um usuário configura seu navegador com os seguintes dados:

página inicial: www.google.com

Idioma preferido: Português do Brasil

Localização: São Paulo

Tema: Clássico

Mostrar favoritos: Sim

Zoom: 100%

Escreva os dados acima na notação JSON. Para esta atividade utilize o bloco de notas, salve o arquivo com o nome: localização_google_sp.json

-----------resolução-----------
[localização_google_sp.json](https://github.com/user-attachments/files/15780184/localizacao_google_sp.json)

 -ETAPA 2

Uma empresa deseja cadastrar seus funcionários. Ao verificar seus documentos, encontrou-se a seguinte planilha abaixo:
![image](https://github.com/thsmaciel/projects-9/assets/166454421/7bcfaf81-92fa-4160-a3ec-901fd9418c4e)

Crie, conforme o modelo relacional, as tabelas normalizadas. Crie também um documento JSON que contenha esses dados.

-----------resolução-----------

  --Normalização

Tabela: Funcionário
ID (PK)
Nome
Endereço
Cargo
Jornada
Salário

Tabela: Email
ID (PK)
FuncionarioID (FK)
Email

  --JSON
[Uploading{
  "Funcionarios": [
    {
      "ID": 1,
      "Nome": "João Grilo",
      "Endereco": "Rua Suassuna, 30, João Pessoa, PB",
      "Cargo": "Contador",
      "Jornada": 40,
      "Salario": "R$ 3000,00",
      "Emails": [
        "grilo@mail.com",
        "joaog@mk.com"
      ]
    },
    {
      "ID": 2,
      "Nome": "Ada Byron",
      "Endereco": "Rua Lovelace, 67, London",
      "Cargo": "Developer",
      "Jornada": 20,
      "Salario": "R$ 15000,00",
      "Emails": [
        "ada@mail.com",
        "abyron@tech.com"
      ]
    },
    {
      "ID": 3,
      "Nome": "Gerundino",
      "Endereco": "Rua Substantivo, 78, Bairro Predicado, Mesóclise-AC",
      "Cargo": "Linguista",
      "Jornada": 44,
      "Salario": "R$ 8000,00",
      "Emails": [
        "gerundino@gmail.com"
      ]
    },
    {
      "ID": 4,
      "Nome": "Chicó",
      "Endereco": "Rua Eurico, 50, João Pessoa, PB, Apt 28 Bloco C",
      "Cargo": "Developer",
      "Jornada": 20,
      "Salario": "R$ 15000,00",
      "Emails": []
    }
  ]
}
 1.txt…]()

   -- Modelo Relacional

   ![image](https://github.com/thsmaciel/projects-9/assets/166454421/f87e6662-e575-4ecc-b47f-8f80e89e5ca8)




  

