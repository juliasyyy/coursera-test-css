# coursera-test-css
coursera test module 2
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title> menu</title>
  <style >
    *{box-sizing:border-box; 
     font-family:ariel; }

h1{text-align:center}

    @media(min-width:992px)
    {.col-lg-4 { 
      background-color:#808080;
      border:2px  solid black;
      float:left;
       margin-left:.5%;padding-left:4px; padding-right:0px; font-family:ariel;}

    
  .col-lg-4 {
    width: 32.5%; height:40%;
  }



      #chicken{float: right;
        clear:right; box-sizing:border-box;
        border:2px solid black; background-color:pink;
        padding:0; width:50%;  margin:0; text-align: center;
        font-weight:bold; font-size: 20px; font-family:ariel;}

        #beef{float: right;
        clear:right; box-sizing:border-box;
        border:2px solid black; background-color:#800000;color:white;
        padding:0; width:50%;  margin:0; text-align: center;
        font-weight:bold; font-size: 20px;font-family:ariel;}
        

        #sushi{float: right;
        clear:right; box-sizing:border-box;
        border:2px solid black; background-color:#FFE87C;color: solid black;
        padding:0; width:50%;  margin:0; text-align: center;
        font-weight:bold; font-size: 20px;font-family:ariel;}


        } 


        @media(min-width:768px) and (max-width: 991px)

        {.col-md-6  { 
      background-color:#808080;
      border:2px  solid black;
      float:left;
       margin-left:.5%;padding-left:4px; padding-right:0px; font-family:ariel; margin-bottom: 2%}

       .col-md-12{clear:left; float:right;box-sizing:border-box; border:2px solid black; background-color:#808080;margin-right: 1%;}

    
  .col-md-6 {
    width: 49.0%; height:40%;
  }

    .col-md-12{width:99%; height:40%;}



      #chicken{float: right;
        clear:right; box-sizing:border-box;
        border:2px solid black; background-color:pink;
        padding:0; width:50%;  margin:0; text-align: center;
        font-weight:bold; font-size: 20px; font-family:ariel;}

        #beef{float: right;
        clear:right; box-sizing:border-box;
        border:2px solid black; background-color:#800000;color:white;
        padding:0; width:50%;  margin:0; text-align: center;
        font-weight:bold; font-size: 20px;font-family:ariel;}
        

        #sushi{float: right;
        clear:right; box-sizing:border-box;
        border:2px solid black; background-color:#FFE87C;color: solid black;
        padding:0; width:25%;  margin:0; text-align: center;
        font-weight:bold; font-size: 20px;font-family:ariel;}


        } 



@media  (max-width:767px)

        {

       .col-sm-12{clear:left; float:right;box-sizing:border-box; border:2px solid black; background-color:#808080;margin-right: 1% margin-bottom:3%; margin-top:3%}


    .col-sm-12{width:99%; height:30%;}



      #chicken{float: right;
        clear:right; box-sizing:border-box;
        border:2px solid black; background-color:pink;
        padding:0; width:25%;  margin:0; text-align: center;
        font-weight:bold; font-size: 20px; font-family:ariel;}

        #beef{float: right;
        clear:right; box-sizing:border-box;
        border:2px solid black; background-color:#800000;color:white;
        padding:0; width:25%;  margin:0; text-align: center;
        font-weight:bold; font-size: 20px;font-family:ariel;}
        

        #sushi{float: right;
        clear:right; box-sizing:border-box;
        border:2px solid black; background-color:#FFE87C;color: solid black;
        padding:0; width:25%;  margin:0; text-align: center;
        font-weight:bold; font-size: 20px;font-family:ariel;}


        } 




  </style>
</head>
<body>
  <h1> Our Menu </h1>

  <div class="row">
    <div class="col-lg-4 col-md-6 col-sm-12"><p id="chicken">Chicken</p><br>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
    tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
    quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
    consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
    cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
    proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p></div>
      <div class="col-lg-4 col-md-6 col-sm-12"><p id="beef">Beef</p><br><p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
      tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
      quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
      consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
      cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
      proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p></div>
        <div class="col-lg-4 col-md-12 col-sm-12"><p id="sushi">Sushi</p><br><p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
        quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
        consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
        cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
        proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p></div>
