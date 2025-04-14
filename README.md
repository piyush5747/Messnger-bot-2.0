##How To setup
search on google
google ai studio 
get apikey
app.py me jao > from google import genai

client = genai.Client(api_key="YOUR_API_KEY")

response = client.models.generate_content(
    model="gemini-2.0-flash",
    contents="Explain how AI works",
)

print(response.text)
isme apni api key daalo
same .env me
same gemini.py me 
now deploy on render

start command is

python app.py
