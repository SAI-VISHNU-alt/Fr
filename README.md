📝 Task 3: GPT-4o – Image Description Using API

✅ What I’ve Done So Far

🔹 Objective:
Use the GPT-4o model to generate a description of an image by sending a request with the image in base64 format.

🔹 Tools Used:

Postman (for API testing)

GPT-4o Model endpoint


🔹 Steps Completed:

1. Converted a local PNG image to a base64 string using Python.


2. Created a valid JSON request body for GPT-4o:

Embedded the base64-encoded image using data:image/png;base64,...

Added a text prompt: “Describe this image.”



3. Sent the request through Postman using the correct OAuth2 credentials.


4. Successfully received and viewed a response from the GPT-4o model describing the image.




---

🧪 Example Output Received from Model:

> “This image appears to show a bar chart with sales data categorized by month…”



(Replace with your actual output)


---

🧭 What’s Next (To Be Done in Python)

I will now automate this entire workflow using Python:

1. Store credentials securely in a .env file


2. Use OAuth2 client credentials to programmatically fetch access token


3. Convert image to base64 and format it as a data URL


4. Send request to the GPT-4o endpoint from the script


5. Print or store the description received from the model




---

🎯 Goal:

Once done, this will eliminate manual steps and allow batch/image automation through code, which can later be integrated into a larger pipeline or UI.
