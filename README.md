/*  import google fonts */
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700");
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600&display=swap");
* {
  margin: 0;
  padding: 0;
  outline: none;
  border: none;
  text-decoration: none;
  box-sizing: border-box;
  font-family: "Poppins", sans-serif;
}
body {
  min-height: 100vh;
  max-height: 100vh;
  background: #dfe9f5;
}
.container {
  display: flex;
}
nav {
  position: relative;
  top: 0;
  bottom: 0;
  height: 150vh;
  left: 0;
  background: #1e2021;
  width: 100px;
  /* overflow: hidden; */
  box-shadow: 0 20px 35px rgba(0, 0, 0, 0.1);
}
.logo {
  font-family: Courier, monospace;
  text-align: center;
  display: flex;
  background-color: rgb(20, 119, 177);
}
.logo img {
  width: 80px;
  height: 43px;
  /* margin-left: 5px; */
  border-radius: 50%;
}
.logo span {
  font-family: "Lato", sans-serif;
  font-weight: bold;
  padding-left: 15px;
  font-size: 14px;
  text-transform: uppercase;
}

nav a{
  margin-top:10px ;
  color: rgb(146, 142, 142);
  padding: 10px;
  font-size: 14px;
}

/* a {
  position: relative;
  color: rgb(85, 83, 83);
  font-size: 14px;
  display: table;
  width: 100px;
  padding: 10px;
} */
nav .fas {
  position: relative;
  width: 60px;
  height: 20px;
  top: 14px;
  /* font-size: 20px; */
  text-align: center;
}
.nav-item {
  text-align: center;
  position: relative;
  top: 12px;
  /* margin-left: 10px; */
}
.logo-text {
  font-weight: bolder;
  font-size: larger;
  color: red;
}

a:hover {
  background: #eee;
}





/* Main Section */
.main {
  margin-top:10px ;
  padding:0;
  box-sizing: border-box;
  width: 100%;
}

.search-container {
  
  height: 4rem;
  display: flex;
  background-color: skyblue;
  place-items: center;
}
.search-box {
  box-shadow: 0 10px 10px rgba(65, 63, 63, 0.1);
  border-radius: 50px;
  height: 2rem;
  text-align: left;
  margin-left: 10rem;
  width: 32rem;
  padding: 20px;
  padding-left: 40px;
  
  
}
.menu {
  display: flex;
  flex-direction: column;
  align-items: center;
}


/* navbar main */
.navbar-main {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #ffffff;
}
.list-main {
  float: left;
}

.list-main a {
  display: block;
  color:rgb(126, 125, 125);
  text-align: center;
  font-family: "poppins", sans-serif;
  padding: 14px 16px;
  
}

.list-main a:hover:not(.active) {
  background-color: #e0dbdb;
  
}

.list-main>.active {
  background-color: #ffffff;
  color:black;
  font-weight: bold;
 
}


/* main container start here */
.stats{
  display:flex;
  flex-direction: row;
}

.first-div{
  display:flex;
  flex-direction:column;
  min-width: 24rem;
  max-width: 27rem;
  margin-left:1.5rem;
  margin-top: 2rem;
}

.first-heading-stats{
  margin-bottom: 10px;
}
.attendance-stats{
  background: white;
  min-height: 12rem;
  max-height: 20rem;
  padding: 1rem;
}

.stats-dropdown{
  margin-bottom: 10px;
}

.avg{
  display: flex;
  flex-direction: column;
  margin-left:50px ;
  margin-bottom:15px ;
}

.avg>p{
  font-size: small;
}

/* second stats */
.week>.navbar-logs>.list-logs{
  border: 2px solid rgb(182, 181, 181);
  border-radius: 50%;
  margin: 5px;
  
}

.week>.navbar-logs>.list-logs>.activate{
  border-radius: 5px solid skyblue;
}

.week>.navbar-logs>.list-logs a{
  padding: 5px 5px;
  font-size: small;
}


.sun,.sat{
  background-color: rgb(247, 245, 245);
}

.range{
  margin-top: 50px;
}

.duration{
  font-size: 12px;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}

.progressbar-container{
 width: 100%;
 height: 10px;
 margin: 5px 0;
 background-color: skyblue;
 border-radius: 15px;
}














/* digital clock third stats */

.clockdate-wrapper {
  min-width:60%;
  max-width: 100%;
  
}
#clock{
  font-family: Digital-7, 'sans-serif';
  width: 100%;
  font-size:24px;
  text-shadow:0px 0px 1px #0a0a0a;
  border: 2px solid rgb(199, 196, 196);
  text-align: center;
  padding: 10px 5px;
  color:#0c0c0c;
  margin-bottom: 10px;
}
#clock span {
  color: rgba(7, 7, 7, 0.8);
  text-shadow:0px 0px 1px #333;
  font-size:14px;
  position:relative;
}
#date {
  
  font-size:14px;
  font-weight: 500;
  color:#080808;
}

.third-stats{
  display: flex;
  flex-direction: row;
justify-content: space-between;

}

.webclock{
  margin-left: 30px;
}










/* navbar logs start */
.logs{
  margin-top: 2rem;
  margin-left:1.5rem;
}
.logs>h3{
  margin-bottom: 10px;
}
.navbar-logs {
  list-style-type: none;
  padding: 0;
  overflow: hidden;
  background-color: #ffffff;
}
.list-logs {
  float: left;
}

.list-logs a {
  display: block;
  color:rgb(126, 125, 125);
  text-align: center;
  font-family: "poppins", sans-serif;
  padding: 14px 16px;
  
}

.list-logs a:hover:not(.active) {
  background-color: #e0dbdb;
  
}

.list-logs>.active {
  background-color: #bfe3f1;
  color:black;
  font-weight: bold;
 
}








/* -------------------------------------------------- */
.wrapper {
  width: auto;
  height: auto;
  background: #fff;
  border-radius: 10px;
  box-shadow: 0 15px 40px rgba(0, 0, 0, 0.12);
}



.calendar {
  padding: 20px;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
.right{
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
}
.duration{
  padding: 10px 15px;
  /* background: #0000f6; */
  color: #0000f6;
  border: 1px solid #86868681;
}
.active{
  background: #0000f6;
  color: #fff;
}
.table-dates table{
  width: 100%;
}
.table-dates tr th{
  padding-left: 1.25%;
  padding-right: 1.25%;
  background: #8b8b8b43;
  text-align: left;
  color: #555454;

}
.table-dates tr td{
  /* padding-left: 2.5%; */
  margin: 0;
  padding: 1.5%;
  border-bottom: 1px solid #0000004d;
}
