 
So like I said in the Material Master, the first thing that we had to discuss was discuss the functionality

of the important fields.

So this part is done.

Now we are going to focus on the material type customization.

So what is material?

Type.

What is a material type?

Examples are third party.

For finished material.

Raw material.

HalB, halb.

Semi-finished.

So on and so forth.

These aren't just weird keys.

There are some controls behind the scenes.

We have already seen some controls when we were discussing quantity and value update.

So we are going to see more controls behind material type customization.

So where is the material type customization?

SPRO.

IMG.

Logistics, General.

Material master.

Settings for key fields or basic settings.

Material type.

Define attributes of material types.

The transaction is to.

So here.

You have all the different material types you want.

It's right here.

First, you want raw materials.

It'll be down there somewhere.

Ah, o h.

There you go.

Right.

You got how we got every different kind of material type here.

If you double click raw or.

These are all the different controls behind the material type.

Again, we don't need to worry about all the different controls.

We're going to discuss 6 or 7 different controls.

The first control is the cross plant material status.

What is a cross plant?

Material status.

We have already discussed this when we talked about the basic data and the material master.

We said the cross plant material status helps us in controlling the status of the material across the

supply chain.

Meaning if you want to block the procurement, if you want to block the production, if you want to

block the use in a bomb, if you want to block the use in a task list of production.

Across the supply chain.

If you want to restrict the use of the material in certain parts or all the parts, then you can use

a cross material status.

Why is it relevant here?

The material type.

Meaning when you use material type to create a raw material, what does this field do?

Say, for example, we are creating coffee beans as a raw material or we have already created coffee

beans as a raw material.

If you put a status here.

Say blocked for purchasing or blocked for procurement.

What does it do?

Let's put that block right.

Well, we don't want to really do it this way, right, Because it's a standard material type supplied

by SAP.

Let's go ahead, make a copy of this.

Create our own material type and then change it the way we like it.

Right.

So let's go back.

Select order and click copy as.

This is one of the fundamental rules of customization.

In SAP when you customize anything.

Wherever there is a possibility.

Always copy to create your own.

Why do you have to do that?

Think of it like this.

So all these material types.

Not just with material types, but with many other parameters.

Anything that SAP provides is basically a template.

Let me give you another example.

If you go to Microsoft Word, when word.

What are these?

These are templates.

This is a blank document, so a blank template.

And then these are specific templates suitable for a specific purpose.

For example, what is this student report with cover photo?

So if a student wants to make a project in his school, he can use that.

So it's a template specifically designed for a purpose.

Now, what do you do if you want to use it?

You click on that.

So it will create a word document based on that template.

So you got the title.

You got the report title.

You got the subtitle, you got the heading.

The template basically dictates how you can go about creating a student report.

Right.

But you don't go about changing the template itself.

Because if you change the template tomorrow, neither you can use the template nor somebody else who

is also using the same computer can use the template.

The template is tampered with forever.

Right.

Same thing with templates in SAP.

It is a material type and it has some controls behind it, and it's a template provided by SAP.

You don't want to change the template.

You want to keep the template intact.

Instead copy the template.

Create your own custom template.

It's like creating your own word document.

From the student report template.

Then you can change whatever you want.

Here, it's your template.

You do whatever you want.

That logic applies to not just M or SD or Phi.

It applies to every kind of customization in SAP.

So let's take our copy.

And then it says specify target.

So here you have to mention a name.

It's like saving your file name.

What name do we use?

Can we use any name?

No, we can't.

We have to follow a naming convention.

What kind of naming convention do we follow?

Any new template names Or when you copy from a standard template, you create your own.

It has to start with a Z or a Y.

So if it is first we are copying, we can say Z.

I thought we were copying our H.

So escape.

Yes, changes will be lost.

Okay.

I think we have copied.

Two and three year.

R o h.

Right.

Okay.

Deselect everything and then select click on copy.

Specified target entries.

All right.

Here we have to mention a Z.

Start with a zero and then you can have anything you want.

It's four characters.

So Z.

R01 to have a unique name.

And then we're going to have a plant specific material status here.

Hit enter.

It says so many entries have been copied.

180.

Click.

Okay.

Number of entries copied one.

Save it and it creates a transport request.

We are good to go.

Now, when you copy the template, why am I asking you to create it?

Either starting with a Z or starting with a Y?

In fact, this has so far reaching consequences that you are never allowed to create a template that

doesn't start with a Z or a Y.

Why is that?

The reason is very simple.

So SAP is an ERP system, right?

It's like any other software and it comes with updates.

Think of Windows.

This is Windows.

And it has versions, right?

It has seven.

It has eight, it has 8.1 and it has ten and it has ten point.

So many different versions with each version.

Windows does an update.

And what does that update do?

It updates certain files.

Where does it update the files?

It updates the system files.

It doesn't touch your photos.

It doesn't touch your emails.

It doesn't touch any of your stuff.

Your stuff is personal.

It doesn't touch it.

But if you look at files like C colon windows.

And then program file system 32.

Any of those system files, there's no guarantee that a file will not be touched.

Maybe there are some exceptions, but most of the time Windows is free to change whatever it wants in

there.

So those files are Windows domain.

We don't have any control over them.

But if you put something in C colon.

My name Ziva slash documents.

And then I put photos.

Videos.

Documents, so on and so forth.

Any of these upgrades will not tamper with these files.

These are my personal files.

Even if Windows updates ten times, these files will not be touched.

Same is the story with SAP.

There are so many different material types.

Write for it, be blah blah, blah.

SAP can come up with more material types as it upgrades the version.

For example, SAP 4.7, SAP 5.0.

SAP

6.06.0579.

For Enhancement Pack.

Think of it like support packs and windows.

With each version, SAP is free to create as many material types as it wants.

So say, for example, you copy and create a material type called R0 one.

Instead of doing A01, you're doing a R0 one and you start using it in this version.

Now, there is no guarantee that SAP can override this with its own version in.

Version nine.

Then all your settings are gone.

Isn't it?

To avoid stuff like that.

SAP asks you to create these templates.

Not just for material type.

Material type.

Document type.

Item category.

There are so many different configuration items that ask you to create these configuration or templates.

And when you start with a Z or a Y, for example, instead of doing it as one, if you do it as zero

1 or 0 one.

Then SAP guarantees you that it will not override anything that starts with a Z or Y.

And that guarantee is what we use to create our own templates.

Anything that starts with a Z or Y respects it and no amount of upgrades will override it.

And that's the reason why anything that's custom is always created, starting with a Z or a Y.