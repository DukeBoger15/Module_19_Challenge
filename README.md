# Module_19_Challenge
This repository contains my FinTech Bootcamp Module 19 Challenge code.
<h1>Background</h1>
<li> I work at a startup that is building a new and disruptive platform called FinTech Finder. FinTech Finder is an application that its customers can use to find FinTech professionals from among a list of candidates, hire them, and pay them. As FinTech Finder's lead developer, I have been tasked with integrating the Ethereum blockchain network into the application in order to enable my customers to instantly pay the FinTech professionals whom they hire with cryptocurrency.</li>
<li>I will complete the code that enables my customers to send cryptocurrency payments to FinTech professionals. To develop the code and test it out, I will assume the perspective of a FinTech Finder customer who is using the application to find a FinTech professional and pay them for their work.</li>
<h1>What I am Creating</h1>
<li>To complete the challange, I will use 2 Python files. The first file contains the code associated with the web interface of the application. The code in this file is compatible with the Streamlit library. You will write all of code for the Challenge in this file.</li>
<li>The second file that will be used contains the Ethereum transaction functions that I have created throughout this module's lessons. By using import statements, I will integrate the crypto_wallet Python script into the FinTech Finder interface program that is found in the fintech_finder.py file.</li>
<li>Integrating these two files will allof me to automate the tasks associated with generating a digital wallet, accessing Ethereum account balances, and signing and sending transactions via a personal Ethereum blockchain called Ganache.</li>
<li>Specifically I will assume the perspective of a customer to do the following:</li>
<li>Generate a new Ethereum account instance by using the mnemonic seed phrase provided by Ganacge</li>
<li>Fetch and display the account balance associated with my Ethereum account address.</li>
<li>Calculate the total value of an Ethereum transaction, including the gas estimate, that pays a FinTech Finder candidate for their work.</li>
<li>Digitally sign a transaction that pays a FinTech Finder, and send this transaction to the Ganache blockchain.</li>
<li>Review the transaction hash code associated with the validated blockchain transaction</li>
<h2>Libraries & Programs Used</h2>
<li>Streamlit</li>
<li>Data Classes</li>
<li>Ganache</li>
