==================================================================================================================================================================

  :									Day 2 OF Python                                       : 

==================================================================================================================================================================





\# Comment :



Comment वह text होता है जो Python interpreter execute नहीं करता।

Comments सिर्फ code को समझाने, notes लिखने, या future reference के लिए use किए जाते हैं।



Comment ko do tarah se likha ja sakta hai in the python



Single Line Comment :



\# Ye ek comment hai

\#code mein improtant notes dalne ke liye

\#bade code ko berief mein show karne ke liye



Note : jis line ke start mein # laga hota hai vah comment hota hai



Chalo ek progrm likh kar samjhte hai ki python comment ke sath kaisa behave karta hai.



program : print('Hello! Kaise Ho')



# mein ye coment ka upyog apne code mein kuch bhi code ke bare mein detail batane ke liye karta hun





==================================================================================================================================================================





Double line comment:



""" ye bhi line comment hai """

''' ye bhi comment hai '''



Note : """ """ triple codes ke andar hum jo bhi word likh denge, wo comment ho jaata hai.





Ab hume Python mein comment karna aata hai.





==================================================================================================================================================================







\# Variable :



Variable banane mein kya use nahi kar sakte



1.starting mein koi bhi digit add nahi kar sakte.



❌ Wrong



1name = "Gaurav"

123age = 21



✅ Correct



name1 = "Gaurav"

age123 = 21



Note : Bich mein ya last mein digit use kar sakte hai



2.Space ka use nahi kar sakte



❌ Wrong



user name = "Gaurav"

total marks = 500



✅ Correct



user\_name = "Gaurav"

total\_marks = 500



Note : Space ke badle \_ ye symbol use kar sakte hai agar space jaisa view dena ho



3.aap variable ke andar special charecter use nahi kar sakte



❌ Wrong



user@name = "Gaurav"

price$ = 100



✅ Correct



username = "Gaura@v"

price = 100



Note : Variable ka jo value store karte hai usme @ ka use kar sakte hai



4.Python Keywords को Variable Name नहीं बना सकते



❌ Wrong



if = 10

class = "Python"

for = 5



✅ Correct



if\_value = 10

class\_name = "Python"

for\_count = 5



Note : python mein kuch function built in hote hai yani pahle se hi bane huye isliye inke key word (if, class, for) ko hum as a varible use nahi kar sakte.



Ye kuch khass niyam hain jo Python mein variable banate samay dhyaan mein rakhna rehta hai.







==================================================================================================================================================================









Ab humen Python mein variable banani aata hai.





1. Simple Variable Name

सिर्फ एक ही word है।

कोई special naming style नहीं है।



✅ Example:



name = "Gaurav"

age = 21

city = "Ahmedabad"



2\. Pascal Case



Rule:



हर word का पहला letter Capital होता है।

Words के बीच कोई space या underscore नहीं होता।



✅ Examples:



SheryiansSchool

GauravSharma

StudentMarks

PythonCourse



3\. Camel Case



Rule:



पहला word small letter से शुरू होता है।

बाकी सभी words का पहला letter Capital होता है।



✅ Examples:



sheryiansSchool

gauravSharma

studentMarks

pythonCourse





4\. Snake Case



Rule:



सभी words lowercase में होते हैं।

Words को underscore (\_) से अलग किया जाता है।



✅ Examples:



sheryians\_school

gaurav\_sharma

student\_marks

python\_course



Note : Python mein sabse zyada snake case ka use karna must be better hota hai.

Isliye main recommend karunga ki jab bhi variable banana ho to snake case ka hi use karo.









==================================================================================================================================================================









Thik hai Ab hum variable banane ke 5 example dekhte hain.





Example 1 :



a = 12



b = 40





Example 2 :



n = "karan"



m = "arjun"





Example 3 :



p = 12.5



q = 17.5





Example 4 :



is\_student = True



is\_married = False

&#x20;

Example 5 :



fruits = \["Apple", "Banana", "Mango"]



