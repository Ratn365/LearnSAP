 
Now we are going to talk about third party item category.

Third party item category.

Is when you procure goods for somebody else.

Who could be that?

Somebody else.

It could be a customer or it could be any other third person.

Right?

Let me take the same coffee example.

A customer.

This is a customer, not a vendor.

A customer comes to you.

And says, I need $1000 or £1000 of coffee.

And please deliver it to me at this address.

We could do that, right?

We have all the contacts.

Although we sell coffee brewed, we can also sell coffee beans.

Why?

Because we are in the same business.

So what we do first is create a sales order.

This is similar to the purchase order but taken from the customer.

The sales order says that you need so many pounds of.

This sales order.

Will stay in the system until you run.

And the MRP will convert this into a purchase requisition.

And later convert this to a purchase order manually somehow.

And this purchase order will be sent to the vendor.

The vendor will not ship it to our plant.

It will ship it or he will ship it directly to the customer.

Because the vendor ships it directly to somebody else, a third party, a customer in this case.

This scenario is called third party order.

Okay, now, now this part of the setup, right?

It's something that is not done in a.

This is.

And this part.

Is all.

Right.

So the way I'm going to demo this is by using a standard available enterprise structure.

Okay.

Don't worry about doing this in the system yet because you need a knowledge of SD.

And that's not something I'm going to provide in this course because it's it's too cumbersome.

All right.

So I'm going to create a sales order.

For Customer 1000.

For material, say M0 £1,000.

Right.

And the way I'm going to specify that this is a drop ship, meaning, you know, this is something that

the vendor is going to provide is by changing the item category.

Quite similar to the way we have item categories in purchasing.

Even sales have item categories.

Right.

And I'm going to save this.

And without even having to run actually with this kind of way of doing a sales order, a purchase requisition

will already be created.

The sales order.

12094.

I'm going to go to change your display.

12094.

Double click this line item.

Go to schedule lines.

Click on Purchase requisition and you see the purchase requisition here.

10013623.

Right.

10013623.

Copy that.

This part is done.

So the sales order is created and it has generated a purchase requisition.

Now the purchase requisition needs to be converted to a purchase order.

How do you do that?

Document overview on purchase requisitions.

Put the purchase requisition number in there.

Remove all the other data.

Click.

Execute.

And there is our purchase requisition.

Drag and drop it.

Enter the vendor.

You can enter the vendor.

Then go to the header and specify the purchase order that's relevant for.

This kind of operation.

So instead of 4001, you could enter 1000 as a vendor.

Right.

But where is this going to be delivered?

Click on delivery address and this is the address where the vendor is going to deliver.

The name is Becker Berlin.

The street is so on and it's in Germany.

Where did he get this address from?

It's not delivered to the plant, we said.

It's delivered to the customer's address.

So when you create a PO, the address that specified in the sales order goes to the purchase requisition,

it goes to the purchase order and.

That's what you see in the delivery address of the purchase order.

If you want, I can open another screen.

Go to the customer.

D03 1000.

And show you the address.

See.

Becker.

Berlin.

Some address.

One, three, four, three, seven.

And in Germany, this is how third party purchase orders were.

And if you look at the item category here, what is it?

S And the account assignment is

one one for third party.

What are the controls behind item category?

S for third party.

Double click that.

The material is possible, but account assignment is mandatory, so you cannot create a third party

order without an account assignment.

When you want to deliver the goods to somebody else, the inventory is not going to come to you.

That means somebody has got to absorb that cost.

And that's why the account assignment is mandatory.

Now, if you look at the goods receipt, there is no goods receipt, right?

Why?

Because it's a third party delivery.

The vendor is going to deliver the goods directly to the customer, so there is no need for goods receipt.

But the vendor sends us the invoice because we are the middleman and we'll process the invoice.

So the vendor is going to deliver the goods directly to the customer.

So no.

G.R..

But the vendor is going to send an invoice and there is going to be an.

Right.

And this is dictated by item category S.

S for third party.