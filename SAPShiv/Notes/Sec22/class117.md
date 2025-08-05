 
Transcript
In this chapter we will talk about automatic Poh.

What is automatic Poh creation?

Let me give you an example.

Say we have ordered for £100.

Of coffee.

And the truck has come in after a couple of days.

Carrying the hundred pounds of coffee suddenly.

So one of the bakers comes in from our bakery.

And says he needs £100 of flour or sugar.

It's an urgent requirement.

So what options do we have?

Option number one is to place an urgent order with the vendor, say the best with the vendor can do

is 4 hours or 6 hours or four days.

Another option is this guy in the warehouse receiving the stock.

So you can just make a phone call to this guy and say, hey, you know what?

The next time the truck comes in, so the truck is going to come in an hour or two and just ask him

if he has £100 of flour.

So when the truck comes in with £100 of coffee that we have originally ordered, that is scheduled for

delivery today.

So this guy asks him if he has £100 of flour.

Assuming the truck already has £100 of flour readily available for sale.

That is, if we get lucky, we can just take that £100 of flour.

But how do we pay for it and where is the corresponding purchase order?

How is this total thing tracked?

This is done with what is called as automatic PO creation.

So let's see this in action.

So in order to do that, let's create the material flower.

Flour zero one Retail Raw material.

And it's a copy of coffee beans.

And we need the basic view, the purchasing view and accounting view and storage view.

And we are creating this for the plant.

Chicago storage location, coffee, say, or raw because it's flour.

It goes into the raw material, right?

Coffee goes into coffee, flour goes into the raw material.

Okay.

Looks like the material already exists, so it will be extended.

All right, that's good.

So everything else is there.

And let's go create a purchase order.

For coffee because that was our original order.

Right?

We have ordered for coffee.

The coffee truck came in for delivery.

Now we are checking with him if he has flour.

So let's create the original order for coffee.

£100 and save.

Now we are going to pick up that PO.

And do a goods receipt.

Michael.

Purchase order here.

Now, the truck has come in with £100 of coffee and we are checking with him if he has hundred pounds

of flour.

He says he has £100 of flour.

Now, what do we do?

We take that bag of £100 of flour, put it in our warehouse.

All right.

How do we track it in the system?

So go click on the plus button here.

So this.

So it says non ordered item.

It's an item that we did not order yet, but since it's an urgent requirement, we just want to take

it and use it.

And then.

Pay for it later.

And in order to pay for the goods, you need to have a purchase order.

So clicking on this button.

Will enable a tab whereby you can enter your material Flowers oh one.

And what's the quantity we have taken in?

We have taken £100 of flower enter.

And where did we take it?

In the plant.

Chicago one and storage location Raw.

Now you see the movement type here is 501 and it says.

Goods receipt without PO.

We have not created a PO for £100 of flour.

Right.

So it's a special movement type that can accommodate goods receipt without a PO.

But you have to provide some additional details.

Like who is the vendor who is supplying the goods?

Because based on this data, your purchase order is automatically going to be created.

Right.

You don't need a count assignment because we are going to raise a PO and click save.

Now, this is our material document.

Ctrl C and how do you know?

What is the PO associated with this ad hoc goods receipt?

If you go to m03 material document.

You should see the PIO here.

Do you see the pill?

I don't see the pill.

Why?

Because creation of an automatic purchase order has to be configured.

So where do you configure it?

You configure it for the movement.

Type 501.

So 501 should be configured to automatically generate a.


