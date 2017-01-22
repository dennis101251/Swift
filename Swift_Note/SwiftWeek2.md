# Swift week 2

1. #### Basic

   - 不需要分号

   - `var` 变量不需要specify

     - 可以自动根据内容进行分配变量类型

     - 不能给确定类型的变量赋值nil

       - 可选类型：类型可能可以改变

         - ```swift
           var str:String? = nill	
           ```

       - 不可选类型

         - 变量类型是唯一确定的
         - 通常情况下是为了保证不为空nil

   - `let` 用于定义常量

     - 不能改变
     - safer  

   - `print(string)`

2. #### Control flow

   - **if**

     - ```swift
       if statement{
         ...
       } else if statement{
         
       }
       else{
         ...
       }
       ```

     - 逐一检查

   - **Switch**

     - ```swift
       switch state{
         case state_0:
         	...
         case state_1:
         	...
         defaul:
         	...
       }
       ```

     - No `break`

     - 不要忘了default

     - pattern match

       - 6…10: range(6,11)
       - 6..<10: range(6,10)
       - 可以在一个范围内比较

   - **Loop**

     - **while**

       - ```swift
         var number = 0
         while number<10{
           number++
         }
         ```

       - 可以在右侧看到graph 和访问历史

     - **for**

       - ```swift
         for (var number = 0: number <10; number++){
           number
         }
         ```

       - **Fast enumerate**

         - ```swift
           for number in 0..<10{
             number
           }
           ```

         - `0..<10` 在这里实际是一个数组

         - 所以也可直接在数组中枚举 `number in [2,1,23,3] `

         - ​

     - ​

