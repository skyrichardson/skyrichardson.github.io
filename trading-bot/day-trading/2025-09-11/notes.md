<div style="max-width: 700px">
<figure>
  <blockquote class="blockquote">
    <p>
        For those interested in trading automation: Today's acton seems like some asset allocation trade was going on with a broad number of stocks up (ignore my opinion as I am just a random dude on the Internet). However the market conditions highlighted a shortcoming of simply using TWS BasketTrader to automate execution. The trading rule of no more than 5 trades per algo protects you from over allocation .  For example 7 of the 10 Second_Day_Short setups triggered. There will always be days when an algo works contrary to the broader market direction. The max positions rule reduces the damage on days like this. Sadly there is no way to make condtional orders with TWS. The best i have come up with is a bot that tracks total positions for each algo and when the max allocation is reached does two cancels orders that have not triggered. Ideally the bot would also close any positions above the max allocation but this is an edge case that is not a priority for now. Is there another way to handle this scenario?
    </p>
  </blockquote>
  <figcaption class="blockquote-footer">
    As commented on the <a href="https://discord.com/channels/842788888615714816/1292846053925585029/1415924665104465971">Discord server</a>
  </figcaption>
</figure>
</div>