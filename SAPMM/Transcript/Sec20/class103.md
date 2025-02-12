 
Transcript
In this chapter, we will essentially achieve the same thing that we have done in the previous chapter.

Transfer the goods from Chicago plant to the San Francisco plant.

But we are going to do that not using transfer posting, but using a different method called s t o.

Esto stands for stock.

Transport.

Order.

The key word to note here is transport.

And we'll see why.

Now the business scenario is exactly the same.

So there is a Chicago plant.

There is a San Francisco plant.

We want to move the goods from Chicago to San Francisco.

Now to move the goods from Chicago to San Francisco.

We would need some kind of a transportation means.

Right.

Like a truck.

Or we could use an external vendor like Fedex, which can do all the logistics for us.

Let's say we use Fedex.

Okay.

Just for simplicity.

The way to do a stock transport order is to create an SDO.

In the receiving plant.

The second step.

Is to do a good issue.

Against.

The S2.

That has been created in the receiving plant.

So you issue the goods.

And step number three is.

Goods receipt against the same store.

Just three steps.

Now, what is the difference between these three steps and transfer posting that we have seen earlier?

How different are they?

Now there are some preconditions that have to be met in order for us to be able to do a stock transport

order this way.

From a San Francisco perspective, we have to create Chicago as a vendor.

Now Chicago is supplying the goods to the San Francisco plant.

So Chicago becomes a vendor for San Francisco.

If you do it in reverse, take the goods from San Francisco to Chicago.

The San Francisco plant becomes a vendor, and that's the first setting that needs to be done.

The second setting is to make sure that the material.

Is extended between both the plants.

Now, we have already extended the material coffee beans to San Francisco in the previous chapter.

So we have got that covered.

Now let's see where you create the vendor as a plant.

So go back.

Go to.

IMG.

Material management.

Purchasing.

Go to purchase order.

Set up stock transport order.

Now, there are a lot of settings here.

We don't want to look at all the settings here because there is another way to do stock transport order

using deliveries, but we are not going to go there.

That's a cross functional area.

We require knowledge of both SD and.

Since we are just learning, we don't want to really go there.

So how do you do a stock transport order?

Go to 21 and just like how you create a purchase order and instead of choosing NB standard PO choose

EU be.

IUB stands for stock transport order.

And you see immediately the field vendor is now changed to supplying plant.

And over here we say Chicago one hit enter.

And you say coffee beans.

Quantity of, say, 75.

And.

The plan that's asking for £75 of coffee is San Francisco.

So enter that there at the line item level.

And it says contracts exist.

We can hit.

Okay.

Doesn't matter.

And click save.

If you see this message and see no errors there, just click.

Okay.

And save it.

Okay.

There you go.

The stock transport order.

4500 is being created.

Now, how different is this from a standard purchase order?

Well, not much different, right?

We've got a vendor.

We entered materials, the price was automatically picked up and all we had to do was change this field

from NB to EB.

This field is called the document type.

Purchasing document type in this case.

So this is part of configuration.

We have not seen purchasing document type configuration yet, so we don't want to go too much into the

details.

But for now, just understand that this transaction, the blueprint for this transaction, when I mean

blueprint in terms of how this document behaves, this purchasing order behaves or stock transport order

behaves is based primarily on this little dropdown here.

And we have changed the blueprint of this transaction.

21.

From a purchase order to a stock transport order by changing the document type.

And like I said, we don't understand the configuration behind the document type just yet.

Don't worry about it.

NB is standard PO and UB is stock transport order.

In case you don't see these codes N.V. and UB, the way to enable them is by going to settings.

Options.

And click on interactive design.

Visualization and ensure that these two check boxes are checked on show keys with dropdowns, sort keys

with dropdown lists.

Once you have them enabled, just go back and come again and you should see these keys enabled the EOB

and Nbps.

If not, you'll just see the description stock transport, order and standard.

And sometimes it can be confusing.

You see, the description for all these keys is the same.

This is easy and this is easy, but the description is the same electronic commerce.

