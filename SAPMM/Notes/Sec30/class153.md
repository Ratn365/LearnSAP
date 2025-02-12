 
Transcript
Go to Sbarro.

IMG.

Material management, consumption based planning.

And if you look at groups carry out overall maintenance.

And go to the Chicago plant.

Click on Maintain.

And here you specify the group.

So we want to look at, um, say we want to make two stock, right?

We are making two stock, keeping it in stock and selling it.

So that's called make two stock.

MTS Make to order is like a birthday cake made specially for you.

Let's make to order.

So you don't produce it until there is a requirement, until there is an order.

But make the stock is what we have been seeing so far.

We require 100 muffins.

It doesn't mean that there are 100 orders or orders for 100 quantity of muffins.

We are making them putting it in stock and that's why we are forecasting we don't have orders yet.

Based on historic consumption we are trying to forecast.

So this is probably a better group for coffee beans make to stock.

Right and then click on Maintain.

And click on Planning horizon.

So this is set to 60.

Let's set it to 30.

Okay.

So we are not going to plan beyond 30 days.

So what material do we select?

We select, let's say zero one.

Let's say coffee beans 14.

This is a different kind of coffee beans, and we're only going to plan.

For 30 days.

All right.

We're not going to plan beyond 30 days.

By default, the selection is 100 days at the plant level.

So select basic purchasing one to MRP, forecasting accounting Chicago one and put some description

here.

Planning Horizon 30 days.

Same basic unit of measure, some purchasing group.

And this is we've forecast based planning and.

And controller 001 Lot Size x.

All right.

Processing time.

Five days.

Planned delivery time, five days.

Schedule margin key.

000.

All right.

And the forecasting model, again, is seasonal.

And let's put some consumption values in there.

Again, let's put some values.

We're going to copy these values.

And save ourselves some time.

All right.

So that's consumption for one year.

And accounting is 3200 or 3000 moving average, but we did not execute the forecast right.

So go back to forecasting and execute the forecast.

That should produce consumption values or predict consumption values for the next 12 months as usual.

And we're okay with that.

And save that material.

Coffee Beans 14.

If you go to zero four, as usual, you should see requirements 12 months into the future.

But if you run for this material and use net PL, which is the based on the planning horizon.

Oh, by the way, did we set the group for that material?

Zero two Coffee beans 14 Go to views Select Chicago Plant.

And the group that we have configured 30 days is make to stock production.

Ten.

Right.

There you go.

We changed the group.

Now when you run based on net planning horizon, although the planning horizon is set at 100 days,

the planned level.

Chicago one.

We have overridden that at the material level using the group.

So let's run this.

Hit enter.

It might be this one.

Now let's go to zero four and look at the stock requirement list and what are the requirements that

were acted upon.

You see, only one purchase requisition was created.

The rest of the requirements were left as is.

If you want to contrast this.

To the previous material.

13, which was again based on the planning horizon, but run.

Based off of the plant's planning horizon.

Three requirements were being converted or four requirements were being converted.

In this case, only one.

And if you look at coffee Beans 12, which was based on the entire list of requirements, not all of

them would have been converted.

You want to see that slash zero for.

And this is tell.

See that?

All of the requirements are converted.

In this case, only three months or only 100 days of requirements were converted either to planned order

or purchase requisition.

In this case, only one.

Why?

Because when we ran with net, when we ran with net, all the requirements were being acted upon.

So all the requirements were being converted to either purchase, requisition or planned order.

But when we ran it with net pl it looked at the planning horizon.

First it looked at the planning horizon of the plant.

It was set to 100 days.

Okay.

It converted requirements or looked into requirements only for 100 days.

But for a particular material, we have set the group to 30 days.

Of planning.

And when we ran again with net.

Because the group is set to 30 days of planning.

It's only planned for 30 days.


