 
So I'm just going to go back, not change any of this.

You want to change it?

No.

Then go back in again.

And open any of these, say the standard item category.

And if you see this, none of these controls are changeable.

Right?

Can you change this?

No.

Can you change this?

No.

None of these are changeable.

So let's go over each of these controls.

The first one is material required.

So for a standard item category, the material required is set to possible.

It's not mandatory.

Think of this as optional.

Right.

What does it mean?

Why is it optional?

Let me give you an example.

Let me go create a new order for vendor 4001.

Blank.

Material and.

Like that right now.

Item category is blank and it says the material is optional.

That means if I delete it.

Will it work?

It says account assignment category mandatory.

So if I go put K in here.

We put a cost center essentially for a blank item category.

What it means is I don't have to enter a material.

So material is actually optional for blank item category.

Okay.

So are there situations where material is not possible or not allowed?

Yes.

Can you think of examples?

Well in the same purchase order.

Let's think of an item or let's think of a sub process where the material is mandatory throughout that

the system does not allow the purchase order or line item to be created.

What could be one such example?

Think of a consignment.

Say, for example, coffee beans, right.

So I want to put coffee beans and I don't want to enter a material.

Right.

And I want to say consignment is right.

And £1.

Enter.

Please enter material number or account assignment category.

Now if I say cost center.

I can't do it.

I'm putting my cursor here.

I'm not able to do it.

Why?

Because that's not a valid combination.

Meaning consignments cannot be procured against a cost centre.

The reason is simple.

A consignment is typically not a sale, right?

Unless you actually consume goods from that lot.

It's not really a sale.

So what SAP is essentially saying is for consignment, you can't really procure it against a cost center

or any other account assignment.

So.

You can't just have text.

You always have to enter a material.

That means for a consignment business process or a sub business process, the material is always mandatory.

You want to check that?

Go back, select K and consignment.

The material is always required.

Right now.

Is there a situation where materials are not allowed?

Well, there are some situations, for example.

Text is one situation.

Material unknown is another situation.

Texts and material unknown.

These two item categories are examples where the item category explicitly does not allow the material

to be entered.

Why is that?

Well, we don't know what texts are, so I don't want to really comment on that yet.

But material unknown.

Is a simple case, right?

We don't know the material.

So put the item category as M, in which case the system is not going to ask you for a material.

We'll see some examples of both of these when to use material alone versus when to use text.

But in general, understand why this particular control is used.

Add the item category, the material required field controls whether a material is required or optional

or not allowed.

Think of it like the hide show display mandatory optional field at the screen level of the master data

like material, master vendor, master info record, or even at the transaction level using screen controls.

Now, in the next chapter, we're going to talk about texts and material unknown and see where they

are used.