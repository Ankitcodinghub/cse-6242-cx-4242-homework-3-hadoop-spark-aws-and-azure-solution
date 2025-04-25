# cse-6242-cx-4242-homework-3-hadoop-spark-aws-and-azure-solution



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/cse-6242-cx-4242-homework-3-hadoop-spark-aws-and-azure-solution/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;89692&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE 6242 \/ CX 4242: Homework 3 : Hadoop, Spark,&nbsp;AWS&nbsp;and Azure Solution&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
<div class="kksr-stars">
    
<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
    
<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>
                

<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
<h2 id="h.duhc5h52xct" class="c66 c67"><span class="c30 c65">Introduction</span></h2>
<p class="c66">In this assignment you will be working with big data analytics using a variety of modern technologies. The dataset which you will be working on for the bulk of the assignment comes from the New York City Taxi &amp; Limousine Commision (TLC). Further details on this dataset are available&nbsp;<span class="c17"><a class="c5" href="https://www.google.com/url?q=https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page&amp;sa=D&amp;ust=1601353860889000&amp;usg=AOvVaw2UNgi-z-RhRDu4y1xYbkIK">here</a></span><span class="c2">. In Q1, you will be doing Java programming to become familiar with Hadoop and MapReduce. In Q2 you will perform further analysis with DataBricks, Scala and Spark, which are tools for working with large datasets. In Q3 you will perform large scale analysis in AWS using EMR and Pig. For Q4 you will work in Microsoft Azure and further hone your MapReduce abilities. Finally, in Q5 you will do some Machine Learning, utilizing Azure ML Studio.</span>

<p class="c66">A main goal of this assignment is to help students gain exposure to a variety of tools that they may use in future (e.g., future project, research, career). That is also why we intentionally include both AWS and Azure (most courses use only one), because we want students to be able to try and compare them (both platforms evolve rapidly), so in the future should they need to select a cloud platform to use, they can make more informed decisions and to be able to get started right away. You may find that a number of computational tasks in this assignment are not very difficult, and there seems to be quite a bit of “setup” to do before getting to the actual “programming” part of the problem. A main reason for this design is because for many students this assignment is the very first time they use&nbsp;<span class="c20">any</span><span class="c2">&nbsp;cloud services; they are new to the pay-per-use model, and they have never used a cluster of machines. There are over 1000 students in CSE 6242 (campus and online) and CX 4242 combined. This means we have students coming from a great variety of backgrounds. We wished we could provide every student unlimited AWS/Azure credit so that they can try out many services and write programs that are more complex. Over the past offering of this course, we have been gradually increasing the “programming” part and reducing much of the “setup” (e.g., the use of VM and Databricks notebook were major improvements). We will continue to further reduce the setup that students need to perform in future offerings of this course.</span>

<h2 id="h.83j9ora5aip5" class="c66 c67">Q1 [15 points]&nbsp;<span class="c16">Analyzing trips data with Hadoop/Java</span></h2>
<p class="c7">Follow these&nbsp;<span class="c17"><a class="c5" href="https://www.google.com/url?q=https://docs.google.com/document/d/e/2PACX-1vQthNkxSbYIlE_4FqChfZb8EQ9j_RWlFe7m-Q-CtDaGj8jKGIfpR1hCpfNxymGJ15LEQoZMwVTI3WTp/pub&amp;sa=D&amp;ust=1601353860890000&amp;usg=AOvVaw22weZxBKMAkUkae0Nm3QwB">Instructions to download, setup</a></span><span class="c17"><a class="c5" href="https://www.google.com/url?q=https://docs.google.com/document/d/e/2PACX-1vQthNkxSbYIlE_4FqChfZb8EQ9j_RWlFe7m-Q-CtDaGj8jKGIfpR1hCpfNxymGJ15LEQoZMwVTI3WTp/pub&amp;sa=D&amp;ust=1601353860890000&amp;usg=AOvVaw22weZxBKMAkUkae0Nm3QwB">&nbsp;a preconfigured virtual mach</a></span><span class="c17"><a class="c5" href="https://www.google.com/url?q=https://docs.google.com/document/d/e/2PACX-1vQthNkxSbYIlE_4FqChfZb8EQ9j_RWlFe7m-Q-CtDaGj8jKGIfpR1hCpfNxymGJ15LEQoZMwVTI3WTp/pub&amp;sa=D&amp;ust=1601353860890000&amp;usg=AOvVaw22weZxBKMAkUkae0Nm3QwB">ine (V</a></span><span class="c17"><a class="c5" href="https://www.google.com/url?q=https://docs.google.com/document/d/e/2PACX-1vQthNkxSbYIlE_4FqChfZb8EQ9j_RWlFe7m-Q-CtDaGj8jKGIfpR1hCpfNxymGJ15LEQoZMwVTI3WTp/pub&amp;sa=D&amp;ust=1601353860891000&amp;usg=AOvVaw2NTqqHJPkgL1KtkduyTrSX">M</a></span>)&nbsp;image that you will use for this assignment.

<p class="c7"><span class="c13 c21">Why use VMs?</span>&nbsp;In earlier iterations of this course, students installed software on their own machines, and we (both students and instructor team) ran into all sorts of issues, some of which could not be resolved satisfactorily. The VM approach allows students to start working on the tasks much more quickly. We continue to experiment with other alternatives, so in the future, this may become even easier for our students!

<p class="c7"><span class="c2">Imagine that your boss gives you a large dataset which contains trip information of New York City Taxi and Limousine Commission (TLC). You are asked to provide the number of trips from each pickup point along with the total amount of fare. This information might help in positioning taxis depending on the demand at each location.</span>

<p class="c7"><span class="c2">&nbsp;</span>

<p class="c7">First, go over the<a class="c5" href="https://www.google.com/url?q=https://hadoop.apache.org/docs/current/hadoop-mapreduce-client/hadoop-mapreduce-client-core/MapReduceTutorial.html%23Example:_WordCount_v1.0&amp;sa=D&amp;ust=1601353860892000&amp;usg=AOvVaw3u_WkexY6E-SgcwuUwY_E9">&nbsp;</a><span class="c17"><a class="c5" href="https://www.google.com/url?q=https://hadoop.apache.org/docs/current/hadoop-mapreduce-client/hadoop-mapreduce-client-core/MapReduceTutorial.html%23Example:_WordCount_v1.0&amp;sa=D&amp;ust=1601353860892000&amp;usg=AOvVaw3u_WkexY6E-SgcwuUwY_E9">Hadoop word count tutorial</a></span>&nbsp;to familiarize yourself with Hadoop and some Java basics. You will be able to complete this question with only some knowledge about Java. Make sure you have&nbsp;already loaded the two trips data files<span class="c2">&nbsp;into the HDFS file system in your VM (following the instructions mentioned in the beginning of this question). Each line in the file represents a trip’s information consisting of four columns:

PickUpLocationId, DropOffLocationId, Distance, Total Fare

separated by commas (,). Below is a small toy data example, for illustration purposes (on your screen, the text may appear out of alignment).</span>

<p class="c7"><span class="c2">&nbsp;</span>

<p class="c7"><span class="c11">PickUpId, DropOffId, Distance, &nbsp;TotalFare</span>

<p class="c7"><span class="c22 c9">1, &nbsp; &nbsp; &nbsp; &nbsp;30, &nbsp; &nbsp; &nbsp; &nbsp;20.2, &nbsp; &nbsp; &nbsp;30.1</span>

<p class="c7"><span class="c22 c9">1, &nbsp; &nbsp; &nbsp; &nbsp;24, &nbsp; &nbsp; &nbsp; &nbsp;19.1, &nbsp; &nbsp; &nbsp;28.2</span>

<p class="c7"><span class="c22 c9">2, &nbsp; &nbsp; &nbsp; &nbsp;20, &nbsp; &nbsp; &nbsp; &nbsp;18.3, &nbsp; &nbsp; &nbsp;20.1</span>

<p class="c7"><span class="c22 c9">1, &nbsp; &nbsp; &nbsp; &nbsp;31, &nbsp; &nbsp; &nbsp; &nbsp;20.2, &nbsp; &nbsp; &nbsp;33</span>

<p class="c7"><span class="c22 c9">1, &nbsp; &nbsp; &nbsp; &nbsp;20, &nbsp; &nbsp; &nbsp; &nbsp;0, &nbsp; &nbsp; &nbsp; &nbsp; 2.5</span>

<p class="c7"><span class="c2">&nbsp;</span>

<p class="c7">Your code should accept two arguments. The first argument (<span class="c20">args[0]</span>) will be a path for the input graph file on HDFS (e.g., data/trip1.csv), and the second argument (<span class="c20">args[1]</span><span class="c2">) will be a path for output directory on HDFS (e.g., data/q1output1). The default output mechanism of Hadoop will create multiple files on the output directory such as part-00000, part-00001, which will be merged and downloaded to a local directory by the supplied run script. Please use the run1.sh and run2.sh scripts for your convenience.</span>

<p class="c7"><span class="c2">&nbsp;</span>

