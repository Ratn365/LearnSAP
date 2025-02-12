 
cure both stock materials and non stock materials in the same order

and see how they are different.

So we have created a material.

Coffee beans zero six And to do a to order stirrers, we have to create stirrers.

Did we create stirrers?

I'm not sure.

Let's go check.

Go to zero one.

Type in stirrers.

Zero one.

And it's a raw material, but we want to create it as a non-stock material.

So use end lag.

And hit.

Okay.

And as usual, select basic data.

One Purchasing accounting.

Select Chicago one.

Stirrers.

Whatever.

Basic unit of measure each.

It's not measured in pounds.

Right?

Enter some material group.

Enter.

Just save it.

All right.

Now let's go to 21 in.

Select 4001.

And say coffee beans zero six £100.

Right.

And then stirrers.

This the IRR ers zero one.

Say, you know, we are ordering 1000 stirrers.

Whoops.

I see red there.

What's the problem?

You see the warning at the bottom?

Account assignment mandatory for servers.

It didn't say that for coffee beans.

Right.

The obvious reason is coffee beans are a different material type and stirrers are a different material

type.

So this one is a stock material and this one is a non stock material.

And how are they different?

Based on the material type this uses for material type, this uses an lag for its material type.

So go back to the material master.

If you have questions on the different material types, how they are different and see more examples

of different kinds of materials.

Now, so SAP is not allowing us to go forward because it's not a warning, it's an error.

So you can't save it.

Well, you can save it technically, but.

You can't really do anything with it.

So how do we fix this problem?

Well, we got to do something like this.

We got to put an account assignment of K.

K means cost center.

Hit enter.

And then.

At the line item level, of course, put a price and then at the line item level, go to account assignment

tab and put a cost center here.

If you put a k k for cost center, if you go to the possible list of values, you'll see that K stands

for Cost Center.

So what's really happening here?

Why is it that the coffee beans does not require a cost center, but stirrers need a cost center?

Well, when coffee is ordered and goods are received, coffee stays in stock in the warehouse.

So coffee is really stock.

Let me go back here.

So when when you order coffee, Coffee says stays as stock in the warehouse because it's a stock material.

Raw material.

And you know, stirrers are raw material, too.

But but you have created it as an lag non-stock material.

That means the system does not track the stock.

Well, there is still stock, but system does not track the stock and it's not treated as stock.

So when?

So when?

Non-stock materials like stirrers or baking sheets or ordered, they don't stay as stock.

They are deemed as consumed immediately.

Now, I know it's confusing, so just stay with me here.

When coffee beans are received and put in stock, it's sitting there waiting to be consumed.

Right.

So the principle is really simple.

This is the principle of dual entry accounting.

So for every transaction there should be an equal and opposite amount of entries, equal credits, equal

debits.

Think of it like a seesaw.

You put something here, you put something here.

Equal and opposite.

It's balanced, right on one hand.

We have paid the vendor.

Say a value of $1,000.

For what?

£100 of coffee and we have £100 of coffee sitting here.

So it's balanced.

So we have stock of £100 and we have paid the vendor of $1,000.

Now, how about Non-stock materials?

Let's say.

Be awarded.

Thousand dollars worth of stirrers.

Right?

The same vendor and we don't store them as stock.

Say we get 10,000 stirrers.

Where are they?

Will.

They are there in the warehouse.

Nobody's going to eat them.

But where are they?

They are deemed as consumed.

What does that mean?

It's not in the stock, but it's still in the warehouse.

That's totally confusing.

Definitely.

No, they are kept physically in the warehouse, but the system is not tracking the stock.

So there are three things here.

They are physically in the warehouse.

And second point is.

ASAP is not tracking it, not tracking the stock, Not tracking the value.

And we are seeing the stock is deemed as.

Consumed.

So they're physically in the warehouse.

The stock is deemed as consumed.

But SAP is not tracking it.

You got to understand these three things, really to understand what non-stock materials are.

So logistically speaking, like I said, there's no difference between coffee beans and steroids in

terms of procurement.

They're there in the warehouse like any other stock.

But SAP is not tracking the stock because we have created that material as a non stock material.

All right.

Now, when SAP is not tracking it, that means that it is off the books.

And when something goes off the books.

It has to be either consumed or damaged.

When I mean consumed, there are many possibilities.

A shop that requires coffee stirrers could consume it.

Or the coffee Stirrers could be burned and they're gone.

They're off the books now.

So when they are consumed, somebody is bearing the cost of it.

That's the bottom line.

How can somebody bear a cost for a material?

Somebody in the company that's done using what is called as a cost center.

Now, there are other ways of consuming.

For example, a customer could consume some stock, and that's called consumption via sales order.

A production order meaning an order to manufacture cakes could consume raw material.

So that's called consumption against a production order.

Right.

There are different ways in which talk can be consumed, and the simplest way is consumption against

a cost center or a department.

The word cost center.

Don't let that word scare you.

A cost center is a technical word for.

The department.

So what departments does my coffee shop have?

I have a marketing department taking care of flyers and advertising my coffee shop.

