 

Lecture thumbnail
0:01 / 9:27
69. What is delivery tolerance ?
Transcript
All right.

So in the previous chapter, we have seen two ways that we can block or mark that line item as complete

from a procurement perspective.

There is a third way to do it, and that is called delivery tolerance.

What is a delivery tolerance?

Where is it set and how is it used?

Let's take an example.

Say we have ordered 100 kilos of coffee in a PO.

And the vendor has delivered, say, 90 kilos.

Now ten is remaining right now for that ten kilos of coffee.

Do we really need the extra ten kilos?

Meaning for some reason the vendor has delivered only 90 kilos, maybe because he's out of stock or

whatever reason.

Now, in order to deliver the remaining ten kilos, the truck or the vendor.

Right has to make another round with just ten kilos of coffee from his warehouse to our warehouse.

Well, for some materials it might not be worth it because for ten kilos of coffee or five kilos of

coffee.

It might not be worth the effort in terms of logistics to deliver the goods.

Right.

We have seen this in Amazon for low value goods.

The freight is going to be so expensive.

In comparison to the quality of the goods.

So it does not make sense to do that extra logistic step of, you know, taking the five kilos or three

kilos or whatever the shortfall is.

Depending on the nature of the goods.

Now, if it's a coffee machine that costs like £10,000 or $10,000, it makes sense.

If you order two of them, only one of them comes in.

The next one also needs to come.

But coffee is something that we procure on a monthly basis, weekly basis, daily basis.

So if there is a shortfall of, say, ten kilos or £10, it doesn't really matter.

So depending on the type of goods.

We can say that, you know, even if you deliver by a tolerance of 5% or 10%, it doesn't matter.

That's fine.

We will deem the purchase order as complete.

You don't need to deliver the remaining.

And of course, the vendor is only going to charge for whatever he has delivered.

He's not going to charge for 100 in this case.

He's only going to charge for 90, which is fair.

Right.

Now this concept is called as a tolerance, delivery, tolerance.

There is also something called as order tolerance, but we're not going to go there.

Delivery, tolerance.

And we know that this is a property of a material meaning.

It's you cannot generalize this for every material.

Coffee has a certain tolerance.

Sugar has a certain tolerance.

Flour has a certain tolerance.

Muffins have a certain tolerance.

Coffee machine has a certain tolerance.

Pastry has a different kind of tolerance.

So naturally, where is this set?

Of course.

The material master.

So that's the first place that the system will look when it wants to look at the tolerance.

We'll see the effect of tolerance in a minute, but let's see where it is set.

So the first place where the system is going to look for tolerance is in the material master.

Material master.

Right.

So delivery tolerance is set in the material master.

So how is it set?

Let's go set it for coffee beans.

So go to M0 to.

Enter coffee.

Beans.

Enter purchasing data.

Click.

Okay.

Plant in Chicago.

And there you go.

This is where you set the tolerance.

Let me change it.

I'm not able to.

It's grayed out.

So how do you set the tolerance?

Really?

It's grayed out, right?

It's set with something called as a purchasing value key, which is an aggregator field, basically

a summarization field that has so many different values.

So it has the reminders, it has the under-delivery tolerance, it has the over delivery tolerance.

Now, we're not going to talk about reminders now, but we can check out this guy over here.

So purchasing value key to has an under delivery tolerance of 10% and an over delivery tolerance of

10%.

So select that and hit enter.

Right.

And you see that these value changes 10%, 10%.

Now, can you define your own purchasing value keys?

Yes, you can.

The reason why purchasing value keys are defined is because you don't really want different kinds of

tolerances to be set at the material master level without any kind of authorization.

You know, there should be a certain standardized way in which you set these tolerances and reminders.

So that's why it's set in configuration and you can change these things manually.

Like you can you can make it 12%.

So somebody has to go and create a purchase value key that has a corresponding under delivery tolerance

of 12%.

So the next question you have is where do you define these purchasing value keys?

Okay.

It's just a complicated way of setting these under delivery or over delivery tolerances.

Don't read too much into this purchasing value key.

It's just a complicated way of setting these tolerances.

If it were up to me, I would have, you know, left this to the user to be able to set it to whatever.

But I'm sure SAP has a very good reason why a purchasing value key is used instead of manually setting

these tolerances.

Remember, SAP is a system that's designed with the requirements of hundreds and thousands of fortune

companies.

Fortune 100, Fortune 500, Fortune 1000.

So whatever SAP does, there is a very, very, very, very valid reason behind them.

Okay.

And of course, not every company is the same and you can choose to deviate from it, but there are

certain things that you cannot deviate from.

For example, you cannot manually maintain the under-delivery tolerance like this.

6% Not possible unless I define a purchasing value key.

Right.

So let's go save it and see where this purchasing value key is defined.

And then after that, we're going to see the effect of setting this under delivery tolerance.

Okay.

Purchase value key.

Do you want to save it?

Yes.

So go back.

Go to Sbarro.

IMG.

Material management.

Purchasing good material, master.

Purchasing value keys.

Now, you don't have to really remember the path.

You can just go here.

Search and you can search for value.

Keys because I don't remember the entire text.

I'm going to just pick some part of it and say, Enter it.

It's going to search the entire menu path of Sbarro and show you all the different areas that contains

these texts.

So there are standard value keys in capacity planning, standard value keys and MRP or maintenance plans,

work centers, and then from process orders.

And in purchasing there is this purchasing value key, right?

So if you click on that and say, okay, it's going to point out to the exact location in Sbarro where

that particular configuration resides.

So like I said, you don't have to remember all the different menu paths and transaction codes and all

that, and you can just go search.

It's like Google.

You don't need to bookmark everything that you need on your browser.

Just go search and Google will tell you where's what?

So go to purchasing value keys.

And we have selected two, I believe.

And two has a delivery tolerances of 10%.

Right.

You could create your own like new entries and then give a purchasing value key.

Then define these reminders.

Define a delivery tolerance.

Okay.

So we'll see the effect of this now.


