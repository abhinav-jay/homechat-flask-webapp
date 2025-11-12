# homechat-flask-webapp

## Usage
To use this application, you will first have to run the `app.py` file to initialize the SQL database tables and everything.
```bash
python app.py
```
To run this chat application locally, you can just run
```bash
flask --app app run
```
To run this globally you will have to specify the `--host=0.0.0.0` flag at the end like this:
```bash
flask --app app run --host=0.0.0.0
```
This should run the application on `aaa.aaa.aaa.aaa:5000` with `aaa.aaa.aaa.aaa` being the IP address of the server.

## Notes
You can edit the styles of the application which are located at `static/style.css` if you want.
The html files for the chat, the login page and the register page are located at `templates/`, `index.html` is the html file for the chat.
You can use this app to make a small chat application for your family if you don't want to use proprietary software or leave these informations on some other server. You can run this on your own computer without anyone else seeing your conversations.

> [!NOTE]
> A webchat application without authentication has been [made](https://github.com/abhinav-jay/homechat_flask_webapp_without_authentication), it is recommended to use that rather than to remove every login thing by yourself.
