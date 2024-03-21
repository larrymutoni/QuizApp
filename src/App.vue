<template>
  <div class="container">
    <header>
      <h1>Quizes</h1>
      <input type="text" placeholder="search ..." name="" id="">
    </header>

    <div class="options-container">
      <div class="card">
        <img src="https://epe.brightspotcdn.com/dims4/default/1e49415/2147483647/strip/true/crop/2956x2006+22+0/resize/840x570!/quality/90/?url=https%3A%2F%2Fepe-brightspot.s3.us-east-1.amazonaws.com%2F02%2Fac%2Fa5498e524778b568fea054141968%2Fmath-102023-1281244731-01.jpg" alt="">
        <div class="card-text">
          <h2>Math</h2>
          <p>
            15 Questions
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
  .container {
    max-width: 100px;
    margin: 0 auto;
  }

  header {
    margin-bottom: 10px;
    margin-top: 30px;
    display: flex;
    align-content: center;
  }

  header h1 {
    font-weight: bold;
    margin-right: 30px;
  }

  header input {
    border: none;
    background-color: rgba(128, 128, 128, a.1);
    padding: 10px;
    border-radius: 5px;
  }

  .options-container {
    /* display: flex;
    flex-wrap: wrap; */
    margin-top: 40px;
  }


  .card{
    width: 310px;
    overflow: hidden;
    border-radius: 2%;
    box-shadow: 1px 1px 10px rgba(0, 0, 0, 0.1);
    margin-bottom: 35px;
    margin-right: 20px;
    cursor: pointer;
  }
  .card img{
    width: 100%;
    height: 190px;
    margin: 0;
  }

  .card .card-text{
    padding: 0 5px;
  }
  .card .card-text h2 {
    font-weight: bold;
  }
  
</style>