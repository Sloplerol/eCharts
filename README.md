# **Wonderful charts**
✨🌟💫

### Concept
> According to the way of Pictures, making us more directive to harvest the knowledge


### Simple_usage
1. Induct the online cdn or npm install
> npm install echarts or <script src="https://cdn.bootcdn.net/ajax/libs/echarts/5.4.1/echarts.js"></script>
2. Acquired the DOM element
```
let div = document.querySelector('div');
```
3. Set up a eChart instance
```
let myecharts = echarts.init(div);
```
4. Writing down the eChart Option
```
myecharts.setOption({
  title: {
       text: 'echarts paragh'
  }
  xAxis: {
      show: false,
      type: 'category'
  },
  yAxis: {
      show: false
  },
  series: [
      {
          type: 'bar',
          data: [10,20,30,40],
          yAxisIndex: 0
      },
      {
          type: 'line',
          data: [6,40,100,39],
          yAxisIndex: 1
      },
  ]

})
```

### Finally
* eCharts are widely cited in the market, hope everyone master the skill as soon as already
* If someone has a lot create in it, Making for your affection in official site
* Wish to have a good job for you
