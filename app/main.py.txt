from flask import Flask

app=Flask(__name__)

@app.route("/")
def home_view():
	return "Welcome to Innovate Yourself"
