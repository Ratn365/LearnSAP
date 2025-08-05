 
The next topic is field level customization.

Customization.

What is field level customization?

A material master.

Look something like this, right?

There are so many different types, basic data, accounting data, so on and so forth.

So these are tabs.

And each tab has certain sections and each section has certain fields like so.

So this is called a sub screen.

The tab is called a screen.

And these are individual fields.

So material master comprises of n number of screens or tabs.

Each screen has n number of sub screens and each sub screen has a certain number of fields.

Now, can you change this?

Do you have the facility to change the sequence of fields?

The sequence of sub screens or the tabs?

Well, you can do it, but you can't do it.

As a functional consultant.

You need the help of a technical consultant for that.

So the settings for that is here.

Go to define structure of data screens for each sequence.

Then the standard sequence is zero one.

Go to data screens.

And then here is how the basic data purchasing data sales, data, data screens are declared.

So if you go to the basic data.

Click on sub screens.

These are all the different sub screens in basic data.

If you want to see the first sub screen, select it, click on view sub screen.

Okay, There's a material number, material description, and then some lock and then some revision

level, Right?

So if you go to zero one.

Let me minimize it.

And then select something basic view.

Right.

Do you see that?

Do you see the similarity here?

This is how the sub screen is defined.

There is a material number.

There is a material description and then revision levels.

And you see, that's how the actual material screen is.

There is a material number.

There is a material description.

And then we have revision levels.

Right.

So this is what I meant by sub screen.

Right.

And this is the main screen or screen.

Let me put that here for reference.

All right.

So we have the main screen and we have the sub screen.

Can you change the way these are displayed?

Meaning can you have the material number here and can you have the material description right underneath?

The material number.

Is that possible?

Yes, it is possible.

But like I said, we as functional consultants cannot do this.

We need the help of a technical consultant.

So how do you do that?

So you take that sub screen, right?

This program, screen number 1002.

Go to SW 51.

This is called the screen Painter.

Put your program in there?

What was the screen number?

The screen number is 1002.

1002 and then click on display.

Right?

This is the logic behind populating those fields.

Then if you go to the layout.

ASAP is opening the screen.

Painter This is how the different elements are created anyway.

What?

We are not aware of it as functional consultants and we don't need to make self aware of this.

We asked the technical consultant, the Abap consultant.

He can do that for you.

All right.

You see that?

You got the material, material number, material description and revision levels.

Now these can be moved around.

Right.

We just don't know how to do it.

If you ask your Abap consultant, they can move them around or they can delete them.

And there are some changes that has to be done behind the scenes, like, you know, changing references

to these screen fields in the code and stuff like that.

We don't know how to do it and we don't care.

Okay.

I just want you to be aware of the possibilities when it comes to fields and screen level customization.

It's possible to customize the fields in the material master, like move them around, change the description,

so on and so forth.

But changing the description is, okay, you can call material something else.

That's fine.

But don't go about customizing the screen too much.

It's not worth it.

It's confusing and it causes more problems in the long run than it solves in the short term.

The users might be tempted to ask you for changes.

They want the material masterpiece to be a certain way.

But remember, SAP has created these screens based on inputs from thousands of customers.

SAP customers.

So there's a reason why, you know, fields have been put in a certain way.

And in extreme cases, some customers, big customers, might ask you to change some of the fields.

And it's not wrong to do that.

Go ahead, do it if you want to.

That's your bread and butter.

But try and avoid those kinds of customization and explain to your customer why you should not be doing

it.

It causes confusion every time there is an update.

These fields have to be protected.

There is so much that has to be done.

Okay.

And it's not worth the effort.

And everything under this configuring the Material Master is how to create these customized screens.

So I don't want to go into too much of that because it's all technical.

Now, this is something that we can do.

Field selection.

What is a field selection?

You know, there are so many fields in the material master material group.

External material group, so on and so forth.

All these fields are grouped together.

So like I said, the material master has so many tabs.

In so many different fields.

These fields are grouped together into something called as field selection.

Groups.

Which is a fancy word for a group of fields.

And each group is assigned a field reference.

The field reference controls.

Whether the field can be displayed, whether the field can be made mandatory.

Whether the field can be made optional.

Or whether the field can be hidden.

What do I mean by that?

So if you go back.

Go to the material Master zero one.

Right.

Zero.

Enter basic data.

Just the basic data.

Now you see, the basic unit of measure is made mandatory.

You know that it's mandatory because you see the check mark, just like the basic material description

and the basic unit of measure.

So you if you don't put anything there, SAP forces you to fill those fields.

So you put some description and then you put basic unit of measure and then you're done.

It doesn't ask you to do anything else.

Now what if you want to make material group mandatory for all new materials that are created?

How do you do that?

You do that using field selection groups.

And in order for you to do that, the first thing that you have to do is find out what is the technical

description of that field.

Go to F1.

And then over here.

Select technical info and then Mara matc.

Mara is the table and is the field.

Don't worry about the table.

The field is important.

