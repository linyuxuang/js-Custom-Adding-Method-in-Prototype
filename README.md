# js-Custom-Adding-Method-in-Prototype
给js的原型链自定义添加功能方法



  例子一：    
     String.prototype.isString=function(num){
         console.log(this) // String {"hahahaha999"}
         return this.indexOf(num)>-1
     }

     var str="hahahaha999";
     console.log(str.isString(0)) // false
     console.log(str.isString(9)) //true



