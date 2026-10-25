# cloud-paas-lab
from flask import Flask

app = Flask(**name**)

@app.route("/")
def home():
return """ <h1>Cloud Computing Lab - PaaS</h1> <p>This application is deployed using a Platform as a Service.</p>
"""
