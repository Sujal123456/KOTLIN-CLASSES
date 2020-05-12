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