<p class="c7"><span class="c2">For each pickup location ID, compute the total number of trips that originate from that location and the total fare.</span>

<p class="c7"><span class="c13 c77">Requirements:</span>

<ol class="c4 lst-kix_uck01goy4uhc-0 start" start="1">
<li class="c0">Output format: each line contains a PickupLocationID, followed by a tab (t), and then the expected “TotalNumberOfTrips,TotalAmount<span class="c2">” tuple (without the quotes; and no space character before or after the comma)</span></li>
<li class="c0"><span class="c2">Lines in output do not need to be sorted</span></li>
<li class="c0"><span class="c2">Exclude trips that do not have pickup locations.</span></li>
<li class="c0">Exclude trips whose distance&nbsp;equals zero</li>
<li class="c0"><span class="c2">Exclude trips whose total fare is less than or equal to zero</span></li>
<li class="c0">Your input must&nbsp;not have any&nbsp;<span class="c2">column headers</span></li>
<li class="c0"><span class="c2">Your output must not include column headers</span></li>
<li class="c0"><span class="c2">In your output, round the total fare amount to two decimal points.</span></li>
</ol>
<p class="c7 c31"><span class="c2">10.236 -&gt; 10.24</span>

<p class="c7 c31"><span class="c2">10.235 -&gt; 10.24</span>

<p class="c7 c31"><span class="c2">10.234 -&gt; 10.23</span>

<p class="c7 c31"><span class="c2">10.2 -&gt; 10.20</span>

<ol class="c4 lst-kix_uck01goy4uhc-0" start="9">
<li class="c0"><span class="c2">In your output TotalFares greater than 1,000 should contain thousands separators (a , for every 3 digits).</span></li>
</ol>
<p class="c7"><span class="c2">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 1000.00 -&gt; 1,000.00</span>

<p class="c7"><span class="c2">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 10100.00 -&gt; 10,100.00</span>

<p class="c7">The following example result is computed based on the toy example above.

<p class="c7"><span class="c13 c79">PickupId&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><span class="c13 c79">TotalNoOfTrips,TotalFare</span><span class="c11">&nbsp;</span>

<p class="c7"><span class="c22 c9">1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp; &nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3,91.30</span>

<p class="c7"><span class="c9">2 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1,20.1</span><span class="c22 c9">0</span>

<p class="c7">We are not considering the &lt;1, 20, 0, 2.5&gt; record for computing the total number of trips and total fare for pick up location 1 because the distance was 0.

<p class="c7"><span class="c2">&nbsp;</span>

<p class="c7"><span class="c13 c83">Deliverables</span>

<p class="c7"><span class="c2">&nbsp;</span>

<ol class="c4 lst-kix_1rdksl5mcrzy-0 start" start="1">
<li class="c0"><span class="c13">[</span><span class="c13">5 points] Your Maven project directory including Q1.java.</span>&nbsp;Please see the detailed submission guide at the end of this document.<span class="c3">&nbsp;You must implement your own MapReduce procedure and must not import external graph processing libraries.</span></li>
</ol>
<p class="c7"><span class="c2">&nbsp;</span>

<p class="c7">&nbsp; &nbsp; &nbsp; 2.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="c70">&nbsp;</span><span class="c13">[5 points] q1output1.tsv</span><span class="c2">: the output file of processing trip1.csv by run1.sh.</span>

<p class="c7 c59"><span class="c13">[5 points] q1output2.tsv</span><span class="c2">: the output file of processing trip2.csv by run2.sh.</span>

<h2 id="h.35nkun2" class="c60">Q2 [25 pts] Analyzing&nbsp;a dataset&nbsp;with Spark/Scala on Databricks</h2>
<p class="c7"><span class="c13 c69">Tutorial</span><span class="c13 c41">:&nbsp;</span>First, go over this&nbsp;<span class="c17"><a class="c5" href="https://www.google.com/url?q=https://databricks.com/spark/getting-started-with-apache-spark/quick-start&amp;sa=D&amp;ust=1601353860898000&amp;usg=AOvVaw2RwnPkaRz-UzG_i0k4PBPV">Spark on Databricks Tutorial</a></span>, to get&nbsp;the basics of creating Spark jobs, loading data, and working with data<span class="c2">.</span>

<p class="c36">You will analyze&nbsp;<span class="c17"><a class="c5" href="https://www.google.com/url?q=https://www.dropbox.com/s/0liid3aydj0hswg/nyc-tripdata.csv?dl%3D1&amp;sa=D&amp;ust=1601353860898000&amp;usg=AOvVaw2fRFMCKFKfbxdYJqP3lagA">nyc-tripdata.csv</a></span><sup class="c46"><a id="ftnt_ref1" href="https://docs.google.com/document/d/e/2PACX-1vQaTAgmrkswYCvRMvenDqYl3EsorFt54DrdC578IKVFM9kISsyrRDqCehLOGA4rWBmJhaXSFVuS7UB-/pub#ftnt1">[1]</a></sup>&nbsp;using Spark and Scala on the Databricks platform. The dataset is a modified record of the NYC&nbsp;<span class="c10">G</span><span class="c10">reen Taxi trips and includes information about the pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, fare amounts, payment types, and driver-reported passenger counts.</span>

<p class="c36"><span class="c13 c80 c77 c93">VERY IMPORTANT:</span><span class="c16">&nbsp;Rename your notebook as&nbsp;</span><span class="c13 c80">q2-yourGTusername</span><span class="c16">&nbsp;(e.g. q2-jdoe3) before submitting. Refer to the&nbsp;</span><span class="c17 c16"><a class="c5" href="https://www.google.com/url?q=https://docs.google.com/document/d/e/2PACX-1vThNWH1fBXwnwp-AIrhTxe7lcwRH7W1Ratj1QHLxs5ySnunDa0-w11unsa4eXxK9YUsMs0EHuti06Fe/pub&amp;sa=D&amp;ust=1601353860899000&amp;usg=AOvVaw1KjF7XqpYf-ZiqHDB4cihS">Databricks Setup Guide</a></span><span class="c16">&nbsp;(open the link in a private browser window if you get ‘Permission Denied’ message) on how to rename the notebook.</span>

<p class="c36">Your objectives:

<ol class="c4 lst-kix_cfad9x7b7oeu-0 start" start="1">
<li class="c18"><span class="c16">Filter the data to only keep the rows where the pickup location is different from the drop location and the trip distance is strictly greater than 2.0 (&gt;2.0).&nbsp;</span><span class="c16 c77">Very important: all subsequent operations must be performed on this filtered&nbsp;</span><span class="c16 c77">data</span><span class="c16 c77">frame.</span></li>
<li class="c18"><span class="c16">List the top-5&nbsp;</span><span class="c16">most popular drop locations, sorted in descending order. If there is a tie, then the one with a lower&nbsp;</span><span class="c16">location</span><span class="c16">&nbsp;ID gets listed first.</span></li>
<li class="c18"><span class="c16">List the top-5 most popular pickup locations, sorted in descending order. If there is a tie, then the one with a lower location ID gets listed first.</span></li>
<li class="c18"><span class="c16">List the top-5 most popular pickup-dropoff pairs, sorted in descending order. If there is a tie, then one with a lower&nbsp;</span><span class="c16">pickup location ID</span><span class="c16">&nbsp;gets listed first.</span></li>
<li class="c18"><span class="c16">List by days, the number of drop-offs over the period from January 1, 2019 (including January 1) to January 5,&nbsp;</span><span class="c16">2019</span><span class="c22 c16">&nbsp;(including January 5). List the entries by day from January 1 to January 5.</span></li>
<li class="c18"><span class="c16">List the top-3 locations with the maximum overall activity, i.e. sum of all pickups and all drop-offs at that location. In case of a tie, the lower location ID gets listed first.</span></li>
</ol>
<p class="c36">You should perform this task using the&nbsp;<span class="c17"><a class="c5" href="https://www.google.com/url?q=https://spark.apache.org/docs/2.4.4/api/scala/index.html%23org.apache.spark.sql.Dataset&amp;sa=D&amp;ust=1601353860901000&amp;usg=AOvVaw32l8de931Q_IDc2pat5qs6">DataFrame API</a></span>&nbsp;in Spark.&nbsp;<span class="c17"><a class="c5" href="https://www.google.com/url?q=https://spark.apache.org/docs/2.4.4/&amp;sa=D&amp;ust=1601353860901000&amp;usg=AOvVaw2tMID0mw5UXTRmNxn_UPOO">Here</a></span><span class="c2">&nbsp;is a guide that will help you get started on working with data frames in Spark.</span>

<p class="c36">A template Scala notebook,&nbsp;<span class="c20">q2.dbc</span>&nbsp;has been included in the HW3-Skeleton that reads in a data file&nbsp;<span class="c20">nyc-tripdata.csv</span><span class="c2">. In the template, the input data is loaded into a dataframe, inferring the schema using reflection (Refer to the guide above).</span>

