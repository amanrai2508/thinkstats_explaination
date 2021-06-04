# thinkstats_explaination
 thinkstats2 uses concept of OOPS, but it assumes the person who is learning already knows OOPS.
 Here,I have introduced some basic concept of OOPS that can help the beginners to understand the functions that are discussed in the 2nd ipynb file.

**Concept of OOPS (In Simple Terms)**

Suppose you are working at a bank that has many accounts. We can create a class named account that would be used to work with any account. For example, below I create an elementary toy class Account which stores data for a user — namely account name and balance. It also provides us with two methods to deposit/withdraw money to/from the bank account.

But, how are these attributes balance and account\_name already set to 100, and &quot;Rahul&quot; respectively? We never did call the \_\_init\_\_ method, so why did the object gets these attribute? The answer here is that \_\_init\_\_ is a magic method(There are a lot of other magic methods)which gets run whenever we create the object. So when we create myAccount , it automatically also runs the function \_\_init\_\_

So, what is this self? The way I like to explain self is by calling the same function in an albeit different way. Below, I call the same function deposit belonging to the class account and provide it with the myAccount object and the amount. And now the function takes two arguments as it should.

So, what is this self? The way I like to explain self is by calling the same function in an albeit different way. Below, I call the same function deposit belonging to the class account and provide it with the myAccount object and the amount. And now the function takes two arguments as it should.

And our myAccount balance increases by 1000 as expected. So it is the same function we have called. Now, that could only happen if self and myAccount are exactly the same object. When I call myAccount.deposit(1000) Python provides

\* List item

\* List item

the same object myAccount to the function call as the argument self. And that is why self.balance in the function definition really refers to myAccount.balance
