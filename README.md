# Takeaway Challenge
## Weekend Challenge
### Week Two

Completed 20 November 2016
==================
```
                            _________
              r==           |       |
           _  //            |  M.A. |   ))))
          |_)//(''''':      |       |
            //  \_____:_____.-------D     )))))
           //   | ===  |   /        \
       .:'//.   \ \=|   \ /  .:'':./    )))))
      :' // ':   \ \ ''..'--:'-.. ':
      '. '' .'    \:.....:--'.-'' .'
       ':..:'                ':..:'

 ```

Instructions
-------

* ``require "./lib/order.rb"`` in IRB or Pry
* Create a new order ``order = Order.new``
* Start the order ``order.start``
* Select the items and quantities you want to order ``order.select_items("burrito", 2) order.select_items("corn", 1) order.select_items("tacos", 2)`` You can order as many items as you want.
* Get the price of your order separated by item ``order.get_price``
* Confirm your order ``order.confirm("yes")``, or don't ``order.confirm("no")``, but then you'll miss out on delicious Mexican food!
* Finally, complete your order ``order.confirmation.complete_order`` and you (well, I), will receive a text message.

The Task as described
-------
We have received a request from a client to build an app for a takeaway restaurant that shows the menu to the customer, allows them to order, verifies the price, and sends them a confirmation text message.

Here are the user stories that we worked out in collaboration with the client.

```
As a customer
So that I can check if I want to order something
I would like to see a list of dishes with prices
```

```
As a customer
So that I can order the meal I want
I would like to be able to select some number of several available dishes
```

```
As a customer
So that I can verify that my order is correct
I would like to check that the total I have been given matches the sum of the various dishes in my order
```

```
As a customer
So that I am reassured that my order will be delivered on time
I would like to receive a text such as "Thank you! Your order was placed and will be delivered before 18:52" after I have ordered
```
