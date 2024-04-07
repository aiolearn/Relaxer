<h1 align="center">Welcome to Relaxer Project! 👋</h1>

# Relaxer

In this project, we have written a relaxer program to relax programmers

## Skills

Html , css , javascript

## Usage

First, we have written and read a constant variable to read the text and the parts that change

```javascript
const text = document.getElementById("text1");
const circle = document.getElementById("circle");
```
Next, we wrote functions to run the program, in each of which different parts are executed
```javascript
dam();

function dam(){
   text1.innerText='Breathe In!';
   circle.className=' circle dam';

   setTimeout(() => {
       hold();
   }, 2000);
}

function hold(){
   text1.innerText='HOLD!';
   circle.className=' circle hold';

   setTimeout(() => {
       bazdam();
   }, 1000);
}

function bazdam(){
   text1.innerText='Breathe Out!';
   circle.className=' circle bazdam';

   setTimeout(() => {
        dam();
   }, 2000);
}
```

## Result

This project was written by Majid Tajanjari and the Aiolearn team, and we need your support!❤️


# ریلکسر

در ادامه توابعی برای اجرای برنامه نوشتیم که در هر کدام قسمت های مختلفی اجرا می شود

## مهارت ها

Html , css , javascript

## نحوه استفاده

ابتدا یک متغیر ثابت برای خواندن متن و قسمت هایی که تغییر می کنند نوشته و خوانده ایم

```javascript
const text = document.getElementById("text1");
const circle = document.getElementById("circle");
```
در ادامه توابعی برای اجرای برنامه نوشتیم که در هر کدام قسمت های مختلفی اجرا می شود
```javascript
dam();

function dam(){
   text1.innerText='Breathe In!';
   circle.className=' circle dam';

   setTimeout(() => {
       hold();
   }, 2000);
}

function hold(){
   text1.innerText='HOLD!';
   circle.className=' circle hold';

   setTimeout(() => {
       bazdam();
   }, 1000);
}

function bazdam(){
   text1.innerText='Breathe Out!';
   circle.className=' circle bazdam';

   setTimeout(() => {
        dam();
   }, 2000);
}
```

## نتیجه

این پروژه توسط مجید تجن جاری و تیم Aiolearn نوشته شده است و ما به حمایت شما نیازمندیم!❤️