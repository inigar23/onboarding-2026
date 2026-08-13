\# Task 4 - Broken Web App

&#x20;  

&#x20;  Fixed two bugs in easy.html:

&#x20;  1. fetch() was using method: "GET" instead of "POST" (GET can't have a body)

&#x20;  2. Endpoint URL had a typo: "/api/submt" → "/api/submit"

&#x20;  

&#x20;  ## Verification

&#x20;  Run npm install \&\& npm start, open http://localhost:3000/easy.html,

&#x20;  fill the form, click Submit — should show "Submitted successfully!"

