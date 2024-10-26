<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FAQ - Permitted Development</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            max-width: 600px;
            margin: auto;
            padding: 20px;
        }
        h1 {
            text-align: center;
            color: #333;
        }
        .faq-section {
            margin-top: 20px;
        }
        .faq-item {
            margin-bottom: 15px;
            border-bottom: 1px solid #ccc;
        }
        .question {
            font-weight: bold;
            cursor: pointer;
            color: #0056b3;
        }
        .answer {
            display: none;
            padding: 10px 0;
            color: #333;
        }
        .link {
            color: #0056b3;
            text-decoration: none;
        }
    </style>
</head>
<body>

    <h1>FAQ - Permitted Development</h1>

    <div class="faq-section">
        <div class="faq-item">
            <div class="question">What is Permitted Development?</div>
            <div class="answer">
                Permitted development allows certain home improvements, like small extensions or loft conversions, 
                without needing full planning permission. This depends on your project meeting specific size and 
                design rules.
            </div>
        </div>
        <div class="faq-item">
            <div class="question">How do I know if my project falls under Permitted Development?</div>
            <div class="answer">
                You can check if your project qualifies by reviewing the permitted development technical guidance or using 
                this chatbot to guide you through the process based on your project details.
            </div>
        </div>
        <div class="faq-item">
            <div class="question">Do Permitted Development rights apply everywhere?</div>
            <div class="answer">
                Permitted development rights are restricted in certain areas, like conservation areas or for listed 
                buildings. Always check with your local authority if you're unsure.
            </div>
        </div>
        <div class="faq-item">
            <div class="question">When do I need full planning permission?</div>
            <div class="answer">
                You’ll need planning permission for larger projects, like two-storey extensions or significant alterations 
                to the front of your home.
            </div>
        </div>
        <div class="faq-item">
            <div class="question">How do I find my local planning authority?</div>
            <div class="answer">
                You may find your Local Planning Authority through this link:
                <a href="https://www.gov.uk/find-local-council" target="_blank" class="link">Find Local Planning Authority</a>
            </div>
        </div>
    </div>

    <script>
        document.querySelectorAll('.question').forEach(item => {
            item.addEventListener('click', () => {
                const answer = item.nextElementSibling;
                answer.style.display = answer.style.display === 'block' ? 'none' : 'block';
            });
        });
    </script>

</body>
</html>
