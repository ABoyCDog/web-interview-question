## 1、h5 储存方式？

## 2、cookie 和 session？

## 3、数组的遍历方式有哪些？

## 4、对象的遍历方式？

## 5、垂直居中的方式？

    行内元素垂直居中：
        1、line-height
        设置行间的距离（行高），将要居中的元素的line-height值设置为和其块级父元素的height值一样时，其内部内容会垂直居中
        用于单行的行内元素的垂直居中：
    	.wrap {
    		height: 100px;
    		line-height:100px;
    	}
        注意：··line-height不能使用负值
              ··在块级元素使用line-height是定义该元素基线之间的最小距离而不是最大距离
        2、Vertical-align: middle；
            .wrap{
                display:inline-block;
                vertical-align: middle;
            }
            .wrap::before{ //或者::after
                content: '';
                display: inline-block;
                height: 100%;
                display:inline-block;
                vertical-align: middle;
            }
            //

## 6、http 和 https 的区别？

    协议：网络通信之间制定的一些规则

    区别：
        1、https是http的安全版本，http是明文传输，是不安全的，https则是使用了SSL/TSL进行加密传输；
        2、http的默认端口是80，https默认端口是443.

    https缺点：
        1、https协议多次握手导致页面加载时间更久；
        2、https连接缓存不如http高速，增加了数据开销和功耗；
        3、申请SSL证书需要花费金钱，功能越强大越贵（废话）；
        4、SSL涉及到的安全算法会消耗CPU资源，对服务器资源消耗大。

## 7、页面渲染过程？

## 8、CSS 选择器优先级，从左还是从右？

    优先级：
        内联 > id选择器 > 类选择器 > 标签选择器
    顺序：
        从右到左 （因为从左到右遍历，如 .nav h3 span, 往下走错的话从头开始花销很大；而从右到左的话，花销较小；当然也不是绝对，只是大部分来说，从右到左更好，也是需要优化的）

## 9、跨域的几种方式？

## 10、react 的渲染过程？

## 11、vuex？ redux 的运行过程？

    vuex采用MVC模式中的model层，规定所有的数据必须通过 action-》mutation-》state 这个流程进行状态改变，再结合vue的数据视图双向绑定实现页面的更新。vue虽然提供了父传子props和子传父emit

    react中的redux对应vue中的vuex

## 12、reactNative 与原生的差异？

## 13、CSS 的 transition、animation、transform 各自的应用场景？

## 14、前端的安全机制都用到 webpack 的哪些特征？

## 15、如何优化首屏展示？

## 16、做过哪些性能优化？

## 17、整体的前端架构的搭建过程是怎样的？

## 18、对 flutter 的理解？

## 19、一项新技术的引进需要考虑哪些方面？
