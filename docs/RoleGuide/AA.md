
<html>
 <head>
    <style>
    {
        box-sizing: border-box;
    }
    /* Set additional styling options for the columns*/
    .column {
    float: left;
    width: 50%;
    }

    .row:after {
    content: "";
    display: table;
    clear: both;
    }
    </style>
 </head>
 <body>
    <div class="row">
        <div class="column" style="background-color:#FFB695;">
            <h2>Column 1</h2>
            <p>Data..</p>
        </div>
        <div class="column" style="background-color:#96D1CD;">
            <h2>Column 2</h2>
            <p>Data..</p>
        </div>
    </div>
 </body>
</html>