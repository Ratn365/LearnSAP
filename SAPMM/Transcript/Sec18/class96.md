 
Transcript
Let's take the same example that we have discussed earlier.

We have ordered for coffee.

And the vendor has delivered the coffee.

And using my go.

We have tried to put the stock is the goods receipt into our plants storage location.

Where do we typically put the coffee?

We put the coffee in the coffee storage location.

Right?

And we enter that during my go, right?

Say, for example, instead of putting it in coffee somewhere in the warehouse, has put it in a different

storage location, say raw materials.

Right.

They've saved it, created the invoice and whatnot.

It's all done.

Now, we have realized that instead of putting coffee in the coffee storage location, we have put it

in the raw material storage location.

Well, it's no big deal.

We can correct it, right?

We can just put it back into coffee.

Let's take that bag of coffee, put it back in the different storage location called coffee storage

location.

But how would you let the system know that you have done that?

The system would still think that that £100 of coffee is still in the raw material storage location.

Why would that matter?

It would matter because if you want to pick some goods like coffee from the coffee storage location,

and if you don't find that £100 bag of coffee there, it's a problem.

So you would want to keep your warehouse physical stock always in sync with what the system thinks.

Right, because after all, we use the system to represent what's really happening physically outside.

So you just want to move that bag of coffee from raw material to the coffee warehouse.

And how do you do that?

If you could carry that bag of coffee over from raw material, warehouse to coffee warehouse, the process

of doing that in shape should be as simple, right?

In fact, it really is.

There's a process in SAP called transfer posting.

It's a very simple process whereby you can do inventory management transactions.

A transfer posting can do a lot of things for you.

We'll see what a transfer posting can do.

I don't want to define transfer postings just yet.

There's time for that.

But let's do a transfer posting now and convert.

Or transfer the stock from here.

To hear.

We're going to do it two ways.

And the first way to do it is called as a one step.

One step.

Transfer posting.

And how do you do that?

Go to my go enter.

But before I do that, I want to post this 100 kilos of coffee into raw material storage location.

All right, let me do that step first and then I'll do the transfer posting.

So go to M-21m and you know the steps, right?

Document overview of.

Vendor 4001 is going to deliver coffee beans 100 in quantity.

Save it.

Copy the number.

Then go to my go.

Put the purchase order number in there and instead of posting it to the coffee storage location, I

want to post it to the raw material storage location because this is the mistake that we want to simulate.

Right.

God, save it.

And then you don't need to do the invoice because the goods are already there.

Now we want to do this one step transfer posting.

And where do we do that?

You do it right here in my go.

Go to my go.

And instead of goods receipt select transfer posting.

And see these options would have changed.

You don't see the purchase order anymore, but instead.

You see this?

Right.

And what do you want to do?

You want to transfer?

£100 or kilos of coffee from raw material storage location to the location where it belongs.

Coffee beans.

So I'm going to enter the material here, the plant.

And where are we transferring it from?

You see the from here we are transferring it from the raw material.

To.

Where are you transferring it to?

To the coffee storage location.

Oops.

And how much do you want to transfer?

Well, we want to transfer.

£100 of coffee.

Right?

And you see when you click on the wear tab from quantity, we're going to move on to the wear tab.

And it says 301 transfer tf.

From plant to plant.

In our case, we are transferring from one storage location to another.

Storage location from here to here.

And both of them belong to the same plant.

So it's not really a transfer from one plant to another.

It's really transfer.

Within the plant.

So this movement, Type 301 is not the right type of movement.

So which one is correct?

So what's the right movement type?

All right.

So it's not 301.

Instead it is this 311 transfer posting storage location.

Now, I know what you're thinking right now.

There are so many different movement types.

What are these numbers?

Do I have to remember them?

The simple answer is no.

You don't have to remember any of these movement types.

Well through the course of time when you start doing so many different things in inventory management

and purchasing.

It'll happen to remember some of them.

And that should be good enough.

But remember.

That a movement type.

Technically is what does all these goods movements.

Goods transfers, transformation and value.

So many different things behind the scenes.

