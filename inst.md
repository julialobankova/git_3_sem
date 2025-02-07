# Markdown 
Markdown (произносится маркда́ун) — облегчённый язык разметки, созданный с целью обозначения форматирования в простом тексте, с максимальным сохранением его читаемости человеком, и пригодный для машинного преобразования в языки для продвинутых публикаций (HTML, Rich Text и других).  
<https://ru.wikipedia.org/wiki/Markdown>  
![лотип](https://guidepc.ru/wp-content/uploads/2019/12/wsi-imageoptim-xjWoHHT4fBIooELdrcLO.jpg)
## **Команды для языка Markdown**

***
## Блочные Элементы
### **Переводы строк**  
> Чтобы вставить перевод строки без начала нового параграфа, в конец нужно добавить два или больше пробелов.    
### **Заголовки**
Для обозначения заголовка 1го уровня необходимо поставить:    
*# Заголовок*  
Получим:
# Заголовок
Для обозначения заголовка 2го уровня необходимо поставить:      
 *## Заголовок*  
 Получим:
 ## Заголовок
### **Цитаты**   
Чтобы обозначить цитату нужно в начале строки обозначить:  
*>Цитата*  
Получим:
> Цитата 

### **Списки**
Нумерованные списки обозначаются обычными цифрами:  
1.  
2.  
3.  

### **Горизонтальная линия** 
Обозначается тремя звездочками:
        
        ***  
Получим:
***
## Строчные элементы 

 ### **Выделение** 
 Одинарные звездочки выделяют текст курсивом:  

  Получаем:   
  *Выделение*  
  Двойные звездочки делают текст полужирным:  
  
  Получим:   
  **Выделение**  

  Чтобы текст стал зачеркнутым,
  его необходимо выделить двумя тильдами ~~ ~~, получим:
  
~~Зачеркнутый текст~~ 
 


 ### **Ссылки**
 Чтобы урл в тексте стал ссылкой его нужно обрамить знаками: *<>*
 ### **Изоброжения**  
 Изображения добавляются следующей комбинацией символов:  
 ! [альтернативный текст](ссылка на картинку)    


## Работа с удаленным репозиторием


 **git pull**    
 
Команда git pull работает как комбинация команд git fetch и git merge, т. е. Git вначале забирает изменения из указанного удалённого репозитория, а затем пытается слить их с текущей веткой.

**git push**  
Команда git push используется для установления связи с удалённым репозиторием, вычисления локальных изменений отсутствующих в нём, и собственно их передачи в вышеупомянутый репозиторий. Этой команде нужно право на запись в репозиторий, поэтому она использует аутентификацию.