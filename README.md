# JWEB4.0
=========


JWEB4.0 is otherwise known as JDollarPart4 and it is used for datatransfer from

Linux to windows . and it is invented by wilmix jemin j in JWEB(JDollar) P.L.

So that Windows JDollar can easily take the data from LInux.

ADVANTAGES
===========

=> It is otherwise known as HYBRID REMOTE WEBAPPLICATION

=> IT is use for data transfer from one OS to other os.

so that hacker can't understood which LInux type os where the data is stored.

===> It is used for datastore and datatransfer agent.

==> JWEB4.0 is used only in Linux platform with VS-OS.

In VS-OS the orginal WDBAJDollar server will run there..

We already know that VS-OS provides high security from hackers

and Virus...

=>> JWEB4.0 is used for DATA HIGH SECURITY PURPOSE.

JDOLLAR PART2 and PART3 Agent SYNTAX: (use only in Linux Platform)
=====================================

<%

public class <classname>

{

public void JDOLLAR-Main( ) throws

{

<! JDOLLAR LOGIC !>

}

}

%>

JDOLLAR PART4 Agent SYNTAX: (use only in Linux Platform)
===========================================================

<%

public class <classname>

{

public void JDOLLAR-Main( ) throws

{

<! JDOLLAR LOGIC !>

}

}

%>



JDollar-Agent Program Syntax:
=============================


<DOMAINS>



<%

public class  <classname>
{




  public void  JDOLLAR-Main( ) throws <EXE>

{
 
 JDollar.Writeln("J$AGENTQUERY");

}


} 

%>


</DOMAINS>


Example:1-JDollarAgentProgram
========


DATAS.Jdollar  // It will  be at  VS-OS  Platform.
===============

<DOMAINS>

<USE>  CDollar.WDBA.*;
<USE> jxl.Cell;
<USE> jxl.Sheet;
<USE> jxl.Workbook;

<USE> jxl.read.biff.Biff<EXE>;

<USE> jxl.write.Write<EXE>;


<%

public class  DATAS
{




  public void  JDOLLAR-Main( ) throws <EXE>  , Biff<EXE>


{
 


String g=JDOLLARAGENT.JDOLLARAGENTS("datastores","USEDATABASE", "dbpwds","/mnt/live/memory/data/WilmixSoftware/WDBA/WDBAJ1");



String t= JDOLLARAGENT.JDOLLARAGENTS("dbuser","dbpwds",1,"wilmix78", "wilmix78",1,5,g);
 
 

 WQUERY.GetURLContent("http://localhost:8090/DATA.Jdollar");
 WQUERY.QUERY(t);

 

}


} 

%>


</DOMAINS>


output:

now  go thru  the  url in google  chrome :http://localhost:8080/DATAS.Jdollar




DATA.Jdollar -JDollarpart4-queryserver// It  may  be at  windows or any linux platform
============

<DOMAINS>



<%

public class  DATA
{




  public void  JDOLLAR-Main( ) throws <EXE>

{
 
 JDollar.Writeln("SELECTRVAL from datastorehg 3 to 33 , 1 to 1 ?= C By 1 1 : {0} : {0} :{1}");

}


} 

%>


</DOMAINS>



Advantages:
===========

a) You   can   pass only  query

using   JDollar.Writeln(QUERY);

B) Use  JDollar-Agent Program  to manipulate the  Query.

c)  You  can  call  the query  and  execute  and  display  the  query results on same  page.

 
Technology code: 14 ;  since  it  is  JDollarpart4...
