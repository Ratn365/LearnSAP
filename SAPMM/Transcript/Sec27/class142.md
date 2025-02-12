Transcript
All right, so let's create a new material M0 one.

So call it coffee beans.

Say 11.

Okay.

And this is, of course, raw material.

Retail and raw material Enter.

And we want to have a basic view, of course, and we are going to procure them.

These are raw materials.

So select purchasing and select these two views.

Mrp1.

Mrp2.

And.

Of course, have an accounting view.

Click.

Okay.

The plant is Chicago storage location is coffee.

Hit enter.

All right.

We call it coffee beans, whatever.

Let's call it.

C.

B.

P.

Manuel.

Order.

Just so that we can identify that material.

And the base unit is pound and the material group 015 doesn't matter.

Purchasing group.

001.

And in one.

We set the type to be.

And this is what tells SAP that this material, coffee Beans 11, is going to be planned using manual

reorder point based planning.

You go to the possible list of options.

If you go far down below.

You'll see the type manual reorder point planning vb.

This is what dictates, like I said, that this material is going to be planned based on reorder point

and that is going to be manually determined.

Okay.

Now, when you say manual reorder point.

You gotta put a number.

What is the number that we said?

500.

500 is the minimum below, which if the stock falls down, I'm going to reorder again.

Right.

So hit.

Enter.

And comptroller Could be anybody.

All right.

Now we go to the lot size.

What is the lot?

Size.

A lot.

Size is the size in which we procure or produce goods.

For now.

Just put x lot for lot.

Don't worry, we'll talk about lots later.

In Mrp2, we are going to be setting the procurement to F because it's a raw material.

It's automatically going to default to F.

And we have to set the planned delivery time, right?

We said it's three days, so we need three days for the vendor to deliver the goods.

That's good.

Then we're going to go to the accounting view.

Set this to 3000, as usual.

And call it moving average because it's a raw material because we are procuring them.

We are going to set it to moving average.

We are done with this material.

Save it.

Now go to.

Select your coffee beans, the one that we've just created, coffee beans 11 and see if there is any

stock.

There is no stock.

So I can go place an order for 500.

So you don't have to explicitly place an order.

We said.

Remember what we said.

This is our reorder point.

And if the stock falls below the reorder point.

We want to place an order right now.

If the process is as simple as saying if the stock falls below a certain point.

Place an order that's very specific, right?

It's really clear.

So you don't have to go place an order.

You can place an order, go create a purchase order, but you don't have to.

There is a process in SAP called MRP run.

Now this can be done either in the foreground like going to MD zero three.

Put your material.

Put your plant.

And hit enter.

Or you can take this program and schedule it to run every day.

Like a robot.

It runs every day, looks at the reorder point, triggers it, and triggers what needs to be done.

Now let's say let's just run this manually for now.

Okay.

Hit.

Enter.

Enter again.

So you see carried out for coffee beans.

Right now.

After this run is done, go to md0 for the requirement list.

And see if a new requirement is generated for this material.

So go to Md0 four.

Enter your coffee beans material plant.

Hit.

Enter again.

And this is something that's generated today.

And we require £500 of coffee.

This is a purchase requisition.

Because we have a stock of zero, SAP says, go ahead, procure £500 of coffee.

Today is the 2nd of November, and the date here says 11 zero seven.

Why?

Because.

We have added a planned delivery time of three days and there could be holidays.

So 1102, let's say.

Today is the November 2nd and we set three days, right?

So third, fourth and fifth and sixth are holidays, right?

Fifth is a Saturday.

Sixth is a holiday.

So seventh is the third day.

So if we order today, we'll get the goods on the seventh because there is a delivery time of three

days.

So three, four and seven are the working days that consume those three days that are required for the

vendor to deliver the goods and Saturday and Sunday are excluded because they are holidays.

So this element over here that was created automatically using the run says that on 11 seven.

I require £500 of coffee and here is my suggestion because it's a robot run is basically a robot.

Because it's a robot, you don't want it to generate purchase orders, send it to the vendor.

It can only give you suggestions.

You don't want to take over, right?

It'll give you a suggestion.

So in case of procurement.

The suggestion is a purchase requisition.

If it is production like a muffin that we produce in our warehouse or plant or bakery.

It will be a planned order.

We'll get to that.

So because it's procurement.

It has generated a purchase requisition.

Now.

For the vendor to supply the goods.

A purchase requisition is not enough.

Remember, purchase requisition is an internal document, so you need this purchase requisition to be

converted to a purchase order sent out to the vendor.

So how do you do that?

Select that.

And that element opens up in a pop up and click on this button Convert Purchase acquisition to purchase

order.

This is a step that's done manually so the bot run has generated suggestions for you.

No, This is where the planner comes in.

The planner comes in.

Looks at all the suggestions for that material.

And specifically converts them manually to a purchase order.

So that is the level of human intervention that is required.

You know, in order for this to happen automatically, some setup needs to be done right.

So everything like the purchase group, purchase organization, company code, all of these things need

to be set up properly.

If all of them are set up, a purchase requisition will be converted to a purchase order.

But that's besides the story.

The point being, as soon as your planning is done, your run is done.

Run generates suggestions and these suggestions need to be acted upon by the planner.

And in case they are acted upon.

Like so.

Set a price.

And you see it's an order for £500 of coffee beans.

11.

Check if everything is okay.

Everything is okay.

Save it.

All right.

So the purchase requisition has been converted to a purchase order manually.

So go ahead and refresh it.

And Md0 for knows that now there is a purchase order for £500 of coffee.

And it's going to be delivered on November the 7th.

Remember, this date is the target date.

The date when we need the goods by.

So this is our purchase order.

The planning part is done.

Planner goes home.

Now the vendor receives the PO.

He prepares the coffee beans and say on the third day or whenever he sends the goods.

Now somebody in our warehouse will take the goods in.

Like a goods receipt.

Against a purchase order.

Enter the purchase order number.

Four £500 of coffee beans, 11 and it's going to be received into the coffee beans storage location.

Set item as okay and click save.

Document is posted.

Now, if you go to MV, you should have £500 of coffee.

There you go.

Now, if the planner runs again, like go to zero three.

Enter the coffee beans material.

Click.

Okay.

Click Okay.

Run carried out.

Go to md0 for requirements list.

Select your material and plant, click.

Okay.

There is talk of 500, so it's not going to generate additional purchase requisitions because there

is stock.

So we are cool.

We got everything we need.

So in order for the system or to trigger another purchase order, stock has to fall below 500.

Remember we said this is our reorder point 500.

Now, to start with, there was no stock.

It was a newly created material.

We didn't have stock, so we ran Mrcp MD zero three went to zero four and found out that the purchase

requisition was created.


