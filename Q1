<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JSON Quiz</title>
</head>
<body>

<h1>JSON Quiz</h1>

<div id="quiz-container"></div>

<script>
    const quizData = [
        {
            question: "下面哪個是 JSON 的正確表示法？",
            answer: "B",
            options: {
                A: "{name: 'John', age: 25, city: 'New York'}",
                B: '{"name": "John", "age": 25, "city": "New York"}',
                C: "('name': 'John', 'age': 25, 'city': 'New York')",
                D: "[name: 'John', age: 25, city: 'New York']"
            }
        },
        {
            question: "如何表示一個包含陣列的 JSON 物件？",
            answer: "C",
            options: {
                A: '{"name": "Alice", "grades":  [90, 85, 92]}',
                B: '{"name": "Alice", "grades":  (90, 85, 92)}',
                C: '{"name": "Alice", "grades":  [90, 85, 92], "city": "Boston"}',
                D: '{"name": "Alice", "grades":  90, 85, 92}'
            }
        },
        {
            question: "在 JSON 中，如何表示布林值 true？",
            answer: "A",
            options: {
                A: "true",
                B: '"true"',
                C: "1",
                D: "'true'"
            }
        }
    ];

    const quizContainer = document.getElementById("quiz-container");

    quizData.forEach((quiz, index) => {
        const questionNumber = index + 1;
        const questionElement = document.createElement("div");
        questionElement.innerHTML = `
            <p>${questionNumber}. ${quiz.question}</p>
            <label>
                <input type="radio" name="question${questionNumber}" value="A"> ${quiz.options.A}
            </label>
            <label>
                <input type="radio" name="question${questionNumber}" value="B"> ${quiz.options.B}
            </label>
            <label>
                <input type="radio" name="question${questionNumber}" value="C"> ${quiz.options.C}
            </label>
            <label>
                <input type="radio" name="question${questionNumber}" value="D"> ${quiz.options.D}
            </label>
            <br>
        `;
        quizContainer.appendChild(questionElement);
    });

</script>

</body>
</html>
