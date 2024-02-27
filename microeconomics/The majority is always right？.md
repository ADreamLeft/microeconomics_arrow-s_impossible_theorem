# The majority is always right？

## From individual preferences to collective decision

大家好，今天我展示内容的主题是“多数总是对的吗？”——从个人偏好到集体偏好。偏好代表着人们进行决策时各个选择的优先关系，是经济学研究的重要议题，微观经济学从个体出发研究个人的选择，宏观经济学研究经济体的行为模式。我们每个人决策的时候都有偏好，当然，一些天秤座除外，我们也把偏好这件事情当作理所当然，甚至在某些情况下，比如众人意见不和时，我们会采取少数服从多数的规则，定义一种优先关系。但集体的偏好或许并不仅仅取决于个人偏好的比例关系。

Hello everyone, today I will present the topic "Is the majority always right?" - From individual preferences to collective decisions. Preferences represent the priority relationship when people make decisions, and it is an important topic of study in economics. Microeconomics studies individual choices starting from the individual level, while macroeconomics studies the behavioral patterns of the economy as a whole. Each of us has preferences when making decisions, of course, except for some Libra individuals. We always take preferences for granted and even in certain situations, such as when there is disagreement among the public, we adopt the rule of majority rule or democracy if you like, defining a priority relationship. However, collective preferences may not only depend on the ratio of who like it more

## More means everything but better, not even good

下面我来向大家介绍一个例子。假如时间回到一个月前，我和我的两个舍友约好打游戏，我邀请他们上线帕鲁世界，但他们俩更想玩元梦之星。根据少数服从多数的原则，你只能玩元梦之星。那么有什么办法可以在不改变他们的偏好的情况下改变结果呢？这时候，我突然想到，其中一个舍友是米哈游的铁粉，于是我说：玩元神不如玩原神。而另一个舍友是反原吧吧友，他很不想玩原神，但是如果再在原神和元梦之星中选择时，多数人更喜欢原神，所以应该选择原神。但是，这时候如果你再说，都玩原神了，还不如来帕鲁，如果大家的偏好没有改变，则也应当选择帕鲁。于是，在少数服从多数的规则之下，宿舍的偏好在引入原神之后发生了逆转，所以也就是说，因为原神，整个宿舍不理性了。这显然是荒谬的，所以我们发现，这个时候的多数规则不能用来作为从个体偏好到群体偏好的桥梁。

Now let me introduce an example to everyone. Let's go back in time to a month ago when I made plans with my two roommates to play a game. I invited them to play "Palworld," but they both preferred to play "Fun Party" According to the rule of majority rule, I would have to play "Fun Party." Is there any way to change the outcome without changing their preferences? At that moment, it reminds that one of my roommates is a die-hard fan of miHoYo, so I said, "Playing Genshin Impact is better than playing Fun Party." On the other hand, the other roommate is against the Genshin Impact community, and he really doesn't want to play it. However, if we were to choose between Genshin Impact and Fun Party again, the majority would prefer Genshin Impact, so we should choose Genshin Impact. But at this point, if you were to say, "Since we're all playing Genshin Impact, why not play Pal instead?" If everyone's preferences haven't changed, then we should also choose Pal. Therefore, under the rule of democracy, the preferences in the dormitory reversed after introducing Genshin Impact, which means that Genshin Impact drives the entire dormitory irrational. This is clearly absurd, so we can see that the majority rule at this point cannot serve as a bridge from individual preferences to collective preferences.

## Arrow's impossibility theorem

这种关系是否是极端情况呢？会不会是因为投票人数太少或者备选方案太少导致的悖论呢？事实上，当我们尝试着增加投票人数和备选方案，我们可以发现，循环依旧存在，而且占比不低，这是用一段简单的代码运行出的结果：在多数规则之下，100个人给出它们对于10个结果的偏好顺序，大部分结果之间是可以相互转换的。这和我们刚刚发现的原神问题一样。

Is this relationship an extreme case? Could it be a paradox caused by too few voters or too few alternative options? In fact, when we try to increase the number of voters and alternative options, we can find that the cycle still exists, and it is not insignificant. This is the result obtained by running a simple code: under the majority rule, 100 people give their preference order for 10 results, and most of the results can be converted to each other. This is similar to the issue we just discovered with Genshin Impact.

事实上，经济学家通过逻辑论证过这样一个结论：满足以下三个条件的多数规则是不存在的1.If every voter prefers alternative X over alternative Y, then the group prefers X over Y.2.If every voter's preference between X and Y remains unchanged, then the group's preference between X and Y will also remain unchanged (even if voters' preferences between other pairs like X and Z, Y and Z, or Z and W change)3.There is no "dictator": no single voter possesses the power to always determine the group's preference.也就是说，即使每一个人都是理性的，多数规则依然会导致悖论。运用我们的经济学直觉，不难发现，这是因为每一次传递，都有可能发生多数人获小利少数人吃大亏的结果，这样就有可能福利小的选择显得优于福利大的选择

In fact, economist Arrow has logically proven that a majority rule satisfying the following three conditions does not exist: 1. If every voter prefers alternative X over alternative Y, then the group prefers X over Y. 2. If every voter's preference between X and Y remains unchanged, then the group's preference between X and Y will also remain unchanged (even if voters' preferences between other pairs like X and Z, Y and Z, or Z and W change). 3. There is no "dictator": no single voter possesses the power to always determine the group's preference. This means that even if everyone is rational, the majority rule can still lead to paradoxes. Applying our economic intuition, it is not difficult to see that this is because in each transmission, there is a possibility of the majority benefiting at the expense of the minority, which can make a choice with lower welfare appear superior to a choice with higher welfare.

## Fix it by more limitations

显然，这个结论是很不讨人喜欢的，因为他让民主人士失去了信仰，也对什么样的一个整体是好的形成了挑战，这就引起了许多的挑战，有很多人就提出了各式各样的解决办法，像这里有人说可以一个个排除，逐步缩小选择集，或者有人说可以为每个选择打分。但他们都不总能很好地应用。

Clearly, this conclusion is not very appealing as it undermines the faith of democrats and challenges the notion of what constitutes a good collective outcome. This has led to many challenges, and various solutions have been proposed. For example, some suggest eliminating options one by one and gradually narrowing down the choice set, while others propose assigning scores to each option. However, these approaches are not always applicable or effective.

## Your choice makes sense.

当然，以上说的都是一个简单的模型，现实的生活不可能这么简单。但我觉得，这个悖论对我们的人生是有启发性的：我们上周刚刚进行了一次比较重要的选择，它影响将持续很长一段时间，在这段时间里，我们可能会为之庆幸，也可能会羡慕别人而后悔，但是如果我们把人生的各个时刻当作一个投票人，那我们可以发现，哪怕大多数时候不够如意，总可能有些时间让你觉得值得。

Of course, the aforementioned discussion is based on a simplified model, and real-life situations are not as straightforward. However, I believe that this paradox can be enlightening for our lives. We recently made an important decision that will have long-lasting consequences. During this period, we may experience moments of contentment or envy and regret. But if we view the different moments of our lives as individual voters, we may realize that even though most of the time may not be ideal, there will always be some moments that make it all worthwhile.