

Ввод данных из двух цифр в одну линию. Первая цифра > 0: размер неограничен. Вторая цифра - число которое должно быть seed для рандомного объекта.   Заметим, что используем seed только один раз.  

Чтобы двигаться от первой элемента к последнему, используем метод nextBoolean()   
(jshell> Random random = new Random();  
         random ==> java.util.Random@7530d0a  
  
(jshell> random.nextBoolean();  
              2 ==> false)   
     
Метод возвращает или true или false  
Используем этот метод, чтобы заполнить поля. Если true, то  
"О", если false, то " ".  



Example 1:  
// первая цифра ввода это размер матрицы (например, 4х4)
> 4 4 // вторая цифра ввода это seed для random = new Random(4);  
OOOO  
O O  
   O  
OOO   

Example 2:  

> 4 120  
OO  
O  O  
 OO  
 O   

Example 3:    

> 10 10  
O    O  O  
 OOOO   O  
 O   OO O  
OO OO  OO  
   O       
OO OOOOOOO  
OO O O  OO  
    O O  O  
OO       O  
OOOO    O   