Okay.

Remember that Matt CL go back, go back and go to the configuration.

Maintain field selections for data screens.

Right.

So this is called the Field Selection Group, which is a grouping of fields.

And under that, we have these field names.

So group number one has these field names.

Mera means Mera MSD.

I don't care what those names mean, they're all German.

And here we have a description base unit of measure.

For each of these field selection groups, a field reference dictates whether that entry is optional

or mandatory.

Now, you have to understand the linkage here.

What is a field reference?

A field reference.

Let me go back here.

Let me go to another SPRO.

SPRO.

IMG.

Uh, logistics, General.

Material master.

Basic settings.

Material types.

Define attributes of material types and Z01.

That's our material, right?

Double click on that.

And this is the field reference.

The field reference is a field reference basically dictates it's a grouping of so many different things

that control whether a particular field is mandatory or optional or can be hidden.

So a field selection group is assigned to a field reference.

A field reference is assigned to a material type.

This completes the link.

Forum, particular material type say zero.

It's assigned to a field reference.

And there are so many different fields right here, and each of these fields is grouped into field selection

groups.

Now, what is our question here?

We want to make a certain field, let's say, mandatory.

Let's create a problem Now.

We want to make the material group mandatory only for a particular type of material.

Zero one.

Right.

How do you do that?

We know.

What's the technical description of it?

Now let's come back here and we know that zero one is assigned to each field reference.

Now go back.

And see which field selection group that field is assigned to.

So we need to medical.

Right?

So go to field name Mara.

Medical.

It's not allowing us to go just by the field name.

We need to put the entire table.

Mara Mitchell Right.

Material Group.

And that is assigned to field selection group to field selection group to contains so many different

fields.

Right?

So Field Selection Group two has met and we want to make CL as mandatory, right?

Meaning a required entry.

And we want to do it only for R0, not for every material type.

Right.

Make this a required entry.

Okay.

And remember, that affects all these fields, not just material.

It affects the name, the plant, you know, all these fields that are assigned to this selection group.

Now save it.

Create a transport?

Sure.

Data was saved.

Now go back all the way.

M0 one.

Zero one.

Basic data.

They see that material group is now a mandatory field.

How do I know that?

Because I got a check mark here.

If I don't fill it, for example, I put some description.

I put each and hit enter.

It forces you to fill the material group.

Now, with this change, we have not only made the material group mandatory, we might have made some

other fields also mandatory.

Any group that has more than one field.

If you make that field mandatory or group mandatory, all the fields in that group will be made mandatory.

But it's controlled by the material type and field selection group.

Okay.

Now, what is the possible customization that you can do here?

You can create your own field references.

That is possible.

So instead of changing our standard field reference, you can create your own field reference, assign

it to your material type.

That way are customizing it in such a way that, you know nobody else has to worry about it.

It's your own field reference.

Now, what else can you do in here?

For example, if you create custom fields in the material master.

Why do you want to create custom fields?

Material master has like, you know, 300 fields or 100 fields that SAP supplies out of the box.

SRP also provides additional fields for specific industry sectors like retail.

Field has the most number of fields because that's how the retail industry wants to capture the materials

or articles, as they are called.

Now, your custom industry, whatever it is, might need more fields, and that's dependent on the nature

of the industry.

For example, if you are working in the government sector.

The garment sector when dealing with, let's say, public, the common public or public utility companies

or any of these vendors or customers of theirs.

Might need certain fields to identify an individual customer.

For example, the individual customer, the end user of that government.

Might want to be classified as belonging to, let's say, domestic or commercial.

Now I'm talking about a customization and the customer master not in the material master, but you can

extend it to anything you want.

You can apply the same logic to the material master.

Certain materials are domestic materials.

Certain materials are commercial materials.

Now, what field do you use for that?

You can use the material group.

Sure, no problem.

Say, for example, if you are already using the material group to do another grouping, you know,

whatever that grouping is based on another kind of classification and you are left with no other field

but you want to create your own.

So you can ask your technical consultant to create a new field in the material master.

He'll do that for you and include that in the basic data or the sales data or the purchasing data.

You just name the view.

He can put it in there.

He can write the code to update the view.

Update the logic.

And all that stuff.

Now if to make that field mandatory or optional, depending on where that field is, you can create

a new field.

Right and assign it to the right field selection group.

And assign that field selection group to the field reference.

Like so and make that field reference mandatory or optional.

That way, for certain material types, this field can be made mandatory or optional or hidden or required

entry or just display.

Right.

That's the customization that we can do with field selection groups.

So you're basically playing with the field reference.

This is assigned to the material type, and that's assigned to the field selection group.

Selection group is a group of fields, and you can make a group of fields, either a display or mandatory

or optional or hidden.

This functionality is not just available in the Material Master, it's available in the vendor master.

It's available in the customer master.

All different kinds of master data has this functionality of suppressing fields or making fields mandatory,

and each of these master data follows the same kind of methodology.

Field selection groups, field references, and then making the major display optional mandatory.