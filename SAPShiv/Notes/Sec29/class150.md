 
Transcript
So let's go create a material right and see how to create a material to follow a forecast based model.

So go to zero one.

MM01.

And say.

Coffee beans say 12.

And this is going to be a raw material.

All right.

Enter.

Select your basic view.

Purchasing one, two and accounting.

And because we are trying to forecast.

You might also want a forecasting view, right?

So select all of that and select Chicago one and storage location as coffee.

All right.

This is for forecasting.

The basic unit of measure is pound, and the material group is 015.

Purchase Group 001.

Type.

So this is where you specifically say that this material should follow this kind of model, right?

Earlier, we used a manual reorder point based planning.

Now we're going to use forecast based planning.

So select Vive.

Hit enter.

And controller 001 Lot Size x.

Mrp2.

Here you specify some data, right?

Processing time is four days and the planned delivery time is, say five days, so on and so forth.

Schedule margin key.

000.

Now forecasting.

So forecasting view is required for materials that are planned using the forecasting method.

Right.

So initialization is set to x.

That means always initialize data.

Don't just go run it without any data.

Forecasting periods 12 periods per season.

We going by the month.

You don't need to always go by the month.

You can go.

With different criteria.

And if you want to further slice and dice your months into, say, 24, you want to plan fortnightly.

You could do that.

Here you could specify consumption values.

So period indicator indicates how you're going to plan this material.

Are you planning every month?

Are you planning every day?

Are you planning every week?

So for materials with very high turnover, you could plan weekly for materials.

With even high turnover, you could plan daily.

Typically for materials like coffee, you tend to go weekly.

Right For now, just make it simple.

Let's go with monthly.

Right.

And then forecasting periods is 12.

So for every year we're going to have 12 periods.

If you want to plan by the week, you could specify the period indicator as week and forecasting periods

as so many weeks, say 52 weeks per annum.

And you specify consumption values.

Because we are creating the material brand new here and we want it to follow a forecasting pattern.

We are specifying all the 12 months of consumption.

Now, this is a new material, right?

How do you know?

12 months of consumption.

You really don't know.

But you want the system to forecast consumption based on 12 periods.

Typically this is done when you're migrating to sap from a non SAP system.

So you know that there is a historical consumption in the old system.

Old ERP.

And now you're migrating to SAP and you are going to manually enter the forecasting data.

So the total consumption in 11 2016 is so much in ten.

2016 is so much right.

Say this is ten.

Now we are here.

11 2016.

November of 2016.

And we are putting the consumption for ten periods here.

12 periods.

Let's even do it for 12 2015.

110.

Okay.

Hit.

Enter.

Go back to the main data and keep going.

And what's the model that we want to do?

Let's say we want a seasonal model.

Okay, because we have 12 months of data and let's assume that this follows a seasonal model or seasonal

demand.

Let's do a seasonal model.

Okay, check the number of periods per season.

Default is 12.

I think we already have 12 so we can execute a forecast if necessary.

All right.

So this is how we execute a forecast.

So the forecast.

Is from 11 2016, which is this month to ten, 2017, and the historic data is from 12 2015.

To ten, 2016.

So the history data is 12 months until now and the forecast data is 12 months from now into the future.

Right.

And we are following a seasonal model.

Click on forecast and then there are some adjustments that can be done, like alpha adjustments, gamma

factors, so on and so forth.

We don't care about all that stuff.

You know, it's typically the domain of the person.

Now, it says historical period, 11 periods smaller than one seasonal cycle.

So it doesn't have one period.

It's short of one period.

So what we can do is go back.

And in consumption.

Go.

Put in.

The extra period.

All right.

Now it has all the tall periods.

Let's see what happens and how the forecast is run.

So SAP has calculated that the future requirements is starting from this month.

Next month.

Next month.

Now, this is November 2016 and then SAP has calculated the future requirements.

So the original value is so much corrected, value is so much, you could manually correct it.

Like you could say, this is 110, not 120 for this month, right?

So this is the seasonality correction.

So based on the season, it has upped or brought down the consumption, right.

Save and keep going.

Accounting.

This is.

Raw materials procured.

So 3000 is the valuation class.

And we don't want standard, but we want moving average.

Tour and save.

So coffee beans.

toiLe is created.

And so here is what has happened.