<p class="c36"><span class="c13 c3">Note</span><span class="c3">: You&nbsp;</span><span class="c13 c3">must&nbsp;</span><span class="c3">use only Scala DataFrame operations for this task. You will lose points if you use SQL queries, Python, or R to manipulate a dataframe.</span>

<p class="c36"><span class="c13 c21">Hint:&nbsp;</span><span class="c2">You may find some of the following DataFrame operations helpful:</span>

<p class="c47"><span class="c9">toDF, join, select, groupBy, orderBy, filter</span>

<p class="c47">Upload the data file&nbsp;<span class="c20">nyc-tripdata</span><span class="c13 c20">.</span><span class="c20">csv</span>&nbsp;and&nbsp;<span class="c20">q2.dbc</span>&nbsp;to your Databricks workspace before continuing. &nbsp;Follow the&nbsp;<span class="c17"><a class="c5" href="https://www.google.com/url?q=https://docs.google.com/document/d/e/2PACX-1vThNWH1fBXwnwp-AIrhTxe7lcwRH7W1Ratj1QHLxs5ySnunDa0-w11unsa4eXxK9YUsMs0EHuti06Fe/pub&amp;sa=D&amp;ust=1601353860902000&amp;usg=AOvVaw0sHI7uyrrfSodTz0G0IKNG">Databricks Setup Guide</a></span>&nbsp;(<span class="c16">open the link in a private browser window if you get ‘Permission Denied’ message)</span><span class="c2">&nbsp;for further instructions.</span>

<p class="c35">List the results&nbsp;of the above task&nbsp;in the provided&nbsp;<span class="c13 c20">q2-results.csv</span>&nbsp;file under the relevant sections.&nbsp;You must manually enter the output generated into the corresponding sections of the&nbsp;<span class="c20">q2-results.csv</span>&nbsp;file.&nbsp;(For generating the output in the Scala notebook, refer to&nbsp;<span class="c9">show()</span>&nbsp;and&nbsp;<span class="c9">display()</span>functions of Scala)

<p class="c35"><span class="c13 c37">Deliverables</span>

<ol class="c4 lst-kix_d10axn9kzlav-0 start" start="1">
<li class="c18"><span class="c13">[10 pts]</span></li>
</ol>
<ol class="c4 lst-kix_d10axn9kzlav-1 start" start="1">
<li class="c36 c62"><span class="c13">q2-yourGTusername.dbc:&nbsp;</span><span class="c2">Your solution as Scala Notebook archive file (.dbc) exported from Databricks. See the Databricks Setup Guide on creating an exportable archive for details.</span></li>
<li class="c36 c62"><span class="c13">q2-yourGTusername.scala</span><span class="c2">: Your solution as a Scala source file exported from Databricks. See the Databricks Setup Guide on creating an exportable source file for details.</span></li>
<li class="c36 c62"><span class="c13">q2-yourGTusername.html</span><span class="c2">: Your solution as a HTML file exported from Databricks. See the Databricks Setup Guide on how to export your code as an HTML.</span></li>
</ol>
<p class="c47 c59"><span class="c13 c3">Note:&nbsp;</span><span class="c3">You should export your solution in all the three formats – .dbc, .scala and .html.</span>

<ol class="c4 lst-kix_d10axn9kzlav-0" start="2">
<li class="c18"><span class="c13">[15 pts] q2-results.csv:</span>&nbsp;The output file of processing&nbsp;<span class="c13 c20">nyc-tripdata.csv</span>&nbsp;from the q2 notebook file. You must copy the outputs of the&nbsp;<span class="c20">display()</span>/<span class="c20">show()</span>&nbsp;function into file titled&nbsp;<span class="c13 c20">q2-results.csv</span><span class="c13">&nbsp;</span><span class="c2">under the relevant sections.</span></li>
</ol>
<h2 id="h.1ksv4uv" class="c66 c67"><span class="c30 c65">Q3 [35 points] Analyzing Large Amount of Data with Pig on AWS</span></h2>
<p class="c36">You will try out&nbsp;<span class="c17"><a class="c5" href="https://www.google.com/url?q=http://pig.apache.org&amp;sa=D&amp;ust=1601353860904000&amp;usg=AOvVaw2awYwThMso-y6q4RNtn6CW">Apache Pig</a></span>&nbsp;for processing data on Amazon Web Services (AWS).<span class="c2 c10">&nbsp;This is a fairly simple task, and in practice you may be able to tackle this using commodity computers (e.g., consumer-grade laptops or desktops). However, we would like you to use this exercise to learn and solve it using distributed computing on Amazon EC2, and gain experience (very helpful for your career), so you will be prepared to tackle problems that are more complex.</span>

<p class="c36"><span class="c2">The services you will primarily be using are Amazon S3 storage, Amazon Elastic Cloud Computing (EC2) virtual servers in the cloud, and Amazon Elastic MapReduce (EMR) managed Hadoop framework.</span>

<p class="c7">For this question, you will only<span class="c3 c10">&nbsp;</span><span class="c10">use up</span><span class="c3 c10">&nbsp;a very small fraction of your $100 credit</span>.

<h3 id="h.44sinio" class="c39"><span class="c38">AWS Guidelines</span></h3>
<p class="c36">Please read the&nbsp;<span class="c17"><a class="c5" href="https://www.google.com/url?q=https://docs.google.com/document/d/e/2PACX-1vRpdZ7Z0lp_KQov0YszFDcxzbO5MoFwv0DJUr-6ms4HyFawBSZBPCESAJxr4ctjxrfeLsBAAdW9rW2i/pub&amp;sa=D&amp;ust=1601353860905000&amp;usg=AOvVaw2GbG9NaX9_wFC0QzvIEkfr">AWS Setup Tutorial</a></span>&nbsp;provided to set up your AWS account.&nbsp;Instructions are provided both as a written guide, and a video tutorial.

<h3 id="h.2jxsxqh" class="c74 c67"><span class="c38">Datasets</span></h3>
<p class="c36">In this question, you will use a dataset of trips provided by the New York City Taxi and Limousine Commision (TLC). Further details on this dataset are available&nbsp;<span class="c17"><a class="c5" href="https://www.google.com/url?q=https://registry.opendata.aws/nyc-tlc-trip-records-pds/&amp;sa=D&amp;ust=1601353860906000&amp;usg=AOvVaw0oyb3PZxVmqKFFge1jGmzJ">here</a></span>&nbsp;and&nbsp;<span class="c17"><a class="c5" href="https://www.google.com/url?q=https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page&amp;sa=D&amp;ust=1601353860907000&amp;usg=AOvVaw3x6L2rmzJyxQkyugRWWGy-">here</a></span>. Using these links&nbsp;you&nbsp;can explore<span class="c2">&nbsp;the structure of the data, however you will be accessing the dataset directly through AWS via the code outlined in the homework skeleton. You will be working with two samples of this data, one small, and one much larger.</span>

<p class="c36"><span class="c13 c3">VERY IMPORTANT</span><span class="c3">: Both the datasets are in the&nbsp;</span><span class="c13 c3 c10">US East (N. Virginia)</span><span class="c3">&nbsp;region. Using machines in other regions for computation would incur data transfer charges. Hence, set your region to&nbsp;</span><span class="c13 c3 c10">US East (N. Virginia)&nbsp;</span><span class="c3 c10">in the beginning (not Oregon, which is the default).&nbsp;</span><span class="c13 c3 c10">This is extremely important, otherwise your code may not work and you may be charged extra.</span>

<h3 id="h.z337ya" class="c39"><span class="c38">Goal</span></h3>
<p class="c7 c14">You work at NYC TLC, and since the company bought a few new taxis, your boss has asked you to determine where good locations for the taxi drivers to frequent so as to pick up more passengers. Of course, the more profitable the locations are, the better. Your boss also tells you not to worry about short trips for&nbsp;<span class="c13">any&nbsp;</span>of your analysis, so only analyze trips which are<span class="c13">&nbsp;2 miles or longer</span><span class="c2">.</span>

<p class="c7 c14">You will be analyzing yellow taxi trips and green taxi trips&nbsp;<span class="c13">together</span>, i.e., perform your analysis on the “<span class="c13">union</span>”<span class="c13">&nbsp;</span>of those trips<span class="c2">.</span>

<p class="c7 c14">First, find the&nbsp;<span class="c13">20&nbsp;</span>most popular drop off locations in the Manhattan borough by finding which of these destinations had the greatest&nbsp;<span class="c13">passenger count</span><span class="c2">.</span>

<p class="c7 c14">Now, analyze all pickup locations, regardless of borough. For each pickup location, determine the&nbsp;<span class="c13">average total amount</span>&nbsp;per trip and the&nbsp;<span class="c13">proportion</span>&nbsp;of trips starting at that pickup location that would end at one of the most popular drop off locations (i.e., proportion = number of trips that start at pick up location and end at a popular destination / total &nbsp;number of trips that start at that pick up location). In other words, these two values represent the average amount of money TLC would make for a trip starting at that location and the probability it will end up at one of the most popular destinations.&nbsp;<span class="c13">Multip</span><span class="c13">ly&nbsp;</span>the&nbsp;<span class="c20">average total amount</span>&nbsp;value and the&nbsp;<span class="c20">proportion</span>&nbsp;value, to weigh the income &nbsp;made based on the probability of passengers going to the popular destinations.

