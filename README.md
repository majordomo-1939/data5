# data5
Transactions
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  
</head>
<body>
    <h1>Transaction Table</h1>
    <h2>Table Structure</h2>
    <ul>
        <li>Column1 - TransactionID</li>
        <li>Column2 - NewPrimaryKey</li>
       <li>Column3 - Deposits</li>
       <li>Column4 - Withdrawals</li>
       <li>Column5 - Transfers</li>
    </ul>
    <h2>Example Queries</h2>
    <pre>
    --Write SQL query to give transaction whose transfers are greater than and equal to 100
SELECT * FROM [dbo].[MergedTableTransactions]
WHERE TRANSFERS >=100
    </pre>
    <a href="../index.html">Back to main page</a>
</body>
</html>

