# KIRILL KNYAZEV

## CONTACT
Phone: +375445554365  
E-mail: <kiryl.kniazeu@gmail.com>  
Discord: Kiryl#6985  
GitHub: [Kiryl1337](https://github.com/Kiryl1337)  
Location: Gomel, Belarus  

## ABOUT ME
I am 22 years old. I have graduated from Gomel State University named after Francisk Skorina in 2020. I have studied at the Faculty of Mathematics and Programming Technologies.
My main goal is to obtain a position of Software Junior JavaScript Developer that will allow me to use my knowledge of programming and teamwork. 
I am hardworking and always try to do all my best to achieve perfect results

## EXPERIENCE
March-2019 - May-2019 - Student, GSU F. Scorina  
Project: Museum  
Team Size: Dev Team: 1 member  
Project Role: C# Developer  
Environment:  
* MsSQL Database  
* C#  
* WPF technology  

Jan-2020 – May-2020 - Student, GSU F. Scorina  
Project: CourseDiplom  
Team Size: Dev Team: 1 member  
Project Role: PHP(Yii2) Developer  
Environment:  
* MySQL Database  
* PHP(YII2)  
* PHP 5.5, MySQL 5.6, Open Server  

Aug-2020 – Oct-2020 – first work after University as a 1C developer  

## EDUCATION
**University**  
2016 - 2020: Gomel State University named after Francisk Skorina  

## SKILLS
* JavaScript
* HTML/CSS
* Java 
* OOP 
* SQL(MsSQL, MySQL) 
* PHP(Yii2)

## LANGUAGES
English: Pre-intermediate  
Russian: Native speaker  

## CODE EXAMPLE
*Task:* Implement the function unique_in_order which takes as argument a sequence 
and returns a list of items without any elements with the same value next 
to each other and preserving the original order of elements.
```javascript
var uniqueInOrder=function(iterable){
  let arr = [];
  if(Array.isArray(iterable)){
     arr = iterable;
  }else{
     arr = iterable.split(''); 
  }
  let res = [];
  for(let i=0; i<arr.length; i++){
    if(arr[i] !== arr[i+1]){
      res.push(arr[i])
    }
  }
  return res;
}
```