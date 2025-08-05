 

Lecture thumbnail
13:59 / 14:07
Now we are going to talk about Material Master in more detail.

In fact, we are going to talk about all the customization from this point on for the next set of chapters.

We'll talk about customizing all different kinds of master data.

Well, what kind of master data do we have?

We have.

Material master.

We have.

Vendor master.

And we have info records.

We will discuss the material master first, then we'll talk about vendor master and then about info

records.

In the material master.

There are three main categories of discussion that we are going to have.

First is.

Discuss the functionality of the most commonly used fields.

Things that we have not discussed so far.

For example, some fields like Ahtopol.

The value been discussed when we talked about Otavio?

But there are some important fields that we have not touched upon.

For example, material group.

Material type.

What do they do?

What's their functionality?

So on and so forth.

So the first point is discuss functionality of important fields.

The second topic is going to be material type.

These are the first efforts, raw material.

So what are these material types and what does it basically control?

So material type customization.

And the third point is field.

And screen level customization.

Meaning the fields in the material master can be moved here and there.

We're not going to go into the detail, but I'm going to explain about the possibilities.

All right.

This is the high level agenda for the material.

Master vendor.

Master also will follow typically the same agenda.

Discuss the functionality and then vendor account group and then field level customization.

Okay, let's start with the high level functionality discussing some of the important fields.

First field material Group.

Material group.

What is a material group?

A material group is basically what it says.

A grouping of materials.

Why do we need to group materials?

In fact, this field exists in the vendor master as well vendor grouping.

It exists in the customer master as well.

Customer grouping.

All kinds of master data typically needs to be grouped or that facility is available in ACP.

Why?

Let's take our coffee shop.

What do we have?

We have different kinds of materials, right?

We have coffee.

We have pastry.

We also sell other items like magazines.

Newspapers.

And we sell so many different products.

We classify these materials or group these materials into different categories.

Based on a variety of reasons.

The reason why we do that typically comes from the business.

Say the business wants to classify all different materials that we sell in the coffee shop as.

Coffee, A non coffee related.

They could do that.

Coffee is all coffee.

Anything that's not coffee is not coffee.

Why would they want to do that?

In any business.

Typically they follow the 8020 rule.

20% of the products give 80% of the revenue.

So in a coffee shop, let's say 80% of the revenue comes from coffee and coffee related products.

In which case they want to first group coffee and coffee related products as coffee, one group and

everything else into another group.

That's a very simplistic way of looking at it.

If it were a small coffee shop, yeah, that would be how I would look at things.

So you can create two groups, one group for coffee.

And the second group is.

Non-coffee or others.

But businesses are rarely so simple, right?

You need so many ways to classify things.

And more importantly, you need to understand why I would want to classify things or why the business

would want to classify things.

The need for classification is manifold.

It's not just one reason why you want to classify things.

But broadly, the need to classify can be categorized into two.

One is operational.

And the other is analytical.

Operational reasons.

What can I think of operational reasons?

For example, on the sales front, you want to give discounts.

Based on material group, you won't have special pricing based on material group, for example.

In the holiday season.

I want to give 10% discount on all coffee products.

How would I do that?

I can only do it if I classify and identify all coffee related materials as belonging to one group.

And give discount or pricing special pricing based on that group.

Same thing with purchasing.

Another example.

All shipments related to coffee will be expedited.

How will I do that?

That's an operational requirement.

Say the business has taken a decision that this Christmas or this holiday season.

All coffee related items will ship it to you overnight.

Okay.

Good decision.

It promotes coffee.

Now.

How do you do it?

How do you implement it in SAP?

Well, on the shipping end, you got to be able to classify coffee as belonging to coffee or any material

belonging to coffee group and then expedited.

If it is not coffee, don't expedite it.

So based on the material, how would they know if it is coffee or not?

It could be coffee cake.

It could be coffee beans.

It could be anything that's related to coffee.

A more relevant example is let's say Amazon wants overnight shipping or wants to give or promote overnight

shipping only for books.

On books is a way to classify a particular kind of material.

Because Amazon sells everything under the sun.

Books now needs to be classified as belonging to a material group of books.

And when you want to expedite only books will be expedited overnight as part of this festival offer.

So these are all examples of operational requirements.

Now material group can also be used for analytical requirements.

For example, give me all the sales of coffee.

Or coffee related items.

So that means coffee cake, Coffee.

Beans.

Coffee cups.

Brewed coffee or any of that stuff.

How would you do that?

You keep selling goods, and one of it might be coffee.

If I go to Starbucks, I could order one coffee and one cookie.

Coffee belongs to the coffee group and Cookie belongs to the baking group.

I only want to analyze the sales for coffee.

So unless I classify coffee as belonging to a coffee group or some special group, I won't be able to

do it right.

So these are analytical requirements, sales value, sales volume.

Similarly, purchasing value purchasing volume.

How much of coffee related goods did I purchase?

These are all reports that you pull out of SAP or business warehouse that uses specific fields like

material group material Group is not the only group.

There are many other parameters, but material group from a material master perspective is one of the

prime fields for grouping materials.

So you know where the material group is, right?

So if you go to M01 or coffee beans zero one, go to basic data.

There you go.

That's your material group.

Where do you create your material group?

If you want to create more material groups, for example, what material groups do we have?

These are all the material groups that are given as part of a standard ID system.

If you go to your system in a productive system or a brand brand new system, you wouldn't have any

of these.

You have to create them by hand.

And where do you do?

Do them?

Somewhere in Sbarro.

Right.

So let's go create some material groups.

Where do we go create methyl groups.

It's all under logistics.

General of Sbarro.

Let me show it to you.

So go to.

IMG.

All master data customization is typically under logistics general unless it is specific customization

required for sales or materials.

Any generic customization of the master data is there in logistics, General.

So go to logistics General.

And the first section is Material Master.

All right, let's go there.

And then in this sea of options, I wouldn't know where the material group option is.

Right.

I don't know where it is.

It must be there somewhere in field selection or basic settings.

Or one of those.

All right.

Settings for key fields, material groups.

So it's there if you don't know where it is.

There is a quick way to go about finding where it is.

You can either go here and click on search like, say, material group material.

Group like that and you could do it in the background or foreground because there are so many different

menu paths to search and SAP comes up with a list.

This material group is defined in so many different places.

You see material groups for export import.

That's part of foreign trade.

Material groups for something else as part of excise duty, so on and so forth.

Right.

This is probably the one that we need because we know it's part of material master functionality.

Core material master functionality.

So select that and it will take you there.

That's one way to find out.

There is another way to find out, which I'll talk about later.

All right.

So here is our material group, and these are all the material groups that SAP provides as part of an

IDs system.

Right.

Because these are all samples.

Now, like I said, in a fresh box, brand new instance, you would not have any of these.

You'd have to create them.

Based on your business need.

Let's say I want to create a material group called Coffee.

Coffee and coffee related material group.

Okay.

One entry Chosen save.

Okay.

Now let's go back to our material Master M02 for coffee beans.

Coffee beans Oh, one basic data and go here and instead of doing A015.

Try to assign a coffee.

Coffee?

Do you have that?

Yes.

Right.

Coffee.

Now, this is a better categorization of coffee, right?

All right.

So material has been changed.

The material group is now changed to coffee.

Now we know what a methyl group and how to create a material group and assign it to the material master.