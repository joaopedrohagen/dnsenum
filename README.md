<h1 align="center">
  <br>
  <img src="ganymede.png" width="200">
  <br>
  Ganymede - DNS Enumerator
  <br>
</h1>

<h4 align="center"> A simple DNS Enumerator developed in Python </h4>

---

Ganymede is a simple Python script to enumerate subdomains of a given domain using a wordlist file. The script uses threads to perform requests asynchronously, which can speed up the enumeration process.

## How to use:
Run the script by providing the target domain and the path to the wordlist file as command-line arguments:

``` python3 dnsenum.py [domain] [wordlist] ``` 

Example:

``` python3 dnsenum.py example.com subdomains.txt ``` 

## Parameters:

* [domain] - The target domain you want to enumerate.
* [wordlist] - The path to the wordlist file containing the subdomains to test.

## Customization:
You can customize the script by adjusting the following parameters:

* max_workers: The maximum number of threads to use to perform requests asynchronously.

* headers: The HTTP headers used in requests. Update as needed.

## Attention
This script is provided for educational and security testing purposes only. Make sure you have permission to perform enumeration tests on any domain.

## Contributions
Feel free to contribute improvements or corrections. Create an issue or submit a pull request.
