# Drug-Simulation

Information and Data aboout QSAR research of mine

-----

第一次做的QSAR方面的研究，分享整个实验的思路和逻辑
整理上传所有的数据和实验方法、实验过程和结果
感兴趣的小伙伴可以看一下

也是第一次使用Github，所以要是有什么问题会逐渐完善：）


#outline

  Research base on experiment result simulate drug property,mostly with compute tools, cuz most the algorithm and software are done, so the core idea is the work :) and some learning experience.
  
#evaluation standard


  Theoretical evaluation criteria
  
    topological molecular descriptor、
  
    Geometric molecular descriptor、
    
    Physical & Chemial molecular descriptor}
  
  Experimental evaluation criteria{
    
    Experimental molecular descriptor
    
    LogP、molar refractive index、dipole moment、polarizability] 
    
    Theoretical molecular descriptor
    
    Atomic number、Molecular number
   
   Criteria:quantity description of abstract property]
   
   Simulation method
    
      CoMFA 
        
        Comparative molecular field analysis
      
      CoMSIA
      
        Comparative moeluar similarity indices analysis
   
-------


#Program flow
  
  Data sorting
  
  Molecular structure drawing
  [software: Chemidrwal pro、3D]
  
  Modeling
  [software:Sybyl]
  
    Molecular structure optmize
  
    Database sort
    
    Alignment molecular
    
    Dataprocessing
    
      CoMFA[Comparative molecular field analysis]
    
      CoMSIA[Comparative molecular similarity indices analysis]
## DATA

  Sample 
  IC50
  
>LHS3 
2.127104798

>LHS5 
1.924

>LHS6 
2.879

>LHS7 
2.985

>LHS8 
3.301

>SI4 
1.279

>SI36 
1.556

>SI37 
2.288

>SI38 
1

>SI39 
1.279

>SI40 
1.279

>MP4 
1.279

>MP29 
1.380

>MP30 
1.342

>MP31 
2.220

>MP32 
1.740

>MP33 
3.699

>MP34 
1.663

>MP35 
1.342

>NC50 
4.699

>NC51 
1

>RHS4 
1.279

>RHS5 
1.924

>RHS15 
1.785

>RHS16 
1.230

>RHS17 
1.544

>RHS18 
3.279

>RHS19 
2.176

>RHS20 
2.057

>RHS21 
1.940

>RHS22
2.678

>RHS23 
3.287

>RHS24 
2.199

>RHS25 
2.465

>RHS26 
2.679

>SA9 
2.624

>SA10 
2.732

>SA11 
2.470

>SA12 
3.903

>SA13 
2.921

>SA14 
2.464

>SI4 
1.279

>SI36 
1.279

>SI39 
1

>SI40 
1.279

>NC49 
3.4140


 
## software list
  
  Chemdraw
  
  Sybyl
  
#Attribute data
  
  name
  descriptor
  lg(ic50)
  pIC50
  
#database sort
  
  train group
  test group
 
#data analysis(have not learned totally QwQ)
 
  Weka
  SPSS
  e-Dragon
  
  
# Method commonly used model database
 
 Partial Squares Analysis (PLS)
 
 The search for a correlation between biological activity (dependent variable) and calculated potentials(independentvariables)forCoMFAandCoMSIAwascarriedoutbymeansofPLSstatistical analysis. Regression analysis was performed through leave-one-out (LOO) cross-validation procedure using SAMPLS method 
 
 In CoMFA and CoMSIA, the cross-validation analysis was applied to determine the value of the cross-validation coefﬁcient (q2), the cross-validated standard error of predictions (SEP), and the optimal number of components (N). The q2 value is a measure of the internal quality of the models which was calculated using the following formula:
 
 q^2 = 1−
∑(yi−ypred)^2 /∑(yi−yE)^2

where yi, y, and ypred are the observed, mean, and predicted activity in the training set, respectively. Final non-cross validated conventional analysis [41] was generated with the optimal number of components equal to that yielding the highest q2, and the corresponding conventional correlation coefﬁcient rncv2 was obtained. In addition, the statistical signiﬁcance of the models was described by its standard error of estimate (SEE) and the probability value (F-value).



 
  
-------

# paper resource

  [origin paper] (https://pan.baidu.com/s/1Zjdkp7DrCrM9GmlxRWMKrQ)

  [reference paper]
  (https://pan.baidu.com/s/1LqcH9JDLjpVjSpbk4gOLWQ)
  
# field paper note 
  
  3D QSAR and Molecular Docking(对接） Studies of Benzimidazol(苯并咪唑） Derivatives as Hepatitis(肝炎） C Virus NS5B Polymerase Inhibitor  


  https://docs.google.com/document/d/1hxyEAX1HBz_scmZbFqi1qZRL8p4mmGMCwJR4MpJ4nH8/edit?usp=sharing
  
  Insights into the Structural Requirements of Potent Brassinosteroids as Vegetable Growth Promoters Using Second-Internode Elongation as Biological Activity: CoMFA and CoMSIA Studies
  
  https://docs.google.com/document/d/1hIdckpnM92W3Z-U4jmneOhsVynhIPrCw66uQ1qPhLX0/edit?usp=sharing
  
  have fun:)
  
  
  



