 
All right.

So what have we seen so far?

In terms of the entire business process.

There are three important parameters that control the business process at the line item level.

One is the document type.

The second is item category.

The third is a counting indicator.

Now this has the most influence on the business process.

An item category.

An accounting indicator to a lesser extent.

So whenever you want to model a business process, these are three main parameters.

Now, what do I mean by business process?

Some of you might already understand it.

But if you don't understand it, I want to give you an example.

The word business process is sometimes confusing to people who are learning, you know, these kinds

of courses for the first time.

So what's a business process?

Let's take a scenario.

Say our coffee company.

Imports a special type of coffee from Kenya.

Okay.

It's importing a special type of coffee from Kenya.

And special import licenses are required.

And it's a totally different process.

Right.

As opposed to what?

As opposed to domestic handling of this process.

So in America, again.

The Chicago.

Right.

And this is Africa.

There's Kenya now.

There is domestic procurement of coffee.

Coffee is procured from so many different vendors either in Chicago or outside of Chicago.

This is all domestic.

And there is a special brand of coffee that we import directly from Kenya.

The vendor might do it for you, but you are importing directly from Kenya.

In which case.

You know, there are special processes that are required for imports.

So the business process required for domestic might be different from the business process that's required

for imports.

So the business has decided that they are going to have a separate business process for imports.

And when they mean separate business process in that business process, they want to have a separate

number range.

Why?

Because they want to clearly demarcate an import order versus a domestic order.

Just by looking at that number, they should be able to tell that it's an import order.

And in that business process Consignments.

Subcontracting or these kinds of business processes are not allowed in imports.

Right.

You might want to create this import orders with reference to purchase requisitions.

Right.

And as usual, returns and credits are allowed.

How do you model this business process?

This is an example of a business process.

A special business process.

How do you model this?

Step number one.

You create.

A new engine.

Right.

You want to set up a new train between us and Kenya?

You create a new engine.

A separate engine that can take care of that or that can differentiate that business process.

Create a new document type.

Remember, document type is the engine.

Number two.

Is what kind of item categories are allowed.

You said we are not allowing consignments.

We are not allowing subcontracting.

These are business processes that are controlled at the item category level, remember.

L For subcontracting.

D For service.

Be for limits.

So on and so forth.

Right?

Only.

A low standard.

Item categories.

Right.

The third requirement is purchase requisitions are allowed.

So envy or whatever kind of purchase requisition.

Should be allowed to be converted to the new document type for purchasing.

You can disallow it if you want.

Right.

Number four.

They wanted a new number range.

So create new number range.

Right.

And in this case, do you allow.

Processing against a cost center.

Meaning can a cost center procure goods from Kenya?

Probably not.

You don't want to allow it for domestic, it's okay.

But for imported, you don't want cost centers to import goods.

Right.

You want them to be stock materials in your stock, in which case you can do some adjustments.

But overall, I'm trying to arrive at the point that.

What we are essentially doing is modeling a business process.

And a business process consists of specific requirements.

The standard system right out of the box like an NBI document type cannot cater to you got to slightly

customize it.

And what we are essentially trying to do is create a new template, a copy from what standard SAP provides,

and tweaking it, just like our word document is being tweaked.

So how do we do that?

So go to Sbarro.

IMG.

Materials management.

And then go to purchasing.

And what are we trying to configure?

We're trying to configure a purchase order.

We're not trying to configure a contract or a scheduling agreement.

We're trying to configure a purchase order.

So this is one of the document categories.

Purchase order, Right.

When we have to configure a new contract, you go to contracts and go to document types.

So what's the standard document type in B?

So you don't copy from UB, right.

This is a stock transport order.

And with Kenya, we don't want to do a stock transport.

We don't have a plant there.

Right.

So we don't want to do a stock transport.

It's a regular vendor from which we are going to import goods.

So it's a standard order.

So what we are going to do is copy from the nearest template.

The nearest template in this case is standard.

It's not stock transport.

It's not something else.

So select NB Copy.

Then what do you want to call it?

Z.

If it's import Z, I01 and we want to change the description to.

Import order.

Select copy all for now.

Okay.

I'll tell you what's being copied.

Copy it and save.

All right.

So it saved.

We have created our own custom document type.

And if you go back inside, go to Z.

Z.

I01.

And inside that there is a hierarchical structure of what item categories are allowed and what purchase

