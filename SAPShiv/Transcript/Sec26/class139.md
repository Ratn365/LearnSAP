 
Transcript
In this section, we will talk about negative stock.

What is negative stock?

Let me give you a scenario from our coffee shop.

So imagine a bag of coffee.

Okay.

This is £100.

Let's say dark roast Arabica organic coffee used for internal consumption.

And the cost of that coffee is $1.10 per pound.

Now the same kind of coffee.

Is also used to sell in retail in smaller bags, say, £1 bag or £2 bags.

For retail consumption.

So this is internal.

This is retail.

And the price for retail is $1.20.

Per pound.

So these are the bags that you put on the shelf for retail consumption.

So suddenly there is an order for ten.

£1 bags.

So that's like $200, right?

But say these £1 bags are gone already, so there is no stock.

But there is an order for ten £1 retail bags.

What do you do?

Well, we have the same coffee here.

At the back of our store.

£100 of coffee.

And we have these bags.

Empty bags laying around so you can just fill in some coffee from here.

Make 10 or £21 bags and then ship them or give them over the counter.

Right.

It's that simple.

Just make these bags on the fly from the wholesale stock and sell the retail bags.

Well, here's the deal.

Before you sell them, you have to put them in stock, meaning you create these bags.

And put them in stock using my go.

And then using your sales order or whatever front end mechanism, do a good issue to the customer.

And before you do that you have to do a GR or goods receipt into the warehouse.

You can only sell goods that you have in the warehouse.

Right.

So this step.

If not done.

And when you're trying to do a good issue and document that there is a sale of ten bags of £1 coffee,

the system will say, I don't have stock.

Right.

But sometimes this step over here.

Cannot be done at that point in time for a variety of reasons.

For example, the store's clerk who is supposed to do all this.

GR He's out, right?

And nobody else has the authorization.

Not everybody can do anything, right?

So he doesn't have the authorization to do a GR.

In which case he cannot input the stock.

And then of course, he cannot sell the stock because System thinks that there is no stock.

Or there is no manpower.

To do any of this stuff.

Or there's no time.

So due to a variety of factors, it's sometimes not possible that you do a good spreadsheet, but you

know that there is physical stock.

There restock, but you just have not done the goods receipt.

So you can just sell it to the customer because you have physical stock.

And later you can do a goods receipt.

But the system does not allow it because when you do a good issue to the customer.

System says that there is no stock, but there is physical stock.

So this is the catch 22 situation that the negative stock solves.

If you enable negative stock.

For a product, then you can do a good scishow.

Irrespective of your stock in hand.

So let me formalize this.

Any time there is physical inventory.

But the book inventory or what thinks the inventory is is less than physical inventory.

So that is physical inventory, meaning there are coffee bags.

We know that there are coffee bags.

But the system does not have a record that it has the coffee bags.

And like I said, it could happen because of a variety of reasons.

Most of the time it's lack of human availability.

Example, according to the book inventory, there is zero kilos or £0 of coffee bags, retail coffee

bags.

But according to the physical inventory, meaning we know that there are ten £1 bags.

So this is physical.

This is book.

It just means that these £10 have not been geared or goods received yet.

We have not had the time to do the goods receipt.

But the customer is waiting.

In which case you don't want to tell the customer that.

Hey, you know what?

Wait for our goods to happen.

He doesn't care.

So you just service your customer first and then later do a good receipt.

And in order for that to happen, you have to enable negative stock.

Let's see an example.

Okay.

Okay, so let's go to zero one.

Create coffee beans oh seven this time and let's make it still raw material.

Okay, so all we have to do is basic data purchasing and accounting.

Right?

Select that and we want to do it for the Chicago plant.

So select Chicago and then say coffee beans.

Dark roast Arabica.

Whatever.

And this is pounds and some material group.

Purchasing view.

You enter a purchasing group and in the accounting view.

Into the valuation class.

Make it as moving average.

Save it.

Enter and your coffee beans Dash zero seven should be ready.

All right.

Now what we're going to do is let's check the stock.

What's the stock of coffee beans?

Zero seven in the Chicago plant?

Zero.

Nothing right now.

Let's do a good issue.

Okay?

Let's say against a cost center.

It could be against a customer cost center.

Anything.

Doesn't matter.

We are doing a good issue.

Instead of a goods receipt, we want to do a goods issue.

Again, not against the purchase order against other.

Okay.

So what's the material?

Coffee beans.

Oh seven.

And quantity is ten.

And where 201 good sushi for a cost center from the Chicago plant and from the coffee storage location.

And the account assignment is.

Whatever cost center.

This is the cost center that's going to eat the cost of goods issue.

An item.

Okay.

Do a check.

So material does not exist in the storage location.

Right.

So that means that the storage location view is not there for that material.

So go to zero one.

Select coffee Beans.

Oh seven.

Select storage location.

All right.

And then select Chicago one and coffee beans, storage location.

