# PHP Vulnerability test suite

Collection of vulnerable and fixed PHP synthetic test cases expressing specific flaws.

## Vulnerability categories description

* IDOR : Insecure Direct Object Reference
* * CWE 862 : Missing Authorization

* Injection : Injection (SQL, LDAP, XPATH, OS Command, Code)
* * CWE 78 : OS Command Injection
* * CWE 89 : SQL Injection
* * CWE 90 : LDAP Injection
* * CWE 91 : XML Injection
* * CWE 95 : File Injection
* * CWE 98 : PHP Remote File Inclusion

* SDE : Sensitive Data Exposure
* * CWE 311 : Missing Encryption of Sensitive Data
* * CWE 327 : Use of a Broken or Risky Cryptographic Algorithm

* SM : Security Misconfiguration
* * CWE 209 : Information Exposure Through an Error Message

* URF : URL Redirects and Forwards
* * CWE 601 : URL Redirection to Untrusted Site

* XSS  : Cross-site Scripting
* * CWE 79 : Cross-site Scripting

## Generation report

The test suite contains: 
Vulnerability | Safe samples | Unsafe samples | Total samples 
--- | --- | --- | ---
IDOR | 400 | 80 |  **480**
Injection | 20912 | 5920 | **26832**
SDE | 5 | 7 | **12**
SM | 5 | 3 | **8**
URF | 2208 | 2592 | **4800**
XSS | 5728 | 4352 | **10080**
Total | **29258** | **12954** | **42212**  

## Directory tree
```
Vulnerability categories
└── CWE numbers
    ├── Safe samples
    │   └── PHP test cases
    └── Unsafe samples
        └── PHP test cases
```

## Discussion

For discussion please send me an email at: Bertrand 'dot' STIVALET 'at' gmail.com

