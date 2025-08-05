 
y.

In this section, we're going to talk about master data.

There are two main kinds of master data in SAP.

Material master.

Winter Master.

Let's talk about the materials that we are going to use in our coffee shop.

So we're going to use a whole bunch of raw materials, right?

Like flour, different kinds of flour and pastry sheets, stirrers for coffee, baking sheets, so on

and so forth.

And we're also going to either procure or manufacture baked goods like croissants, pastries, tarts,

cakes, that kind of stuff.

And we're going to either use or sell coffee beans, for example.

We could be using coffee beans for our own internal consumption, or we could back them up and sell

them as coffee, our own branded coffee.

And we will also be selling some of the stuff that we just procure and sell like newspapers.

Now, each of these materials are different.

Not all of these materials are the same, right?

So there's raw materials, there's finished goods, there is trading goods.

We're going to talk about all these things now and in every material has a number of views.

A view is basically a set of data that you can see when you go to that particular view.

And it's logically separated into a view so that you know that if you want to go look at the manufacturing

view of a material, it contains all the manufacturing related data.

For example, let's take a material.

Say sugar.

Okay when sugar is bought.

You inspect it for quality, right?

When sugar is brought, you put it in a warehouse.

So you need some data.

Like what kind of storage conditions are required to store it in a warehouse?

Like, should it be stored in cold storage or should it be just left out in the open?

That kind of data is stored in the warehouse view.

And whether you buy or sell sugar, it needs an accounting view.

So how should all the transactions related to buying or selling or manufacturing that particular material

be accounted for?

And then there's.

Costing.

So how do you cost this material?

Costing is the process of calculating the price of the material in terms of how much it costs us.

So not all materials are costed in the same way.

Some materials are manufactured.

They have a more elaborate costing process.

Some materials are procured.

They have a different casting process.

All the costing relevant details are available for sugar in the costing view.

And similarly, if sugar is procured.

The procurement settings of sugar are available in the purchasing view.

So I think you get the idea right.

Planning.

View.

Manufacturing View.

Sales view.

For example, we don't sell sugar.

In that case, we don't need this view.

We're not bothered about that view.

Say we don't manufacture sugar.

Do we need this view?

Maybe not.

But there are cases where we might need them even though we don't manufacture because, you know, those

settings might be used in some other places.

But those are specifics.

We'll talk about them as we go forward.

Overall, though, just understand that every material has a whole bunch of data related to all the

different aspects of dealing with that material.

Like the material you buy, a material, you manufacture a material, and through the process you cost

it, you account for it, you plan it, you check quality.

And not all materials have the same set of parameters depending on the type of use you use, the corresponding

views.

Similarly, for example, if you have coffee beans, a coffee beans are not manufactured, so you don't

care about a manufacturing view.

So maybe you don't sell coffee, you only use it for internal consumption.

You don't need the sales view.

If you take finished goods like like, like, like a muffin.

Right.

You manufacture a muffin in your factory, so you need a manufacturing view.

And you also need to plan for how you manufacture things.

You might also need extensive quality related data because your manufacturing them yourself internally.

And then there are some materials for which you don't really care about a lot of stuff.

For example, there are stirrers for coffee.

You don't care about the stock of steroids, right?

It's such low value that you don't really bother to spend a lot of time documenting how much stock you

have, what's the value of it?

So these materials are treated differently.

They don't have planning, they don't have quality, they don't have warehouse, they don't even have

accounting or they might have accounting, but it's done differently.

They don't have costing, they don't have sales.

They don't have manufacturing.

Right.

So these materials are different.

They are such low value that you don't really bother to document about the stock or about the cost of

those materials.

So you don't have a whole lot of these views for materials like this.

Now the parameter in SAP that dictates what different kinds of views a material has is called the material

type.

So when you talk about material, probably the most important piece of information is the material type.

The reason being it dictates what kind of views that material can have.

Let's take some examples.

So if you look at finished goods.

First f r.

So it's a dropdown here.

So if you go to the material type and click on the dropdown, you get a whole bunch of material types.

Well, the most popular one is fert f e r t, which stands for finished goods.

So what do you use it for?

Anything that's a finished.

Good.

As opposed to what?

As opposed to raw materials or trading goods.

We'll see some examples.

Croissants, Black Forest, BlackBerry tart.

These are all examples of goods that we might manufacture or we might procure.

For example, almond croissants, say, is a speciality that we don't produce, but we procure from

somebody else, in which case it's still a finished good because we sell it.

We don't do further processing on it.

It's not like a semi-finished good.

It's not a raw material that we process further.

It's a type of goods that's finished and ready to sell.

You might manufacture it, you might procure it.

It doesn't matter.

So these are all examples of finished goods that you would create using material type first for art.

And then we have raw materials, flour, coffee beans.

These are raw materials.

We use flour to make cakes.

We use coffee beans to produce cappuccinos.

What's the material type for that?

The standard SAP supplied material type is R or H.

Which is raw materials.

And then we have semi-finished goods.

H a l.

B Some examples of semi-finished goods could be pastry sheets.

Well, these are partially ready, but not fully ready maybe.

And then there is not a lot of difference between raw materials and semi-finished goods.

So don't, don't get into the nitty gritties of it.

Just understand that there is a material type for semi-finished goods.

It might not be relevant for the coffee shop, but it could be relevant for, say, a car industry.

And then we have trading goods.

Probably newspapers is a very good example of a trading goods because we don't really print newspapers,

right?

We procure it from someplace and then we just sell them.

So trading newspapers in the coffee store.

That's all there is to it.

You don't treat it as a raw material.

You don't treat it as a finished goods.

And then we have non stock materials.

Non stock materials are materials that we do not stock.

Well, examples are steroids and breaking sheets.

Let's take steroids.

What do I mean when I say we do not stock?

Well, we have to put it in the stock or storeroom somewhere.

Right?

So why am I calling them non stock?

We call them non stock because although we put them in stock, we don't count them in the stock.

Meaning at any given point of time, if you go to ASAP, you wouldn't know what is the total number

of stores that you have.

Simple.

And why do you do that?

Because there is no point in counting stores, because it's such low value and ubiquitous that they

are used everywhere and you don't need to really count them.

They're just there.

They are done.

You get more.

So typically, all low value goods really, really low value goods are called non stock materials.

And you use the material type in lag for non stock materials.

And then there's another type called non evaluated materials, where you keep account of the stock,

but you don't evaluate them.

So if you go to ASAP and then say how many coffee cups I have, you might have a number like a count,

but they don't have a value.

So those kinds of materials use material type u BW.

Now, don't worry if you don't understand all these different material types.

In order to really understand them, you have to perform certain transactions and see the stock and

see the value updates and then you'll understand what's really going on and why we're using so many

different material types.