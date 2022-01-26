<template>
  <footer class="pie">
    <div class="enlaces">
      <div class="izquierda">
        <a href="#">Política de cookies</a>
        <a href="#">Política de privacidad</a>
        <a href="#">Condiciones generales</a>
      </div>
      
      <div class="cent">
        <a href="#">Aviso legal</a>
        <a href="#">Trabaja con nosotros</a>
        <a href="#">¿Dónde estamos?</a>
      </div>
      <div class="loN">
      <img id="logon" alt="logotiponeg" src="@/assets/logoN.png" />
        </div>

     
<div class="redes">
  <div>
  <h3> ¡Síguenos!</h3>
  </div>
  <div class="red">
       <a href="#" id="face"><img id="f" alt="facebook" src="@/assets/face.png" /></a>
        <a href="#"  id="twitter"><img id="t" alt="twitter" src="@/assets/twitter.png" /></a>
         <a href="#"  id="instagram"><img id="i" alt="instagram" src="@/assets/insta.png" /></a>

         </div>
    </div>

    <div class="pagos">
  <div>
  <h3> Formas de pago</h3>
  </div>
  <div class="formap">
       <a href="#" id="credit"><img id="c" alt="facebook" src="@/assets/credit.png" /></a>
        <a href="#"  id="bizum"><img id="b" alt="twitter" src="@/assets/bizum.png" /></a>
         <a href="#"  id="pay"><img id="p" alt="instagram" src="@/assets/paypal.png" /></a>

         </div>
    </div>
    
   
      </div> 
       <div class="copy">
      <p>&#169; 2022 Irina Casas Duarte</p>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style>
.red{
 display:flex;
 gap:1rem;

 
}
.redes{
text-align: center;
  margin-left:18rem;
}
.pagos{

text-align: center;
   margin-left:15rem;
}

.formap{
display:flex;
 gap:1rem;
}

 .redes h3{

    font-family: "Urbanist";
  color: rgb(223, 223, 223);
  
}

.pagos h3{
 font-family: "Urbanist";
  color: rgb(223, 223, 223);
  margin-left:-1rem;

}

#f{
  width: 2rem;
}
#t{
  width: 2rem;
}
#i{
  width: 2rem;
}
#c{
  width: 2.5rem;
}
#b{
  width: 2.5rem;
}
#p{
  width: 2.5rem;
}
#logon{
  width: 8rem;
  padding-top:2rem;
}
.pie {
  display: flex;
  flex-direction: column;
  margin-top:2rem;
}
.pie p {
  font-family: "Urbanist";
  color: #333333(223, 223, 223);
  text-align: center;
}
.enlaces {
  display: flex;
  

  border-top-left-radius: 10px 10px;
  border-top-right-radius: 10px 10px;
  align-items: center;
 
  
  padding-bottom: 2rem;

  background-color: #333333;
}

.enlaces a {
  text-decoration: none;
  font-size: 1.2em;
  font-weight: bolder;

  font-family: "Urbanist";
  color: rgb(223, 223, 223);
}

.izquierda {
  margin-left: 2rem;
  display: flex;
  flex-direction: column;
  padding-right: 10rem;

}

.cent {
  display: flex;
  flex-direction: column;
  margin-right: 2rem;
  padding-right: 22rem;
}
</style>