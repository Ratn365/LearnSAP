 

Lecture thumbnail
6:26 / 6:28
All right.

The next section is the views.

When you go create a material, you have so many different views, right?

You select basic view, you select accounting view, you select purchasing view, so on and so forth.

But not every material type can be assigned to any view you want.

It's not possible.

So each material type can only have a certain number of views.

So in this case, raw material, for example, does not have a work scheduling view.

See, it's not checked on like that.

So by default, when SCP comes up with a definition of raw material.

It says raw material does not have a work scheduling view.

Why is that?

What is your work scheduling view?

A work scheduling view.

Then we have seen planning defines the parameters that a plant requires to manufacture that material.

With a raw material is not manufactured by definition.

But not necessarily.

You know, you could go and manufacture some raw materials if you want.

In cases like that don't create them as raw materials.

Create them as probably semi-finished products or finished products.

But you could still use them as raw materials.

This is SAP's suggestion.

That raw materials need not have a work scheduling view or a production resource view.

A sales view because you're not going to sell raw materials.

If you need raw materials to be sold, then create your own custom material type and check sales on.

If you don't check sales on and if you go create a raw material, let's say zero one.

Right.

Raw material.

Enter.

Where are your sales views?

You don't see them, right?

You don't see sales views.

That's because, by definition, the template of zero one raw material says that there is no sales view.

There is no work scheduling view.

If you want, you can go and turn them on like that.

Save.

Now you should be able to go and create a raw material with a sales view.

The Cecil's view now sales views.

Right.

So I'm unchecking that because I don't need sales view for raw material, right?

So all the different views that a material type is allowed to have are defined here.

The next one is price control.

The raw materials are typically procured, Right?

So for procured materials, what kind of price control do you use?

You don't use standard.

You use moving average.

Now, this can be changed in the material Master.

I'll show you.

But when you set it here to.

We save it.

Right now.

Go back.

Go back all the way and start again with zero one raw material.

Enter.

Select basic and accounting One view and for the Chicago one plan.

The given name doesn't matter what name and basic unit of measure each.

And you see that I didn't put any price control here.

It automatically has selected a V.

If I did not change that to V here, it would have come up as s standard price.

So this defaults the valuation or price control in the material master.

So why do you want to use this?

You want to use this when you know that for certain material types you're going to use a particular

type of valuation always.

So when your internal user base in the company is creating materials, not everybody might know what

price control to use in cases like that.

SAP based on the configuration in the material type, can default to a particular material type.

Address.

Irby.

Right.

And then there's accounting category reference.

We'll talk about it when we come to Obike MFI Interface.

But that's an important control.

Remember it.

We'll touch upon it later.

And then price control mandatory.

Now, if you check this on save It.

What happens is you cannot create a material without the price control.

Now, what this means is if I create a material now.

Right with the basic data and accounting one.

K1 enter something here.

Each.

Then you see that.

Then I set that to mandatory.

I cannot even change this.

It is set to V and that's it.

I'm trying to double click to S, click on green.

It's not happening.

What this means is if you want to force a certain material type to have a certain type of price control,

then use price control mandatory.

This forces all your internal users that when you create materials of a particular material type, it

does not give them an option to choose the price control.

The price control is set at the material type and that's it.

They don't have a choice.

That's price control.

Next we have quantity and value update.

I think we have seen quantity and value update already when we talked about valuation.

Quantity update versus value update.

Typically, finished materials have both quantity and value update.

Some materials like non stock materials.

They are not maintained by quality or value.

They are consumed all the time.

Some materials have quantity update, but they don't have value update.

We have seen examples of all the three different cases.

All right.

That's the material type.