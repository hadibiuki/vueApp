<template>
   <div class="container">
        <div class="box">
            <div class="content">
                <img src="../../../assets/image/Mask1.png" alt=""/>
            </div>
        </div>
         <div class="box">
            <div class="content">
                <img src="../../../assets/image/image7.png" alt=""/>
            </div>
        </div>
        <div class="box">
            <div class="content">
                <img src="../../../assets/image/Mask3.png" alt=""/>
            </div>
        </div>
        <div class="box">
            <div class="content">
                  <img src="../../../assets/image/Mask8.png" alt=""/>
                  <div class="hoverd">
                      <h6>Portfolio</h6>
                      <p>Writing paragraphs takes practice, but what should students write 
                        about? Good paragraph writing prompts allow students to write 
                        about what they know and like, so their focus can be on the writing 
                        process and using the four essential elements.</p>
                  </div>
            </div>
        </div>
        <div class="box">
            <div class="content">
                 <img src="../../../assets/image/Mask4.png" alt=""/>
            </div>
        </div>
        <div class="box">
            <div class="content">
                <img src="../../../assets/image/Mask5.png" alt=""/>
            </div>
        </div>
        <div class="box">
            <div class="content">
                <img src="../../../assets/image/Mask6.png" alt=""/>
            </div>
        </div>
        <div class="box">
            <div class="content">
               <img src="../../../assets/image/Mask7.png" alt=""/>
            </div>
        </div>
        
        
        
    </div>
</template>

<script>
export default {
    
}
</script>


<style  scoped>

.container{
    position: relative;
    max-width: 100%;
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px , 1fr));
    grid-template-rows: minmax(50px , auto);
    margin: 40px;
    grid-gap: 10px;
    grid-auto-flow: dense;
}


.container .content{
    position: relative;
}

.container .box img{
    width: 100%;
    height: 100%;
    margin-bottom: 10px;
    object-fit: contain;
}

.hoverd{
    position: absolute;
    background: #754ef9f2;
    top: 0;
    width: 100%;
    height: 96%;
    color: var(--white);
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}
.hoverd h6{
    font-family: 'Trebuchet MS';
    font-size: 35px;
    font-weight: normal;
}

.hoverd p{
    color: #f3f3f3;
    font-family: 'Open Sans';
    font-size: 15px;
    font-weight: normal;
    opacity: 50%;
    width: 70%;
    line-height: 24px;

}

.container .box:nth-child(1){
    grid-column: span 1;
    grid-row: span 1;

}
.container .box:nth-child(2){
    grid-column: span 1;
    grid-row: span 1;

}
.container .box:nth-child(3){
    grid-column: span 1;
    grid-row: span 1;

}
.container .box:nth-child(4){
    grid-column: span 2;
    grid-row: span 1;

}



</style>