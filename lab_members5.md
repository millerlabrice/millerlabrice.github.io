---
title: Lab Members
icon: fa-users
order: 3
---
<head>
  <style>
@import url(https://fonts.googleapis.com/css?family=Source+Sans+Pro:400,200,200italic,300,300italic,400italic,600,600italic,700,700italic,900,900italic);

body {
    font-family: 'Source Sans Pro', sans-serif;
    color:#161616;
    text-rendering: optimizeLegibility;
    -webkit-font-smoothing: antialiased;
    -moz-font-smoothing: antialiased;
}
.heading-title {
    margin-bottom: 100px;
}
.text-center {
    text-align: center;
}
.heading-title h3 {
    margin-bottom: 0;
    letter-spacing: 2px;
    font-weight: normal;
}
.p-top-30 {
    padding-top: 30px;
}
.half-txt {
    width: 60%;
    margin: 0 auto;
    display: inline-block;
    line-height: 25px;
    color: #7e7e7e;
}
.text-uppercase {
    text-transform: uppercase;
}

.team-member, .team-member .team-img {
    position: relative;
}
.team-member {
    overflow: hidden;
}
.team-member, .team-member .team-img {
    position: relative;
}

.team-hover {
    position: absolute;
    top: 0;
    left: 0;
    bottom: 0;
    right: 0;
    margin: 0;
    border: 20px solid rgba(0, 0, 0, 0.1);
    background-color: rgba(255, 255, 255, 0.90);
    opacity: 0;
    -webkit-transition: all 0.3s;
    transition: all 0.3s;
}
.team-member:hover .team-hover .desk {
    top: 35%;
}
.team-member:hover .team-hover, .team-member:hover .team-hover .desk, .team-member:hover .team-hover .s-link {
    opacity: 1;
}
.team-hover .desk {
    position: absolute;
    top: 0%;
    width: 100%;
    opacity: 0;
    -webkit-transform: translateY(-55%);
    -ms-transform: translateY(-55%);
    transform: translateY(-55%);
    -webkit-transition: all 0.3s 0.2s;
    transition: all 0.3s 0.2s;
    padding: 0 20px;
}
.desk, .desk h4, .team-hover .s-link a {
    text-align: center;
    color: #222;
    line-height: 1;
}
.team-member:hover .team-hover .s-link {
    bottom: 10%;
}
.team-member:hover .team-hover, .team-member:hover .team-hover .desk, .team-member:hover .team-hover .s-link {
    opacity: 1;
}
.team-hover .s-link {
    position: absolute;
    bottom: 0;
    width: 100%;
    opacity: 0;
    text-align: center;
    -webkit-transform: translateY(45%);
    -ms-transform: translateY(45%);
    transform: translateY(45%);
    -webkit-transition: all 0.3s 0.2s;
    transition: all 0.3s 0.2s;
    font-size: 15px;
}
.desk, .desk h4, .team-hover .s-link a {
    text-align: center;
    color: #222;
    font-size: 15px;
    line-height: 1;
}
.team-member .s-link a {
    margin: 0 10px;
    color: #333;
    font-size: 18px;
    line-height: 1;
}
.team-title {
    position: static;
    padding: 0px 0;
    display: inline-block;
    letter-spacing: 2px;
    width: 100%;
    line-height: .85em;
}
.team-title h5 {
    margin-bottom: 0px;
    display: block;
    text-transform: uppercase;
    line-height: .85em;
}
.team-title span {
    font-size: 16px;
    text-transform: uppercase;
    color: #a5a5a5;
    letter-spacing: 1px;
    line-height: .85em;
}
</style>
</head>
{%- include header.html -%}
<body>

<div class="container">
                    <div class="row">
                        <div class="col-md-4 col-sm-4">
                            <div class="team-member">
                                <div class="team-img">
                                    <img src="/assets/images/tom_nm_final_crop2.jpg" alt="team member" class="img-responsive"  width="300" height="200">
                                </div>
                                <div class="team-hover">
                                    <div class="desk">
                                        <h4>Research Interests</h4>
                                        <p>Population dynamics, quantitative ecology, and species interactions</p>
                                    </div>
                                    <div class="s-link">
                                        <a href="https://github.com/texmiller"><i class="fab fa-github"></i></a>
                                        <a href="https://scholar.google.com/citations?user=50kDLlkAAAAJ&hl=en"><i class="fab fa-google"></i></a>
                                         <a href="https://github.com/millerlabrice/millerlabrice.github.io/blob/master/assets/CV/Miller_CV.pdf"><i class="far fa-file"></i></a>
                                    </div>
                                </div>
                            </div>
                            <div class="team-title">
                                <h5>Tom E.X. Miller</h5>
                                <span>PI</span>
                            </div>
                        </div>
                         <div class="col-md-4 col-sm-4">
                            <div class="team-member">
                                <div class="team-img">
                                    <img src="/assets/images/tingfa_dong.jpg" alt="team member" class="img-responsive" width="300" height="200">
                                </div>
                                <div class="team-hover">
                                    <div class="desk">
                                        <h4>Research Interests</h4>
                                        <p>Sex-specific demographic performance and population dynamics in dioecious plant species under biotic and abiotic stress.</p>
                                    </div>
                                     <div class="s-link">
                                        <a href="https://scholar.google.com/citations?user=H7RzIz8AAAAJ&hl=zh-CN"><i class="fab fa-google"></i></a>
                                    </div>
                                </div>
                            </div>
                            <div class="team-title">
                                <h5>Tingfa Dong</h5> 
                                <span>Visiting Scholar</span>
                            </div>
                        </div>
                        <div class="col-md-4 col-sm-4">
                            <div class="team-member">
                                <div class="team-img">
                                    <img src="/assets/images/MDonald.jpg" alt="team member" class="img-responsive" width="300" height="200">
                                </div>
                                <div class="team-hover">
                                    <div class="desk">
                                        <h4>Research Interests</h4>
                                        <p>Drivers of microbial symbiont prevalence and diversity within host populations, communities, and metacommunities.</p>
                                    </div>
                                    <div class="s-link">
                                        <a href="https://github.com/mdonald"><i class="fab fa-github"></i></a>
                                        <a href="https://mdonald.github.io"><i class="fas fa-star"></i></a>
                                        <a href="https://scholar.google.com/citations?hl=en&user=RcXMO0MAAAAJ&view_op=list_works&gmla=AJsN-F6z0ekQnOgA8Gr0RyokKIB2_n9t1Na2wYVZtfD_LfEPKsYAjYvnJj1tKGmXqL48fhnvV5ZIswSt4QgxblzU4p5ScBEoCkJF8ttFHxPAqePLMJiDM0M"><i class="fab fa-google"></i></a>
                                    </div>
                                </div>
                            </div>
                            <div class="team-title">
                                <h5>Marion Donald</h5>
                                <span>Ph.D. Student</span>
                            </div>
                        </div>
                        <div class="col-md-4 col-sm-4">
                            <div class="team-member">
                                <div class="team-img">
                                    <img src="/assets/images/josh_fowler.jpg" alt="team member" class="img-responsive" width="300" height="200">
                                </div>
                                <div class="team-hover">
                                    <div class="desk">
                                        <h4>Research Interests</h4>
                                        <p>Contributions of context-dependent mutualisms to species range limits and how they help hosts cope with environmental variability.</p>
                                    </div>
                                    <div class="s-link">
                                        <a href="https://github.com/joshuacfowler"><i class="fab fa-github"></i></a>
                                        <a href="https://joshuacfowler.github.io"><i class="fas fa-star"></i></a>
                                        <a href="#"><i class="fab fa-google"></i></a>
                                    </div>
                                </div>
                            </div>
                            <div class="team-title">
                                <h5>Josh Fowler</h5>
                                <span>Ph.D. Student</span>
                            </div>
                        </div>
                        <div class="col-md-4 col-sm-4">
                            <div class="team-member">
                                <div class="team-img">
                                    <img src="/assets/images/Jr_cropped.jpg" alt="team member" class="img-responsive" width="200" height="200">
                                </div>
                                <div class="team-hover">
                                    <div class="desk">
                                        <h4>Research Interests</h4>
                                        <p>Squirrels</p>
                                    </div>
                                    <div class="s-link">
                                    </div>
                                </div>
                            </div>
                            <div class="team-title">
                                <h5>Junior</h5>
                                <span>Best dog</span>
                            </div>
                        </div>
                        <div class="col-md-4 col-sm-4">
                            <div class="team-member">
                                <div class="team-img">
                                    <img src="/assets/images/chollaedited.jpg" alt="team member" class="img-responsive" width="200" height="200">
                                </div>
                                <div class="team-hover">
                                    <div class="desk">
                                        <h4>Research Interests</h4>
                                        <p>Growth, reproduction, and ant-plant mutualisms</p>
                                    </div>
                                    <div class="s-link">
                                    </div>
                                </div>
                            </div>
                            <div class="team-title">
                                <h5>Opuntia imbricata</h5>
                                <span>Prickly team member</span>
                            </div>
                        </div>
                    </div>
                </div>

</body>



<p>&nbsp;</p>


### Miller Lab Alumni


<head>
<style>
table {
  font-family: 'Source Sans Pro', sans-serif;
  font-size: 18px;
  color:#161616;
  border-collapse: collapse;
  width: 100%;
}

td, th {
  
  text-align: left;
  padding: 0px;
}

tr:nth-child(even) {
  background-color: #dddddd;
}
</style>
</head>

| Alum   |      Miller Lab       |  Current Position 
|:----------:|:-------------:|:------:
| Trevor Drees | Senior thesis 2019 | Ph.D. student - Shea Lab at Penn State 
| Nakian Kim |   Senior thesis 2018   | Ph.D. student, Crop Sciences, U. Illinois 
| Emily Schultz | Ph.D. 2018 | Postdoc - Evans Lab at U. Arizona 
| Michael Saucedo	| Lab manager 2018	| Teacher - NYC
| Michelle Sneck	| Ph.D. 2017	| Data Scientist, USAA
| <a href="https://bradochocki.com"> Brad Ochocki</a>	| Ph.D. 2017	| Data Scientist, Croptix
| <a href="https://aldocompagnoni.weebly.com">Aldo Compagnoni</a>	| Postdoc 2013-17	| German Centre for Integrative Biodiversity Research (iDiv) 
| Kevin Czachura	| Senior thesis 2017	| English instructor, Japan
| Belle Harris | Senior thesis 2017| 	
| Andrew Bibian	| M.S. 2015, Database Developer 2016-17|  Data Scientist, Insight
| Kory Kolis	| Lab manager 2015-16	| Ph.D. student - Fishman Lab at U. Montana 
| Brittany Cavazos | Senior thesis 2016	| Ph.D. student - Rogers Lab at Iowa State 
| Charlene Thomas	| Senior thesis 2016	| Biostatistician
| Marisol Palomeres	| Senior thesis 2015	| English instructor, South Korea 
| Emily Begnel	| Senior thesis 2015	| Public health graduate program, U. Washington 
| Teresa Bohner	| Lab manager, 2012-14	| Ph.D. student - Diez Lab at UC-Riverside
|<a href="https://mdonald.github.io">Marion Donald</a>	| Senior thesis 2014	| Ph.D. student - <a href="https://millerlabrice.github.io/lab_members5.html">Miller Lab at Rice</a>
| Olivia Ragni	| Senior thesis 2014	| Medical student
| Jesse Passman	| Senior thesis 2014	| Medical student
| Rande Patterson	| Senior thesis 2014	| Environmental consultant
| Natalie W. Niepoth	| Senior thesis 2014	| Ph.D. student - Bendensky Lab at Columbia University
| Johanna Ohm	| Senior thesis 2013	| Scientist, Verily
| Rebecca Searle	| Senior thesis 2013	| 
| Kate Snyder	| Senior thesis 2012 |	Ph.D. student at Vanderbilt
| Tatiana Fofanova | Senior thesis 2012 | Ph.D. Baylor College of Medicine  
| Nicole Freidenfelds	| Lab manager 2011-12	|  
