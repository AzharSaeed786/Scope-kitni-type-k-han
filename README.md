# Scope-kitni-type-k-han
1.GlobalScope:

Yeh ek global scope hai jo kisi specific job ya lifecycle se nahi juda hota.
Ismein define ki gayi coroutines application shutdown tak ya unka completion tak run karte rehte hain.
2.CoroutineScope:
Yeh flexible aur common scope hai jo custom scopes ko define karne ke liye istemal hota hai.
Ismein define ki gayi coroutines ko manually manage kiya jata hai.
3.MainScope:
Yeh scope specifically UI applications ke liye design kiya gaya hai.
Ismein define ki gayi coroutines UI lifecycle ke sath judi hoti hain.
4.ViewModelScope:
Android Architecture Components mein shamil, yeh scope ViewModel lifecycle ke sath juda hota hai.
Jab ViewModel destroy hota hai, ismein define ki gayi coroutines automatically cancel ho jati hain.
5.LifecycleScope:
Yeh scope kisi Android LifecycleOwner jaise Activity ya Fragment ke lifecycle se juda hota hai.
Ismein define ki gayi coroutines LifecycleOwner destroy hone par automatically cancel ho jati hain.
