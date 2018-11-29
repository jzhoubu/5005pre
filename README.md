# Knowledge Discover from Horizon Graph

In this session, we focus on the change of volume across various coins.

Below shows a line chart and streaming river graph, both can describe the change of coin volume across time. However, they both suffer from the large difference bewteen BTC and NEO, which makes us barely can detect any change of NEO.

## Basic Line Chart
<iframe width="900" height="400" frameborder="0" scrolling="no" src="//plot.ly/~sysu-zjw/195.embed"></iframe>


## Streaming River
<iframe width="900" height="400" frameborder="0" scrolling="no" src="//plot.ly/~sysu-zjw/206.embed"></iframe>



## Embed into Horizon Graph
To make things clear, we use horizon graph to describe the change of each coin. We use mean as baseline and standard deviation as layer height.

<table cellpadding="0">
    <tr>
        <td>
            <iframe width="600" height="400" frameborder="0" scrolling="no" src="//plot.ly/~sysu-zjw/216.embed"></iframe>
        </td>
        <td>
            <iframe width="600" height="400" frameborder="0" scrolling="no" src="//plot.ly/~sysu-zjw/220.embed"></iframe>
            <br/>
        </td>
    </tr>
    <tr>
        <td>
            <iframe width="600" height="400" frameborder="0" scrolling="no" src="//plot.ly/~sysu-zjw/218.embed"></iframe>
        </td>
        <td>
            <iframe width="600" height="400" frameborder="0" scrolling="no" src="//plot.ly/~sysu-zjw/224.embed"></iframe>
            <br/>
        </td>
    </tr>         
</table>



## Horizon Graph
Then We stack each graph of coin to make horizon graph, with which we could compare the change both inside and between.  
<iframe width="900" height="400" frameborder="0" scrolling="no" src="//plot.ly/~sysu-zjw/226.embed"></iframe>


## Knowledge Discovery
- Five types of coins' volume share nearly same distribution. They all raised dramatically during the end of 2017 and the beginning of 2018, and then went down to where slight higher than the beginning.

- The volumne of BTC is more preserving, because it only raise up to 4 * std while others raise up 7 to 10+, and reduce slower than others.

- BTC is the first coin raise up at the end of 2017, which means changes on BTC could affect changes of others.





