pageTurning
===========

one small pageTurning plugins

###use
*  import the necessary css&&js:
    <pre><code><link type="text/css" rel="stylesheet" href="pageTuring.css">
    <script type="text/javascript" src="jquery-1.9.1.min.js"></script> 
    <script type="text/javascript" src="page.js"></script>
    </code></pre>

*   write the necessary code in your html
   

    <pre><code>var currentPage = 1;
    
    
    var totalPage = 29;
    
    
    $.pageShow(currentPage,totalPage,"pager");
    </code></pre>
    
  
*  notice:
  currentPage is variational,every page is different,you can transmit variate,and the hyperlink in page.js you must padding
