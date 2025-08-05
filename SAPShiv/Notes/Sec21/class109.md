 
Transcript
Now, another interesting factor here is something called as consumption.

Okay.

I want to talk about consumption in the context of scrapping.

Consumption.

Consumption.

What is consumption?

Consumption is how much goods has been consumed.

ASAP keeps track of that.

How much goods have been consumed?

Similar to the way SAP tracks how much goods have been produced or how much goods have been stored in

the storage location.

All of these aggregates I'm calling them aggregates because those are numbers that keep accumulating

over a number of transactions.

If you go to me and say that there are £100.

So that 100 could have been got over there through any number of transactions, like five purchase orders.

Each £20 would have accumulated to 100.

That accumulation is what I'm calling as aggregation.

So SAP keeps having these aggregates stock is one example of aggregate.

Similarly, consumption is another example of aggregate.

So when you look at consumption.

Scrap is not an example of consumption.

Well, what do I mean by that?

When you sell goods to the customer, say coffee.

That is consumption.

When you use coffee for internal consumption and make rather let me put it this way.

When you use coffee beans for internal consumption, prepare a latte.

Give it to your customer.

That's also called as consumption.

So whether you sell it to a customer or use it to make or manufacture something else.

Those are examples of consumption.

There are more examples that we'll see later.

Scrapping is not an example of consumption because it's just being wasted.

It's not consumed.

But where do you see consumption to start with?

Go to the material master.

Slash N03.

Put your coffee beans or any material.

Okay.

Enter general plant surge location data and we're talking about Chicago plant and coffee beans, storage

location.

And go to additional data.

And you should see a tab called consumption now.

You'll only see the consumption tab when you specify the plant and storage location.

If you don't specify those org elements, you don't see the consumption tab.

So if you just go to zero one or try to open up consumption from the additional data, you won't see

consumption.

Consumption will only be available as a tab in additional data if you specify the plant and storage

location.

All right.

So what do we see here?

Total consumption, corrected value, blah, blah, blah.

I'm interested in this column.

Consumption.

Total consumption.

And the other column is period.

So the aggregation or calculation that SAP is doing is by period.

So it's saying that in October 10th is October, right?

10th month in October 2016.

The total consumption is £125.

That could have been consumed over a number of transactions.

This 125 over here could be a result of.

Five different customer transactions.

£60 could have been sold to a customer.

£60 would have been consumed for making coffee by the barista.

And another £5 could be used for a birthday party.

These are all examples of consumption and SAP tracks consumption by period.

So in the 10th month it has consumed £125.

But when I scrapped £100 of coffee, I said SAP should not deem it as consumption because it's not really

consumption.

Now why am I so worried about deeming it as consumption or not?

You know, that's probably a more important question.

And why is consumption important?

Okay.

We consume £125 in October.

What's the big deal?

Well, the big deal is that that consumption is an important parameter for planning.

What planning?

Well, in the month of October, we consumed £125.

In the month of November, we might consume around the same amount or a little bit more.

Maybe it's Thanksgiving, so you might consume 10 or £50 more.

Right.

So consumption in any given period is a very valuable indicator of how much we might consume in the

next quarter, next month, next year, we could accumulate that.

So consumption, like I said, is a very important parameter.

In calculating future usage.

Think of Apple.

Apple released a new product iPhone.

Some version now in the first month.

How many iPhones should it manufacturer?

It will typically base it off of previous releases, first month production.

Right.

And then, of course, it will make some marketing adjustments because last year the demand was so much.

This year the demand might be 10% more, but there should be some baseline based on which it tries to

get to a solid number and then do some adjustments off of that.

And that is based on consumption.

Another example.

I have a restaurant.

Say I sold 100 Biriyanis today.

Tomorrow.

How many biryani should I sell?

Well, that depends on the customers.

But how many biryani should I keep ready?

Well, I based it off of my yesterday's consumption.

Right.

Otherwise, I wouldn't have a clue how many I should make.

So consumption is a very important parameter, and SAP very rightly keeps track of that and it does

that by period.

So in this period, this is the aggregate consumption.

When I mean aggregate, just think of totals.

This is the total consumption aggregate is a word that's used these days in the context of Hana.

But bottom line is aggregate means total.

So SAP does calculate aggregations and consumption is a very important parameter.

Okay, now.

When we receive goods from a purchase order.

You update the stock?

When you issue goods to a customer or for your barista to make coffee.

That's called consumption.

So consumption is updated.

