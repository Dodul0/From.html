
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=Edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <title>Registation From</title>
  
  <!-- HTML -->
  <style type="text/css" media="all">
      body{
          margin: 0;
          padding: 0;
          color: white;
          background-image: url('see.jpeg') ;
          background-size: cover;
          background-position: center;
          background-repeat: no-repeat;
          height: 100vh;
          width: 100%;
      } 
      
      .header{
          position: absolute;
          top: 10px;
          left: 200px;
          background-color: rgba(0, 0, 0,.5);
          border-radius: 20px 20px 0 0;
          width: 600px;
          text-align: center;
      } 
      .box{
          height: 400px;
          width: 600px;
          background-color: rgba( 0, 0, 0, .4);
          position: absolute;
          top: 110px;
          left: 200px;
          border-radius: 0 0 10px 10px;
      } 
      .name{
          margin-top: 15px;
          margin-left: 20px;
      } 
      .name > h3{
          display: inline;
          margin-right: 30px;
      }
      input{
          outline: none;
          color: white;
          font-size: 15px;
      } 
      button{
          outline: none;
      } 
      select{
          outline: none;
      } 
      .name > input{
            height: 40px;
            margin-right: 20px;
            border-radius: 5px;
            background-color: rgba(0, 0, 0,.4);
            border: none;
      }
      .company{
          margin-top: 10px;
          margin-left: 20px;
      } 
      .company > h3{
          display: inline;
      }
      .company > input{
          margin-left: 20px;
          background-color: rgba(0, 0, 0,.4);
          border: none;
          border-radius: 5px;
          height: 40px;
          width: 420px;
      } 
      .phone{
          margin-top: 10px;
      } 
      .phone > h3{
          display: inline;
          margin-left: 20px;
      }
      .phone > input{
          margin-left: 20px;
          background-color: rgba(0, 0, 0,.4);
          Width: 452px;
          border: none;
          border-radius: 5px;
          height: 40px;
      } 
      .email{
          margin-top: 10px; 
      } 
      .email > h3{
          display: inline;
          margin-left: 20px;
      } 
      .email > input{
          margin-left: 20px;
          height: 40px;
          width: 460px;
          border: none;
          border-radius: 5px;
          background: rgba(0, 0, 0,.4);
      } 
      .subject{
          float: left;
      } 
      .subject > h3{
            margin-left: 20px;          
      } 
      .subject > select{
          margin-left: 20px;
          background-color: darkcyan;
          height: 40px;
          width: 150px;
          color: white;
          border: none;
          border-radius: 5px;
      } 
      .radio{
          float: right;
          margin-right: 40px;
      } 
      .radio p{
          display: inline;
      } 
      button{
          position: absolute;
          height: 40px;
          width: 550px;
          display: block;
          top: 340px;
          left: 20px;
          font-size: 18px;
          background-color: darkcyan;
          border: none;
          border-radius: 5px;
          color: white;
      } 
  </style>

  <!-- Custom Styles -->
  <link rel="stylesheet" href="style.css">
</head>

<body>
  <div class="reg-from">
      <form action="" method="get" accept-charset="utf-8">
          <div class="header">
             <h1>Registation From</h1>     
          </div>
          <div class="box">
            <div class="name">
            <h3>Name</h3>
            <input type="text/submit/hidden/button/image" value="" placeholder="First Name" />
            <input type="text/submit/hidden/button/image" name="" id="" value="" placeholder="Last Name" />    
            </div>
            <div class="company">
                <h3>Company</h3>
                <input type="text/submit/hidden/button/image" name="" id="" value="" placeholder="Company Name" />    
            </div>
            <div class="phone">
                <h3>Phone</h3>
                <input type="text/submit/hidden/button/image" name="" id="" value="" placeholder="Phone" />    
            </div>
            <div class="email">
                <h3>Email</h3>
                <input type="text/submit/hidden/button/image" name="" id="" value="" placeholder="Email" />    
            </div>
            <div class="subject">
                <h3>Subject</h3>
                <select name="" id="">
                    <option value="">Wab Programmer</option>
                    <option value="">Software Programmer</option>
                    <option value="">Artificial Intaligent</option>
                </select>    
            </div>
            <div class="radio">
                <h3>Are you beginner?</h3>
                <input type="radio" name="" id="" value="Yes" />
                <p>yes</p>
                <input type="radio" name="" id="" value="" />
                <p>No</p>
            </div>
            <div class="sub">
                    <button type="submit">Submit</button>    
            </div>
          </div>
         </form>
  </div>
  <!-- Project -->
  <script src="main.js">
      
  </script>
</body>
</html>
