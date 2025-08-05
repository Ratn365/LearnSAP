 
Transcript
In this chapter, we're going to see what is called as a processing.

What is the processing key?

This is one of the parameters in MRP that dictates how far into the future we have to consider the requirements.

If you look at Mrcp run MDS zero three.

This is the processing key.

There are mainly two main parameters.

Net catch.

Net.

What is net catch?

What is net?

Net.

Versus net.

PL.

Stands for planning.

Horizon.

So net.

Is basically looking at the entire set of requirements.

Let's take an example and understand this.

If you go back and look at md0 for for coffee beans 12.

If you look at the requirements for coffee beans.

Well, something that we have done in the previous chapter.

You see, SAP has predicted requirements one year into the future.

And has acted on each and every requirement.

Every requirement has either been created as a purchase requisition or it's been created as a planned

order.

Now, this is something that's required.

If you look at current date, which is November the 7th.

Why is SAP even touching a requirement which is on the June of 2017?

That's 7 or 8 months from now.

Why is it touching that requirement?

Why does it need to bother about that requirement just because there is a plan that forecast has suggested.

Why is touching that requirement?

If I am the planner, I wouldn't want anybody to touch it.

That's eight months from now.

Why did touch it?

Or why did he touch it and convert it into a plant order?

That's because when we ran MRP, we have specified the processing key as net cash.

That means we are telling SAP to take action on all requirements irrespective of the timeline.

From today.

Look at all the requirements into the future and take action on it.

So that's why I said net.

When you run with this option, it looks at all the requirements and acts on it.

Well, it creates suggestions.

Of course it is not really act on it and create a purchase order.

Just create suggestions like either creates a purchase requisition or creates a planned order.

Of course, it's up to the discretion of the controller or the planner.

To convert it either into a purchase order or a production order.

But sometimes there are so many materials, especially in retail.

Or in trading goods.

But you don't need to run or look at requirements so far into the future.

It just causes too much work for the planner.

For example, I don't need to bother about coffee requirements six months from now.

Right.

So in cases like that, what we can do is we can run with a planning horizon.

Meaning only bother about requirements so far into the future.

It could be two months.

Three months.

Or 100 days.

30 days.

Depends on the nature of the material.

For example, coffee.

You don't need to plan coffee three months from now.

But maybe coffee machines, if you have like a thousand stores, coffee machines need to be planned

well in advance.

Why?

Because they take time.

Maybe you need to plan four months in advance or six months in advance.

Right.

So it depends on the material.

And the immediate question that you have now is where do you set the planning horizon?

Planning horizon can either be set at the plant level.

So for this plant, we don't plan 100 days ahead.

We can do that or you can set it or override it at the group level.

So this overrides.

The generic parameter, the plant level, for example.

At the plant level.

We say we don't plan 100 days ahead into the future, but group for a particular material could say

that for this material, you don't plan beyond 30 days or 60 days.

All right, let's put 60 days here.

So let's go set these parameters and I'll show you the example and contrast.

Net versus net.

So if you go back go to.

IMG.

Material management.

Consumption based planning.

Plant parameters.

And carry out overall maintenance and click on maintenance.

Select your plant.

Go maintain and look at the planning horizon.

So for Chicago, the planning horizon is set 200.

Okay.

Now, if you run with the planning horizon, will not plan beyond 100 days.

All right.

So you want to test that?

What you can do is create a material M0 one.

Call it coffee beans 13.

Okay.

And you want to copy it from coffee beans one or let's not even do it.

Let's do it from scratch.

And we want to do forecast, right, because we want to see into the future.

So select basic view one purchasing one, two forecasting accounting.

This is how we have created coffee beans 12 Right When we were testing forecasting the Chicago one and

coffee beans storage location.

So this is forecast.

Based.

On.

Hundred day planning horizon.

That's what we want to name this material.

And this is pounds.

This is some group.

Doesn't matter.

Purchasing group 001 again, doesn't matter.

MRP type.

We want to set this as V, right?

Because we want to predict.

The future consumption based on a seasonal model and the lot size is.

The controller is 001.

Enter and the processing time is three days.

The planned delivery time is five days.

Schedule margin key.

000.

All right.

And we want to set the forecast model to seasonal.

Right.

So we are saying that this material follows a seasonal trend and we're going to simulate some consumption.

Like.

So this goes into the past.

See, we started in November and it goes to October, September, August and so on.

So for this month, you specify some consumption, say 110, 100.

Uh, 130.

So this is all simulation.

This is how much we have consumed in the past month.

I'm just going to go with a constant number.

You go down.

And 105.

110 and then 105.

So we have specified some values around the 100 mark and we're going to go back and execute the forecast.

We're going to execute the forecast starting this month and 12 months into the future.

And that's going to be based on 12 months of past consumption.

Forecast.

Forecast and it has produced some forecasting.

All right.

So going forward, put an accounting view.

Set it as moving.

Average.

Save it and done.

Now, when you go to MD zero four, you'll see SAP has predicted requirements.

12 months into the future, right until this is November 2016.

And SAP has predicted the requirements until October 2017.

12 months into the future.

Now when I run MRP using net cash.

There are 12 requirements.

This is November 2016 and then December 2016, Jan 2017 all the way until October 2017.

So that is the forecast.

And when you run with net cash, it looks at all the requirements and either creates a purchase requisition

or a planned order so it acts on all the requirements.

If you have requirements three years into the future, it will act on them.

But we don't want that, right?

We only want to look at requirements for 100 days.

Three months.

Right.

So we have set the planning horizon to 100 days at the plant.

Chicago one.

Right.

That's what we have done when we went to Sbarro.

You flip the horizon to 100 days.

Now.

When we run with net pl.

It should only look at 3 or 4 requirements.

Something that spans 100 days into the future.

The rest of the requirements should be left as is.

They should not be touched.

They should not be acted upon.

Let's test that.

So go back, go to zero three.

Select your coffee beans 13 and instead of net cash net change for the total horizon.

Select net PL, which is planning for the planning horizon.

Right now, let's say, carried out.

Go back.

Go to Md0 for stock requirement list for coffee beans 13.

And you see that these requirements were not even touched.

It's only acted upon 3 or 4 different requirements, something that plants 100 days into the future.

Not beyond that.

In contrast, if you look at Md0 zero four for the material that we have done previously.

Let's say.

Right.

Coffee beans 12.

You see, SAP has created planned orders for 427 527 six 2017.

But over here for five and six are left alone.

They are not touched by MRP.

That's because we have set the planning horizon as 100 days for the plant and we have used net pl.

To run.

That means we are asking to run or act on requirements only for 100 days.

And this 100 is set in the configuration at the plant level.

It also said that using group, you can override the configuration at a material level.

You see, group is a parameter that's set at the material level, just like plant.

So in a single plant, you don't want to always plan for 100 days for every material for Chicago plant.

I need coffee, I need muffins, I need cakes, I need pastry, I need coffee machines.

I need so many things.

Maybe some materials need to be planned only for a month.

Maybe some materials need to be planned for three months.

Some material for nine months.

It depends on the nature of the material.

And if you set it at the plant level, that means you are expecting that every material should be planned

only for 100 days.

That's not correct.

Right?

So you can override at the material level using group.

So let's look at the configuration.