<p class="c7 c14">Bear in mind,&nbsp;your boss&nbsp;is not as savvy with the data as you are, and is not interested in location IDs. To make it very easy for your boss, provide the&nbsp;<span class="c13">Borough&nbsp;</span>and&nbsp;<span class="c13">Zone&nbsp;</span>for each of the top 20 pick up locations you determined. To help you evaluate the correctness of your output, we have provided you with&nbsp;<span class="c17"><a class="c5" href="https://www.google.com/url?q=https://www.dropbox.com/s/aqk515oydiqup23/pig-output-small.txt?dl%3D1&amp;sa=D&amp;ust=1601353860909000&amp;usg=AOvVaw1XMLrbxBup8x21MDNats9v">the output for the small dataset</a></span>.

<p class="c7"><span class="c13 c3">Note</span><span class="c3">: Please strictly follow the formatting requirements for your output as shown in the small dataset output file. You can use&nbsp;</span><span class="c17"><a class="c5" href="https://www.google.com/url?q=https://www.diffchecker.com/&amp;sa=D&amp;ust=1601353860910000&amp;usg=AOvVaw0i4FxqMnRKvkMAF9V9gyc3">https://www.diffchecker.com/</a></span><span class="c3 c44">&nbsp;to make sure the formatting is correct. Improperly formatted outputs may not receive any points, as we may not know how to interpret them.</span>

<h3 id="h.4i7ojhp" class="c67 c74"><span class="c38">Loading data in PIG</span></h3>
<p class="c7"><span class="c2">You are provided with two Pig files in the skeleton. One defines the small data set, and the other defines the large one. Go through them to find out which fields are available and how they are typed. Do not change any of the code already provided in the files</span>

<p class="c7">Data will be loaded into&nbsp;<span class="c13">3 relation</span><span class="c2">s (a construct in Pig similar to variables).</span>

<ol class="c4 lst-kix_z9p18e4g1se2-0 start" start="1">
<li class="c0"><span class="c2">green (Data from Green Taxi trips)</span></li>
<li class="c0"><span class="c2">yellow (Data from Yellow Taxi trips)</span></li>
<li class="c0"><span class="c2">locations (Relates to the PULocationID and DOLocationID in green and yellow)</span></li>
</ol>
<h3 id="h.1y810tw" class="c39"><span class="c38">Using PIG (Read these instructions carefully)</span></h3>
<p class="c7">There are two methods to debug PIG on AWS (all instructions&nbsp;are in the&nbsp;<span class="c17"><a class="c5" href="https://www.google.com/url?q=https://docs.google.com/document/d/e/2PACX-1vRpdZ7Z0lp_KQov0YszFDcxzbO5MoFwv0DJUr-6ms4HyFawBSZBPCESAJxr4ctjxrfeLsBAAdW9rW2i/pub&amp;sa=D&amp;ust=1601353860911000&amp;usg=AOvVaw3-7JW1HCBFDNjiZJThHWzN">AWS Setup Tutorial</a></span>):

<ol class="c4 lst-kix_list_7-0 start" start="1">
<li class="c0"><span class="c13">Use the interactive PIG shell</span>&nbsp;provided by EMR to perform this task from the command line (grunt). Refer to&nbsp;<span class="c13">Section 5</span><span class="c2">&nbsp;in the AWS Setup Tutorial for a detailed step-by-step procedure. You should use this method if you are using PIG for the first time as it is easier to debug your code. However, as this method requires &nbsp;a persistent ssh connection to your cluster until your task is complete, it is suitable only for the smaller dataset.</span></li>
</ol>
<ol class="c4 lst-kix_list_7-0" start="2">
<li class="c0"><span class="c13">Upload a PIG script&nbsp;</span>with all the commands which computes and direct the output from the command line into a separate file. Once you verify the output on the smaller dataset, use this method for the larger dataset. You do not have to ssh or stay logged into your account. You can start your EMR job, and come back after the job is complete! This is covered in&nbsp;<span class="c13">Section 6</span><span class="c2">&nbsp;of the tutorial.</span></li>
</ol>
<p class="c7"><span class="c13 c3">Note</span><span class="c3">: In summary, verify the output for the smaller dataset with Method 1 and submit the results for the bigger dataset using Method 2.</span>

<p class="c7"><span class="c13 c3">Note:</span>

<ul class="c4 lst-kix_list_18-0 start">
<li class="c0"><span class="c2">Refer to other commands such as LOAD, USING PigStorage, FILTER, GROUP, ORDER BY, FOREACH, GENERATE, LIMIT, STORE, UNION, JOIN, etc.</span></li>
</ul>
<ul class="c4 lst-kix_list_9-0 start">
<li class="c0">Your script will fail if your output directory already exists. For instance, if you run a job with the output folder as&nbsp;<span class="c13">s3://cse6242-&lt;</span><span class="c13 c10 c23">GT account username</span><span class="c13">&gt;/output-small</span><span class="c2">, the next job which you run with the same output folder will fail. Hence, please use a different folder for the output for every run.</span></li>
</ul>
<h3 id="h.2xcytpi" class="c39 c14"><span class="c38">Deliverables</span></h3>
<ol class="c4 lst-kix_c6mrwy28ztd2-0 start" start="1">
<li class="c0"><span class="c13">[15 pts]&nbsp;</span><span class="c13">pig-script.txt</span>: The PIG script for the question (using the&nbsp;<span class="c13">larger</span>&nbsp;data set).</li>
</ol>
<ol class="c4 lst-kix_c6mrwy28ztd2-0" start="2">
<li class="c0"><span class="c13">[20 pts]&nbsp;</span><span class="c13">pig-output.txt</span>: Output&nbsp;<span class="c13">(tab-separated)&nbsp;</span>(using the&nbsp;<span class="c13">larger</span>&nbsp;data&nbsp;set).</li>
</ol>
<p class="c7"><span class="c13 c3">Note:&nbsp;</span><span class="c44 c3">Please strictly follow the guidelines below, otherwise your answer may not be graded.</span>

<ol class="c4 lst-kix_list_20-0 start" start="1">
<li class="c0"><span class="c3">Ensure that file names (case sensitive) are correct.</span></li>
<li class="c0"><span class="c3">Ensure file extensions (.txt) are correct.</span></li>
<li class="c0"><span class="c44 c3">Double check that you are submitting the correct set of files — we only want the script and output from the larger dataset. Also double check that you are writing the right dataset’s output to the right file.</span></li>
<li class="c0"><span class="c3">You are welcome to store your script’s output in any bucket you choose, as long as you can download and submit the correct files.</span></li>
<li class="c0"><span class="c3">D</span><span class="c3">o not make any manual changes to the output files</span></li>
</ol>
<h2 id="h.1ci93xb" class="c60">Q4 [35 points]&nbsp;<span class="c16">Analyzing a&nbsp;</span><span class="c16">Large&nbsp;</span><span class="c16">Datasets&nbsp;</span><span class="c16">using Hadoop on Microsoft Azure</span></h2>
<p class="c36"><span class="c13 c3">VERY IMPORTANT</span><span class="c3">: Use Firefox or Chrome in incognito/private browsing mode when configuring anything related to Azure (e.g., when using Azure portal), to prevent issues due to browser caches. Safari sometimes loses connections.</span>

<h3 id="h.3whwml4" class="c39 c14"><span class="c38">Goal</span></h3>
<p class="c36">The goal of this question is to familiarize you with creating cluster/storage and running MapReduce programs on Microsoft Azure. Your task is to write two separate MapReduce programs for NYC Taxi &amp; Limousine Commission Dataset to compute (a) compute the distribution of degree differences of locations; (b) the average fare for different passenger counts (see example below).&nbsp;<span class="c21">Note that this question shares some similarities with Question 1 (e.g., both are analyzing graphs). Question 1 can be completed using your own computer. This question is to be completed using Azure. We recommend that you first complete Question 1.&nbsp;</span>Please carefully read the following instructions.

<p class="c36">You will use the data file&nbsp;<span class="c17"><a class="c5" href="https://www.google.com/url?q=https://www.dropbox.com/s/7t01pw6neo2nyrb/data.zip?dl%3D0&amp;sa=D&amp;ust=1601353860916000&amp;usg=AOvVaw3t-yoBic-3II9b72KzM0wV">data.tsv</a></span><sup class="c46"><a id="ftnt_ref2" href="https://docs.google.com/document/d/e/2PACX-1vQaTAgmrkswYCvRMvenDqYl3EsorFt54DrdC578IKVFM9kISsyrRDqCehLOGA4rWBmJhaXSFVuS7UB-/pub#ftnt2">[2]</a></sup>&nbsp;(~ 7.6 million rows).&nbsp;<span class="c2">Each line represents a single taxi trip consisting of four tab-separated values: PickUpLocationID, DropOffLocationID, PassengerCount, TotalFare.</span>

