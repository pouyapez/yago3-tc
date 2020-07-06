---
layout: default
---
<div class="menu-container noselect">
   <table class="content-table">
      <tr>
        <td style="width:60%;" align="left">
        <font style="font-size:20px"><b>What is YAGO3-TC?</b></font>
         <hr>
        <p class="text right-align text-large add-top-margin" style="width:100%;">
        YAGO3-TC is a semi-complete KG created from a random subgraph of the test and validation data of YAGO3-10. As the test        data, YAGO3-TC contains 28,364 triples from which 2,976 ones of them labeled as positive triples. 
        </p>
        <font style="font-size:20px"><b>Submission instructions</b></font>
          <hr>
        <p class="text right-align text-large add-top-margin" style="width:100%;">           
           You can find the validation and test data <a href="https://github.com/pouyapez/yago3-tc/tree/master/data">here</a>. To get the ranking and evaluation metrics, after training the triple classifier, please submit the labels of test triples in <a href="https://forms.gle/T4tTJS5P2o1kUKfY8">here</a>. If you want to contribute to improvmenmt of YAGO3-TC benchmark please please drop an email to pezeshkp@uci.edu.
        </p>
        </td>
        <td align="center">
            <div class="container" style="text-align:center;">
               <font style="font-size:20px"><b>Leaderboard</b></font>
               <table class="content-table" rules="rows">
                    <tr>
                       <td>
                           Rank
                       </td> 
                       <td>
                           Model
                       </td> 
                       <td>
                           F1
                       </td> 
                    </tr>
                    <tr>
                       <td>
                           1
                       </td> 
                       <td>
                           Tucker
                       </td> 
                       <td>
                           <b>22.3</b>
                       </td> 
                    </tr>
                    <tr>
                       <td>
                           2
                       </td> 
                       <td>
                           DistMult
                       </td> 
                       <td>
                           20.4
                       </td> 
                    </tr>
                    <tr>
                       <td>
                           3
                       </td> 
                       <td>
                           RotatE
                       </td> 
                       <td>
                           19.4
                       </td> 
                    </tr>
                 </table>
               </div>
         </td> 
      </tr>
   </table>
</div>
***
<font style="font-size:20px"><b>Citation:</b></font>
<p>
@inproceedings{pezeshkpourrevisiting, <br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; title={Revisiting Evaluation of Knowledge Base Completion Models},<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; author={Pezeshkpour, Pouya and Tian, Yifan and Singh, Sameer},<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; booktitle={Automated Knowledge Base Construction (AKBC)},<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; year={2020}<br>   
}   
</p>
