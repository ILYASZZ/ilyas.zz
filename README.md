<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>My Responsive Layout</title>
  <link href="https://fonts.googleapis.com/css?family=Lato" rel="stylesheet">
  <link href='css/master.css' rel='stylesheet' type='text/css'>
  <style>
        *{
    box-sizing: border-box;
    margin:0;
    padding:0;
  }
  
  body{
    font-family: 'Lato', sans-serif;  
  }
  
  .row{
    width: 100%;
  }
  
  .menu-title{
    text-align: center;
    margin-bottom: 30px;
  }
  
  .container{
   position: relative;
   top:60px;
   margin: 15px; 
  }
  
  .item{
    position: relative;
    top: 0;
    background-color:#999999;
    margin: 15px;
    padding: 25px;
    border: 3px solid #000;
  }
  
  .item p{
    margin-top: 18px;
    text-align: justify;
    font-size:100%;
  }
  
  .item-title{
    position: absolute;
    top:0;
    right: 0px;
    background: green; 
    padding: 6px 90px;
    border-left: 2px solid #000;
    border-bottom: 2px solid #000;
  }
  
  #title-one {
    background-color: #D59898;
  } 
  
  #title-two{
    background-color: #C14543;
  }
  
  #title-three{
    background-color: #E5D198;
  }
  
  /* Simple Responsive Framework. */
  /*------ Desktop ------*/
  @media (min-width: 992px){
    .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
      float: left;  
    }
    .col-lg-1 {
      width: 8.33%;
    }
    .col-lg-2 {
      width: 16.66%;
    }
    .col-lg-3 {
      width: 25%;
    }
    .col-lg-4 {
      width: 33.33%;
    }
    .col-lg-5 {
      width: 41.66%;
    }
    .col-lg-6 {
      width: 50%;
    }
    .col-lg-7 {
      width: 58.33%;
    }
    .col-lg-8 {
      width: 66.66%;
    }
    .col-lg-9 {
      width: 74.99%;
    }
    .col-lg-10 {
      width: 83.33%;
    }
    .col-lg-11 {
      width: 91.66%;
    }
    .col-lg-12 {
      width: 100%;
    }
  
  }
  
  
  /*------ Tablet ------*/
  @media (min-width: 768px) and (max-width: 991px){
    .col-lg-4 {
      width: 50%;
      float: left;
    }
    .col-lg-tablet{
     width: 100%;
     float: left;
   }
  }
  
  
  /*------ Mobile ------*/
  @media (max-width: 767px){
    .col-lg-4{
      width: 100%;
      float: left;
    }
  }
  </style>
</head>
<body>
  <div class="container">
    <div class="row">

    <h1 class="menu-title">Our menu</h1>
      <div class="col-lg-4">
        <div class="item">
          <div class="item-title" id="title-one">
            <h3>Chicken</h3>
          </div>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Culpa perferendis enim, consequatur obcaecati iusto! Quia aliquam, obcaecati explicabo adipisci non. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Culpa perferendis enim, consequatur obcaecati iusto! Quia aliquam, obcaecati explicabo adipisci non.
          </p>
        </div>
      </div>
      <div class="col-lg-4">
        <div class="item">
         <div class="item-title" id="title-two">
          <h3>Beef</h3>
        </div>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Culpa perferendis enim, consequatur obcaecati iusto! Quia aliquam, obcaecati explicabo adipisci non. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Culpa perferendis enim, consequatur obcaecati iusto! Quia aliquam, obcaecati explicabo adipisci non.
        </p>
      </div>
    </div>
    <div class="col-lg-4 col-lg-tablet">
      <div class="item">
       <div class="item-title" id="title-three">
        <h3>Sushi</h3>
      </div>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Culpa perferendis enim, consequatur obcaecati iusto! Quia aliquam, obcaecati explicabo adipisci non. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Culpa perferendis enim, consequatur obcaecati iusto! Quia aliquam, obcaecati explicabo adipisci non.
      </p>
    </div>
  </div>

</div>
</div>
</body>
</html>
