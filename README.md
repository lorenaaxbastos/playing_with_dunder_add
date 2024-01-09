# Playing with *dunder* add in Python

This a repo for exploring encapsulation and dunder method uses in custom classes. 

## What are *dunder* methods?

First, let me tell you what they are not: *dunder* methods are NOT the different ways Michael from Dunder Mifflin sells paper.
Sigh, me and my weird sense of humour. 

Jokes aside... In Python, dunder methods are methods that allow instances of a class to interact with the built-in functions and operators of the language. You can chek out the full explanation [here](https://mathspp.com/blog/pydonts/dunder-methods).

## Goal

For this project, the main goal was to enable merging different bank accounts using the sum arithmetic operator. E.g.: `account_1 + account_2.`.

If the merge is successful, the first account should have its balance and account types updated and the second account should be deactivated. To be merged, both accounts should be active and belong to the same client. Either way, the user gets a feedbak message informing the status of the merge.

When printing the account, it should show the name of the client and the balance for each account type. If the account is inactive, it should print a message informing the user about it.

## Contributing

Pull requests are welcome! If you want you can also upload different applications for other dunder methods. Have fun :)