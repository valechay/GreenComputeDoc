# GreenCompute
<!DOCTYPE html>
<html lang="en">
<head>
    <title>GreenCompute</title>
    <!-- Meta -->
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="">
    <meta name="author" content="">    
    <link rel="shortcut icon" href="favicon.ico">  
    <link href='https://fonts.googleapis.com/css?family=Open+Sans:300italic,400italic,600italic,700italic,800italic,400,300,600,700,800' rel='stylesheet' type='text/css'>
    <!-- FontAwesome JS -->
    <script defer src="assets/fontawesome/js/all.js"></script>
    <!-- Global CSS -->
    <link rel="stylesheet" href="assets/plugins/bootstrap/css/bootstrap.min.css">   
    <!-- Plugins CSS -->    
    <link rel="stylesheet" href="assets/plugins/prism/prism.css">
    <link rel="stylesheet" href="assets/plugins/elegant_font/css/style.css">  
      
    <!-- Theme CSS -->
    <link id="theme-style" rel="stylesheet" href="assets/css/styles.css">
    
</head> 

<body class="body-green">
    <div class="page-wrapper">
        <!-- ******Header****** -->
        <header id="header" class="header">
            <div class="container">
                <div class="branding">
                    <h1 class="logo">
                        <a href="index.html">
                            <!-- <span aria-hidden="true" class="icon_documents_alt icon"></span> -->
                            <span class="text-highlight">Green</span><span class="text-bold"><i>Compute</i></span>
                        </a>
                    </h1>
                    
                </div>
                
               <!--  <div class="top-search-box">
	                 <form class="form-inline search-form justify-content-center" action="" method="get">
	            
			            <input type="text" placeholder="Search..." name="search" class="form-control search-input">
			            
			            <button type="submit" class="btn search-btn" value="Search"><i class="fas fa-search"></i></button>
			            
			        </form>
                </div> -->
                
            </div><!--//container-->
        </header><!--//header-->
        <div class="doc-wrapper">
            <div class="container">
                <div id="doc-header" class="doc-header text-center">
                    <h1 class="doc-title"><i class="icon fa fa-paper-plane"></i> Green<i>Compute</i></h1>
                    <div class="meta"><i class="far fa-clock"></i> Last updated: March 3rd, 2023</div>
                </div><!--//doc-header-->
                <div class="doc-body row">
                    <div class="doc-content col-md-9 col-12 order-1">
                        <div class="content-inner">
                            <section id="download-section" class="doc-section">'
                                <h1 class="section-title"> Also known as green technology, is the use of computers and other computing devices and equipment in 
                                    energy-efficient and eco-friendly ways.</h1>
                                <h3 id = "description" class="block-title">What is Green<i>Compute?</i></h3>
                                <div class="section-block">
                                    <p>Green<i>Compute</i> is tool, that traverses the source code sections with  BFS - <i> (Breadth First Seach)</i>, <i>Intel Gadget API</i>, <i>Python (PSutil)</i>
                                </div>
                                <h3 id = "features" class="block-title">Features of Green<i>Compute</i></h3>
                                <div class="section-block">
                                    <ol>
                                        <li><p>Breadth-first search algorithm for traversing a source code repesented as an Abstract Syntax Tree to compute the CPU Utilization of each node (code snippet)   </p></li>
                                        <li><p>Aggregates the total power consupltion to further visualise energy trends on the Tableau dashboard</p></li>
                                        <li><p>Help developers identify critical energy inefficient areas in source code.</p></li>
                                    </ol>
                                </div>
                                <h3 id = "uses" class="block-title">Uses of Green<i>Compute</i></h3>
                                <div class="section-block">
                                    <ol>
                                        <li><p>Energy inefiicient code snipptes are discouraged from being written in further software developments.</p></li>
                                        <li><p>To help developers mitigate the usage of energy consuming code during new software developments, the developer must be aware of the usage of inefficent APIs and / or code in the project.</p></li>
                                        <li><p>With the help of Green<i>Compute</i> developers can identify the energy consuption in the development phase.</p></li>
                                    </ol>
                                </div>
                            </section><!--//doc-section-->
                            <section id="icons-section" class="doc-section">
                                <h2 class="section-title">Working of Green<i>Compute</i></h2>
                                <div class="section-block">
                                    <p>The approach followed by Green<i>Compute</i> is summarized below:</p>
                                    <ol>
                                        <li><p>In the current trend we parse the source code with Breadth First Search Alogorithm and we have a tree structure ready.</p></li>
                                        <li><p>We then parse the soure code of library to generate Abstract Syntax Tree.</p></li>
                                        <li><p>We then extract the CPU utilization metrics of the code snipptes by using Intel Gadget API and Python Psutil API.</p></li>
                                        <li><p>We then extract the CPU utilization metrics of the code snipptes by using Intel Gadget API and Python Psutil API.</p></li>
                                        <li><p>Green<i>Compute</i>, now visually represents the energy trends of our code</p></li>
                                    </ol>
                                </div><!--//section-block-->
                                <div class="section-block">
                                    <img class="img-fluid" src="assets/images/updated_process_diagram.PNG" alt="elegant icons" />
                                </div><!--//section-block-->
                                
                            </section><!--//doc-section-->
                            <section id="code-section" class="doc-section">
                                <h2 class="section-title">Source Code of Green<i>Compute</i></h2>
                                 <div class="section-block">
                                    <p>
                                        Source code of the extension can be found here - <a href="https://github.com/rishitha957/GreenCompute">Green<i>Compute</i>-Dev</a> 
                                        <ol>
                                            <li><p>energy-profiler is the entry point of the repository</p></li>
                                            <li><p>parse.py helps parse the source code of code repositories to create a abstarct syntax tree and visitors.py does a braedth first search on the created abstarct tree</p></li>
                                            <li><p>cpu.py uses Intel Power Gadget API to compute the CPU utilization of each node in the AST and outputs in the format of KiloWHs</p></li>
                                        </ol>
                                    </p>
                                </div>
                                
                                <div class="section-block">
                                    <img class="img-fluid" src="assets/images/image.PNG" alt="elegant icons" />
                                </div>
                                
                             
                            <section id="tables-section" class="doc-section">
                                <h2 class="section-title">Results</h2>
                                <div class="section-block">
                                    <p>Below summarizes the total number  of  deprecated  API elements detected by the Algorithm. The proposed algorithm identified 838 out of 871 API elements across six different Python libraries
                                    </p>
                                </div>
                                <div class="section-block">
                                    <img src="assets/images/results.JPG">
                                </div><!--//section-block-->
                            </section><!--//doc-section-->
                        </div><!--//content-inner-->
                    </div><!--//doc-content-->
                    <div class="doc-sidebar col-md-3 col-12 order-0 d-none d-md-flex">
                       
                    </div><!--//doc-sidebar-->
                </div><!--//doc-body-->              
            </div><!--//container-->
        </div><!--//doc-wrapper-->
        
        <div id="promo-block" class="promo-block">
            <div class="container">
                <div class="promo-block-inner">
                    <h3 class="promo-title text-center">Contributors</h3>
                    <p class = "text-center"><b>Rishitha Kalicheti, Smita Kumthekar, Yukti Valecha, Priyanka Salunke <br>
                    <i>UBS Business Solutions India Pvt. Ltd
                        Pune
                    </i></b>
                    </p>
                </div><!--//promo-block-inner-->  
            </div><!--//container-->
        </div><!--//promo-block-->
        
    </div><!--//page-wrapper-->
    <!-- Main Javascript -->          
    <script type="text/javascript" src="assets/plugins/jquery-3.4.1.min.js"></script>
    <script type="text/javascript" src="assets/plugins/bootstrap/js/bootstrap.min.js"></script>
    <script type="text/javascript" src="assets/plugins/prism/prism.js"></script>    
    <script type="text/javascript" src="assets/plugins/jquery-scrollTo/jquery.scrollTo.min.js"></script>      
    <script type="text/javascript" src="assets/plugins/stickyfill/dist/stickyfill.min.js"></script>                                                             
    <script type="text/javascript" src="assets/js/main.js"></script>
    
</body>
</html> 