<p class="c36">PickUpLocationID and DropOffLocationID are positive integers. We view this dataset as a&nbsp;<span class="c13">graph</span>&nbsp;(or network) of locations, where each&nbsp;<span class="c13">node</span>&nbsp;in this graph is a location ID (PickUpLocationID or DropOffLocationID) and we connect two location IDs with a separate&nbsp;<span class="c13">directed edge</span>&nbsp;for&nbsp;each trip&nbsp;<span class="c2">that goes from the “Source” location (PickUpLocationID) to the “Target” location (DropOffLocationID). Every trip is shown as a separate directed edge.</span>

<table class="c96">
<tbody>
<tr class="c57">
<td class="c52" colspan="1" rowspan="1">
<p class="c8"><span class="c22 c9">PickUpLocationID</span>

</td>
<td class="c99" colspan="1" rowspan="1">
<p class="c8"><span class="c22 c9">DropOffLocationID</span>

</td>
<td class="c81" colspan="1" rowspan="1">
<p class="c8"><span class="c22 c9">PassengerCount</span>

</td>
<td class="c94" colspan="1" rowspan="1">
<p class="c8"><span class="c22 c9">TotalFare</span>

</td>
</tr>
<tr class="c106">
<td class="c52" colspan="1" rowspan="1">
<p class="c8"><span class="c22 c9">264</span>

</td>
<td class="c32" colspan="1" rowspan="1">
<p class="c8"><span class="c22 c9">264</span>

</td>
<td class="c76" colspan="1" rowspan="1">
<p class="c8"><span class="c22 c9">5</span>

</td>
<td class="c108" colspan="1" rowspan="1">
<p class="c8"><span class="c22 c9">4.3</span>

</td>
</tr>
<tr class="c57">
<td class="c52" colspan="1" rowspan="1">
<p class="c8"><span class="c22 c9">97</span>

</td>
<td class="c27" colspan="1" rowspan="1">
<p class="c8"><span class="c22 c9">49</span>

</td>
<td class="c40" colspan="1" rowspan="1">
<p class="c8"><span class="c22 c9">2</span>

</td>
<td class="c25" colspan="1" rowspan="1">
<p class="c8"><span class="c22 c9">7.3</span>

</td>
</tr>
<tr class="c57">
<td class="c52" colspan="1" rowspan="1">
<p class="c8"><span class="c22 c9">49</span>

</td>
<td class="c27" colspan="1" rowspan="1">
<p class="c8"><span class="c22 c9">189</span>

</td>
<td class="c40" colspan="1" rowspan="1">
<p class="c8"><span class="c22 c9">2</span>

</td>
<td class="c25" colspan="1" rowspan="1">
<p class="c8"><span class="c22 c9">5.8</span>

</td>
</tr>
<tr class="c57">
<td class="c52" colspan="1" rowspan="1">
<p class="c8"><span class="c22 c9">189</span>

</td>
<td class="c27" colspan="1" rowspan="1">
<p class="c8"><span class="c22 c9">17</span>

</td>
<td class="c40" colspan="1" rowspan="1">
<p class="c8"><span class="c22 c9">2</span>

</td>
<td class="c25" colspan="1" rowspan="1">
<p class="c8"><span class="c22 c9">19.71</span>

</td>
</tr>
<tr class="c57">
<td class="c52" colspan="1" rowspan="1">
<p class="c8"><span class="c22 c9">264</span>

</td>
<td class="c27" colspan="1" rowspan="1">
<p class="c8"><span class="c22 c9">264</span>

</td>
<td class="c40" colspan="1" rowspan="1">
<p class="c8"><span class="c22 c9">1</span>

</td>
<td class="c25" colspan="1" rowspan="1">
<p class="c8"><span class="c22 c9">19.3</span>

</td>
</tr>
<tr class="c57">
<td class="c52" colspan="1" rowspan="1">
<p class="c8"><span class="c22 c9">49</span>

</td>
<td class="c27" colspan="1" rowspan="1">
<p class="c8"><span class="c9 c22">17</span>

</td>
<td class="c40" colspan="1" rowspan="1">
<p class="c8"><span class="c22 c9">1</span>

</td>
<td class="c25" colspan="1" rowspan="1">
<p class="c8"><span class="c22 c9">7.8</span>

</td>
</tr>
</tbody>
</table>
<p class="c36"><span class="c2">Your code should accept two arguments upon running. The first argument (args[0]) will be a path for the input graph file, and the second argument (args[1]) will be a path for output directory. The default output mechanism of Hadoop will create multiple files on the output directory such as part-00000, part-00001, which will have to be merged and downloaded to a local directory (instructions on how to do this are provided below).</span>

<h3 id="h.ldk837hmtuns" class="c74 c67">4a.<span class="c38">&nbsp;Compute distribution of degree differences for locations</span></h3>
<p class="c36"><span class="c2">Each line of your output is of the format:</span>

<p class="c36"><span class="c22 c9">diff&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;count</span>

<ol class="c4 lst-kix_mq8kttyot7vq-0 start" start="1">
<li class="c18"><span class="c9">diff</span><span class="c2">&nbsp;is a node’s out-degree minus its in-degree</span></li>
<li class="c18"><span class="c9">count</span>&nbsp;is the number of nodes that have the value of&nbsp;<span class="c9">diff</span><span class="c2">&nbsp;(specified in 1)</span></li>
<li class="c18">Separate&nbsp;<span class="c9">diff</span>&nbsp;and&nbsp;<span class="c9">count</span><span class="c2">&nbsp;by a tab (t) character</span></li>
<li class="c18"><span class="c2">Lines in your output do not need to be sorted</span></li>
<li class="c18"><span class="c2">Do not add any header or column name to your output</span></li>
<li class="c18"><span class="c2">All values in the output should be integer</span></li>
</ol>
<p class="c36">The out-degree of a node (location ID) is the number of edges where that node is the Source (PickUpLocationID). The in-degree of a node is the number of edges where that node is the Target (DropOffLocationID).&nbsp;When the source and target are the same node,&nbsp;that self-loop contributes to both the node’s in-degree and out-degree.&nbsp;For example, in the above table, there are two entries of&nbsp;<span class="c9">264</span>→<span class="c9">264</span>,&nbsp;then&nbsp;both&nbsp;in-degree and out-degree&nbsp;of node&nbsp;<span class="c9">264</span>&nbsp;will be 2.

<p class="c36">The following result is computed based on the data above.

<p class="c7"><span class="c22 c9">-2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1</span>

<p class="c7"><span class="c22 c9">0&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2</span>

<p class="c7"><span class="c22 c9">1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2</span>

<table class="c96">
<tbody>
<tr class="c88">
<td class="c34" colspan="1" rowspan="1">
<p class="c7"><span class="c19 c13">Output</span>

</td>
<td class="c55" colspan="1" rowspan="1">
<p class="c7"><span class="c19 c13">Explanation</span>

</td>
</tr>
<tr class="c88">
<td class="c34" colspan="1" rowspan="1">
<p class="c36"><span class="c9">-2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1</span>

</td>
<td class="c55" colspan="1" rowspan="1">
<p class="c36">There is 1 node (node 17) whose degree difference is -2

</td>
</tr>
<tr class="c88">
<td class="c34" colspan="1" rowspan="1">
<p class="c36"><span class="c9">0&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2</span>

</td>
<td class="c55" colspan="1" rowspan="1">
<p class="c36">There are 2 nodes (node 264,node 189) whose degree difference is 0.

</td>
</tr>
<tr class="c88">
<td class="c34" colspan="1" rowspan="1">
<p class="c36"><span class="c9">1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2</span>

</td>
<td class="c55" colspan="1" rowspan="1">
<p class="c36"><span class="c2">There are 2 nodes (node 49,node 97) whose degree difference is 1.</span>

</td>
</tr>
</tbody>
</table>
<p class="c36"><span class="c13 c21">Hint​:</span><span class="c21">&nbsp;</span><span class="c2">One way of accomplishing this task is to use the mapreduce procedure twice. The first one for finding the difference between out-degree and in-degree for each node, the second for calculating the node count of each degree difference. You will need to make changes in the skeleton code for this.</span>

<h3 id="h.b5ah3en7hauk" class="c74 c67">4b.<span class="c38">&nbsp;Compute average fare for different passenger counts</span></h3>
<p class="c36"><span class="c2">Each line of your output is of the format:</span>

<p class="c36"><span class="c22 c9">PassengerCount&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;AverageFare</span>

<ol class="c4 lst-kix_7dq02xjlols3-0 start" start="1">
<li class="c18"><span class="c9">PassengerCount&nbsp;</span><span class="c2">is the set of the third column of the data</span></li>
<li class="c18"><span class="c9">AverageFare&nbsp;</span>is the average fare for different&nbsp;<span class="c9">PassengerCount</span></li>
<li class="c18">Separate&nbsp;<span class="c9">PassengerCount</span>&nbsp;and&nbsp;<span class="c9">AverageFare</span>&nbsp;by a tab (t) character<span class="c2">&nbsp;</span></li>
<li class="c18">Lines in your output do not need to be sorted</li>
<li class="c18"><span class="c2">Do not add any header or column name to your output</span></li>
<li class="c18">The&nbsp;<span class="c9">PassengerCount</span>&nbsp;in the output should be integer</li>
<li class="c18">The&nbsp;<span class="c9">AverageFare</span>&nbsp;must&nbsp;<span class="c10 c98">be rounded to 2 decimal places</span></li>
</ol>
<p class="c36"><span class="c2">The following result is computed based on the data above.</span>

