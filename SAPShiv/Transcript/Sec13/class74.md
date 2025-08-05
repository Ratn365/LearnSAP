 
Transcript
So how do you create a contract?

Create a contract by going to logistics, material management, purchasing and outline agreements.

Like I said, there are two different tools that vendors use to negotiate with customers.

One is a contract and next is a scheduling agreement.

Now, as a contract is a primary tool.

A scheduling agreement is used only in specific kind of industries.

We'll go through the scheduling agreement a bit, but we're going to focus more on contracts in this

chapter.

So click on contracts.

And M 31 K Let's go and create it.

So we want to create a contract with the vendor 4001 And what kind of contract is it?

The first kind of the first kind of contract that we are going to create is a quantity contract.

So we'll create a contract with the vendor 4001 for delivering £50,000 or kilos of coffee at $9 per

pound.

Okay.

So in order to do that, we have to select the right agreement type.

This is where you select whether it's a quantity contract or a value contract.

For now, we are doing a quantity contract.

Right.

So we'll select quantity contract.

So select quantity contract.

And this is the date that the contract is effective from.

And purchase Group 001.

Click.

Okay.

The company code is US zero one.

There is a piece of configuration that we have to do in order for the system not to ask this pop up

window.

We'll get to that later.

Click.

Okay.

And how long do we want this to be valid until?

So this is 2016, right?

Let's say we want this to be valid for one year.

2017.

Okay.

Hit.

Enter.

Okay, now what are the materials that we want to commit to now?

We have a requirement for coffee beans for a quantity of 50,000.

Right.

And just ignore that message.

And at a price of $9 per pound or $9 per kilo.

Right.

Hit enter and you can click save.

There you go.

We have created a contract for 600000 65.

Now.

What do you do with the contract?

Say we have created a contract.

And this is a quantity contract.

Whereby we have committed with the vendor that we will purchase £50,000.

Per year of coffee.

So we shook our hands, said goodbye.

We came back to our plant.

Chicago plant.

Now, from this point on, for the next one year, we committed to purchase £50,000 of coffee and we

created that contract in the system, 50000 28 say so going forward any time there is a requirement

for coffee.

I'll create a PO.

Right.

I'll create a PO with vendor 4001 and I'll say coffee.

And instead of just creating a like that, I will refer to this contract which is saying which is like

saying, hey, you know what?

We have committed to £50,000 of coffee at nine, $9 per pound.

And here is my first PO.

And because there could be multiple contracts, I'm referring to this contract for the price.

So that way the vendor knows what is the contract that this company is referring to.

So it's an easy way to track prices and terms and volumes.

Right.

We'll see the advantages of doing that.

So we are referring to this contract creating a purchase order.

And automatically the price for this is not going to be $10 instead $9 per pound, because that is what

we have negotiated here.

Right.

If we create a standalone purchase order, the price is going to be $10 per pound.

Remember, that's how we have created our info records.

Now, when we refer this contract, the price is going to be $9 per pound.

Let's see that in action.

So we have created a contract.

All good.

So time has come for this week to purchase coffee.

So how do you do that?

Go create a purchase order.

Create.

Right like that.

Now, if you don't refer a contract.

The price for coffee is going to be.

Let's say we are procuring £100 this week.

What's the price for coffee?

Well, I think we have deleted that info record.

So the price for coffee is going to be $10 per pound.

Right.

That was the price that we have been procuring all along.

But look at SAP.

It says a scheduling agreement exists for this material.

Or I might have created some scheduling agreements.

So it's saying scheduling agreement exists or contracts exist.

So there are some outline agreements.

It could be scheduling agreements or contracts that exist.

And it's a warning.

Right.

It's not an error.

It's a warning.

So it's saying, hey, you know what, you're trying to procure coffee at $10 per pound, which is good,

but there are some agreements that exist which might offer you better prices.

So better refer to it and see if they're really offering better prices or terms or not.

Right.

Okay, Now we know that contract exists.

Now, how do we refer to that contract?

There are a couple of ways to do it.

A simple way is just scroll all the way to the right and then you get a column called the Outline Agreement.

Okay, so paste the contract number there.

Hit.

Okay.

You see, the price has changed to nine.

Right.

It automatically changed to nine because that's how we have negotiated that contract at $9 per pound

as opposed to a regular price of $10 per pound.

Okay, so this is one way you refer a contract.

Now, from this point onwards, the next steps are really the same, nothing different.

So you create this purchase order and then you do a go and then you do a my row and then that's done.

And you keep referring to that contract until you exhaust the contract.

Now, in this purchase order, we are trying to procure a quantity of 100, right?

What is the total that we have negotiated in the contract?

50,000.

So this is just 100 out of 50,000.

Right.

Let's see the effect of this purchase order on the contract.

Click save.

Right.

So we created this bio for £100 of coffee at $9 per pound and we did the goods receipt, invoice receipt,

let's say.

Now, if you go look at this contract, the total quantity that we have negotiated would still remain

50,000.

But the quantity consumed will be 100.

So this is what we have promised the vendor will buy.

And this is what we have consumed so far.

So SAP automatically tracks how much we have consumed and how much is remaining.

And how do you see that?

Go back to the contract.

A close.

This close this.

Go to outline, agreement, contract and change or display.

Right.

So this is our contract.

And go to this line item and we have released 100 out of the 50,000.

So the keyword is called release.

So how much has been released out of the total that we have negotiated?

We have negotiated a value of 50,000.

And we have released 100 quantity out of it.

So over the course of the year.

We will release 100, 200, 300, 500, However many we require.

Right?

An SAP is supposed to track how much we have released.

Now, if you create another PO and release, say, 200, this number is going to go to 300.

100 plus.

200.

Now and said there is another way to release contracts into a purchase order.

Right.

Another way.

Is like so.

Contract release order.

Let go to contract.

Follow on functions.

Contract Release Order.

It's going to pull that contract here.

And now you can do either of two things.

You can just drag this contract and put on the shopping cart.

Or you could select that contract and click on Adapt.

So when you click on Adapt, it's going to adapt the details from the contract into the PIO.

And we're going to say this time we are releasing a quantity of 200.

So this saves us from having to go all the way to the right, putting the contract number in there.

So instead of doing that, you could go to the contract, click on release order And.

SAP automatically creates this purchase order with reference to the contract.

And the way to do that is by either selecting that contract and clicking on adopt or just dragging that

into the shopping cart.

You can do it either way.

Right.

So these are the different ways in which you can create release orders with reference to the contract.

Now, earlier, we have created a purchase order for 100.

Now we have created a purchase order for 200.

Save it.

And if you go back to the contract and change your display mode, you should see that out of the 50,300

should have been consumed and it still says 100 here.

Why is that?

Well, this is not the cumulative release quantity.

It's the release quantity that's typically released Per Poe.

If you want to see the cumulative quantity.

So you have to go click on this button.

This is called the release documentation.

So it gives you a list of all the polls that have been created with reference to this contract.

So the first press release for 100, the next for 200, the next for 200.

The total that have been released is 500.

And the value of the total that has been released is 4500.

And it gives you this summation by plant and company code.

So if somebody else is releasing purchase orders for the San Francisco plant, it gives you that breakup

as well.

So we have the target quantity and the total quantity that has been released here, including the value.

So this is a quantity contract.

So in the next chapter, we'll talk about value contracts.