Well, we don't care much about any of the stuff here.

And save it.

Okay.

Now do, amigo.

Goods issue of Coffee Beans.

Oh seven.

£10.

From the Chicago plant and from the coffee bean storage location associated with that plant.

Against the cost center admin, make sure item is clicked on and click check Deficit of Storage Location

Unrestricted use £10.

That means the system is saying we cannot do a good issue because you don't have £10.

We just checked it and that's real.

We don't have £10 in.

Right?

We know that this is a physical order.

It just has not been goods received yet.

The ideal situation would be to go here, do a good receipt for this material and for whatever quantity

you want to do goods receipt, either against a PO or without a PO, and that will put stock in.

And now you can do a goods issue.

But like I said, if we do not have the manpower to do a goods receipt at that point in time we can

directly do a goods issue because we know that goods already exist physically.

All right.

So in order for that to happen, we have to do a setting on the material master.

So go to M0 to select coffee beans and select storage location.

Go to Chicago one and storage location.

Coffee.

Go to storage location to view and enable negative stocks and plant.

So remember, this is enabled at the plant and storage location level, so it need not be enabled all

the time for a material at the plant and storage location level, you can enable negative stocks.

Okay, now let's do a major and see if we can really issue goods when there are no goods according to

the book inventory.

So select coffee beans oh seven.

Quantity of £10.

And of course, from the Chicago plant and coffee beans storage location from the cost center admin.

Now, let's check this again.

What does it say?

Deficit of unrestricted use, £10, blah, blah, blah.

Still, it does not work.

Why?

Because it's not just enough that you enable negative stocks, the material level.

You have to also do a setting at the plant and storage location level.

Where do you do that?

Of course, in Sbarro.

So go to Sbarro.

SPRO.

IMG.

Go to material management.

Go to inventory management.

And go to.

I think it's goods issues.

Okay.

Allow negative stocks.

This is the configuration where you have to enable negative stocks at the plant level and specifically

at the storage location level.

So we're interested in Chicago, so.

If it were not checked on, just go and check it on.

Okay, I've checked this on to test how it works, but if it's not checked on for your plant, go and

enable that.

Now, underneath that for the Chicago plant.

Don't worry about these settings.

These are special settings only for special stocks like consignment pipeline.

Project stock, so on and so forth.

If you want to generally enable it, go to the storage location for coffee and check negative stocks

on and ensure you save your settings.

So you have enabled this negative stock at the storage location and the plant level.

All right.

Now you should be able to do a go.

So go to coffee beans oh seven, a quantity of, say, £10.

Where?

You want to do it in the Chicago plant and coffee bean storage location against the admin cost center.

Now do a check.

You see, you get the same message.

But this time it's a warning.

And that means that you can just go ahead and do that goods issue.

Right.

So click save.

Okay, goods have been issued.

What happens to me now?

According to the book inventory, there is no stock.

But you did, amigo, and issued the goods.

What happens now?

Let's go check.

You see ten minus, that means there is a negative stock of ten.

So at a later point in time, because we have really issued goods, somebody who comes in the next morning

has to go and do a goods receipt for the ten physical quantity that we have issued without the system

knowing it as physical inventory.

This is called negative stock.

So just to summarize what we've learned.

When you know that there is physical inventory, meaning ten coffee bags lying down there.

But there is no book inventory because nobody has booked this £10 of coffee into inventory by doing

a goods receipt either because there is no manpower or there's not proper authorization for the person

at that point in time or because of some other error.

But you know that the bags exist physically.

In which case, if the customer is waiting for those £10 of coffee, you don't have to keep him waiting.

You can just issue these goods.

Using a regular goods issue or sales order stock or project stock or any kind of goods issue mechanism.

And later, when that error is corrected or the manpower has come in, you can do a phantom £10 goods

receipt, either against a PO or without a PO.

And in order to do that, there are two things that have to be done.

First thing in SPRO.

Enable negative stocks.

At plant level.

And storage location level.

You don't need to enable this for all storage locations or all for all plants.

Just for the ones that you want to enable, where you expect these scenarios to happen.

And the second thing is you have to specifically also enable this for Material master.

Material master storage location to view.

Enable negative stock.

If you do these two things, then you can do a good issue even though you don't have stock on the book

inventory.

Now, since this is a little tricky, you don't want to probably enable this for all materials, all

plants, all storage locations, because it can result in fraud issues.

So typically the warehouse manager will know for what stocks negative stocks needs to be enabled.

This is probably typically done for high volume goods where customers are waiting.

Or even for low volume goods that can be tracked where there is a sudden demand, in which case.

You can't wait for the goods receipt to happen.

Or sometimes for either for traded goods or manufactured goods.

Where you have the goods ready physically, but because of some process issues, you cannot do a goods

receipt yet.

In which case you can directly hand them over to a customer using a goods issue that allows negative

stocks.


