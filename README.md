# zepto-slider
基于Zepto移动端滑块插件（更改自现有的jQuery版本）

 ![zepto-slider](https://github.com/chenruchang/zepto-slider/blob/master/image/demo.png)
  
  $('.single-slider-yellow').zptSlider({
        from: 0,
        to: 100,
        step: 1,
        scale: [0, 25, 50, 75, 100],
        format: '%s',
        width: 250,
        showLabels: true,
        showScale: true,
        theme: 'theme-yellow',
        onstatechange: function (value) {
          var start = value.split(',')[0];//起始值
          var end = value.split(',')[1];//结束值
        }
  });
  
  
  $('.range-slider-pink').zptSlider('setValue', '2, 120');//给控件设置值