requisitions can be linked to.

So we have created this step, right?

We have created a new business process.

Z import zero one.

And we said only standard item categories are allowed.

What is the standard item category?

Blank.

Right.

That means we don't want to allow limit.

We don't want to allow consignment.

None of this stuff.

Delete that because it's our own custom template.

We are free to delete it.

Delete all entries.

Yes.

And Inside Standard.

What kind of purchase requisitions are allowed?

Probably you don't want to allow all different kinds of purchase requisitions you only want to allow.

Standard purchase equation are not even a stock transfer.

So we are selecting the stock transfer line item and clicking on delete.

And save it.

Now you got a very lean.

Document type.

Z.

I01.

Which only allows the standard process.

And which can be linked only to a standard purchase requisition.

Right.

So this step is done.

Now we have to create a new number range.

How do you do that?

Number ranges.

Now, what kind of number ranges do you want to create?

The business just said we want a different number range.

Okay.

What kind of number ranges are there and what does the purchase document type and we use.

Let's go back to the purchase document, type in B or the one that we have created, Right?

And the item number range is.

45 number range internal and this is number range external.

So what's the internal number?

Range 45 and that's what has been copied into zero one.

If you look at these two, all the parameters, all the controls will be the same.

Same item number increment.

Same number.

Range interval internal same number.

Range interval.

External same.

Everything is same.

Every parameter is the same.

And that's why it's called a copy.

You are copying from a template and everything in the template comes through.

Now you are free to change whatever you want.

Right.

You want to change the number range internal change it from 45.

45 is worth 45,000 to 45,000.

999.

You want to change this to something else?

Right.

What do you want to change it to?

So this starts with 43 to 44.

45 to 40.

So if you want to create a new number range, let's say something in the range 44.

So I'm copying this number.

Right.

And I want to create a new number range, starting with 44 000 until 44.

Some number range.

Okay.

Just some number.

So go back.

Go to number ranges.

Go to intervals and edit an interval or insert an interval.

If you want to call it Z five, let's say, or Z four.

This is the number range we want to start 44 000.

I don't even know what that number is.

All the way up to, uh, let's say.

Nein, nein, nein, nein, nein.

Right.

And it's internal, not external.

If it were external, you should have to check this one.

Right now, I don't know if this number is already taken.

I don't know that.

Save it.

And it says enter intervals without overlap.

That means that there is some number range here that has already taken that four, four or that number

range four four starting with four four.

Right.

Which one is that?

Look at this.

44 is already taking that number.

So if necessary you might want to use that.

Now, if that suits the requirement, you might want to use it.

If not, you might have to again go back and see what's the range that is not already taken.

Say five is taken, six is taken, four is taken.

How about something starting with a three?

Right.

So let's start with a three like that and.

Like that.

Now what's the total range you are giving?

99999.

Meaning starting with this number, you can go on up to 100,000 almost.

And beyond that, it expires, Right.

So you don't want to limit to 100,000.

You might want to give it, you know, a full range like like so.

But for our test, we might want to go with a small range.

But if in production, really go with the full range.

Full range of numbers because you don't want to exhaust numbers.

Okay.

So Z four is the one that we have created, right?

Is it there?

Z4 And we are starting with this number ending in this number.

And it's not external, it's internal.

Save it.

And it says number ranges cannot be transported.

We'll see why this cannot be transported and how to actually create these number ranges in a productive

system.

Okay, you say?

Okay.

Save it.

Go back.

Go back.

Now click on document types.

And what's our document?

Type Z import zero one.

Right.

And for internal number range, we don't want 45 like NB, we want z for.

Right.

See, we have copied the template and now we are doing changes like the way we have created our own

combination of item categories are our own.

Possible purchase requisitions from which this order can be created.

Now.

Let's go back and create a purchase order.

Emmy 21.

Don't let it be NB Because we have created our own business process.

Okay, Enter our own vendor 4001.

Material is coffee beans one.

Enter.

The contract exists.

It's all right.

It's all right.

Just click save.

Issued some messages.

No message generated for output.

Okay.

Contract exists.

All right.

That's all right.

And.

See.

What's the number?

You see that?

It's in our number range.

34000.

And it created what?

An import order.

Now, if you create another purchase order, it will create 3400001 and the next purchase order is going

to be 34002.

So this part is done.

Right now, let's add some more requirements.