USER_ID = 'ade qilua'
AUTH_KEY = 'your_999_key'

url = 'https://royaldomino.net/api/v1/user/info'

headers = {
    'Accept': 'application/json',
    'Authorization': 'Bearer ' + AUTH_KEY,
    'User-Agent': 'Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/58.0.3029.110 Safari/537.36 Edge/16.16299'
}

params = {
    'user_id': ade qilua 
}

response = requests.get(url, headers=headers, params=params)

print(response.text)