So in cases like that, it becomes difficult to select the right key from the dropdown.

In our case, we have chosen B for stock transport order.

We just change the blueprint of how we do this purchasing order.

Now, if you go back and enter that purchase order number in there, it's not really much different.

The vendor has changed from 4001 to supplying plant.

Now it's not the vendor who is delivering the goods, it's the supplying plant.

It's a plant.

It's one of our plants and the way we have done it previously is using transfer posting.

And what is a transfer posting?

Have it has the material, it has the movement type, it has the source plant, it has the target plant

and quantities.

Well, we have all of that here, right?

We have the material, we have the source plant.

We have the target plant, which is San Francisco.

It's just that the description is different, but but it's San Francisco and we have quantity.

Right.

We have everything.

What else is there?

Well, we have a delivery schedule.

This is one of the advantages of using a stock transport order.

Using transfer posting either one step or two step.

We don't have a schedule of delivery.

And we'll see what a schedule of delivery is when we start to compare a transfer posting with stock

transport order.

And we also have deliveries.

We have texts, we have delivery addresses, confirmation.

There is so much more functionality in a stock transport order when doing stock transfer versus doing

it using transfer posting.

Before we compare this, let's just finish this truck transport order.

So step number one is done.

Now let's do step number two, which is issuing a goods against the stock transport order in the supplying

plant.

How do you do that?

This is simple.

Using my go.

So what do you want to do?

You want to do a good issue?

Okay.

Against a purchase order.

And the purchase order number is this.

I just pasted it from my clipboard and hit enter.

All right.

The movement type is automatically determined.

It's 351 from stock in transit.

From plant to stock in transit.

And the storage location from which we want to pick up the goods is coffee.

And what's the quantity?

75.

We're good with that.

Click item.

Okay.

And hit save.

All right.

The material document is posted.

Now let's go check the stock.

So the stock over here in Chicago, coffee, coffee storage location should go down by 75, just like

how we have done in terms of posting.

Let's go refresh this.

Did it go down from 700?

It went down by £75 and came down to 625.

But the San Francisco plant stock did not go up just yet.

So we have done this goods issue which removed stock from the storage location using movement type 351.

And of course, it's a minus because it's removing the stock.

And where is the stock now?

The £75.

Is it there in the stock transfer?

No.

Where is it?

You see it's an unordered stock.

So the way to check for in-transit stock when you do it via stock transport order.

Is not by going and checking it in.

You cannot see the stock in transit in.

When you do this whole process of stock transfer via.

Stock transport order map shows it as on order stock.

So that means the San Francisco has ordered.

475.

Purchase order like a purchase order.

Not from a vendor, but from another plant.

The Chicago plant.

There is another transaction that you can use to purely look at the stock and transact from the perspective

of stock transport order.

So if you go to EMB five T.

And select the material.

And the receiving plant is San Francisco.

Right.

And.

And click execute.

You should see the 75 right there.

And the supplying plant is Chicago one.

So why is this different from transfer posting?

It's the way the accounting is done.

So behind the scenes.

Transfer posting is is more of a inventory management based solution to transferring stock.

But stock transport order can involve logistics as well.

It can involve accounting as well.

It's much more involved.

All right.

So before we go talk about the differences, let's complete this transaction using 351.

We have removed the stock from Chicago into transit of San Francisco now.

We want to receive the goods into the San Francisco plant.

Based on that stock transport order, that's step number three.

So select goods receipt.

Against the.

All right.

Hit enter and it automatically determines the material quantity where it's going to go.

The movement type.

ET cetera.

ET cetera.

And the storage location, of course, is coffee.

Click item.

Okay.

And save.

Now the stock in transit should be gone.

It's no longer stock in transit.

So you don't see anything there.

And it should magically appear in the San Francisco plant.

Do you see that 150 plus 75 is 225.

All right.

So we have used 101 plus as the movement type to receive goods from that stock transport order.

Now, I'm sure you must be wondering why.

Why do we have to do it one way versus the other?


