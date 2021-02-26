<script>
import Education from "./education.svelte";

</script>
    <head> 
        <title> 
            Music 
        </title> 
        <style> 
            * { 
                box-sizing: border-box; 
            } 
              
            
            .header { 
            background-color: #fcb1a67c; 
            padding: 15px; 
            text-align: center; 
        } 
              
          
            .nav_menu { 
            overflow: hidden; 
            background-color: #5d2a42; 
        } 
        .nav_menu a { 
            float: left; 
            display: block; 
            color: white; 
            text-align: center; 
            padding: 14px 16px; 
            text-decoration: none; 
            font-family: 'Big Shoulders Inline Display', cursive;
            font-size:125%;
        } 
        .nav_menu a:hover { 
            background-color: white; 
            color:#fb6376; 
        } 
          
              
          
            .columnA, .columnB, .columnC { 
            float: left; 
            padding: 15px;
            width:33%; 
            text-align:justify; 
        } 
        
        h2 { 
            color:#fb6376; 
            text-align:center;
            font-family: 'Lobster Two', cursive; 
        }
        p {
            font-family: 'Manrope', sans-serif;
        }
        h3 {
            text-align:center;
            color:#fcb1a6;

        }  
        .footer {
                position: fixed;
                left: 0;
                bottom: 0;
                width: 100%;
                background-color: #5d2a42;
                color: white;
                text-align: center;
 </style> 
    </head> 
      
    <body> 
          
        <!-- header of website layout -->
        <div class = "header"> 
            <h2 style = "color:white;font-size:400%"> 
                Music 
            </h2> 
        </div> 
          
        <!-- nevigation menu of website layout -->
        <div class = "nav_menu"> 
            <a href = ".">Home</a> 
            <a href = "education">Education</a> 
            <a href = "entertainment">Entertainment</a>
            <a href = "music">Music</a> 
        </div> 
          
        <!-- Content section of website layout -->
        <div class = "row"> 
              
            <div class = "columnA"> 
                <h2>T-Series</h2>
                <h3>172 million subs</h3> 
                <p>T-Series is a record label in India started by Gulshan Kumar in 1983. T-Series is one of the 
                    fastest-growing channels on YouTube. In April 2019, T-Series became a YouTube channel with 
                    the most subscribers, surpassing PewDiePie. In late May 2019, T-Series officially became the 
                    first YouTube channel ever to pass 100 million subscribers.
                    </p> 
            </div>  
              
            <div class = "columnB"> 
                <h2>Zee Music Company</h2>
                <h3>68 million subs</h3> 
                <p>Zee Music Company (ZMC) is an Indian music company, a subsidiary of Zee Entertainment Enterprises Ltd. 
                    It carries its business activities mainly from New Delhi. The company has captured a major chunk of 
                    market share in Bollywood Music in a short span of time.
                    </p> 
            </div> 
              
            <div class = "columnC"> 
                <h2>Canal KondZilla</h2>
                <h3>63 million subs</h3> 
                <p>Konrad Dantas (born 29 September 1994), better known by the stage name KondZilla, or just KOND, is 
                    a Brazilian screenwriter and director. He is the founder of KondZilla Records, which is a music video 
                    production company and record label often credited for being the main popularizer of funk ostentação. 
                    He currently owns the largest YouTube channel in Brazil and Latin America, and the third largest music 
                    channel in the world, with more than 53 million subscribers and over 26 billion views. In addition to 
                    his music videos, he is also the creator and director of the Netflix drama Sintonia.
                    </p> 
            </div> 
        </div>
        
        <div class="footer">
            <p>&copy; Sarah2021</p>
          </div> 
    </body> 
