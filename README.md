<!DOCTYPE html>
<html lang="en">
<head>
</head>
<body>
    <div class="container">
        <h1>Spam SMS Detection</h1>
        <p>The Spam SMS Detection project is a machine learning initiative focused on distinguishing between spam and non-spam (ham) messages. The project utilizes a logistic regression model trained on a set of messages, each labeled as either 'spam' or 'ham'. The model's performance is then evaluated based on its accuracy in categorizing new messages. The project employs a workflow of data preprocessing, training-testing data split, and prediction using the trained model. The model's prediction is then used to classify new messages as either 'spam' or 'ham'.</p>
        <p>We can divide the mail into two types:</p>
        <ul>
            <li><strong>Spam Mails:</strong> These are also known as unwanted emails, spam emails are designed to catch the recipient's attention or deceive them into action. Spam emails commonly include irrelevant, promotional, and often fraudulent content, such as offers for unknown products, shortened links, and all capped uppercase messages with the use of exclamation marks.</li>
            <li><strong>Ham Mails:</strong> These are also known as non-spam emails, ham emails typically contain information or messages that the recipient expects or finds useful. Examples of ham email content include personal messages, work-related information, subscription updates, and notifications.</li>
        </ul>
        <h2>Examples</h2>
        <div class="example">
            <p><strong>Example of SPAM Mail:</strong> Free entry in 2 a weekly comp to win FA Cup final tickets 21st May 2005. Text FA to 87121 to receive the entry question.</p>
        </div>
        <div class="example">
            <p><strong>Example of HAM Mail:</strong> Please go ahead with watts. I just wanted to be sure. Do have a great weekend.</p>
        </div>
        <h2>Workflow</h2>
        <ul>
            <li>Mail Data</li>
            <li>Data Preprocessing</li>
            <li>Train Test Split</li>
            <li>Logistic Regression Model</li>
            <li>New mail</li>
            <li>Trained LRM</li>
            <li>Spam or Ham Mail Prediction</li>
        </ul>

        <h2>Data Link</h2>
        <p><a href="https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset">https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset</a></p>
    </div>
</body>
</html>
