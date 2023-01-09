<!--- This section is Cascading Style Sheet (CSS) and applies to HTML -->
<style>
/* "row style" is flexible size and aligns pictures in center */
.row {
  align-items: center;
  display: flex;
}

/* "column style" is one-third of the width with padding */
.column {
  flex: 33.33%;
  padding: 5px;
}
</style>

## Triple AJ IPO Project

> We want to construct a calendar that can efficiently summarize and predict wether new initial public offerings in the market will be a good investment or not. We will also take mergers/acquisitions and other market conditions into account when evaluating an IPO. 
<br>
<br>
> As a frontend developer, my job is to construct the design below and create a functioning table with a good user interface. The table's objective is to lead the user to resourceful reports for each initial public offering. Our website will have a report for each upcoming IPO and also additional financial documents that help to evaluate IPOs (S-1 Filings, Balance Sheets, etc). 


<br>

![frontend design](/images/csplideo2.png)

<br>


> The design shows a calendar which alerts the user for upcoming investment opportunities regarding new IPOs that might be a valuable asset in the future. Our job is to construct an efficient product that can deliver exceptional research which provides useful information to a potential investor. 

> The probable method to constructing an efficient calendar would be to embed other APIs that can constantly show stock prices fluctuating no matter how volatile they are. 

> My job as a frontend is extremely important to make sure that the user interface is well crafted and accomplishes the job of being portrayed as an worthy investment tool. 

See more information regarding Triple AJ's IPO Calendar: [Additional Information]()

See current progress for our project: [LiDEO.ai]()

<html>
<head>
<style>
* {box-sizing: border-box;}
ul {list-style-type: none;}
body {font-family: Verdana, sans-serif;}

.month {
  padding: 70px 25px;
  width: 100%;
  background: #1E90FF;
  text-align: center;
}

.month ul {
  margin: 0;
  padding: 0;
}

.month ul li {
  color: white;
  font-size: 20px;
  text-transform: uppercase;
  letter-spacing: 3px;
}

.month .prev {
  float: left;
  padding-top: 10px;
}

.month .next {
  float: right;
  padding-top: 10px;
}

.weekdays {
  margin: 0;
  padding: 10px 0;
  background-color: #ddd;
}

.weekdays li {
  display: inline-block;
  width: 13.6%;
  color: #666;
  text-align: center;
}

.days {
  padding: 10px 0;
  background: #eee;
  margin: 0;
}

.days li {
  list-style-type: none;
  display: inline-block;
  width: 13.6%;
  text-align: center;
  margin-bottom: 5px;
  font-size:12px;
  color: #000;
}

.days li .active {
  padding: 5px;
  background: #000;
  color: white !important
}

/* Add media queries for smaller screens */
@media screen and (max-width:720px) {
  .weekdays li, .days li {width: 13.1%;}
}

@media screen and (max-width: 420px) {
  .weekdays li, .days li {width: 12.5%;}
  .days li .active {padding: 2px;}
}

@media screen and (max-width: 290px) {
  .weekdays li, .days li {width: 12.2%;}
}

</style>
</head>
<body>

<h1>BASIC UI</h1>

<div class="month">      
  <ul>
    <li class="prev">&#10094;</li>
    <li class="next">&#10095;</li>
    <li>
      January IPO Calendar<br>
      <span style="font-size:18px">By TripleAJ</span>
    </li>
  </ul>
</div>

<ul class="weekdays">
  <li>W1</li>
  <li>W1</li>
  <li>W2</li>
  <li>W2</li>
  <li>W3</li>
  <li>W3</li>
  <li>W4</li>
</ul>

<ul class="days">  
  <li>IntTech</li>
  <li>2</li>
  <li>BullFrog AI</li>
  <li>4</li>
  <li>5</li>
  <li>6</li>
  <li>Saint Brown</li>
  <li>N/A</li>
  <li>9</li>
  <li><span class="active">None Today</span></li>
  <li>11</li>
  <li>12</li>
  <li>13</li>
  <li>14</li>
  <li>MGO Global</li>
  <li>16</li>
  <li>17</li>
  <li>Laser Inc.</li>
  <li>19</li>
  <li>20</li>
  <li>21</li>
  <li>22</li>
  <li>23</li>
  <li>24</li>
  <li>25</li>
  <li>26</li>
  <li>CGA Corp.</li>
  <li>28</li>
  <li>29</li>
  <li>Hephaestus & Co.</li>
  <li>31</li>
</ul>

</body>
</html>

