# gallery-react
My first react demo, drag gallery using react.学习慕课网上materliu老师的教程做的练习，其中有两个地方不太一样，获取dom元素时候直接用this.refs.***获取，没有用findDOMNode方法,还有虚拟的数组数据，然后父组件访问子组件的refs有点儿问题，这里是避开了，方法是在子组件加了ref然后用父组件的this.refs.组件ref属性.refs子组件名获得的，感觉有点憋。
