struct test {
    
    static func ex1() {
         for _ in 0...10 {
            print("hello world")
        }
     }

    
   static func ex2() {
        for k in 0...43 {
            if k % 2 == 0{
            }
            else{
                print(k)
            }
        }
    }
  static func ex3(input: String) -> String {
        
       let result = "TR-" + input
        return result
    }
       
  
  static func ex4(In: Int) -> Int {
        
        var sum = 0, digit: Int
        var number = In
         while(number>0) {
         digit = number % 10
           number = number / 10
            sum = sum + digit
        }
        return sum
    }
    
  static func ex6(num1: Int, num2: Int, num3: Int){
        
        if (num1 >= num2 && num1 >= num3) {
            print(num1, "is the maximum number" )
                  }
        else if ((num2 > num1) && (num2 > num3)){
            print(num2, "is the maximum number")
            }else
            {
                print(num3, "is the maximum number")
            }
    }
  static  func ex7(numb1: Int, numb2: Int) -> Int {
        
    var multp = 0, result = 0
        while (multp < numb2)
        {
            result += numb1
            multp += 1
        }
        return result
    }
    
    static func ex8(str: String) -> String
    {
     return String(str.prefix(3))

    }
    
    static func ex9(str: Array<String>) -> Array<String> {
        
    for list in str{
            print(list)
    }
        return str
        }

    static func ex10(text: Array<String>) -> Array<String> {

    let result = text.filter { $0.count > 4 }
    print(result)
        
        return text
    }

  static  func ex11(countstr: String) -> String {
        var count = 0
        for char in countstr {
            if(char == "e") {
                count += 1
            }
        }
        return String(count)
    }
    
    static func ex12(stro: String) -> String{
         
         let newstring = stro.prefix(1).capitalized + stro.dropFirst(1)

         return newstring
     }
}