<p class="c7 c14"><span class="c22 c9">1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;13.55</span>

<p class="c7 c14"><span class="c22 c9">2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;10.94</span>

<p class="c7 c14"><span class="c22 c9">5&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.30</span>

<table class="c96">
<tbody>
<tr class="c88">
<td class="c29" colspan="1" rowspan="1">
<p class="c7"><span class="c19 c13">Output</span>

</td>
<td class="c73" colspan="1" rowspan="1">
<p class="c7"><span class="c19 c13">Explanation</span>

</td>
</tr>
<tr class="c88">
<td class="c29" colspan="1" rowspan="1">
<p class="c7 c14"><span class="c9">1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;13.55</span>

</td>
<td class="c73" colspan="1" rowspan="1">
<p class="c36">There are 2 rows for&nbsp;<span class="c9">PassengerCount=1</span>

The average fare&nbsp;<span class="c9">(19.3 + 7.8) / 2 = 13.55</span>

</td>
</tr>
<tr class="c88">
<td class="c29" colspan="1" rowspan="1">
<p class="c7 c14"><span class="c9">2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;10.94</span>

</td>
<td class="c73" colspan="1" rowspan="1">
<p class="c36">There are 3 rows for&nbsp;<span class="c9">PassengerCount=2</span>

The average fare is&nbsp;<span class="c9">(7.3 + 5.8 + 19.71) / 3 = 10.94</span>

</td>
</tr>
<tr class="c88">
<td class="c29" colspan="1" rowspan="1">
<p class="c7 c14"><span class="c9">5&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.30</span>

</td>
<td class="c73" colspan="1" rowspan="1">
<p class="c36">There is 1 row for&nbsp;<span class="c9">PassengerCount=5</span>

The average fare is&nbsp;<span class="c9">4.30</span>

</td>
</tr>
</tbody>
</table>
<p class="c7">In the Q4 folder of the hw3-skeleton, you will find the following files we have prepared for you in&nbsp;<span class="c13">a</span>&nbsp;and&nbsp;<span class="c13">b</span><span class="c2">&nbsp;subfolders:</span>

<ul class="c4 lst-kix_list_10-0 start">
<li class="c0"><span class="c13 c20">s</span><span class="c13">rc&nbsp;</span>directory contains a main Java file that you will work on. We have provided some code to help you get started. Feel free to edit it and add your files in the directory, but&nbsp;<span class="c13">the main class must be called “Q4a” and “Q4b”</span><span class="c2">.</span></li>
<li class="c0"><span class="c13">pom.xml</span><span class="c2">&nbsp;contains necessary dependencies and compile configurations for the question.</span></li>
</ul>
<p class="c7">To compile, you can run the command in the directory which contains&nbsp;<span class="c13">pom.xml</span><span class="c2">.</span>

<p class="c7"><span class="c22 c9 c95">mvn clean package</span>

<p class="c7"><span class="c22 c16">This command will generate a single JAR file in the target directory (i.e., a/target/q4a-1.0.jar or b/target/q4b-1.0.jar).</span>

<h3 id="h.5gn51gujq78r" class="c39"><span class="c38">Creating Clusters in HDInsight using the Azure portal</span></h3>
<p class="c7"><span class="c16">Azure HDInsight is an Apache Hadoop distribution. This means that it handles large amounts of data on demand. The next step is to use Azure’s web-based management tool to create a Linux cluster.&nbsp;</span><span class="c16">Follow the&nbsp;</span><span class="c16">recommended&nbsp;</span><span class="c16">steps shown&nbsp;</span><span class="c17 c16"><a class="c5" href="https://www.google.com/url?q=https://docs.google.com/presentation/d/e/2PACX-1vSjffMM3aX4vFZtx6E3FxRPiWoK9txSEqBStp22n9CGKjXJi84YfLwuMfnGzluaYDAF8oL540tromKn/pub?start%3Dfalse%26loop%3Dfalse%26delayms%3D3000%26slide%3Did.p1&amp;sa=D&amp;ust=1601353860945000&amp;usg=AOvVaw3RQgFGWJ6Wlp-mY8TlAt9i">here</a></span><span class="c16">&nbsp;</span><span class="c16">(or the full Azure’s documentation&nbsp;</span><span class="c17 c16"><a class="c5" href="https://www.google.com/url?q=https://azure.microsoft.com/en-us/documentation/articles/hdinsight-hadoop-create-linux-clusters-portal/&amp;sa=D&amp;ust=1601353860946000&amp;usg=AOvVaw2Qk5RR_hgywhZ0U8HHTV7x">here</a></span><span class="c16">)&nbsp;</span><span class="c16">to create a new cluster.</span>

<p class="c7"><span class="c16">At the end of this process, you will have created and provisioned a New HDInsight Cluster and Storage (the provisioning will take some time depending on how many nodes you chose to create).&nbsp;</span><span class="c16 c21">Record the following important information (we also recommend that you take screenshots) so you can refer to them later:</span>

<ul class="c4 lst-kix_list_25-0 start">
<li class="c0"><span class="c1">Cluster login credentials</span></li>
<li class="c0"><span class="c1">SSH credentials</span></li>
<li class="c0"><span class="c1">Resource group</span></li>
<li class="c0"><span class="c1">Storage account</span></li>
<li class="c0"><span class="c1">Container credentials</span></li>
</ul>
<p class="c7"><span class="c13 c3">VERY IMPORTANT</span><span class="c3">:&nbsp;</span><span class="c16 c3">HDInsight cluster billing starts once a cluster is created and stops when the cluster is deleted. Thus, you should delete your cluster when it is no longer in use. You can find all clusters and storages you have created in “All resources” on the left panel. &nbsp;Please refer to the official Azure documentation&nbsp;</span><span class="c16 c102"><a class="c5" href="https://www.google.com/url?q=https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-delete-cluster&amp;sa=D&amp;ust=1601353860948000&amp;usg=AOvVaw0ph_-8S_t7lrRMcZfF0zu8">here</a></span><span class="c16 c3">&nbsp;for how to delete an HDInsight cluster.</span>

<h3 id="h.j3ykavl6e9iy" class="c39"><span class="c38">Uploading data files to HDFS-compatible Azure Blob storage</span></h3>
<p class="c7"><span class="c2">We have listed the main steps from the documentation for uploading data files to your Azure Blob storage here:</span>