veg = \["Potato", "Tomato", "Onion", "Brinjal"]





aise aap kitne bhi Variable create kar sakte ho,lekin Humne abhi sirf variable ke naam denne mein jo bhi rule lagta hai, uske baare mein jaanne hain.

variable ke value ke liye jo rule lagta hai, wo abhi Hum dekhne wale hain.







==================================================================================================================================================================









kisi bhi variable ke andar store kiye gaye value ko data kahte hain.





Wo kis prakar ka data hai? Isse janne ke liye data type ka use kiya jata hai.





Numeric: int, float, complex



Text : str



Boolean : bool



Sequence : list, tuple, range



Set : set, frozenset



Mapping : dict



Binary : bytes, bytearray, memoryview





Bigginer ke liye :



1. integer
2. float number
3. string
4. boolian
5. list
6. tuple
7. set
8. dictionary



Itna hi enough hai abhi starting ke liye.

Day 2 Ke lecture ka yahi par hum samapti karte hai next lecture mein hum varible create karna and user se iput lekar code mein implement karna sikhenge..









==================================================================================================================================================================







Day 2 - Short Summary :



Aaj humne Python mein Comment, Variable aur Data Types ke baare mein sikha.



Sabse pehle humne Comment ko samjha. Comment aisa text hota hai jise Python execute nahi karta. Comment ka upyog code ko samjhane, important notes likhne aur future reference ke liye kiya jata hai. Python mein Single Line Comment (#) aur Triple Quotes (""" """ ya ''' ''') ka upyog kiya ja sakta hai.



Uske baad humne Variable ke baare mein sikha. Variable ek container ki tarah hota hai jo data ko store karta hai. Variable banate samay kuch niyamon ka dhyaan rakhna hota hai:



Variable ka naam digit se start nahi ho sakta.

Variable naam mein space ka use nahi kar sakte.

Variable naam mein special characters ka use nahi kar sakte.

Python Keywords ko variable naam nahi bana sakte.



Phir humne Variable Naming Styles ke baare mein jana:



Simple Variable Name

Pascal Case

Camel Case

Snake Case



Python mein Snake Case ka upyog sabse adhik kiya jata hai.



Uske baad humne Variable ke examples dekhe aur samjha ki variable ke andar store ki gayi value ko Data kaha jata hai.



Data ke prakaar ko pehchanne ke liye Data Type ka use kiya jata hai.



Beginner Level ke Important Data Types:



Integer (int)

Float (float)

String (str)

Boolean (bool)

List (list)

Tuple (tuple)

Set (set)

Dictionary (dict)



Aaj ke lecture mein humne Variable banane ke rules aur Data Types ki basic understanding hasil ki.



Agale lecture mein hum Variable create karna, User Input lena aur us data ko program mein use karna seekhenge.



































==================================================================================================================================================================

&#x09;									Day 3 OF Python

==================================================================================================================================================================





Umeed karta hun practice achha chal rha hoga..



Chalo, ab ek-ek karke sare data type ki paribhasha samajhte hain.





==================================================================================================================================================================





string : String ek Data Type hai jiska upyog Text, Word, Character ya Sentence ko store karne ke liye kiya jata hai.



Python mein String ko hamesha Single Quotes (' ') ya Double Quotes (" ") ke andar likha jata hai.



Example :



name = "Gaurav"

mobile = "9870100000"



Yah sabhi String values hain.



Note : Sare word " " (Double quotes) ke andar likhna hota hai us value ko string kahte hai. jaise mobile variable ke value mein jo number hai vah integer nahi hai balki string hai kyun ki "" ke andar hai.



###### **String mein kya-kya store ho sakta hai?**



✅ Name



name = "Anshu"



✅ City



city = "Banglore"



✅ Sentence



message = "Welcome to Python Programming"



✅ Number ko bhi String bana sakte hain



mobile = "9876543210"



Dhyan do, yah Number nahi balki String hai kyunki yah Quotes ke andar likha gaya hai.





==================================================================================================================================================================





Integer : "Integer ka upyog Positive Numbers, Negative Numbers aur Zero ko store karne ke liye kiya jata hai. Integer mein decimal value nahi hoti."
Example:



age = 21

marks = 90

temperature = -5

balance = 0



Yah sabhi Integer values hain.

Note : Bina decimal ka number matlab aap integer value hi hoga.



Integer mein kya-kya store ho sakta hai?



✅ Positive Numbers



10

50

100



✅ Negative Numbers



\-10

\-50

\-100



✅ Zero



0





==================================================================================================================================================================





float number : Float ek Data Type hai jiska upyog decimal (.) wale numbers ko store karne ke liye kiya jata hai.



Jis number mein decimal point hota hai, use Float Number kaha jata hai.

Example :



price = 99.99

height = 5.8

temperature = -10.5



Yah sabhi Float values hain.



Note : float number mein integer store kiya ja sakta hai. but intiger mein agar value 10 hai to float mein integer ki value ko 10.0 ho jayega.



Float mein kya-kya store ho sakta hai?



✅ Positive Decimal Numbers



10.5

25.75

99.99



✅ Negative Decimal Numbers



\-10.5

\-25.75

\-99.99



✅ Zero Decimal Value



0.0



==================================================================================================================================================================





Boolean : Boolean ek Data Type hai jo sirf do values ko store karta hai:



True

False



Boolean ka upyog kisi condition ke sahi (True) ya galat (False) hone ko darshane ke liye kiya jata hai.



Example :



is\_student = True



is\_married = False



Yah dono Boolean values hain.

yaha par agar

True = is\_student

agar variable banaya jaye to ye galat syntax ho jayega python ise accenpt hi nahi karega.





Note : Kisi bhi line ko code mein galt ya sahi batane ke liye Boolean data type yani true or false ka use kiya jata hai.



Boolean mein kya-kya store ho sakta hai?



✅ True



is\_logged\_in = True



✅ False



is\_logged\_in = False



==================================================================================================================================================================



List : List ek Data Type hai jiska upyog ek hi Variable mein multiple values ko store karne ke liye kiya jata hai.



List ko Square Brackets \[ ] ke andar likha jata hai.



List Mutable hoti hai, yani iske values ko baad mein change kiya ja sakta hai.



Examples:



\["Apple", "Banana", "Mango"]



\[10, 20, 30]



\[True, False]



Yeh sab List hain.



Note : \[] squre brakets ke andar jab bhi multiple value store kiya huaa hoga to vah list hoga. List ke value ko baad mein badla ja sakta hai.

Ek example se dekh lete hai kaise badal sakte hai.



Example:



fruits = \["Apple", "Banana", "Mango"]

fruits\[0] = "Orange"



Fruits = \["Orange", "Banana", "Mango"]



List mein kya-kya store ho sakta hai?



✅ String Values



fruits = \["Apple", "Banana", "Mango"]



✅ Integer Values



numbers = \[10, 20, 30, 40]



✅ Float Values



prices = \[10.5, 20.5, 30.5]



✅ Boolean Values



status = \[True, False, True]



✅ Mixed Data Types



data = \["Gaurav", 21, 95.5, True]





==================================================================================================================================================================



Tuple :Tuple ek Data Type hai jiska upyog ek hi Variable mein multiple values ko store karne ke liye kiya jata hai.



Tuple ko Parentheses ( ) ke andar likha jata hai.



Example :



fruits = ("Apple", "Banana", "Mango")



veg = ("Potato", "Tomato", "Onion", "Brinjal")



students = ("Karan", "Arjun", "Gaurav")



numbers = (9876543210, 9876543211, 9876543212)

Yah sab Tuple hain kyunki inmein ek hi Variable ke andar multiple values store ki gayi hain.



Note : Agar values Round brackets  ( ) ke andar likhi hui hain, to vah Tuple hai. tuple immutable hai matlab ek baar create hogya phir badla nahi ja sakta.



Chalo dekhte hai agar hum tuple mein variable create hone ke badd add karne par kya aata hai.



fruits = ("Apple", "Banana", "Mango")

fruits\[0] = "Orange"

Python error dega kyun ki by rule tuple ke variable change hi nahi kiya ja sakta hai.



Tuple mein kya-kya store ho sakta hai?



✅ String Values



fruits = ("Apple", "Banana", "Mango")



✅ Integer Values



numbers = (10, 20, 30, 40)



✅ Float Values



prices = (10.5, 20.5, 30.5)



✅ Boolean Values



status = (True, False, True)



✅ Mixed Data Types



data = ("Gaurav", 21, 95.5, True)





==================================================================================================================================================================





set : Set ek Data Type hai jiska upyog ek hi Variable mein multiple unique values ko store karne ke liye kiya jata hai.



Set ko Curly Brackets { } ke andar likha jata hai. Set Duplicate Values ko allow nahi karta.

Examples



fruits = {"Apple", "Banana", "Mango"}



veg = {"Potato", "Tomato", "Onion", "Brinjal"}



numbers = {10, 20, 20, 30, 30, 40}





Note : Agar values Curly Brackets { } ke andar likhi hui hain aur unke beech Colon (:) nahi hai, to vah Set hai. Set bhi Mutable hota hai



Set mein kya-kya store ho sakta hai?



✅ String Values



fruits = {"Apple", "Banana", "Mango"}



✅ Integer Values



numbers = {10, 20, 30, 40}



✅ Float Values



prices = {10.5, 20.5, 30.5}



✅ Boolean Values



status = {True, False}



==================================================================================================================================================================





dictionary : Dictionary ek Data Type hai jiska upyog data ko Key : Value Pair ke roop mein store karne ke liye kiya jata hai.



Dictionary ko Curly Brackets { } ke andar likha jata hai. Dictionary Mutable hoti hai.



Dictionary ke Examples

student = {

&#x20;   "name": "Gaurav",

&#x20;   "age": 21,

&#x20;   "marks": 90

}



Yah ek Dictionary hai.



Yahan:



"name" → Key

"Gaurav" → Value

"age" → Key

21 → Value

"marks" → Key

90 → Value



Note : Agar hum {} Curly Brackets mein data ko Key : Value Pair ke roop mein store karte hain, to use Dictionary kaha jata hai.Dictionary Mutable hoti hai



Dictionary mein kya-kya store ho sakta hai?



✅ String Value



person = {

&#x20;   "name": "Gaurav"

}



✅ Integer Value



student = {

&#x20;   "marks": 90

}



✅ Float Value



product = {

&#x20;   "price": 99.99

}



✅ Boolean Value



user = {

&#x20;   "is\_student": True

}







Note :   (IMP) Mutable mein list, set, dictionary teeno mutable hai and tuple immutable hai



&#x09; (IMP) duplicate mein list and tuple duplicate allow karte hai, set duplicate allow nahi karta, dictionary only key value duplicate allow karta hai.



&#x09; (IMP) Orderd and unorderd mein list,tuple and dictionary ordered hai set unordered hai.



&#x09;(Optional) Indexing mein List and tuple Support karte hai, Set unordered hota hai, and dictionary mein key ka through access kiya jata hai



&#x09;(Optional) Slicing mein list and tuple ko slice kar sakte hai and set and dictionary ko slice nahi kar sakte hai.



&#x09;(Optional) Heterogeneous mein Python ki List, Tuple, Set aur Dictionary sab heterogeneous data store kar sakte hain.



&#x09;(Optional) Hashable mien tuple hashable value handle karta hai baaki list,set, dictionary hashable value handle nahi karta.



&#x09;(Optional) Dynamic Size mein list,set and dictionary dynamic size ko support karta hai but tuple immutable hone ke karan dynamic chan



&#x09;





==================================================================================================================================================================

