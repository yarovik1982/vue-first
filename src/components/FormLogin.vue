<template>
    <form action="#" class="form__login">
         <div class="form__content">
            <div class="form__header">
              <div class="form__row" id="form-row-1">
                <p class="form__title">Вход</p>
                <span class="form__close">&times;</span>
              </div>
            </div>
            <div class="form__body">
              <div class="form__row" id="form-row-2">
                <label for="name-log" class="form__label">Введите имя</label>
                <input type="text" class="form__input" id="name-log">
              </div>
              <div class="form__row" id="form-row-3">
                <label for="pass-log" class="form__label">Введите пароль</label>
                <input type="password" class="form__input" id="pass-log">
              </div>
              <p class="form__row">
               Нет акканта?
               <!-- <a href="#">Зарегистрироваться</a> -->
               <router-link to="/registration">Зарегистрироваться</router-link>  
              </p>
            </div>
            <div class="form__footer">
              <div class="form__row" id="form-row-7">
                <button type="submit" class="form__submit">Авторизоваться</button>
              </div>
            </div>
          </div>
    </form>
</template>
<script>
export default {
components:{

},
data(){
return{

}
},
methods:{

},
}
</script>

<style scoped>
.form__login{
   width: 30%;
    min-width: 300px;
   position: absolute;
   top: 50%;
   left: 50%;
   transform: translate(-50%,-50%);
   background-color: #fff;
   border-radius: 30px 5px 30px 5px;
 }
 .form__header {
   background-color: var(--bg-dark);
   border-radius: 30px 0 0 0;
   padding: 20px;
   margin-bottom: 10px;
 }
 .form__header .form__row {
   display: flex;
   align-items: center;
   justify-content: space-between;
   color: var(--text-light);
 }
 .form__title {
   font-size: 24px;
 }
 .form__close {
   font-size: 30px;
   padding: 0 10px;
   cursor: pointer;
 }
 .form__body {
   padding:0 20px;
 }
 .form__label {
   display: inline-block;
 }
 .form__body .form__row {
   margin-bottom: 10px;
 }
 #form-row-2 input,#form-row-3 input,#form-row-4 input{
   display: block;
   width: 100%;
   height: 34.6px;
   background-color: #e0f2f1;
   outline: none;
   border: none;
   box-shadow: inset 2px 2px 2px  var(--bg-dark);
   padding-left: 10px;
   font-size: 20px;
 }
 #form-row-5,
 #form-row-6{
   display: flex;
   align-items: center;
   justify-content: start;
 }
 #form-row-5 input,
 #form-row-6 input{
   display: inline-block;
   width: 30px;
   height: 30px;
   margin-right: 10px;
 }
 .form__agree-link {
   text-decoration: none;
   color: #4db6ac;
 }
 .form__footer {
   background-color: var(--bg-dark);
   padding: 20px;
   border-radius: 0 0 30px 0px;
 }
 .form__footer .form__row{
   display: flex;
   align-items: center;
   justify-content: center;
 }
 input[type=submit]{
   padding: 0 10px;
   height: 34.6px;
   font-size: 24px;
   background-color: var(--text-light);
   color: var(--text-dark);
   border: none;
   outline: none;
 }
 .form__submit {
   height: 40px;
   color: var(--text-light);
   border-radius: 5px;
   padding: 10px 25px;
   font-family: sans-serif;
   font-size: 20px;
   background: transparent;
   cursor: pointer;
   transition: all 0.3s ease;
   position: relative;
   display: inline-block;
    box-shadow:inset 2px 2px 2px 0px rgba(255,255,255,.5),
    7px 7px 20px 0px rgba(0,0,0,.1),
    4px 4px 5px 0px rgba(0,0,0,.1);
   outline: none;
 }
 button {
   background: var(--text-light);
   border: none;
   z-index: 1;
 }
 button:after {
   position: absolute;
   content: "";
   width: 100%;
   height: 0;
   top: 0;
   left: 0;
   z-index: -1;
   border-radius: 5px;
   background-color: gold;
   background-image: linear-gradient(315deg, gold 0%, #f6fc9c 74%);
    box-shadow:inset 2px 2px 2px 0px rgba(255,255,255,.5),
    7px 7px 20px 0px rgba(0,0,0,.1),
    4px 4px 5px 0px rgba(0,0,0,.1);
   transition: all 0.3s ease;
 }
 button:hover {
   color: #000;
 }
 button:hover:after {
   top: auto;
   bottom: 0;
   height: 100%;
 }
 button:active {
   top: 2px;
 }
</style>>

