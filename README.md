![logo](/extras/logo.png)

Active reconaissance, information gathering and OSINT built in a portable web application

---

* All credit goes to ex0dus-0x

---


### CHANGELOG

01/22/19

* Reinovating D0x-K1t

#### TODO:

* Add more features / websites

---

## 1.0 Introduction

1. __What is this?__

D0x-K1t-v2 is an __open-source__, __self-hosted__ and __easy to use__ OSINT and active reconaissance web application for penetration testers. Based off of the prior command-line script, D0x-K1t-v2 is now fully capable of conducting reconaissance and penetration testing for security researchers who need a framework without the 
head-scratching.

2. __Is this a website / webapp ?__

Yes and no. In essence, it is not a typical website. D0x-K1t-v2 is self-hosted. There is no server stack, cloud-based service, SaaS, etc. that is holding it up. You can have the option of deploying D0x-K1t-v2 on a local network, or deploying
your own instance on any infrastructure / technology as you wish (although not recommended).

3. __Is this free ?__

Yes. D0x-K1t-v2 will forever be open-source. If you wish to contribute, you can make a fork, add any changes, and send a pull request on Github.

4. __How else can I develop on this?__

I have created API endpoints, and more will be coming soon.

---

## 2.0 Features

* Easy-to-build, risk-free installation
* Simple Bootstrap Admin Dashboard
* Deployable to the Internet
* Serverless (at the moment)
* Expansive to any OS

---

## 3.0 Installation 

Since D0x-K1t-v2 is self-hosted, it does not work immediately out-of-box. It is recommended that you use a `virtualenv` container due to the sheer number of dependencies that can run into conflict with your Python configuration.

### 3.1 Building

__Manual Way:__

    $ git clone https://github.com/roo7k1d/D0x-K1t-v2 && cd D0x-K1t-v2
    $ # Start virtualenv if you wish
    $ pip install -r requirements.txt
    $ python run.py
    

### 3.2 Deployment

Once installed, run with `python run.py`. The application will run a first-time boot, and will then be accessible at `127.0.0.1:5000`. 

Of course, this is self-hosting on localhost. Although work-in-progress, D0x-K1t-v2 will soon support hosting on a variety of SaaS and server stacks of your choice.

* [Heroku](https://www.heroku.com/) - __TODO__: build a `Procfile`, as well as bash scripts for automatic deployment
* [ngrok](https://ngrok.com/) - __TODO__: build a script for deployment to ngrok

---

## 4.0 Modules

#### D0x Module

The D0x module is a comprehensive info-gathering database that enables the pentester to write "D0x", or a file that holds a collection of data of a certain target, or targets.
Using this data, the tester will be able to effectively understand their target, which is a critical point in the attacker's kill chain. D0xing is usually deemed malicious and black-hat in nature. However, with the D0x module, we aim to help security researchers gain momentum when conducting in-the-field pentesting. 

The D0x module does come with several features, improved upon based off of the prior revision. 

---

## 5.0 How to Contribute

Contributing is easy! Send a pull request if you feel that anything should be changed, removed, optimized, etc. Issues are also great for reporting bugs. 

# License

D0x-K1t-v2 is distributed under a [MIT  License](https://choosealicense.com/licenses/mit/).