We have created coffee beans.

12.

As a new material.

And let's say we have simulated a consumption of 12 months.

So we are in November 2016.

And we want to know the consumption for.

12 periods into the future.

And that should be based on historic consumption.

Historic consumption.

So we have simulated consumption.

For 12 periods.

Because remember.

For some type of forecast models, we need 12 months of consumption.

So we have simulated 12 months of consumption.

And SAP has predicted this is all prediction.

Based on what?

Based on.

Seasonal model.

You could have selected other models like a trend model or a constant model.

But in this case, because we want to simulate 12 periods and the seasonal model requires 12 periods.

SAP has now predicted that coffee beans are required in, say, £100, £120, £110, so on and so forth.

12 months into the future, based on the seasonal model and.

And we created the material.

The type.

Is we.

We.

And then the forecasting tab.

We set to initialize.

Consumption.

And we have simulated consumption, meaning we have assumed that, you know, last month we required

so much, the previous month we required so much so on and so forth.

And we set the period.

To em monthly and we said we're going to simulate 12 months of data because seasonal model requires

12 months of data.

And we said we are going to choose seasonal model to forecast this material because assuming that this

type of coffee beans go with a seasonal model.

And once that is set.

Execute forecast.

And once the forecast was executed, it predicted consumption, like I said, for the next 12 months,

and that was stored in the materials consumption data.

Right now, predicting consumption is one thing and taking action on that is another thing.

Now the material has consumption values both past and prediction into the future.

That means this prediction has to be acted upon.

So SAP says that in December 2016, which is next month, it requires £120 of coffee.

And that's all it said during the forecast.

Now it's up to the duty of the controller or the planner to ensure that £120 of coffee beans is available

in December.

How do you do that?

You got to either produce or procure.

In case of coffee.

We don't produce coffee beans.

We procure coffee beans.

So we have to create a purchase requisition or a purchase order.

And do you have to create it manually?

Of course not.

You can go.

Run.

Executing a forecast.

So if I go to zero three.

Select forecasting.

Select my plant.

And when I clicked on execute forecast button here let me go to zero to.

Change.

Forecasting view.

Chicago.

Execute forecast.

When you say that, it's almost equivalent to running a.

You don't have to explicitly run when you do execute forecast.

You can also go to zero three run MRP or this is a shortcut.

So when you execute an generates requirements or acts on requirements.

Right.

So that means we have already executed the forecast.

The forecast values are so much like £100, £200 per month into the future.

Right.

This is all in the future.

2016.

2017.

So that means that there should be entries like that in MRP or m04, Right.

So if you go to MD zero four, what do you expect to see there?

If he has run for a material, will generate either planned orders or purchase requisitions.

Right.

So SAP has predicted that it requires £100 next month, £120 the next month.

Those should be created as.

MRP elements in zero.

Now that we have executed the forecast.

What we have to do is we have to run.

But before you run, let me show you what forecasting has done.

So if you go to Md0 for the requirement list.

Enter that material.

You see these entries?

And this cannot be acted upon yet.

So, for example, if you select that, you can't take any action on it.

This is just more or less an FYI for the planner.

So executing the forecast does not mean that has been run has not been run yet.

So when you execute the forecast, SAP has predicted some data, but it did not act on it.

Somebody has to act on it.

The planner has to go and act on those requirements.

And how do you act on requirements?

You run.

How do you run?

Zero three?

Select your material and click okay.

Okay.

An has been run.

Now let's go back to zero for the stock requirement list.

Put that material in there.

And what happens?

For against this requirement, SAP has generated a purchase requisition.

Purchase requisition because this material is externally procured.

Right.

And you see.

This is the only element against which purchase requisition has been created.

For the rest of the requirements.

Only planned orders have been created.

Right.

So planned orders are one step behind.

Purchase requisition is one step ahead.

So planned order can be converted to a purchase requisition if required.

But we don't need so much of coffee into the future.

Right?

That's for the next month, for period, February for period.

January of the next year.

We don't need all that coffee right now.

So SAP has generated planned orders and kept it like that now.

So it also gives an indication to the planner that you don't need to convert it yet.

But this one purchase requisition is right away because we need it next month.

We need it on November.

So you can convert that into a purchase order and the purchase order can be procured, stocked and goods

made available.

This is forecasting.


