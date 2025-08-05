 
Transcript
So when you want to transfer a material from one plant to another.

The material needs to be created or extended to each of the plants.

Now we know that the material coffee Beans zero one is created in Chicago because we have created it

using MMO zero one ourselves.

But it also needs to be extended to the San Francisco plant.

I would say created slash extended.

I'll tell you why.

The process of extending a material to another plant or company code or any other element that you have

seen in the enterprise structure.

Is through the process of creation.

Now, I wish we had another transaction for extension, but that's not the case.

The process of extending a material to another plant.

Is through the process of creation.

Zero one So the creation and extension can be used interchangeably.

When I was learning SAP long back, I had a question.

I have already created this material.

Why create it again?

Well, logically speaking, the process is called extension.

That makes sense.

Well, we are extending the material, but the transaction code to do that is not zero 2 or 0 three

or any other transaction.

It's zero one through the process of creation.

Well, let's do it and then we'll get back and talk a little bit about it.

Okay.

Let's go back.

And the transaction code is zero one.

The material is coffee beans and hit enter and it automatically picks up the material type industry

sector, blah blah blah.

Hit enter and do I need to select basic view?

No, because basic data is something that's not specific to a plant.

Those are the properties of the coffee beans.

That does not change from one plant to another.

Right.

So basic data is something you don't need to select.

Now, that should tell you something about these views.

Well, we have seen master data already, like material master vendor.

Master.

But I don't think but we have not seen this aspect of it.

We know that Material Master has views.

Vendor Master has views.

But but what we don't know is that basic data is data associated with that material.

That does not change with the plant.

Now, what are some examples of data associated with that material that changes with plant?

Well, let's see.

Uh.

Let's take this general plant storage and accounting.

Okay.

Click.

Okay.

Then it's asking you for a plan.

Now, we have already maintained this for Chicago, isn't it?

So we're going to say San Francisco because we want to maintain data for the San Francisco storage location.

San Francisco plant and coffee beans, storage location and click okay.

Now you see the message at the bottom.

It says the material already exists and will be extended.

No SAP knows that the material has already been created.

So it's going to extend this from the Chicago plant to the San Francisco plant.

And it copies as much of the information as it can.

But where it thinks information could be different between the plants, it's leaving it as blank.

Let me give you an example.

The shelf life.

Well, we have not seen what shelf life is, but you know, shelf life, right?

You go to Safeway or any of your supermarkets and you look at a muffin.

It has an expiration date.

You look at your juice, it has an expiration date.

You look at milk, it has an expiration date.

That's called shelf life.

The gallon of milk sitting on your supermarket shelf has a shelf life of, say, five days or ten days.

The shelf life is a property of the material, right?

Say, for example, we are transferring muffins from Chicago plant to San Francisco plant.

And the shelf life on the Chicago plant is ten days or five days.

But on the San Francisco plant is just three days because we are transporting and we are losing two

days in the transport.

So the maximum storage period, say, for example, is three days in San Francisco, but five days in

Chicago.

See, the data for the same material is different from one plant to another.

Well, you can imagine more examples, but the basic concept is simple.

Data for a material could differ from one plant to another or one storage location to another.

And that's the reason why you extend the material from one plant to another and give it more meaningful

data that's relevant for that storage location or that plant.

We have maintained the plant data for this material for San Francisco.

Now let's maintain the accounting data.

Hit.

Enter.

It's going to move on to accounting.

And here for the San Francisco plant, we're going to maintain.

The valuation class.

And we see that the price control is we.

And hit enter.

And see.

It.

Okay.

And your material will be saved.

Now let's go back to my go.

Click okay and click on Check.

Everything seems okay.

You can go on.

Save it.

Before saving it.

What do you have to do?

You have to go check your stock.

Right.

We want to make sure that £100 of coffee is being transferred from Chicago to San Francisco.

How do you do that?

M m.

B e.

Right.

Don't specify the plant.

Instead just leave it open and executed.

So that way you get the stock for both San Francisco and Chicago, right?

