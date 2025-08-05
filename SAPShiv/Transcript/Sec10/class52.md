 

Lecture thumbnail
52. How is stock valuated in SAP - Part 2
Transcript
The formula for calculating the moving average is this The moving average price equals total value.

Meaning portal existing value plus GR value the value of the goods that we have received.

Divided by the total stock.

The total stock at hand, plus the quantity, the new quantity that's being received.

So when the first order was created, let me let me go back.

So when the first order was created, the value was everything was zero, right?

So it was all 000.

The quantity was zero.

Value was zero.

And the average price or moving average price was zero.

Now, as soon as you have done the goods, this is when the PO was created.

And then you have created a goods receipt.

You have created a goods receipt.

At what price?

Quantity of one.

And the value.

We don't know the moving average price or the price.

The average price was $10, so ten multiplied by one will be $10 and that will be our valuation and

that was expected.

So when you created the second order.

Right.

The PIO is created for.

Quantity of two.

And the dollar price was $20.

So the gr value of course we didn't do a gr here so that's that and.

When we have done the gr.

The quantity for which we have done the GR is two.

The dollar value is at $20.

Per pound.

So the gr.

Value is 22 to.

$40.

Right now.

How did SAP calculate the moving average price?

That's the question.

So we said the moving average price.

Equals.

Current value.

What's the current value?

$10.

Plus the new value.

What's the new value?

40.

Divided by.

Current quantity.

What's the current quantity?

One.

What's the quantity to.

So that is equals ten plus 40 is 50.

By three.

This should equal 16.67.

You can just go to the calculator and you'll find out that that's the correct value.

Right.

And now you can go on and on and on.

Next time, for example, Let me let me do one final example.

Again.

Let's do a quantity.

Of three.

At a dollar price of.

30.

And do you do goods receipt.

Of course.

For.

Quantity three at a dollar price of 30.

So the dollar gr value meaning what's the total value of goods that we have received that would be equal

to.

13.

Two, three.

$90.

Now let's calculate the moving average price again.

Now the moving average price is.

The current value.

What's the current value?

The current value is $50.

Plus, what's the new value?

90 divided by the current quantity three plus.

What's the current quantity?

Three.

50 plus 90 is 140.

Divided by six.

So.

140.

Divided by six.

Is 23.33.

So that's the new moving average price, right?

You can go see it in the system.

It will not deviate from that value.

All right.

You want to test it, let's go do it.

M 21 n.

Same vendor.

4001.

And every time we have to enter this purchase or purchase group company code.

Right?

It's a pain.

So SAP has a provision to default your values to a certain set of values.

The reason is real simple.

If I have ten coffee shops.

Five in the US.

Five in Canada.

Each coffee shop will have the respective people doing transactions.

Creating purchase orders, receiving goods, receiving invoices.

Paying invoices.

And they'll be doing only for that respective shop or plant.

Assuming a shop represents a plant.

So in that case, why should they go and change these values or enter these values again and again and

again?

The purchase or purchase group and purchase company code instead for that user, the user sitting in

Chicago plant.

Say if we can default the values to the same values that he uses again and again and again, he doesn't

have to enter these values every time he creates a PO.

And how can we do that?

Go to personal settings.

Go to default values.

And here for the purchase log, enter us zero one.

And purchase group enter 300.

That's the one that we have been using, right?

And for company code also enter US zero one.

And click see.

Okay.

Now go back.

No.

And come again.

You see, they're all defaulted.

I didn't enter them.

Now, if you enter the vendor.

The other field, the purchase group field will also be defaulted.

So you don't have to enter these fields again and again and again.

Now, how about the plant?

Can we default the plant?

Yes.

Go to personal settings.

Go to default values.

Go to item.

And for plant.

Enter Chicago one and click save.

Again.

Go back.

M 21.

N.

Enter your vendor.

And enter your material, say coffee beans.

Zero six.

Quantity of three.

You want to check the plant?

See Chicago.

It's already entered.

So that's how you default certain fields.

Not all fields can be defaulted, certain fields can be, and they are predetermined by SCP.

So use that if you don't want to enter these fields again and again.

So imagine a person sitting in Chicago plant.

He's ordering for the Chicago plant only.

So it doesn't make sense to always enter the plant for Chicago.

Here it's always Chicago for him.

So for that user, it's always Chicago.

And these are personal settings specific to a particular user, not for everybody.

So if you log in with your user ID, these are not your default settings.

Definitely not.

So they will not be defaulted until you go to personal settings and then set your defaults.

All right, so that's that now.

Now, what were we trying to do overall?

We were trying to create a new purchase order and see the effect of the price.

So what was the price that we wanted to try?

The price that we wanted to try was $30 for a quantity of three.

So let's go put $30 here.

And the quantity is three and click save.

So go to the PO, save the PO and quickly do a goods receipt.

Michael.

Paste your purchase order and we're going to put it in the storage location of raw materials.

Click item.

Okay.

And click save.

All right.

So let's go back to the material and see the price changes.

Go back, enter again.

Go to accounting view.

Enter Chicago.

Do you see that?

23.33.

That's the moving average price.

Want to check that.

Here it is.

So that's the formula to compute the moving average price.

And this is how you set the defaults.

Go to personal settings.

And all settings in the header or in the header section like purchase or purchase group company codes

and all settings in the item or in the item.

So once you set that, go back and come again and all your settings will be saved and those values will

be defaulted every time you create a purchase order.

So I think we are done with our detour of moving average price and valuation and let's go on to procure

non stock materials.