That's just a saps way of doing these goods movements or goods transfers.

So you have to understand that when you do a goods receipt, there is a movement type that runs behind

the scenes to do all the accounting work for you.

But I mean, accounting work, it could be reduction in inventory in one storage location or addition

of inventory in another storage location doing or updating the accounting documents behind the scenes.

Purely from an inventory perspective and accounting perspective, the movement type is what is going

to handle all these things.

So why is movement type used?

The reason is very simple.

So that the person in the warehouse doing a particular transaction need not worry about what really

happens to the inventory and what really happens to accounting.

He can be oblivious to all that stuff.

He can just simply do his micro and be done with it.

Behind the scenes through the use of a proper movement type.

It's going to take care of what needs to be done.

We'll slowly see what are the things that happen behind the scenes.

But for now, understand that every inventory movement.

Happens behind the scenes through the use of a movement type.

And the movement type is basically a three digit number followed by a letter.

And we'll go into the configuration of the movement types in the next set of chapters.

All right, so select three.

One, one and hit enter.

And you see it's transfer within the plant.

Right.

So what's really happening here?

We are transferring coffee beans.

Of quantity 100 from the raw material storage location.

To the coffee bean storage location.

That's what we wanted to do here, right?

All right, let's do that.

And before we do that, let's go to.

Put coffee beans in here.

In the Chicago plant.

Hit.

Execute.

In the raw material storage location, there is a quantity of 160 that can be used.

And in the coffee storage location there are 630.

And when you move a quantity of 100 from here to here, obviously this is going to be down by 100 and

this is going to be up by 100.

So let's do the transaction in my go and see how the inventory is affected.

Okay.

Let's go and save this.

All right, Material document is posted.

So I'm going to refresh the screen.

The.

And did you see that from 160?

This has gone down to 60 and there have been added to the coffee bean storage location.

Now let's take this material document.

Like.

So And the way to see a material document is go to M0 three.

Picture material document in there.

Hit, enter.

And you see that from raw material to the coffee storage location, a quantity of 100 has been posted.

And the material movements that we've used is listed in here.

And if you want to look at the accounting document.

It says that you don't really have an accounting document.

Why is that?

That is because anything that happens within the plant does not need an accounting document.

Let me explain what what I mean by that.

So what are we doing here?

We are trying to transfer some goods from the raw material to the coffee beans storage location.

When we are doing that, the ownership still lies with the Chicago plant, right?

So who cares about accounting?

It's all still with Chicago.

Accounting is not done at the storage location level.

It's done at the plant level.

And because of that, no accounting document is generated.

And if you want to understand what an accounting document is, we have seen what happens at the end

of an invoice.

Basically, it creates an entry in accounts and similar to the way accounts are being posted to after

invoice creation in the same way.

Accounts are being posted to after goods movement has happened.

That is.

If there is a change in accounting now, don't worry too much about this accounting stuff.

It's not something we need to worry about at this point.

But just understand that the movement type will take care of the accounting for you, number one and

number two.

In the case that we have just done, no accounting document is generated because the transfer of goods

really happened within the plant.

It's like saying I moved some stuff in my home from my kitchen to my garage.

Does it really matter?

Well, it matters from a physical inventory or stock or goods perspective.

But does it really matter from an accounting perspective?

It's all still in your home.

You don't need to do any accounting.

You might ask me.

As opposed to what?

What situation might demand some accounting?

If you move some goods from your home to your neighbor's home, then you need accounting, right?

Or if you have two homes, one in Chicago and one in San Francisco.

And if you move the goods from the San Francisco plant to the Chicago plant.

Then you need some level of accounting.

But if you move the goods from your kitchen to your garage, then you don't need accounting.

As simple as that.

Right.

So what have we learned here?

We have learned that there is something called as transfer posting.

Which is a function in my go that you can do to transfer goods from one storage location to another

within the plant.

This step is called one step transfer posting.

Again, You have a question I can sense.

Is there a two step transfer posting or three step transfer posting?

Well, there is a two step transfer posting for sure.

And when do you use a two step versus a one step?

Well, let's see.


