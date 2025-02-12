 
ght.

So in this video, we're going to create some materials.

Let's create a material for unbleached flour.

It's a raw material.

So we're going to select a material type of raw don't worry about industry sector.

So it doesn't have any control over how this material behaves.

It's used for reporting.

So as soon as you go to zero one, put your material, put your material type and hit enter.

You're going to get these views.

And the views that you get are based on the material type like we discussed in the previous video.

So flour.

Unbleached.

And this is a raw material.

Hit enter.

And these are the views.

Now, do we need all the views for purchasing?

You don't really need all the views, although SAP allows you to maintain all these views for a raw

material.

We don't need them now.

For now, just select basic.

Purchasing.

And accounting with just these three views, you can do the entire purchase order cycle.

Because we going to procure raw materials, right?

Our job as an consultant is to configure the system so that you can procure raw materials.

We don't care about manufacturing at this point.

That's the role of a consultant for us.

We care about purchasing.

So just these three views are more than enough.

Later, when we talk about MRP and consumption based planning, we'll talk about the MRP views.

So hit.

Okay.

Then it asks you.

For which plant do you want to maintain this data?

Now, why is SAP asking this question?

Because purchasing data for each plant could be different.

Now, think of the plant in Chicago that we have.

We have a plant in Chicago, and we procure unbleached flour.

Good.

Let's say if I have another coffee shop in Seattle, I procure unbleached floor there as well.

And the type of data there could be different from the type of data in Chicago.

We'll see some examples.

For now, let's select.

Car one.

Hit.

Okay, then give a description.

Unbleached flour.

The best unit of measure is pound material Group is 015.

Don't bother about material group and before you go further, go to additional data.

And I want to show you something.

You can maintain the data in different languages.

Meaning think of Starbucks.

Starbucks has stores across the world.

The same coffee is called as something else in German or French language.

Right?

So when you print a PO in France, it should print in French language.

Right.

You can maintain the material description in different languages because one system can support any

number of languages.

So this is what is.

So let's say.

I don't know what it's called in German, so I'm just going to say unbleached flour in German.

So this is how you can maintain descriptions in different languages.

Next go to unit of measure again.

In the US we use pounds.

In India we use kilograms or in Great Britain, we could use something else.

So it's the same material, unbleached flour.

You got to be able to use and convert this into any kind of denomination for weight or volume or whatever,

be the unit of measure.

And over there you could specify the conversion rate for standard units.

SAP already has the conversion.

But you could have your own units of conversion.

Think about beer.

A crate of beer for Budweiser could be 12 cans or 12 bottles.

A crate of beer for Corona could be eight bottles.

That's very, very specific to the company and does not have a say in it.

Right.

They can't say what a crate is.

So you can maintain your own units of conversion here.

In our case, for example, we could procure flour in bags and each bag could be, say, £25.

So you say one and then select bag.

I don't know what's the unit of measure for bag?

So let's go here and search.

Star bag.

Or there is no unit of measure for back.

So let's select something that's close.

You could create your own unit of measure, but that's fine.

We don't bother about it now.

See a cartoon.

Okay.

One carton is equal to say.

£25.

Okay, So any time you use carton in your purchase order, SAP can automatically convert that into LPs

if you want.

If you want.

If that is the unit of purchasing, unit of measure.

Because when you think of Carton as a company, your vendor might not understand it.

So this unit of measure conversion that you specify here will be used depending on the nature of your

action.

If you are doing sales, the unit could be different.

If you're doing purchasing, the unit could be different.

If you're doing manufacturing, the unit could be different.

So depending on the type of action when SAP tries to convert, it takes the conversion rates from here.

All right.

Now we can go back and then hit enter.

It takes you directly to the purchasing view.

If you go look at all the views here by clicking on this little button.

You have selected basic data, one purchasing and accounting.

Right.

So although you have selected them, you can specifically click on any of the views that's available

here and go maintain data.

But if you don't select a particular view and hit enter, the system automatically takes you to the

next selected view.

In this case, we have the next selected view is purchasing.

So in purchasing you select a purchase group.

Remember, what's a purchase group?

The Purchase group represents a group of people responsible for purchasing a certain set of materials.

It could be based on materials.

It could be based on location.

Depends on how that company wants to do its division of procurement.

So in this case, I'm going to use the one that we have created us one hit enter.

And finally.

It went down to the accounting view because we have selected only three views.

Remember basic data purchasing.

Accounting.

So in accounting, there is something called as a valuation class that deserves a bigger topic.

So I'm not going to go too much into the depth here for now.

Select valuation class.

Select 3000 and here instead of price and here.

Select V for moving average.

And hit enter.

It's going to throw you a message.

Just ignore it.

Hit.

Enter again.

And you have come to the end of the screen.

Do you want to save it?

Yes, of course.

So the system is saving unbleached flour material that we have just created.

Flour dash, unbel.

So what have we done here?

We have selected three different views basic data, one purchasing and accounting, and we have selected

a unit of material we want to sell in pounds or kilos, select a material group.

Don't worry about material group for now.

We'll talk about it later.

And we went to additional data.

Then We have described the material in different languages and we have seen why we need to describe

them.

And then there is unit of measure conversion.

If you are going to procure or produce or manufacture flour in different units of measure other than

pounds or kilos, you need to specify the conversion here.

For example, Carton.

Two kilos.

Pound.

Two kilos.

I say, like I said, will already have all the basic conversions ready.

Whatever does not have.

You can specify them here.

So that's unit of measure conversion.

And then we moved on to the purchasing view and we specified a purchasing group that we have created

here.

And then on to the accounting view.

We specified a valuation class.

Specified a price control of V and then hit save.

Your material flower underscore UNB for unbleached is ready.