# Random Joke Generator

This is a simple Python script that fetches and displays a random joke from an API. It runs in the command line and prints a joke each time it's executed.

## Features
- Fetches jokes from the [Official Joke API](https://official-joke-api.appspot.com/)
- Displays both the setup and punchline of the joke
- Includes a fallback joke in case of API failure
- Lightweight and requires only the `requests` module

## Installation
Make sure you have Python installed. Then, install the required package:
```sh
pip install requests
```

## Usage
Run the script using:
```sh
python joke_generator.py
```
Each time you run the script, it will print a random joke.

## Example Output
```
🃏🤣 Random Joke Generator 🤣🃏

Why did the chicken cross the road?

To get to the other side!
```

## Error Handling
If the API request fails, the script will return a default programmer joke:
```
Why did the programmer quit his job?

Because he didn't get arrays!
```

## License
This project is open-source and free to use.

