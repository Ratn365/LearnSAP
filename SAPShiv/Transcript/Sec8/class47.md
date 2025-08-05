 
 previous videos we have seen.

Vendor, Master and Material master.

And we said that not all vendors supply all the materials.

So some vendors supply some materials and some other vendors supply other materials.

So where is the relationship between the vendor and material documented?

So if I want to know.

Who can supply whole wheat flour.

I need to be able to understand that it's this vendor and maybe this vendor.

All right.

I need that information handy.

And how much is it going to cost for this vendor versus this vendor?

So the relationship between materials and vendors is created in what's called as a purchasing info record

or info record for short.

So what kind of data is available in an info record?

Let's go create one.

So go back.

So where is the info record?

So we go to logistics, material management, purchasing, and then go to master data.

Go to info record.

And there you have.

M11, M11 1213 So go to create mode M11.

Put you vendor for zero zero 3 or 4 001.

And don't worry about entering the plant for now.

I'll tell you why you need to enter a plant a little bit later.

So select coffee beans.

Hit Enter and Info record has also a bunch of screens.

It has purchasing related data, general data, text, so on and so forth.

Again, not all fields are important at this point, and for now here are some of the important fields.

Planned delivery time.

This tells you how long it takes for this vendor to supply this material.

This tells you how long it takes for the vendor to supply this material.

Say this vendor takes.

Say this vendor takes ten days to supply coffee beans.

And then what's the typical standard quantity?

Do we order £100?

Do we order £10?

Do we order £50?

And then there could be a minimum order quantity.

So some vendors don't take orders below a certain number just for convenience reasons.

So the minimum order quantity is, say, £20.

So the standard order quantity is 100.

And minimum order quantity is 20.

And then we have delivery tolerances.

Important fields.

But we're not going to touch about them now.

But we're not going to touch them now.

And the net price.

What's the net price?

$10 per pound and a purchasing group of us one hit enter.

Hit.

Enter.

Hit.

Enter again.

And here you can put in some text.

Now, I'm not going to bother about this text now, but we're going to revisit this when we cover text

determination in a later chapter.

Enter.

And save.

So for 4003 vendor for coffee beans, we have created a record.

Let's go create a purchase order now.

M e 21 n.

For vendor 4003.

Put the material coffee beans and enter £10.

In Plant Chicago.

One first thing that you see, order quantity is below £20.

Remember, we have entered the minimum order quantity as 20.

So it's giving us a warning.

It's a warning.

So you can hit, enter and let it go away.

All right.

The next thing.

Today's date is 22nd April 2016.

And what's the delivery date?

May 2nd, 2016.

So the system has added ten days to April 22nd and that comes to May 2nd and set that as a delivery

date.

The date on which we can receive the goods.

Why?

Because we have set the number of days for delivery as ten days for this vendor and material combination.

So as SAP takes the number of days from the info record.

Adds it to the current date and puts them in the delivery date field.

And $10.

Who specified that for this vendor and coffee beans, the price is $10.

We did it when we created the purchase info record.

So what's an info record?

Info Record ties the material to the vendor.

Why do you create info record?

We create info records so that at any given point in time we know what a vendor can supply.

Or we also know who can supply a particular material.

What are the details that go into it?

So for a particular purchasing org, you can even narrow down it by plant if you want, but you don't

need to.

You specify how long it takes for the vendor to deliver that particular material.

So you call them and ask them how long it takes, he says.

Five days.

You put five there, you put the purchase org, and you also put the standard quantity.

Standard quantity does not really have a lot of functionality, but minimum quantity can be used to

give a warning if at all.

The vendor requires us to procure in a certain minimum lot and then you put a price $2, $5, $10,

whatever that material costs from that vendor.

And if you look at the price.

You see a two followed by a comma, followed by five.

Right?

So the intention there is 2.50, but it shows it as a comma.

If you want to try it, go to M11 this time.

Let's do it for vendor 4001.

Hit enter.

And so if you say to.

So if you put in $2, the system automatically takes it as 2.00.

But sometimes you could see it as two comma zero zero, like how it shows here.

The reason is not all countries, unfortunately, specify decimals as with a dot.

Some countries do it with a comma.

So in order to account for that, SAP has specified a something called as a user profile.

So go back.

No.

Go to SU3.

That's a transaction to check your own user profile so it's dependent on the user.

So the user is in Germany and his profile is set to German profile.

He can have a comma in place of decimals.

Hit enter.

And this is my profile.

And if I go to defaults.

This specifies what my decimal notation is, so it's the same number behind the scenes.

But when it shows that to me, if my decimal notation is come up with dots, it shows it like this.

But if it if it's commas in place of dots, it shows it like this.

So you can choose it either way you want.

Try it with different possible combinations so you'll understand what I mean by decimal notation.

So that's user profile.

Transaction code for this is ESU three.

So we have seen that the delivery date.

Comes from here.

And we have seen that the price comes from here and we have seen that the price.

Comes from here.

So let's look at the purchase order once again.

A purchase order has a header.

And then line items.

Most of the data.

In the header.

Comes from the vendor and most of the data in the line items come from material.

Now this is very important.

So any time you look at a piece of data, say you saw this unit of measure and want to understand where

this came from, follow the thumb rule.

Anything from the header comes from the vendor.

Anything at the line item.

This is a line item field.

It comes from the material master.

The reason why I mention this is because you can't really understand the source of all the different

fields in the purchase order.

There are hundreds of fields in the purchase order and you can't possibly know what each field is and

what's the source of it.

Just remember the thumb rule header from the vendor line items from the material.

So any time in the future, if you have a question on a particular field, just check yourself.

Is it in the header or line item?

If it is in the header, this field should come from the vendor master.

So go check the vendor.

If it's a line item, go to the material master.