<script>
export default {
  name: 'casos'
}
</script>

<template>

   <div class="exito" id="contact">
        <div class="rown">
            <div class="cell-100">
                <div class="rown">
                    <div class="cell-100 aling-center">
                        <h2>Contacto</h2>
                        <hr>
                        <p>Cualquier idea que tengas en mente, nos encantaría leerte.</p>
                        <br>
                        <i class="material-icons">keyboard_arrow_down</i>
                    </div>
                </div>
                <div class="rown contained">
                    <div class="contained" >
                        <form class="form" action="#">
                            <div class="cell-100">
                                <fieldset class="">
                                    <label for="name">
                                        <span data-text="Nombre">Nombre</span>
                                    </label>
                                    <input type="text" id="name" tabindex="0"  placeholder="Nombre"/>
                                </fieldset>
                            </div>
                            <div class="cell-100">
                                <fieldset class="">
                                    <label for="email">
                                        <span data-text="Correo Eléctronico">Correo Eléctronico</span>
                                    </label>
                                    <input type="email" id="email" tabindex="0" placeholder="Correo Eléctronico"/>
                                </fieldset>
                            </div>
                            
                            <div class="cell-100">
                                <fieldset>
                                    <label for="message">
                                        <span data-text="Mensaje">Mensaje</span>
                                    </label>
                                    <textarea name="" cols="10" id="message" rows="5" placeholder="Mensaje"></textarea>
                                </fieldset>
                            </div>
                        
                            <div class="cell-100">
                                <button class="btn-send">Enviar</button>
                            </div>
                        </form>
                    </div>
                </div>
            </div>
        </div>
        <div class="fixed">
            <ul>
                <li><a class="aling-center btn-messenger" href=""> <i class="fab fa-facebook-messenger"></i></a></li>
                <li><a class="aling-center btn-whatsapp" href=""> <i class="fab fa-whatsapp"></i></a></li>
            </ul>
        </div>
   </div>
</template>

<style scoped>


    .h{
        margin-top: 20px;
    }

    .contained {
        max-width:1024px;
        margin: 0 auto;
        padding: 20px 16px 40px 16px;
        transform: translateZ(0);
        text-align: left;
    }

    .btn-send{
        background: #fff;
        border: 1px solid #4834d4;
        color: #4834d4;
        width: 100%;
        display: block;
        padding:10px;
        border-radius:50px;
        text-decoration: none;
        font-size: 20px;
    }

    .btn-send:hover{
        background: #4834d4;
        border: 1px solid #4834d4;
        color: #fff;
    }

    label{
        display: none;
    }

    .fixed{
        position: fixed;
        bottom:5px;
        right: 5px;
    }

    .fixed ul li {
        /*display: inline-block;*/
        list-style: none;
        margin:5px;
    }
    .btn-messenger{
        background: #0084ff;
        color: #fff;
        width: 100%;
        display: block;
        padding:10px 12px;
        border-radius:50px;
        text-decoration: none;
    }

    .btn-whatsapp{
        background: #1ebea5;
        color: #fff;
        display: block;
        width: 100%;
        padding:10px 12px;
        border-radius:50px;
        text-decoration: none;
    }

    fieldset{
        border: none;
    }

    input,textarea{
        width: 100%;
        border:none;
        border-bottom: 1px solid #ccc;
        padding: 20px;
        font-size: 14px;
    }

    .pd{
        padding: 20px;
    }

    .fab{
        font-size: 25px;
    }

    .c{
        padding: 40px;
    }

    .exito {
        background: #fff;
        height: 700px;
        padding: 40px;
    }
    @media(max-width:991px){
        .exito{
            height: 800px;
            padding: 0px;
        }
    }
    h2{
        font-size: 30px;
        margin-top:20px;
        font-family: 'Montserrat', sans-serif;
        color: #4834d4;
        font-weight: 200;
    }
    hr{
        border:4px solid #4834d4;
        border-radius: 20px;
        max-width: 100px;
        margin: 0 auto;
        margin-top: 20px;
        margin-bottom: 60px;
    }

    img{
        width: 100%;
    }

    


</style>

  