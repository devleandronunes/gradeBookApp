# Grade Book App (In English|Em Inglês)

## Overview
This project evaluates students' performance based on their individual scores and the class average. It provides details such as the class average score, the student's grade, and whether the student passed or failed the course.

## Features
- Calculate the class average score.
- Determine a student's grade based on their score.
- Check if a student passed the course.
- Provide a detailed message with the class average, the student's grade, and their passing status.

## Functions
### `getAverage(scores)`
Calculates the average score from an array of scores.
- **Input**: Array of numeric scores.
- **Output**: Average of the scores as a number.

### `getGrade(score)`
Determines the grade based on the provided score.
- **Input**: A single numeric score.
- **Output**: A grade as a string (e.g., `A++`, `A`, `B`, `C`, `D`, or `F`).

#### Grade Scale:
- `100`: A++
- `90-99`: A
- `80-89`: B
- `70-79`: C
- `60-69`: D
- Below `60`: F

### `hasPassingGrade(score)`
Checks if the score corresponds to a passing grade.
- **Input**: A single numeric score.
- **Output**: Boolean (`true` if passing, `false` otherwise).

### `studentMsg(totalScores, studentScore)`
Generates a detailed message for the student.
- **Input**:
  - `totalScores`: Array of all students' scores.
  - `studentScore`: The student's individual score.
- **Output**: A string message containing:
  - The class average.
  - The student's grade.
  - Whether the student passed or failed.

### Example Output
#### Input:
```javascript
studentMsg([92, 88, 12, 77, 57, 100, 67, 38, 97, 89], 37);
```
#### Output:
```
Class average: 71.4. Your grade: F. You failed the course.
```
#### Input:
```javascript
studentMsg([56, 23, 89, 42, 75, 11, 68, 34, 91, 19], 100);
```
#### Output:
```
Class average: 50.8. Your grade: A++. You passed the course.
```

## How to Use
1. Copy the script into a JavaScript environment (e.g., Node.js or browser console).
2. Call the `studentMsg` function with the required parameters:
   - An array of all students' scores.
   - The individual student's score.
3. Observe the returned message in the console.

### Example:
```javascript
const totalScores = [90, 85, 78, 88, 92];
const studentScore = 87;
console.log(studentMsg(totalScores, studentScore));
```

## License
This project is licensed under the MIT License.

----------------------------------------------------------------------------------------------------------------------------------------------------

# App Boletim de Notas (Em Português|In Portuguese)

## Visão Geral
Este projeto avalia o desempenho dos alunos com base em suas notas individuais e na média da turma. Ele fornece detalhes como a média da turma, a nota do aluno e se o aluno passou ou não no curso.

## Funcionalidades
- Calcular a média da turma.
- Determinar a nota de um aluno com base em sua pontuação.
- Verificar se um aluno foi aprovado no curso.
- Fornecer uma mensagem detalhada com a média da turma, a nota do aluno e seu status de aprovação.

## Funções
### `getAverage(scores)`
Calcula a média das notas a partir de um array de notas.
- **Entrada**: Array de notas numéricas.
- **Saída**: Média das notas como um número.

### `getGrade(score)`
Determina a nota com base na pontuação fornecida.
- **Entrada**: Uma única pontuação numérica.
- **Saída**: Uma nota como uma string (por exemplo, `A++`, `A`, `B`, `C`, `D` ou `F`).

#### Escala de Notas:
- `100`: A++
- `90-99`: A
- `80-89`: B
- `70-79`: C
- `60-69`: D
- Abaixo de `60`: F

### `hasPassingGrade(score)`
Verifica se a pontuação corresponde a uma nota de aprovação.
- **Entrada**: Uma única pontuação numérica.
- **Saída**: Booleano (`true` se aprovado, `false` caso contrário).

### `studentMsg(totalScores, studentScore)`
Gera uma mensagem detalhada para o aluno.
- **Entrada**:
  - `totalScores`: Array com as notas de todos os alunos.
  - `studentScore`: Nota individual do aluno.
- **Saída**: Uma mensagem em string contendo:
  - A média da turma.
  - A nota do aluno.
  - Se o aluno foi aprovado ou reprovado.

### Exemplo de Saída
#### Entrada:
```javascript
studentMsg([92, 88, 12, 77, 57, 100, 67, 38, 97, 89], 37);
```
#### Saída:
```
Média da turma: 71.4. Sua nota: F. Você foi reprovado no curso.
```
#### Entrada:
```javascript
studentMsg([56, 23, 89, 42, 75, 11, 68, 34, 91, 19], 100);
```
#### Saída:
```
Média da turma: 50.8. Sua nota: A++. Você foi aprovado no curso.
```

## Como Usar
1. Copie o script para um ambiente JavaScript (por exemplo, Node.js ou console do navegador).
2. Chame a função `studentMsg` com os parâmetros necessários:
   - Um array com as notas de todos os alunos.
   - A nota individual do aluno.
3. Observe a mensagem retornada no console.

### Exemplo:
```javascript
const totalScores = [90, 85, 78, 88, 92];
const studentScore = 87;
console.log(studentMsg(totalScores, studentScore));
```

## Licença
Este projeto está licenciado sob a Licença MIT.