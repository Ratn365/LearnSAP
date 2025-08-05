 
Transcript
In this section.

We will talk about valuation.

And.

Split valuation.

Before we talk about split valuation, we will revisit some of the topics in valuation.

So what is valuation?

We have seen what valuation is.

In one of the previous chapters when we discussed moving average price and how is moving average price

computed.

So what is valuation?

Valuation of stock is just looking at how much stock you have and how much is it worth.

You're specifically not looking at the quantity, but you're looking at the value.

See, for example.

I have.

Hundred pounds.

Of copy.

And it's worth, say, 100.

Dollars.

Now, where is this £100 of coffee?

Say out of £100.

I have.

£80 in Chicago.

And.

£20.

In San Francisco.

Now, the value of the goods in the Chicago plant is.

At a value of $10 per pound.

That is 880 multiplied by.

Ten and say the Chicago plant.

The valuation is.

At $11 per pound.

That comes to.

$220.

Right.

So the total is 1100 or $1120 or total is $1,020.

Now, let me put a question here.

In Chicago.

The plant.

Chicago.

There are multiple storage locations, right?

Like coffee.

Raw materials.

Finished goods.

Baked goods.

So on and so forth.

Well, technically, you can store coffee in any of the storage locations.

Now, can you have a price of dollar ten here at this storage location and value coffee as dollar 11

in the raw storage location?

Is that possible?

No, this is not possible.

Meaning?

Valuation, meaning maintaining a value per pound or per piece or whatever the unit quantity is.

At the storage location is not possible.

The lowest level at which you can maintain a unit price or unit cost rather.

For material is at the plant level.

And not at the storage location level.

Okay.

This is an important concept that you gotta drill into your mind.

Valuation is not possible at the storage location level.

The lowest org unit at which you can do valuation is the plant.

However, at the storage location level.

You can maintain quantities, meaning there is £100 of coffee here, £20 of coffee here.

That differentiation can be done at the storage location level.

But valuation or maintaining a unit value cannot be done at the storage location level.

And when I say valuation, I'm using two words here valuation and unit price.

This is where some of you might be confused.

Valuation.

Unit price or cost.

Valuation versus unit cost.

What is the difference?

What am I trying to get at?

The reason why I mention these two terms is the word valuation can sometimes cause confusion.

Meaning?

I'm saying that in the Chicago plant I have dollar 1000.

Worth of goods.

But I'm saying I would not be able to tell you.

That the coffee storage location has $800 worth of goods and raw material has $200 worth of goods.

It looks a little bit odd, isn't it?

You know the quantity.

You know the price.

Why don't you just multiply that by the price and get a valuation of the storage location level?

You could.

You could, definitely.

But you cannot maintain a different unit cost at the storage location level.

You cannot have $1.10 here per pound and you cannot have $1.11 here per pound.

However, the San Francisco plant, you could say that the unit cost is dollar 12 and the unit cost

here is, say, dollar ten.

Maintaining a unit cost at a plant level is possible, but at the storage location is not possible.

But like I said, you could multiply the quantity with the unit cost and then arrive at the valuation,

even at the storage location level, no problem.

But you cannot maintain a separate valuation.

And when mean valuation, a separate unit cost at the storage location level does not support that.

Now.

Do we need to maintain a unit cost at the plant level?

Well, for the most part, it is done at the plant level.

But if you don't want to do it, you don't need to.

You could maintain a unit price directly at the company code level.

But since manufacturing happens at the plant level by default, most companies maintain valuation at

the plant level.

If you want to switch between maintaining plants at the company code level versus the plant level.

You can just go to this transaction.

Oh x 14.

And set the valuation either at the plant level or at the company code level.

And this is only set once at the beginning of the project and you never change it.

As you can see, this message, the valuation area cannot be maintained.

It's already defined.

You cannot change it.

Now.

Okay.

And like I said, most of the time it is always set at the plant level.

Now, the next question is where is this valuation data stored?

Okay, the valuation at $10 and £100 is $1,000.

Right.

Quantity multiplied by the unit price.

Or in San Francisco, it's $12 multiplied by whatever quantity in there.

Where is this valuation data stored?

This is stored at an aggregate level in a g l account.

To which account and what is the account?

Gmail account is basically an account.

Similar to a bank account.

Internally, you have a number of accounts.

GL stands for General Ledger.

General Ledger.

Now, we don't need to go into the details of what a general ledger is and which account.

But based off of the valuation class, if you go to zero three.

M03.

Enter coffee beans.

Select the accounting view.

And enter the plant.

Chicago one.

Easy evaluation class here, right?

The valuation class along with a different set of parameters.

Determine a GL account.

Which is an account.

This is just a fancy word for an account.

An account where we store the value of the total amount of goods.

Now, how do I know what the account is?

Well, in another lecture, we'll talk about how we arrive at the account, but for now, what we are

going to do.

Using what is called as account determination or material account determination.

But for now, what we are going to do is we are going to create a PO and then do a goods receipt and

look at the goods receipt accounting document and see which account is being hit.

Well, let's find out.

Let's go create a purchase order 21 and.

Take the pill.

Go to my go and do a goods receipt against that.

And we want to take that goods into the coffee storage location.

Click item.

Okay.

And then save.

Pick up the material document.

Go open the material document.

Zero three.

Hit enter.

And go to the accounting documents.

Double click.

Accounting document.

And this account right here where you see inventory for raw materials or finished goods.

This account right here, 300000 is the account valuation is stored.

Okay.

The the account.

For raw materials.

Coffee is 300000.

I'm saying this is the account where the valuation data.

Is stored.

This account is also called as a GL account.

But for now, don't worry about the word GL, it's just an account.

So the question now is what is the total value of material?

Coffee?

Zero one.

We said that it stored in this account.

Right?

The valuation data for a material, which is basically how much or how much worth of goods that we have.

Of a particular material is stored in that account.

Okay.

So how do we see that?

Go to the transaction.

F.

S ten n.

Okay.

Put that.

Gmail account.

And there.

Okay.

Hit.

Execute.

And if you look at the cumulative balances, the balance is 6755.

Now, remember, this is not just for coffee.

Any material that has a raw material as the type and valuation class as 3000 goes and sits in this account.

This is basically accumulation of the value of all the raw materials in company code.

US zero one.

It's 6755.

So the total value of raw materials is $6,755.

If you want to see the breakup by plant.

So how much value of stock is there in a particular plant?

You can go to zero three.

For that material, Say coffee beans.

Go to accounting view, select your plant, say Chicago one.

And this is the total value 1100.

So this account that this material is related to.

Contains a summation.

All the value of all the raw materials.

Now 300,000 for raw materials, maybe another number for finished goods.

But that count is going to contain the summation of value for all the raw materials.

Now, if you want to go view the value material by material, you can just go open M03.

Select the material.

Say coffee.

Go to accounting view.

And go to total value.

And this, when you select the accounting view is by plant.

So by plant, you know, what's the total value, say $1100 or $2300.

So if you want to know the value of all the raw materials, you can directly go to the account.

If you want to understand the value at the plant level, you can go to the material master, select

the plant and find out what's the total value in the accounting view.


