# Reading_20170406
## 涂鸦 About me  <br>
- 今天又看了很多，有本《Web全栈工程师的自我修养》种草了，想买一本，其实可以先读读别人的读书笔记，已记录在Evernote。  
- 阮大推荐的[深度优学](http://cn.udacity.com/)看起来不错的样子，想学习看看。<br>
- 突然又想到以前那些瞧不起百度的“开发者”，现在回过头来看看，这帮人的眼光还真是短浅，百度，甚至说在国内的开发环境越来越好了。真是打脸，微博上那个E开头会不会从此不提这茬，甚至墙头草呢？嘛，我也不想去理睬此类自喻高端的“技术人员”，但我之前的观察，他还真不算技术类的，应该是个产品或者管理吧。 

## 目的   
- Git
- Vue
- 考试
- javascript
- 目录
- 写个栗子  
- 同步异步
## Main
### 目录  
大致的框架已经搭建完成，以后就慢慢码字


### Git

### Vue

### 考试

### javascript

### 同步异步
同步：当一个同步调用发出去后，调用者要一直等待调用结果的通知，直到得到调用结果。异步：当一个异步调用发出去后，调用者不能立即得到调用结果的返回。<br>
异步调用，要想获得结果，一般有两种方式：<br>
1、主动轮询异步调用的结果;<br>
2、被调用方通过callback来通知调用方调用结果。<br>

举个栗子：<br>
同步买奶茶：小明点单交钱，然后等着拿奶茶；<br>
异步买奶茶：小明点单交钱，店员给小明一个小票，等小明奶茶做好了，再来取。<br>
异步买奶茶，小明要想知道奶茶是否做好了，有两种方式：<br>
1、小明主动去问店员，一会就去问一下：“奶茶做好了吗？”...直到奶茶做好。<br>
2、等奶茶做好了，店员喊一声：“小明，奶茶好了！”，然后小明去取奶茶。<br>

阻塞与非阻塞<br>
阻塞与非阻塞的重点在于进/线程等待消息时候的行为，也就是在等待消息的时候，当前进/线程是挂起状态，还是非挂起状态。<br>
1、阻塞调用发出去后，在消息返回之前，当前进/线程会被挂起，直到有消息返回，当前进/线程才会被激活。<br>
2、非阻塞调用发出去后，不会阻塞当前进/线程，而会立即返回。<br>

举个栗子：<br>
1、阻塞买奶茶：小明点单交钱，干等着拿奶茶，什么事都不做；<br>
2、非阻塞买奶茶：小明点单交钱，等着拿奶茶，等的过程中，时不时刷刷微博、朋友圈...<br>

同步与异步，重点在于消息通知的方式;<br>
阻塞与非阻塞，重点在于等消息时候的行为。<br>
所以，就有了下面4种组合方式<br>
同步阻塞：小明在柜台干等着拿奶茶；<br>
同步非阻塞：小明在柜台边刷微博边等着拿奶茶；<br>
异步阻塞：小明拿着小票啥都不干，一直等着店员通知他拿奶茶；<br>
异步非阻塞：小明拿着小票，刷着微博，等着店员通知他拿奶茶。<br>
