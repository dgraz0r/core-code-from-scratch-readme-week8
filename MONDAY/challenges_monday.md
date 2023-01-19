# MONDAY CHALLENGES WEEK 8

## Training JS #7: if..else and ternary operator

![image](https://user-images.githubusercontent.com/117783981/213355886-16697461-027b-4f72-ab41-f334404ddf07.png)

![image](https://user-images.githubusercontent.com/117783981/213355916-08beb42c-a040-462a-8a5a-053c571a0c64.png)

![image](https://user-images.githubusercontent.com/117783981/213355957-773331fe-6e13-4e2f-994e-1001e0595862.png)

![image](https://user-images.githubusercontent.com/117783981/213355978-54e2e0bf-9ba5-4cfa-a2c7-579b825f4202.png)

function saleHotdogs(n){
  if (n < 5) {
    return n * 100};
  if ( n >= 5 && n < 10) {return n * 95};
  if (n >= 10) {return n * 90};
 
}


## Training JS #8: Conditional statement--switch

![image](https://user-images.githubusercontent.com/117783981/213360821-50860147-07c2-4ec4-86ff-45f119928687.png)

![image](https://user-images.githubusercontent.com/117783981/213360870-f8f808ac-5c1c-4d59-9b45-845f1d3b6546.png)

function howManydays(month){
  var days;
  switch (month){
      
      case 1:
      days = 31;
      break;
      
      case 3:
      days = 31;
      break;
      
      case 5:
      days = 31;
      break;
      
      case 7:
      days = 31;
      break;
      
      case 8:
      days = 31;
      break;
      
      case 10:
      days = 31;
      break;
      
      case 12:
      days = 31;
      break;
      
      case 2:
      days = 28;
      break;
  
      default: 
      days = 30
      break;
  }
  return days;
}