For now, you don't see San Francisco because there is no stock for San Francisco.

Well.

We're going to put some now Click Save material document is created.

And let's refresh this.

Okay.

There you go.

You got San Francisco and the coffee bean storage location in San Francisco now has a stock of £100

using the one step transfer posting method using movement type 301.

We have transferred the stock from Chicago plant to San Francisco plant.

Now, this is one step method.

Really.

For plants that are so far apart, you would really not want to do the one step method, although it's

allowed.

Because they are so far apart.

One step method doesn't give the inventory manager the correct picture.

Is it really in the San Francisco stock in like a second?

No, it's not.

It will take two days.

Three days?

So a more appropriate method is to use a two step method and to do a two step method.

Let's go find out what is the movement type that we should be using.

To go open the possible list of movement types and.

Okay.

Transfer posting plant to plant reversal.

We know that we could just reverse what we have just done using 301 with 3 or 2.

Uh.

303.

Transfer posting Plant to plant.

Remove from storage.

That looks like it.

Right.

So let's use 303 to remove, let's say, £50 from Chicago plant.

And if we want to place it back, you can use placing storage transfer, posting plant to plant.

Right.

303.

305.

So let's use 303 for now.

303.

Whenever you change the movement type, you get this message.

Now change, default value, blah, blah, blah.

You can just say skip this in the future and click okay.

So when you do transfer posting, right?

SAP wouldn't know which movement type the warehouse guy wants to use.

So it defaults a particular movement type over there.

And if you keep repeatedly doing the same movement type, SAP lets it stay there.

But if you want to do several different movement types, you've got to go manually change it.

Okay.

That's one way they could do errors.

But we're going to look more into that later.

We know the material is coffee beans.

All right, plant Chicago.

All right.

Storage location.

Coffee beans.

And the destination is San Francisco.

Okay.

And how much do you want to send?

£50.

Just to differentiate from the £100 that we have done earlier.

Let's go check.

Make sure everything is okay.

Okay.

Save it.

Okay.

Pick up this material.

Document control C.

Close it.

Now we want to do a place in storage.

And we want to refer to the material document that we have just created.

Well, if you forgot it, you can always go and search for that material document.

Since we have just done it, It just puts it right there.

If you've done it yesterday or if somebody else has done it, you can always go and search for that

material document using the search button.

All right.

This gives you all the list of material documents created by plant, by storage, location, by posting

date.

By username, you know, so many different search criteria.

We don't want to go there.

We already know the movement type.

Then hit enter.

So it copies all the data, like £50 of what?

Coffee beans from two.

Everything is being copied.

And what's the quantity?

50.

Where do you want to place it?

To the San Francisco storage location.

We just happened to not name it as San Francisco.

We left it as Chicago.

We'll go and change the name.

And to which storage location?

Coffee beans, storage location.

You could change it to any storage location you want.

Item.

Okay.

Click save.

That's done.

Now, if you go here and refresh this.

Coffee storage location in Chicago should go down by 50, which should make it 700, and San Francisco

should increase by 50, which should make it 150.

C 700.

And 150.

So this is an example of a two step transfer posting.

So what have we done?

We have extended the material from one plant to another, which is essential if you want to do a transaction

with a material between two different plants.

SCP has to have the data for both the plants.

Well, in this case, the data is the same, but still you got to extend it.

And the process of extending a material or any kind of master data.

He's using the Create transaction.

So that's why I'm saying create, slash, extend.

So technically it's creation, but you know, logically it's extension because it's already been created.

And what have we done here?

We have done a one step transfer posting using a particular movement type, say 3 or 1 doesn't matter

what it is, but I'm just listing it out there.

And we have also done a two step transfer posting using movement type 303, which removes stock from

the storage location of the source plant into in-transit.

Right now this becomes in transit.

And then place in stock using movement type 305.

So this.

Is.

To step.

Transfer posting.

So this is an example of stock transfer using transfer posting from one plant to another.

The next example, we are going to do the same thing functionally move stock from one plant to another,

but we're going to use a totally different method for that called stock transport order.


