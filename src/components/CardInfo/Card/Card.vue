<template>
   <div class="card">
       <img :src="require(`./../../../assets/icon/${iconImg}`)" alt="">
       <h6>{{title}}</h6>
       <p>{{desc}}</p>
       <button>Learn more</button>
    </div> 
</template>

<script>

export default {
    props:{
        iconImg: {
            type: String,
            required: true,
            default: ''
        }, 
        title: {
            type: String,
            required: false,
            default: 'On time'
        }, 
        desc: {
            type: String,
            required: false,
            default: "All i want to have client setisfaction & this is my aim"
        }, 
    }
}
</script>

<style  scoped>
.card{
    width: 300px;
    height: 500px;
    box-shadow: 0px 5px 15px #754EF916;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 40px;
    margin: 10px;
}

.card img{
    width: 60px;
    height: 60px;
    margin-bottom: 50px;
}

.card h6{
    font-family: 'Open Sans';
    font-weight: 100px;
    font-size: 18px;
    margin-bottom: 20px;
    margin-bottom: 50px;

}

.card p{
    font-family: 'Open Sans';
    font-weight: 300px;
    font-size: 14px;
    color: #505050;
    margin-bottom: 50px;
    text-align: center;
    line-height: 24px;
    width: 80%;
}

.card button{
    font-family: 'Open Sans';
    font-weight: 100px;
    font-size: 11px;
    margin-bottom: 20px;
    background: var(--perpel);
    color: var(--white);
    width: 120px;
    height: 30px;
}
</style>