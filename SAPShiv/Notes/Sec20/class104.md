 
Transcript
So let's compare a transfer posting.

Versus.

An SDO or a stork transport order.

Why do you have to use one method versus the other?

A transfer posting.

Is typically used when the source.

And destination.

It could be transporting between two different storage locations like the coffee and raw material storage

location.

Or you could use a transfer posting to do a stock transfer between two different plants, Chicago and

San Francisco.

Now, when the source and destination are close by, you typically tend to use a one step transfer posting.

If they are far away, then you have two options.

Of course, the first option is to use a transfer posting and you can also use a stock transport order.

This is far away.

This is.

Nearby or far away.

You can use transfer posting for either of these methods.

But a stock transport order is typically used when the source and destination are far away.

The second difference is transfer posting is used when you want to do a stock transfer between.

Plant to plant.

Or storage location to storage location.

A stock transport order is typically used from plant to plant.

It's not used when you want to do it from storage location to a storage location within the same plant.

A transfer posting gives you.

Two different ways to do the same thing.

One is via one step.

The second is via two step.

A stock transport order, by definition is to step.

There's no one step stock transport order.

A transfer posting cannot do external logistics.

What do I mean by external logistics?

Now when you want to transfer the goods from Chicago to San Francisco.

I said we're going to use Fedex and Fedex, say, for example, is going to use two days.

Now, the San Francisco plant is expecting this goods to be received in two days.

Where do you specify those two days?

Let's open that stock transport order.

And you can see that you can specify a delivery schedule.

Oh, I'm expecting this to take two days.

If you have multiple schedules, you can specify that there.

Like if there is a large quantity of goods to be transferred, you can do it in two trucks.

Two Fedex trucks.

One is going to take two days.

The second is going to take three days.

Sure, you can specify that in the delivery schedule.

You can also do over delivery and under delivery tolerances.

And.

And you can specify the delivery address.

Where is it going to go?

So this is all data related to logistics and you cannot specify that in transfer posting.

Why transfer posting is a very simple way to do stock transfers.

It's a pure inventory management transaction.

But a stock transport order, on the other hand, is almost like the receiving plant is placing an order

with a sending plant.

And you have all the facilities and advantages that you have when you do using a standard purchase order.

So because we can put dates, addresses and stuff like that in a in a stock transport order.

We can plan the receipts.

So the receiving plant, San Francisco plant, can just run a report and say, what am I going to receive

today?

If it's a huge truck, he's got a line up the labor force so that they can receive it.

If you're going to do that using transfer posting, the person in the receiving plant would not have

any idea because there is no question of putting date in a transfer posting.

Right.

There cannot be tolerances.

And another advantage with using a stock transport order is traceability.

Tracy ability.

What do I mean by traceability?

With the stock transport order, you have a history.

What have we done here?

We have done a good issue in a particular plant.

The sending plant.

And we have done a good receipt in the receiving plant.

How much quantity has been received?

Is there a shortfall or is there a surplus?

All of that can be tracked.

With transfer posting, you really can't track anything.

There's no history.

There's no traceability.

You don't know who has done what.

And let me explain another advantage of using stock transport order.

Say, for example.

Uh, this is America, right?

And say this is San Francisco.

And this is Chicago.

And say we are getting our coffee from Africa.

This is a good time to laugh at my drawings.

Okay.

Now from Africa.

Say the coffee comes in a ship all the way to San Francisco and then from here.

From a truck to Chicago.

Now, let's say, for example, because San Francisco has is located on the coast.

Let's say, for example, the vendor is saying that he's going to take dollar one per kilo.

In freight to deliver the plant to Chicago.

To San Francisco.

But if we want the vendor to deliver the goods to Chicago, he's going to take.

Dollar to.

One plus one, say internally, it's not just coffee that moves from Chicago to San Francisco.

We move muffins.

We move pastry.

We move so many different things.

So we have our own truck.

And because we have our own truck, we don't need this extra surcharge of moving coffee.

San Francisco plant can procure all the coffee.

And when I mean all the coffee, all the coffee requirements of Chicago and San Francisco put together,

say Chicago needs £50,000 of coffee per month and San Francisco needs 75,000 per month.

The total requirement can be planned right out of San Francisco, 125,000.

So the vendor is going to deliver 125,000 to San Francisco and the freight is going to be cheaper.

Because it's port to port.

So and the requirements from Chicago will be created.

As purchase requisitions.

With the supplying plant as.

San Francisco, not the vendor in Africa.

Can you do that using transfer posting?

No, you cannot do that.

You cannot plan anything using transfer postings, but with purchase requisitions you can.

Let's see how it works.

So go to logistics, material management, purchasing.

Purchase requisition create.

So what's our material?

Coffee.

Saving £8,000 of coffee.

And the item category over here is stock transfer as opposed to standard.

And you need them in Chicago.

And what's the supplying plant now when you create a purchase requisition?

It doesn't ask you for the supplying plant.

It only asks you what is the plant that you need the goods for?

But because you have changed the item category to stock, transport or stock transfer, it's asking

you, Oh, it's not a purchase.

It's a stock transfer between plants.

So the supplying plant is San Francisco.

And at what price?

Say $10.

Okay.

Save it.

So here is our purchase requisition, which was created not as a standard purchase requisition, but

as a stock transfer purchase requisition.

So which is this step here?

So every day or every week, the Chicago plant's planner will be creating these requirements.

Oh, I need £100 of coffee.

I need £1,000 of coffee.

So all the requirements are being tracked as purchase requisitions.

And this purchase requisition will not be converted to a purchase order that goes out to a vendor 4001.

Why?

Because we know that the Chicago plant does not have any relation with the vendor, say, sitting in

Africa because we know it's going to be more expensive if the vendor directly supplies us instead.

San Francisco plant is going to be the supplier of coffee and that's why we have created this purchase

requisition as a stock transport purchase requisition.

How did we do that?

We did that by changing the item category and thereby the system asked us to specify the supplying plant.

So we have entered the item category as you for stock transfer and supplying plant as San Francisco.

That was just a requisition.

That doesn't mean that the San Francisco is going to provide the goods.

For San Francisco to provide the goods you have to create.

An order.

How do you do that?

Go click on.

Purchase requisitions.

And what is the purchase requisition number?

And let me look at my purchase requisitions.

This is my purchase requisition.

You can just go here by looking at my purchase requisitions and then drag and drop it here.

So that's the data from the purchase requisition for £1,000 of coffee and it's in you, which means

it's meant for a stock transport order.

So in this case, we don't need a vendor, right?

What do we need?

We need.

Stock transport order.

Now it doesn't ask you for a vendor.

It automatically picks the supplying plant from the purchase requisition.

And from this point onwards, all we have to do is is do two things.

Do a goods receipt.

Do a goods issue.

Goods issue at the supplying plant.

Goods receipt in San Francisco.

The receiving plant.

Right.

So linking.

The sto.

Two requirements.

Is something that you cannot do here, but you can do that here using the stock transport order.

Now there are some more differences between using transfer posting versus stock transfer order.

But in order for us to understand it, we have to understand the concept of delivery, which is an SD

sales and distribution concept.

Since that is cross-functional customization.

I don't want to discuss creation of stock transport order using deliveries.

Now, since this course is more about inventory management, we're not going to go too much into stock

transport order, but instead start to focus more on some of the other things that we can do in inventory

management.