<ol class="c4 lst-kix_list_16-0 start" start="1">
<li class="c0">Follow the documentation&nbsp;<span class="c17"><a class="c5" href="https://www.google.com/url?q=https://azure.microsoft.com/en-us/documentation/articles/xplat-cli-install/&amp;sa=D&amp;ust=1601353860949000&amp;usg=AOvVaw37BI-OAvijT0khOLgSXug0">here</a></span><span class="c2">&nbsp;to install Azure CLI.</span></li>
<li class="c0">Open a command prompt, bash, or other shell, and use&nbsp;<span class="c24">az login</span><span class="c2">&nbsp;command to authenticate to your Azure subscription. When prompted, enter the username and password for your subscription.</span></li>
<li class="c0"><span class="c63 c95 c82">az storage account list</span><span class="c2">&nbsp;command will list the storage accounts for your subscription.</span></li>
<li class="c0"><span class="c24">az storage account keys list –account-nam</span><span class="c24">e &lt;storage-account-name&gt; –resource-group &lt;resource-group-name&gt;</span>&nbsp;command should return “key1” and “key2”.&nbsp;<span class="c77">Copy the value of “key1” because it will be used in the next steps.</span></li>
<li class="c0"><span class="c24">az storage container list –account-name &lt;storage-account-name&gt; –account-key &lt;key1-value&gt;</span>&nbsp;command will list your blob containers.</li>
<li class="c0"><span class="c24">az storage blob upload –account-name &lt;storage-account-name&gt; –account-key &lt;key1-value&gt; –file &lt;data.tsv&gt; –container-name &lt;container-name&gt; –name&nbsp;</span><span class="c24">&lt;new-</span><span class="c24">blob</span><span class="c24">-name</span><span class="c24">&gt;</span><span class="c24">/&lt;data.tsv&gt;&nbsp;</span>command will upload the source file to your blob storage container.&nbsp;<span class="c63 c82">&lt;new-blob-name&gt;</span><span class="c63 c82">&nbsp;</span><span class="c2">is the folder name you will create and where you would like to upload tsv files to. If the file is uploaded successfully, you should see “Finished [#####] 100.0000%”.</span></li>
</ol>
<p class="c7">Using these steps, upload&nbsp;<span class="c13 c20">data.tsv</span>&nbsp;to your blob storage container. The uploading process may take some time. After that, you can find the uploaded files in storage blobs at&nbsp;<span class="c17"><a class="c5" href="https://www.google.com/url?q=http://portal.azure.com&amp;sa=D&amp;ust=1601353860951000&amp;usg=AOvVaw1oUsQSqDXzKd8zJLZIJRoi">Azure</a></span>&nbsp;(portal.azure.com) by clicking on “Storage accounts” in the left side menu and navigating through your storage account

(&lt;”All resources” in the panel&gt; → &lt;Your Storage Account&gt; → &lt;Select your container to which you’ve uploaded the dataset&gt; → &lt;Select the relevant blob folder&gt;).

For example, “jonDoeStorage” → “jondoecontainer-xxx” → “jdoeData” → “data.tsv”.

<span class="c2">After that write your hadoop code locally and convert it to a jar file using the steps mentioned above.</span>

<h3 id="h.hjp7gq1o449x" class="c39"><span class="c38">Uploading your Jar file to HDFS-compatible Azure Blob storage</span></h3>
<p class="c7"><span class="c16">Azure Blob storage is a general-purpose storage solution that integrates with HDInsight.&nbsp;</span>Your Hadoop code should directly access files on the&nbsp;<span class="c16">Azure Blob storage</span>.

<p class="c7">Upload the jar file created in the first step to Azure storage using the following command (here we take&nbsp;<span class="c63">q4a-1.0.jar</span>&nbsp;as an example, and you need to repeat steps for&nbsp;<span class="c63">q4b-1.0.jar</span><span class="c2">):</span>

<p class="c7"><span class="c24">scp &lt;your-relative-path&gt;/q4a-1.0.jar</span><span class="c43">&nbsp;&lt;ssh-username&gt;</span><span class="c43"><a class="c5" href="mailto:USERNAME@CLUSTERNAME-ssh.azurehdinsight.net">@</a></span><span class="c43">&lt;cluster-name&gt;</span><span class="c24"><a class="c5" href="mailto:USERNAME@CLUSTERNAME-ssh.azurehdinsight.net">-ssh.azurehdinsight.net</a></span><span class="c24 c64">:</span>

<p class="c7">You will be asked to agree to connect by typing “yes” and your cluster login password. Then you will see&nbsp;<span class="c63">q4a-1.0.jar</span><span class="c2">&nbsp;is uploaded 100%.</span>

<p class="c7"><span class="c2">SSH into the HDInsight cluster using the following command:</span>

<p class="c7"><span class="c43">ssh &lt;ssh-username&gt;</span><span class="c43"><a class="c5" href="mailto:USERNAME@CLUSTERNAME-ssh.azurehdinsight.net">@</a></span><span class="c42">&lt;cluster-name&gt;-ssh.azurehdinsight.net</span>

<p class="c7"><span class="c63 c82">&lt;ssh-username&gt;&nbsp;</span>is what you have created in step 10 in the flow.

<p class="c7"><span class="c13 c3">

Note</span><span class="c3">: if you see the warning – REMOTE HOST IDENTIFICATION HAS CHANGED, you may clean /home/&lt;user&gt;/.ssh/known_hosts” by using the command&nbsp;</span><span class="c63 c23 c84">rm ~/.ssh/known_hosts</span><span class="c3">. Please refer to&nbsp;</span><span class="c17"><a class="c5" href="https://www.google.com/url?q=https://stackoverflow.com/questions/20840012/ssh-remote-host-identification-has-changed&amp;sa=D&amp;ust=1601353860955000&amp;usg=AOvVaw23OWKViOadPtHF6MHO-pbr">host identification</a></span><span class="c44 c3">.</span>

<p class="c7"><span class="c3">&nbsp;</span>

<p class="c7">Run the&nbsp;<span class="c43">ls</span>&nbsp;command to make sure that the&nbsp;<span class="c24">q4a-1.0.jar</span><span class="c2">&nbsp;file is present.</span>

<p class="c7">To run your code on the&nbsp;<span class="c63">data.tsv</span><span class="c2">&nbsp;file, run the following command:</span>

<p class="c7"><span class="c43">yarn jar q4a-1.0.jar edu.gatech.cse6242.Q4a wasbs://&lt;container-name&gt;@</span><span class="c24">&lt;storage-account-name&gt;</span><span class="c43">.blob.core.windows.net/</span><span class="c24">&lt;new-blob-name&gt;</span><span class="c43">/data.tsv wasbs://&lt;container-name&gt;@</span><span class="c24">&lt;storage-account-name&gt;</span><span class="c43">.blob.core.windows.net/degreeoutput</span>

<p class="c7"><span class="c42">Command format: yarn jar jarFile packageName.ClassName dataFileLocation outputDirLocation</span>

<p class="c7"><span class="c13 c3">Note</span><span class="c3">: if “</span><span class="c63 c23 c3">Exception in thread “main” org.apache.hadoop.mapred.FileAlreadyExistsException…</span><span class="c23 c3">”</span><span class="c63 c23 c3">&nbsp;</span><span class="c3">occurs, you need to delete the output folder and files from your Storage. You can do this at portal.azure.com.</span><span class="c3">&nbsp;Click&nbsp;</span><span class="c16 c3">“All resources” in the left panel, you will see you storage and cluster. Click your storage, then your container, you will see all folders created by you and the “degreeoutput” folder. You need to click “Load more” at the bottom to see all folders/files. You need to delete output at different places: 1. degreeoutput; 2. user/sshuser/*</span>

<p class="c7">The output will be located in the directory:&nbsp;<span class="c43">wasbs://&lt;container-name&gt;@</span><span class="c24">&lt;storage-account-name&gt;</span><span class="c43">.blob.core.windows.net/degreeoutput</span>

<p class="c7"><span class="c2">If there are multiple output files, merge the files in this directory using the following command (you may see there is only one output file and no need to merge, but there is no hurt to run this command):</span>

<p class="c7"><span class="c43">hdfs dfs -cat wasbs://&lt;container-name&gt;@</span><span class="c24">&lt;storage-account-name&gt;</span><span class="c42">.blob.core.windows.net/degreeoutput/* &gt; degree.out</span>

<p class="c7"><span class="c42">Command format: hdfs dfs -cat location/* &gt;outputFile</span>

<p class="c7"><span class="c2">Then you may exit to your local machine using the command:</span>

<p class="c7"><span class="c54">exit</span>

<p class="c7">You can download the merged file to the local machine (this can be done either from&nbsp;<span class="c17"><a class="c5" href="https://www.google.com/url?q=https://portal.azure.com/&amp;sa=D&amp;ust=1601353860958000&amp;usg=AOvVaw2NddsY2BcvlDv4CRM4ODhg">Azure Portal</a></span><span class="c2">&nbsp;or by using the scp command from the local machine). Here is the scp command for downloading this output file to your local machine:</span>

<p class="c7"><span class="c43">scp &lt;ssh-username&gt;@&lt;cluster-name&gt;-ssh.azurehdinsight.net:/home/&lt;ssh-username&gt;/degree.out&nbsp;</span><span class="c43">&lt;your local directory&gt;</span>

<p class="c7">Using the above command from your local machine will download the&nbsp;<span class="c63">degree.out</span>&nbsp;file into the local directory. Repeat this process to download&nbsp;<span class="c63">average.out</span>. Make sure your output file has exactly two columns of values as shown above.&nbsp;<span class="c3">Your output files should be able to be opened and readable in text editors like notepad++</span><span class="c12">.&nbsp;</span><span class="c13 c3">The extension MUST be exactly “.out”, NOT “.txt.out”, “.tsv.out” or others.</span><span class="c12">&nbsp;</span><span class="c3">You should implement your own map/reduce procedure and should not import external graph processing library.</span>

<h3 id="h.4zsa3qe57719" class="c39">Deliverables</h3>
<ol class="c4 lst-kix_list_21-0 start" start="1">
<li class="c0">[8pt]&nbsp;<span class="c13">Q4a.java &amp; q4a-1.0.jar:&nbsp;</span><span class="c2">Your java code and converted jar file for Q4a.</span></li>
</ol>
<ol class="c4 lst-kix_list_21-0" start="2">
<li class="c0">[7pt]&nbsp;<span class="c13">Q4b.java &amp; q4b-1.0.jar:&nbsp;</span>Your java code and converted jar file for Q4b.</li>
</ol>
<ol class="c4 lst-kix_list_21-0" start="3">
<li class="c0">[10pt]&nbsp;<span class="c13">degree.out</span><span class="c2">: the output file generated after processing data.tsv.</span></li>
</ol>
<ol class="c4 lst-kix_list_21-0" start="4">
<li class="c0">[10pt]&nbsp;<span class="c13">average.out</span><span class="c2">: the output file generated after processing data.tsv.</span></li>
</ol>
<h2 id="h.2bn6wsx" class="c60">Q5 [10 points] &nbsp;Regression: Automobile price prediction, using Azure ML Studio</h2>
<p class="c7"><span class="c13 c3">Note</span><span class="c3">: Create and use a free workspace instance on&nbsp;</span><span class="c17"><a class="c5" href="https://www.google.com/url?q=https://studio.azureml.net/&amp;sa=D&amp;ust=1601353860961000&amp;usg=AOvVaw2vK5wFXknrDJOAcijWy1Cm">Azure Studio</a></span><span class="c3">&nbsp;instead of your Azure credit for this question. Please use your Georgia Tech username (e.g., jdoe3) to login. &nbsp;</span>

<h3 id="h.qsh70q" class="c67 c109"><span class="c37 c13">Goal</span></h3>
<p class="c36">The main purpose of this question is to introduce you to Microsoft Azure Machine Learning Studio and familiarize you with its basic functionality and typical machine learning workflow. Go through the “<span class="c17"><a class="c5" href="https://www.google.com/url?q=https://docs.microsoft.com/en-us/azure/machine-learning/studio/create-experiment&amp;sa=D&amp;ust=1601353860962000&amp;usg=AOvVaw2Cr4JNXNnhVu5ATdF_YEu4">Automobile price prediction</a></span><span class="c2">” tutorial and complete the tasks below.</span>

<p class="c36">You will modify the given file,&nbsp;<span class="c13">results.csv</span>,<span class="c13">&nbsp;</span><span class="c2">by adding your results for each of the tasks below. We will autograde your solution, therefore DO NOT change the order of the questions. &nbsp;Report the exact numbers that you get in your output, and DO NOT round any numbers.</span>

<ol class="c4 lst-kix_list_13-0 start" start="1">
<li class="c18">Update your GT username in the results.csv file to replace gburdell3.</li>
<li class="c18">[3 points] Repeat the experiment mentioned in the tutorial and report the values of the metrics as mentioned in the ‘<span class="c20">Evaluate Model’</span>&nbsp;section of the tutorial.</li>
<li class="c18">[3 points] Repeat the same experiment, change the ‘<span class="c20">Fraction of rows in the first output’</span><span class="c13 c41 c10 c103">&nbsp;</span>value in the split module to&nbsp;0.8&nbsp;(originally set to 0.75)&nbsp;and report the corresponding values of the metrics.</li>
<li class="c18">[4 points] Evaluate the model with the 5-fold cross-validation (<span class="c17"><a class="c5" href="https://www.google.com/url?q=https://docs.microsoft.com/en-us/azure/machine-learning/studio/evaluate-model-performance&amp;sa=D&amp;ust=1601353860963000&amp;usg=AOvVaw3Z2mzN5u48H1DFNQu3UJCR">CV</a></span>), select the parameters in the module&nbsp;<span class="c20">‘Partition and sample’</span>&nbsp;(<span class="c17"><a class="c5" href="https://www.google.com/url?q=https://docs.microsoft.com/en-us/azure/machine-learning/studio-module-reference/partition-and-sample&amp;sa=D&amp;ust=1601353860964000&amp;usg=AOvVaw2rCN3M9OPMvJHkB1adN6td">Partition and Sample</a></span>) (see figure below). Report the values of Root&nbsp;Mean Squared Error (RMSE) and&nbsp;Coefficient of Determination for each fold.&nbsp;(1st fold corresponds to fold number 0 and so on).</li>
</ol>
<p class="c7"><img decoding="async" title="" data-src="https://lh6.googleusercontent.com/bO9fhztxO4efWsUOhXApxPnu0Knc6YBks_1niWYhQvc7Fiw1uGPBMw2S2vDyQ5UmZOkgBMKO0yMApfdc9nie2iJFW1EycCQdlhZPScq-Z5n2AjV7uw2b4h0K8QMQMH6jtjbNJxdr" alt="" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload">

<p class="c7"><span class="c2">Figure: Property Tab of Partition and Sample Module</span>

<p class="c7 c14 c59">To summarize, in order to complete&nbsp;sub question 4,&nbsp;you need to do the following:

<ol class="c4 lst-kix_list_14-0 start" start="1">
<li class="c7 c14 c62">Import the entire dataset (<span class="c10">Automobile Price Data (Raw))</span></li>
<li class="c7 c14 c62"><span class="c2">Clean the missing data by removing rows that have any missing values</span></li>
<li class="c7 c14 c62"><span class="c2">Partition and Sample the data.</span></li>
<li class="c7 c14 c62"><span class="c2">Create a new model (Linear Regression)</span></li>
<li class="c7 c14 c62"><span class="c2">Finally, perform cross validation on the dataset.</span></li>
<li class="c7 c14 c62">Visualize/Report the values.</li>
</ol>
<p class="c7"><span class="c37 c13">Deliverables</span>

<ol class="c4 lst-kix_list_23-0 start" start="1">
<li class="c0">[10pt]<span class="c13">&nbsp;results.csv:</span>&nbsp;a csv file containing results for all of the three parts.</li>
</ol>
<h2 id="h.3as4poj" class="c66 c67"><span class="c30 c65">Important: folder structure of the zip file that you submit</span></h2>
<p class="c7">You are submitting a single zip file HW3-GTUsername.zip (e.g., HW3-jdoe3.zip, where “jdoe3” is your GT username), which must unzip to the following directory structure (i.e., a folder “HW3-jdoe3”, containing folders “Q1”, “Q2”, etc.). The files to be included in each question’s folder have been clearly specified at the end of each question’s problem description above.

<p class="c7"><span class="c9">HW3-GTUsername/ &nbsp; &nbsp; &nbsp;</span>

<p class="c7"><span class="c9">&nbsp; &nbsp; Q1/</span>

<p class="c7"><span class="c9">&nbsp; &nbsp; &nbsp; &nbsp; src/main/java/edu/gatech/cse6242/Q1.java</span>

<p class="c7"><span class="c9">&nbsp; &nbsp; &nbsp; &nbsp; pom.xml</span>

<p class="c7"><span class="c9">&nbsp; &nbsp; &nbsp; &nbsp; run1.sh</span>

<p class="c7"><span class="c9">&nbsp; &nbsp; &nbsp; &nbsp; run2.sh</span>

<p class="c7"><span class="c9">&nbsp; &nbsp; &nbsp; &nbsp; q1output1.tsv</span>

<p class="c7"><span class="c9">&nbsp; &nbsp; &nbsp; &nbsp; q1output2.tsv</span>

<p class="c7"><span class="c13 c79 c75">&nbsp; &nbsp; &nbsp; &nbsp;</span><span class="c13 c3 c79">&nbsp;(do not attach target directory)</span>

<p class="c7"><span class="c9">&nbsp; &nbsp; Q2/</span>

<p class="c7"><span class="c9">&nbsp; &nbsp; &nbsp; &nbsp;&nbsp;</span><span class="c22 c9">q2-yourGTusername.dbc</span>

<p class="c7"><span class="c22 c9">&nbsp; &nbsp; &nbsp; &nbsp; q2-yourGTusername.scala</span>

<p class="c7"><span class="c22 c9">&nbsp; &nbsp; &nbsp; &nbsp; q2-yourGTusername.html</span>

<p class="c7"><span class="c9">&nbsp; &nbsp; &nbsp; &nbsp; q2-results.csv</span>

<p class="c7"><span class="c9">&nbsp; &nbsp; Q3/</span>

<p class="c7"><span class="c9">&nbsp; &nbsp; &nbsp; &nbsp; pig-script.txt</span>

<p class="c7"><span class="c22 c9">&nbsp; &nbsp; &nbsp; &nbsp; pig-output.txt</span>

<p class="c7"><span class="c9">&nbsp; &nbsp; Q4/</span>

<p class="c7"><span class="c22 c9">&nbsp; &nbsp; &nbsp; &nbsp; a/</span>

<p class="c7 c15"><span class="c22 c9">src/main/java/edu/gatech/cse6242/Q4a.java</span>

<p class="c7 c15"><span class="c22 c9">pom.xml</span>

<p class="c7"><span class="c22 c9">&nbsp; &nbsp; &nbsp; &nbsp; b/</span>

<p class="c7 c15"><span class="c22 c9">src/main/java/edu/gatech/cse6242/Q4b.java</span>

<p class="c7"><span class="c22 c9">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;pom.xml</span>

<p class="c7"><span class="c9">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; q4a-1.0.jar&nbsp;</span><span class="c49 c13 c3">(from target directory)</span>

<p class="c7 c59"><span class="c9">&nbsp; q4b-1.0.jar&nbsp;</span><span class="c49 c13 c3">(from target directory)</span>

<p class="c7"><span class="c9">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; degree.out</span>

<p class="c7"><span class="c22 c9">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; average.out</span>

<p class="c7"><span class="c49 c13 c3">&nbsp; &nbsp; &nbsp; &nbsp;(do not attach target directory)</span>

<p class="c7"><span class="c13 c3 c79">&nbsp; &nbsp;&nbsp;</span><span class="c9">Q5/</span>

<p class="c7"><span class="c9">&nbsp; &nbsp; &nbsp; &nbsp; results.csv</span>