I have a production department making cakes, pastries and all the good stuff.

I have my HR department taking care of employees salaries, promotions, etcetera, etcetera.

I have a finance department taking care of accounting.

Right.

Each department will incur some costs.

The HR department might need paper for printing.

So paper is a cost that the HR department is incurring and paper needs to be procured.

So all orders of papers that are coming in will be charged against the HR department if that's the only

department that uses it.

Why are we not putting in stock and charging directly to the HR department?

That's a good question.

We'll get to that in a minute.

So for now, let's create this cost center.

And creating a cost center is creating a code for a department as simple as that.

Okay.

Now.

How to create a cost center.

The transaction for that is.

So the transaction to create a cost center is CS zero one.

And the controlling area is 2000.

That's what we have been already using.

We're going to create a cost center for h.r.

h.R.

Zero one.

And it's valid from today.

Give it a name.

h.R.

Department.

Our description does matter.

Person responsible say I am responsible.

And the cost center category.

Uh, say administration.

Because it's all right.

Administration and the hierarchy code.

You can always go and select from the possible list, say, finance and administration.

Company code, of course, is US zero one.

And the currency is USD that will be derived automatically.

And say, oops.

Okay, so it says the company code is not created.

Let's fix this problem real quick.

Go to enterprise structure.

Assignment.

Controlling.

A company code to controlling area select 2000.

Click on new entries.

Enter your zero one.

Don't worry about this step.

It's not important for us.

All right.

And we've done some magic behind the scenes, so let's go back and try this again.

K is zero one.

Zero one.

For the name of HR department.

The person responsible is Siva.

And the business area is.

The business area is something hit enter.

Save it.

Now let's go try to order those terrors again.

4001.

And order coffee beans for the first item.

And stirrers for the second item.

It says account assignment mandatory.

And we've said in the a column of the account assignment column put a value of K.

Hit enter.

For the price.

Price could be $10, $20, whatever.

And an account assignment.

We're going to say h.r.

Zero one.

So what we are essentially saying is.

The cost of.

One quantity of stirrers.

Whatever the price is, the cost of stirrers is to be consumed by the department.

Don't worry about this error.

We're going to fix this.

But try to understand this concept.

The cost of steroids is consumed by this department.

So when something is consumed, it's no longer in stock.

Done.

It's consumed already.

That's the reason why ASAP does not really track stock because it's consumed.

It's done.

You can physically keep it in the warehouse because you don't have you don't want to keep your stirrers

right by your desk.

Right.

You could keep it in the warehouse, but purely from a consumption perspective, they are consumed,

done.

They are no longer tracked as stock.

So the vendor has been paid and some department has consumed it.

And that's how it will be accounted.

Right now.

Let's go fix this problem.

Version zero is not defined for fiscal year 2016.

And the way to fix that problem is.

Go open a new window.

Go to Octave.

This is all controlling so you don't have to really understand it.

Somebody else will fix these things for you.

So since there is no finance consultant, we are doing it all on our own.

Enter controlling area 2000.

Click.

Okay.

And it says I've locked the cost center.

All right.

So we'll save that.

Go back.

Go back, Go back.

And come here.

I say no and try again.

Hit enter.

And go to version zero and settings for each fiscal year.

Right here.

Enter.

Or copy 2009 into 2016.

That's the current.

Fiscal year.

And save it.

Doesn't matter.

Any transport and we're done.

Let's see if this gets refreshed.

Click Enter.

Save documents till 40.

Now we want to edit it.

Purchase order, blah, blah, blah.

Looks like that's not refreshed.

So let's go back and come again to save the document now.

So M 21 n.

Put your vendor of 4000.

And everything else is taken care of for you.

You start entering the materials.

So coffee beans, the first item and stirrers.

The second item.

It says Account assignment Mandatory.

We know what to do.

Enter K here.

And then enter the price here.

And then enter H.R. as the department that's going to consume the cost of that material.

That's it.

Now, you can save that transaction, right?

All right.

What have we seen here?

Creation of cost center transaction zero one.

And we have entered some details.

Doesn't matter what details.

And we've entered.

Key is the account assignment.

For starters and under account assignment.

We have entered admin, hr, whatever as the cost centre that we have created.

So the cost of this material, whatever the quantity is.

Is being absorbed or consumed by this cost center.

And that's achieved.

Through account assignment.

So.

Account assignment.

Is a modifier.

That modify.

So account assignment is really a modifier to the way accounting is done.

And like I said, the logistics does not change.

You go to the same.

Receive both the materials you go to same pay for both the materials pure.

Nothing really changes from a logistics perspective.

The only change is from an accounting and consumption perspective.

And eh, the account assignment column is used to effect that modification.

In this case we are consuming against a cost center.

There are other ways to consume it, which we'll see in the next set of chapters.

So we can create more cost centers.

Marketing could be another cost center.

So create a material called flyer and then consume it against a cost center of marketing.

Right?

So if the marketing department needs flyers, they'll be consumed against the marketing department cost

center.

So anybody creating a purchase order for this material should have to enter here and then enter the

cost center here.

Done.


