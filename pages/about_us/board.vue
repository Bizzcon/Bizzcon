<template>
  <div class="contain">
      <div class="all">
        <h3>Board</h3>
        <p>Bizzcon is the pioneer of organised recruitment in India. Our roots in management consulting enable us to bring a unique approach to recruitment.</p>
        <div class="view"></div>
      </div>
      <div class="info">
      <h6>
Bizzcon is led by the most experienced thought leadership talent in the country, whose creative and innovative ideas on talent management has a significant impact on organisational business strategy.
</h6>
  </div>
<div class="leaders">
  <div class="team">
    <div class="image">
      <img :src="`https://avatars.dicebear.com/v2/avataaars/jj.svg?options[mood][]=happy`" alt="" class="img1">
    </div>
    <h3>XYZ</h3>
    <h4>Managing Director</h4>
    <p>Shiv is a management graduate from the London Business School and possesses over 20 years of experience in the executive search and selection industry.</p>
  </div>

  <div class="team">
    <div class="image">
      <img :src="`https://avatars.dicebear.com/v2/avataaars/gg.svg?options[mood][]=happy`" alt="" class="img1">
    </div>
    <h3>XYZ</h3>
    <h4>Senior Director</h4>
    <p>Shiv is a management graduate from the London Business School and possesses over 20 years of experience in the executive search and selection industry.</p>
  </div>

  <div class="team">
    <div class="image">
      <img :src="`https://avatars.dicebear.com/v2/avataaars/ggwp.svg?options[mood][]=happy`" alt="" class="img1">
    </div>
    <h3>XYZ</h3>
    <h4>Senior Director & CFO</h4>
    <p>Shiv is a management graduate from the London Business School and possesses over 20 years of experience in the executive search and selection industry.</p>
  </div>
</div>
</div>
</template>

<script>
export default {

}
</script>

<style scoped>
.all{
  background: url(https://images.unsplash.com/photo-1436262513933-a0b06755c784?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=871&q=80);
  text-align: left;
  color: white;
  padding: 30px;
  width: 100%;
}

.all h2{
  font-size: 40px;
  font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}

.all p{
    font-size: 20px;

}

.view{
  background: rgb(252,140,20);
  height: 10px;
  width: 80px;
}

.info{
  padding: 20px;
  text-align: center;
}

.info h6{
      font-size: 19px;

}

.image .img1{
  width: 40%;
  background: rgb(226, 226, 226);
  border-radius:1000px ;

}

.leaders{
  display: flex;
  flex-direction: row;
}

.team{
  text-align: center;
  padding: 10px;
  background: rgb(243, 241, 241);
  margin: 10px;
}

.team h4{
  color: rgb(167, 163, 163);
}

@media screen and (max-width: 900px) {
  .leaders{
    flex-direction: column;
  }

}

</style>