Now, of course, stock is also removed and updated, but consumption is another parameter that's updated.

Where is the configuration for that?

In many places like material type, right?

We have seen that the material type has a quantity upgrade value update.

That's one parameter.

Another parameter is the movement type.

If I use a particular movement type, should I update the quantity or value?

That's a piece of configuration.

Let's go to the movement type.

Oh, MJ.

Right select movement type.

And we want to check, let's say, movement type 101.

Right.

That's a standard movement type when you receive goods against a purchase order and.

If you go to update control there, you will see value upgrade versus quantity upgrade.

Value update versus quantity update.

That means that 101 does value update.

Yes or no or quantity update, yes or no for a particular movement and a.

Now, these two columns control whether value updates and quantity updates happen.

And this column over here.

CNS.

CNS stands for consumption.

This column over here says whether consumption should be updated or not.

So there are different values for it.

A blank means that there is no consumption.

Right?

V means it's consumption.

E means it's consumption against an asset, against a sales order or so on and so forth.

But a blank value here means that there is no consumption.

So here is the row that corresponds to a goods receipt done against a PO.

So we have value update.

So when goods receipt is done against a PO.

Meaning if you order £100 of coffee from vendor 4001 and when it's time to do the goods receipt, you

use movement type 101 and when you use that, value is updated and quantity is updated.

Now why am I only specifically selecting that row?

Not so many other rows?

Well, this is a relevant row.

And I know that because.

What is the movement here?

It's B.

What does B stand for?

B.

Stands for goods movement for purchase order.

And that's what we're trying to do.

Right.

101 is goods movement against a purchase order.

So select B, and I know that that's the row for purchase order.

And what kind of a receipt is that?

Is it a stock transfer order or is it a regular PO?

A blank means it's a normal receipt and X means it's an Sto.

Well, we are not talking about an Sto now.

We're talking about a regular goods receipt, so it's blank and.

What's the consumption?

Consumption is blank.

That means there is no consumption.

Is it fair?

Is it correct?

When you receive goods against a purchase order, do you increase the stock?

Yes, we increase the stock.

This check mark says that it increases the stock and this check mark says that the value is also increased,

meaning the corresponding account is updated.

Be.

Says that it's a purchase order.

Blank says that it's a normal.

And a blank over here means that there is no consumption.

Well, do we need to update consumption?

No, it's not a consumption.

Right.

We are receiving the goods.

No need to update consumption.

Right?

So when you're trying to do a goods receipt, normal goods receipt, not a stock transport order.

Consumption is not updated.

Well, that's expected, right?

When is it updated?

Typically in case of issues.

A simple example of an issue could be 201.

Consumption against a cost center.

The HR department wants some papers, they're consuming papers or somebody in the company wants to purchase

coffee from our own shop.

That's an example of internal consumption.

Right.

Maybe we want to give some coffee for free.

So £100 of coffee is being withdrawn to be distributed to the employees.

£1 each or £10 each.

That is an example of internal consumption.

What's the movement type for that?

201.

So let's go back.

And select.

Go back to OMG, and if you look at material types like 543 goods issue sales order stock, you see

that there is a consumption posting.

In this case, the consumption posting is G.

What does G stand for?

Planned withdrawal.

If it is blank.

Then there is no consumption.

If it is G.

Then there is consumption.

So consumption account is updated.

Typically in case of issues where we are issuing stock to an asset, where we are issuing stock to a

project or to a customer.

So wherever you see a blank, that means that for that particular movement type.

Consumption is not updated, so.

551.

Is an example of goods movement, in this case scrapping where the consumption is not updated.

And why is it not updated?

Because it's not really consumption.

It's scrapping where we're not consuming, but we're just wasting it away.

And now if you look at 201 goods issue for Cost Center, you can see that there is a consumption here.

Consumption is of type R.

What does R stand for?

R is planned or unplanned with reference to a reservation.

Well, it could be with reference to a reservation or without reference to a reservation.

But the bottom line is when you are consuming it internally, still it is consumption.

So essentially I'm trying to harp around the point of consumption.

Some movement types induce consumption and some movement types do not.

And how do you know which movement type induces consumption and which movement type does not?

So if you go to OMG movement type configuration, every movement type is associated either with no consumption

or with some kind of consumption.

So scrapping using movement type 551 does not do consumption.

Now you understand what is consumption?

Why certain types of transactions induce consumption and why sometimes they don't.

And what are the parameters that control consumption movement type.

Okay.

That's example of sampling and scrapping.


