# Fi-Bot

<p> A ChatBot built using LLM (gemini) that work as financial advisor, it predict the stock market give financial advises, cover almost every sector of finance like banking, taxes, loans and even personal finance. it track user expenses and note it down on mongodb. On demand it provide monthly report to the user of their transaction and remaining budget. </p>

<h2> Working <h2>
    <ul>
        <li>This chatbot uses two fine tuned models trained using specific datasets.</li>
        <li>One predicts stock market trends & give financial advises and the other one track user expense & give reports.</li>
        <li>It uses NLP to identify the nature of the query and pass it to the best fit model.</li>
        <li>This bot uses MongoDB to store user's transaction systematically.</li>
        <li>Then uses the data to generate the report.</li>
    </ul>