# KOTLIN-CLASSES

//Classes

fun main()
{
val user:User=User()
user.email 
}

class User  {
 val name:String=""
val mobile: Int=1
val gender:String=""
val email:String=""
val bio: String=""
fun checkEmail():Boolean{
      return email.isNotEmpty()
}

}


//Another example of Classes

fun  main()
{
val account=Account()
account.insert(ac:12345, n:"Suajl", amnt:1000f)
a ccount.deposit(money:100f)c
account.withDraw(money:150f)
account.withDraw(money:50f)
println(account.amount)
println("Account no ${account.accNo]}")


}
class Account{


var accNo: Int=0
var name:String? Float=0f


fun insert(ac:Int,name:String,amnt:Float)
accNo:=ac
name =n
amount=amnt
}
//this point to the current receiver




fun deposit(money:Float)
{
amount+=money
println(amount)
}
fun withDraw(money:Float){
if(amount<money){  //amount=5 && money==6
println("Not Sufficient Funds")
}else{
amount=amount-money  //Short hands 
println(amount)
}
}
}





}





}
