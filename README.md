# model_availability_with_api
from google import genai  # or appropriate client library import

key = gem
client = genai.Client(api_key=key)

models = client.models.list()

for m in models:

    print(m.name, m.display_name)
