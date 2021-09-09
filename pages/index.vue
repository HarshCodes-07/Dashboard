<template>
  <div class="container">
    <div>
      <div class="flex">
        <div class="left">
        <img class="author-img" src="@/assets/images/harsh.png" alt="">
        </div>
        <div class="right">
          <h1>Harsh Dwivedi</h1>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Reprehenderit incidunt cumque corrupti iste vel, mollitia soluta quae. Corporis eaque aspernatur dolores, aliquid distinctio at fugiat nulla voluptate veniam ipsum esse repellat, amet nesciunt eius delectus! Nesciunt ipsa aperiam quod, eaque earum quaerat neque nostrum consectetur rem perferendis cum expedita quibusdam!</p>
          <p><span>Email</span> : harshdvd10@gmail.com&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span>Number</span> : 8910786224</p>
        </div>
      </div>
    </div>
     <div class="sales">
       <h1>My Book Sales</h1>
      <div class="flex">
        <div class="left">
        <img class="book-img" src="@/assets/images/book.png" alt="">
        </div>
        <div class="cards">
          <h4>Books Sold</h4>
          <p>All Time : 128</p>
          <p>Current Month : 88</p>
        </div>
        <div class="cards">
          <h4>Payments</h4>
          <p>Total Earned : 12000</p>
          <p>Total Recieved : 8000</p>
          <p>Next Payment Value : 4000</p>
          <p>Next Payment Date : 12/31/2021</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.flex{
  display: flex;
  padding: 20px;
}
.author-img{
  width: 200px;
  height: 200px;
}
.left , .right{
  padding:20px;
}
.right , .sales{
  text-align: center;
}
.right span{
  font-weight: bold;
}
.book-img{
  widows: 300px;
  height: 400px;
}
.cards{
  padding: 20px;
  text-align: center;
  flex: 1;
}
.cards p{
  text-align: left;
}
.sales .left{
  flex: 1;
}
.sales .right{
  flex: 1;
  display: flex;
}
</style>
