 
Transcript
So what is a planned order?

A planned order.

Is a suggestion to either procure or produce goods.

So a planned order typically is more relevant to be converted to a production order.

And what is a production order?

A production order is an order given to your baker making the goods.

To make so many muffins.

A production order is an order given to the shop floor manufacturer in Honda to make a car.

The production order is an order given to your barista to make one coffee or ten coffees.

So a production order is an instruction to manufacturing to produce something.

What to produce can be listed here when it is required, can be listed here in which plant it is requested

can be written here.

Also, a planned order conveniently can be converted to a purchase requisition.

Now.

I see a question here.

So in case the material is externally procured.

Does it produce a planned order or a purchase requisition?

So which one is more relevant or which one is being triggered by SAP?

When MSPs run.

So MSP run.

For externally procured materials.

Does what does it do?

Planned order or does it do purchase requisition.

Let's go to Md0 three and I'll show you a setting that switches between either planned order or production

order.

So do you see that create purchase requisitions?

If we set this to three and run MRP, then SAP creates planned orders even for materials that are procured

externally.

But if you set this to either 1 or 2.

MRV produces purchase requisitions directly and bypasses planned orders for externally procured materials.

So let's come back.

So when you run for externally procured materials.

If the setting is three, it produces planned orders and a planned order can be converted either to

a purchase requisition or to a production order.

It's your choice.

But if the setting is one.

Or two, then it directly creates the purchase requisition.

So it bypasses this step.

All right, now our material muffin.

Is internally produced, right?

So it's created a planned order.

A planned order, like I said, is a precursor either to a purchase requisition or to a production order.

Now, what do we want to do?

We need 500 muffins.

So SAP s run has generated a planned order for 500 quantity.

But we need to produce them.

You can't take any other actions on a planned order other than either cancel it or change it or take

it forward.

In this case, to a production order.

So let's do that.

So go to MD 04MD04.

Select your muffin.

And this is the line item that we are talking about, right?

The one that has just created a planned order for a quantity of 500.

So click.

Okay.

And here are your options.

You can convert it to a purchase requisition.

That is this step.

Or you can convert it to a production order.

That is this step.

So in our case, a muffin needs to be produced.

So the MRP controller is going to take an action of converting it into a production order.

How?

Like so just click on production order now.

SAP is trying to create a production order against this.

Plant order.

Now at this point.

The MRP controller or the person planning muffins has two choices.

Purchase requisition is ruled out because Muffin is produced internally.

The only other option is maybe he can go and change the plant order.

Maybe he doesn't want 500.

He wants only 400.

In our case, he can do that.

We'll see how to do it after we complete the production order.

All right.

So this is the production order.

So SAP is trying to create a production order for this material.

And it says work scheduling data of Muffin is not being maintained.

This is what I was talking about when we were trying to create the material.

For materials that require internal production or in-house production.

They require the work scheduling view.

So let's go back.

Go change the material or go create a work scheduling view for the muffin.

Which is basically a view that contains production related data.

In this case, we don't need to really add anything.

It's all in there.

All you have to do is if you have to set up some setup time, if you have to set up some serial number

profiles, all that stuff, but something that we don't care at this point, you know, you just need

to put that view in.

Okay.

This is more relevant for people learning or production planning.

Since we're not doing that, we don't care.

Now go to Md0 for.

And select that material and try to create a production order like we have seen previously.

So let's see what happens now.

In our case, some of the settings are not there, and that's the reason why you get these issues.

But you understand the point, right?

A planned order is being converted to a production order, and if everything goes well, your muffin

will be produced and received into our warehouse.

So we'll have a stock of 500.

So a production order.

Produces.

The goods.

And.

Do a goods receipt against this production order, and that will increase the stock.

In case of purchase requisitions, purchase requisition will be converted to a PO.

And as usual.

Goods will be received against that and that increases the stock to.


