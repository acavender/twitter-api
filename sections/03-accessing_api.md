[<<< Previous](02-getting_key.md) | [Next >>>](04-creating_twitterbot.md )

# Accessing the API

1. Clone (or [download](https://github.com/smythp/twitter-workshop/archive/master.zip)) this repository to your computer and navigate to the folder once it's downloaded. You can clone the repository with this command in your terminal:

    ```
    git clone https://github.com/DHRI-Curriculum/twitter-api.git
    ```

    Once you've cloned or downloaded the directory, navigate into it using your command line.

2. Open the my_keys.py file in your text editor, VS Code.

3. Copy your four numbers (Consumer API key, Consumer API secret key, Access Token, and Access Token Secret), replacing the `xxx` on each relevant line. Make sure to keep the single quotes around the numbers.

4. Save the `my_keys.py` file.

5. Make sure you have the Tweepy library for Python installed. To check, type

    ```
    python
    ```

    at the command line. When you see the >>> prompt, type

    ```python
    import tweepy
    ```

    If you see no output, then Tweepy is already installed, so skip to Step #7. If you get an error, follow Step #6. Once you're finished with Python, type

    ```python
    exit()
    ```

    to return to the bash shell.  

6. If Tweepy isn't installed, run

    ```python
    pip install tweepy
    ```

    at the bash shell to install the library.  

7. To test out your key, run the api.py script:

    ```bash
    python api.py
    ```

    If you see the name of your Twitter account, everything is working!


[<<< Previous](02-getting_key.md) | [Next >>>](04-creating_twitterbot.md)
