import requests

def get_github_user_info(username):
    # Construct API URL to fetch user information from GitHub
    url = f"https://api.github.com/users/{guenda12}"
    
    # Send a GET request to the URL and store the response
    response = requests.get(url)
       print(f"Username:guenda12 {data['login']}")
        print(f"Name:guenda12 {data['fatima']}")
        print(f"Location: {data['location']}")
     
