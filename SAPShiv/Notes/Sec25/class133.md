 
Transcript
In this section, we will talk about physical inventory.

Well, in the context of inventory management, what do you mean by physical inventory?

It's all inventory, right?

Well, physical inventory is a special term.

Used to represent the actual inventory in stock on the ground in the warehouse as opposed to.

Book inventory.

What is book inventory?

If you go to MMV, enter your material plant.

Hit.

Execute.

What do you get?

For that material, Say coffee beans.

In Chicago plant.

You have a stock of 100, £100.

What does that mean?

That means that SAP thinks that there is a stock of £100 of coffee beans in the Chicago plant.

Is there really £100 in the Chicago plant?

Most of the time, yes.

But sometimes, maybe not.

Why?

Well, there could be many reasons that we are going to discuss.

But why is it this important?

Why does SAP think that there is £100?

And if at all, there is not £100, why do we need to take care that whatever shape thinks or whatever

has in its book inventory is really corresponding to the physical inventory or the stock that's there

in the warehouse?

One of the primary reasons is availability.

Well, in the context of coffee, it might not be very relevant because out of £100, if the customer

wants £10 of coffee, you can just bag it and give it.

But think about companies like Amazon.

So there is the Chicago plant and say we are now Amazon.

And if I am the customer going to Amazon.com and placing an order for some material Amazon.

Checks for the availability.

Of that material in the stock, assuming Amazon runs SAP, which it does not.

Say, for example, I have ordered for a laptop.

And say Amazon procures it, stores it and then sells it.

And in the warehouse, there are four laptops.

And that's what is shown in.

But say, for example, one of the laptops is stolen.

So physically there are only three laptops.

But SAP thinks there are four because SAP does not know that somebody can go in and steal.

Now what?

Well, I've ordered one laptop.

There are three laptops, so it's fine.

It can still give me that laptop because availability is fine.

But what if I ordered four laptops?

In which case SAP thinks in me that there are four laptops in the warehouse.

But in actuality one was stolen and there are only three laptops.

So that means Amazon cannot fulfill my order.

And it's not correct, right?

I'll be -- off.

So availability is one of the main reasons why companies make sure that what SAP thinks is the stock

called book inventory really corresponds to physical inventory, the stock that's really there physically

in the warehouse.

The second reason why companies do it is planning can sometimes go wrong.

What is planning?

Any time goods are required to be procured or produced.

There is a process called MRP.

Material requirement planning.

Well, we have not talked about material requirements planning yet, but consider it as a magical process.

That's intelligent.

And understands when to procure a material or produce a material, when to make it available, depending

on the customer demand or internal demand.

Irrespective of MRP, every company has to plan.

The availability of goods, right.

So think of a company like Apple.

It said, releases a new iPhone.

It's got a plan for a certain number of iPhones to be produced, say a million iPhones in the first

month or 10 million iPhones in the first month.

I don't know the count, but they have a number.

This is called planning.

Irrespective of whether you are producing or procuring, everything has to be planned to make sure that

goods are available either for your customer or sometimes for internal consumption.

Meaning if you are producing a car, say Honda is producing a car and it needs tires, axles, paints.

Metal.

And it needs to plan to procure them from the vendors.

That's also called as a planning process.

So if the book inventory and the physical inventory are different, if Toyota thinks that there are

10,000 tires but there are only 8000 in stock, then there is a mismatch.

Planning can go very wrong.

You might either end up with excess inventory, which is also not good.

Or you might end up with less inventory, in which case your production line will stop.

So the planning or MRP can only be as accurate as the stock that you really have.

If SAP thinks that there is four quantity.

Then if the physical quantity is really four, there is no mismatch between the two.

Then planning can go absolutely well.

If not, then you have a problem.

And the third reason why physical inventory counting is important or a match between physical inventory

and book inventory is important is that stock goes on to.

So first was availability.

Right.

Let me just mark them first is availability, second is MRP or planning.

The third reason is stock sits on balance sheet.

What do I mean by that?

Well, every company has a profit and loss statement and a balance sheet.

A balance sheet shows the true picture of the company.

Ever since it started until today.

What is the total stock at hand?

What is the total assets?

What is the total liabilities?

And balance sheet most of the time is almost used as the basis for the stock price.

Well, there are other parameters, of course.

Hundreds of other parameters.

But a balance sheet is a primary statement based on which a company's performance is measured.

For example, Apple has 50 billion or 100 billion in cash reserves.

Well, that makes it strong, right?

The share price goes up.

Similar to cash.

The stock say, for example, Apple has 10 million iPhones lying in the warehouse and they represents

some value.

10 million iPhones at, say, $200 an iPhone, which is the cost price, let's say, is a lot of money.

And they can sell it any time.

That means.

That there is so much of cash lying in the form of stock in our warehouse and that sits on the balance

sheet.

And if you represent stock wrongly, meaning if you have 10 million, but you show 20 million.

That's cheating your customer, right?

Or that's cheating your investor.

That's not correct.

So stock always sits on your balance sheet.

And because of that, in many countries, there is always a legal regulation that forces companies to

go and physically check whether they have 10 million iPhones in stock or four laptops in stock.

And that's precisely the process that we are going to learn in this section how to physically check

the inventory and match it against the book inventory.

If there are differences, what to do with it?

So we have seen three reasons why physical inventory needs to be done.

Number one availability.

If availability goes wrong, it results in customer satisfaction issues.

Number two, planning.

If planning goes wrong other than customer satisfaction, the company's performance internally will

suffer.

Number three stock sits on the balance sheet and balance sheet is a primary document for the investor

in that company.

If somebody wants to invest money in my coffee shop.

What do they look at apart from my profit and loss statement, my other investments?

They look at my balance sheet, How much cash do I have?

How many liabilities do I have, How much assets do I have, How much stock do I have?

All of them sit on the balance sheet.

Now, if you don't understand what a balance sheet is, you don't have to.

Think of it as a statement that represents my company's assets and liabilities.

And stock is an asset and you cannot overstate your stock or understate.

So many companies.

Are forced to ensure that the stock that the represent on their balance sheet say 10 million iPhones

in my stock is really 10 million.

It's not something else.


