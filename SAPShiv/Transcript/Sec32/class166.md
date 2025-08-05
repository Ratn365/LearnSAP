 
All right.

Now that we understand why we need to start with a zero, why now?

Let's go inside the controls.

Zero one.

And now we were talking about the first control cross plant material status.

We know what it does in the material Master.

But what does it do in the material type?

Any material that you create now with this material type will automatically have this cross material

plant status defaulted to BP.

You want to check that?

Sure.

Did we save it?

Yes, we saved it.

So go to.

M0 one.

And remember this material type zero one.

Retail z.

R01.

And I'm not even putting a material, it'll automatically pick it up.

Click on basic data.

They see that I didn't put anything here, it automatically defaults to beep.

So now why do you want to use this parameter?

Or why do you want to use this functionality?

Some materials by default start out with a certain status.

For example, think of Apple.

Apple is creating a product, say a brand new iPad, iPhone, whatever.

When it's creating that product, it doesn't want to sell it yet, but it wants to create that material.

Why?

Because that material needs to be planned.

That material needs to be manufactured.

That material needs to be stocked.

That material probably needs to be procured.

All of the functionalities can be done except for sales because they are not ready yet until somebody

announces it.

The point being, by default you allow everything for a new material except sales.

And when you're ready to sell, you go and remove the cross plant material status whereby you're allowing

everything and anything to happen with that material.

So by default, if you want to set a certain status so that certain activities are prohibited in the

logistics supply chain cycle of that material, then you use a cross plan, material status.

Next is the item category group.

I don't want to discuss the item category group much.

The reason being it's more of a sales functionality.

But nevertheless.

Just keep it in the corner of your mind.

That item category group is an important field and you can default it right from here.

Right.

So we have seen so many different number ranges so far.

We have seen finance number ranges in FB and one.

So whenever we post a goods movement or whenever we post an invoice receipt, as says, Oh, this number,

Range 51 does not exist.

So we went to Fbn1, created a number range.

When we try to do goods movement.

Initially, the very beginning of the course, there were some issues saying, hey, you know what,

I can't post this goods movement because some number range is missing.

Then we went to the goods movement number ranges, created number ranges.

Same thing with material.

Every material type is assigned a set of number ranges.

One external number.

Range one internal number range.

So let's see how they are assigned.

Okay.

It's right here.

Define number ranges for each material type.

So here you create number ranges, group them and assign material types to groups.

If you look at the groups or if you go to the groups.

For example, Group one is assigned to a particular number, range one internal and one external.

So if you try to create one more number range, for example.

Edit insert interval does not work because each group can only be assigned to one number range.

So let me put it this way.

Material type.

And there's a group.

And there is external number range and.

Internal hemorrhage.

So there is a third finished material.

There is a raw.

Raw material, so on and so forth.

And.

N number of material types can be assigned to a group.

Group one.

And each group can be assigned precisely at most one external number range, and at most one internal

number range.

Now, why would you need an internal number range?

Let's look at an example.

So if you go to zero one.

Right.

Zero one.

For example, hit, enter, say, basic data.

Hit.

Enter.

You see that?

One, Four, two, three.

That's a number that's automatically assigned by SAP based on the internal number ranges.

And what's that number?

Range.

Let's go back to the config.

So where is zero one?

Go hit the binocular and select zero one.

Okay.

It's right here.

And that is assigned to which group it got assigned automatically because the standard material type.

So it's assigned to which group?

Group one.

So select group one and click on this function and you see that this is the number range.

It starts from zero and ends in 99999, and the current number range is 1426.

So current number range is typically buffered, so don't try to exactly match it.

There will be some differences.

For example, it's one, four, two, three.

The next time you create material again, zero 1 or 0 one, it will create 1424.

142514361427.

So on.

That is if you use internal number range.

If you want to assign an external material number, range to it.

This is the number range, anything from one character to 6 or 7 characters.

How many do we have here?

I think we have seven, seven characters.

Now you can change this.

You can go on to change it to whatever you want, you know, want.

This is 8/9, right?

You want 9/9?

Sure.

You can do that.

And that's the target number range.

You can start with another number range.

You can start with so many different fives.

Right.

So this is how you maintain number ranges.

Number ranges are typically not very relevant for materials unless you want to always use internal.

And some companies, in fact, SAP.

Recommends that you use internal number ranges for materials because it's easier.

It's auto generated, so you don't have to come up with creative names.

But nevertheless, business tends to typically use names like coffee beans oh one or coffee beans,

coffee beans, Arabica.

The name is restricted to 18 characters.

For example, if you look at this hit F1.

Or help button.

And if you go to the technical information.

You see that this is the field name, this is the data element.

Double click on data element and you'll see that material number.

Is 18 characters, and that's the maximum limit.

You can change it.

Go back.

Close this.

Close this.

And let's come back to where we were.

Number ranges, right?

So this is how you create number ranges and assign it to the material type.

Now, we were talking about this field here, external number assignment without check.

So if you check this on, that means that system does not worry or check the name that you've entered

against the external number range.

Basically it allows you to go wild and create any name you want.

It doesn't check it against the external number range.

Now, sometimes if you don't want to allow that, if you want to restrict all external naming to that

A to Z, Z, Z, Z, Z, seven characters, then you check it off.

Okay.

Once you check it off, the system does not allow you to create anything out of that number range in

the external number range, internal number range.

Anyway, we don't have control.

So with respect to number ranges, a material can have two number ranges, one external, one internal.

SAP recommends that you use the internal number range and you use the external number range most of

the time in the industry because it's easy to remember.

But if you have a large number of materials.

Think of Walmart.

Walmart has, like, I don't know, millions of materials.

In cases like that, it makes sense to go with internal number range.

You can't create mnemonics for millions of materials, right?

So it depends on the nature of the industry.

Either way, ASAP recommends that you use internal number range and if you want to use an external number

range, you are free to use it.

And check this on if you don't want SAP to check against the external number ranges that you have configured

against the material type.

Basically, this allows you to create whatever kind of external number range you want within the limitations

of 18 characters.