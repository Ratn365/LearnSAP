 
Transcript
In this chapter.

We'll see how to cancel.

Goods receipt.

What is canceling of goods receipt, say, for example.

You have created a.

£400 of coffee.

And the vendor struck has come in for goods receipt.

And he has delivered the coffee.

And we have taken the goods receipt and we are ready to receive the invoice as well.

But what we later found out is that the coffee bag that he has delivered is the wrong coffee bag.

Or it might not even be coffee.

Well, why, You might have a question there.

Why would the person in the warehouse accept that?

Well, it could be a human error.

There is an intern in the warehouse who did not know the entire process.

Maybe he just took the delivery.

Or it could be a human error on the vendor's part.

The vendor might have delivered a different grade of coffee, which we might not be able to find out.

But the vendor has later realized and said, Hey, you know what?

Don't take the delivery.

Just keep it on hold.

I'll do another delivery.

So the goods receipt that we have created needs to be reversed.

And sent back to the vendor the next time the truck comes in.

How do you reverse or cancel a goods receipt?

So first let's do a PO and then do a goods receipt and then reverse that goods receipt.

In the interest of time, I have already created a goods receipt.

Let me copy it.

And now let's do a go.

So where do you want to receive it?

Into the coffee warehouse.

Click item.

Okay.

And save.

So here is the material document that was generated.

2549.

Now we want to reverse this goods receipt.

So in my goal, select cancellation.

And select the material document that you want to reverse.

Now, in this case, we have just done the goods receipt, so it automatically picked up the material

document.

If you don't know the material document, you can always go to the purchase order, go to the purchase

order history tab at the line item, and then pick up the goods receipt number from there.

Now hit enter.

And SAP automatically pulls up the quantities, the materials, plant, storage, location.

And the movement type in this case is 102.

You see 101 is goods receipt.

102 is a reversal of goods receipt.

Remember, reversal numbers are always.

One added to the original movement type.

So 101 is goods receipt and 1 or 2 is reversal of goods receipt.

And every time you do a reversal, typically a movement type is required.

So flag item.

Okay, click on check, make sure everything is all right and click save.

Now, if you go back to the purchase order M 23 n.

Go to purchase order history.

You should see two documents there.

5002549 is the original goods receipt with movement type 101 and 2550 is the reversed or cancelled goods

receipt with movement type 102.

Now.

Let me ask you a question here.

What happens to the purchase order?

We have received the goods against the purchase order and then we have cancelled it or sent it back.

Now what happens to the purchase order?

Is it open or is it closed?

Obviously it should be open, right?

Because we have cancelled the goods movement.

So where can we see that?

If you go to the delivery schedule, you should see that quantity should have been reversed.

And the open quantity should come back again to 100.

Now you can go create another goods receipt when the vendor delivers the right goods and create an invoice

receipt.


