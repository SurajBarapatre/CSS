<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Justify-Content & Align-Content</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="main">
        <div class="body body-1 ">
            <div class="container">
                <div class="head">
                    <h1>Display : Flex(Parent Property) Justify-Content</h1>
                     <br>
                    <li>The Justify-Content properrty align the flexible container's items do not use all available space on the main-axis(horizontally).</li>
                    <li>The Justify-Content properrtycan also be used on a grid container to align grid items in the inline
                        direction. For pages in English , inline direction is left to right and block direction is 
                        downward.
                    </li>

                    <h2>Display : Flex(Parent Property) Justify-Content : flex-start </h2>
                    <li> ➡️ Items are packed at the start of the main axis (left side).</li> <br>
                </div>

                <div class="sub-box box-1">
                    <div class="box">1</div>
                     <div class="box">2</div>
                      <div class="box">3</div>
                       <div class="box">4</div>
                    </div>
            </div>
        </div>

        <div class="body">
            <div class="container">
                <div class="head">
                    <h2>Display : Flex(Parent Property) Justify-Content : flex-end </h2>
                    <br>
                    <li> ➡️ Items are packed at the end of the main axis (right side).</li>
                </div>

                 <div class="sub-box box-2">
                    <div class="box">1</div>
                     <div class="box">2</div>
                      <div class="box">3</div>
                       <div class="box">4</div>
                    </div>
            </div>
        </div>

        <div class="body">
            <div class="container">
                <div class="head">
                    <h2>Display : Flex(Parent Property) Justify-Content : center </h2>
                    <br>

                <li> ➡️ Items are centered in the middle of the main axis.</li>
                </div>

                 <div class="sub-box box-3">
                    <div class="box">1</div>
                     <div class="box">2</div>
                      <div class="box">3</div>
                       <div class="box">4</div>
                    </div>
            </div>
        </div>

         <div class="body">
            <div class="container">
                <div class="head">
                    <h2>Display : Flex(Parent Property) Justify-Content : space-between  </h2>
                    <br>

                <li> ➡️ Items stretched across container with equal gaps between them..</li>
                </div>

                 <div class="sub-box box-4">
                    <div class="box">1</div>
                     <div class="box">2</div>
                      <div class="box">3</div>
                       <div class="box">4</div>
                    </div>
            </div>
        </div>


        <div class="body">
            <div class="container">
                <div class="head">
                    <h2>Display : Flex(Parent Property) Justify-Content : space-around  </h2>
                    <br>

                <li> ➡️ Items have equal space around them. Items evenly spaced, but outer sides have smaller space than between items.</li>
                </div>

                 <div class="sub-box box-5">
                    <div class="box">1</div>
                     <div class="box">2</div>
                      <div class="box">3</div>
                       <div class="box">4</div>
                    </div>
            </div>
        </div>

         <div class="body">
            <div class="container">
                <div class="head">
                    <h2>Display : Flex(Parent Property) Justify-Content : space-evenly </h2>
                    <br>

                <li> ➡️ Items have exactly equal space between them, including edges.
                    Items spaced perfectly evenly, including start and end. 
                </li>
                </div>

                 <div class="sub-box box-6">
                    <div class="box">1</div>
                     <div class="box">2</div>
                      <div class="box">3</div>
                       <div class="box">4</div>
                    </div>
            </div>
        </div>


         <div class="body body-1">
            <div class="container">
                <div class="head">
                    <h1>Display : Flex(Parent Property) Align-content  </h1>
                   <br>
                    <li>The css Align-items properly sets align-self value on all direct children as a group.
                        it controls the alignment of items on the cross axis . In grid 
                        layout , it controls the alignment of items on the block axis within their grid areas.
                    </li><br>

                    <h2>Display : Flex(Parent Property) Align : flex-start </h2> 
                    <li> Items align at the top of the container..All items stick to the top</li> <br>
                </div>

                <div class="sub-box box-7">
                    <div class="box">1</div>
                     <div class="box">2</div>
                      <div class="box">3</div>
                       <div class="box">4</div>
                    </div>
            </div>
        </div>


        <div class="body">
            <div class="container">
                <div class="head">
                     <h2>Display : Flex(Parent Property) Align-content  : flex-end </h2> 
                    <li> Items align at the bottom of the container..All items stick to the bottom</li> <br>
                </div>

                <div class="sub-box box-8">
                    <div class="box">1</div>
                     <div class="box">2</div>
                      <div class="box">3</div>
                       <div class="box">4</div>
                    </div>
            </div>
        </div>

         <div class="body">
            <div class="container">
                <div class="head">
                     <h2>Display : Flex(Parent Property) Align-content : center </h2><br> 
                    <li> Items align vertically in the middle of the container. All items appear in the center vertically</li> 
                </div>

                <div class="sub-box box-9">
                    <div class="box">1</div>
                     <div class="box">2</div>
                      <div class="box">3</div>
                       <div class="box">4</div>
                    </div>
            </div>
        </div>

         <div class="body">
            <div class="container">
                <div class="head">
                     <h2>Display : Flex(Parent Property) Align-content  : stretch </h2> 
                    <li> if the items than the alignment container,auto-sized items will be equally to fill the
                        container the items width and height limits
                    </li>
                </div>

                <div class="sub-box box-10">
                    <div class="box">1</div>
                     <div class="box">2</div>
                      <div class="box">3</div>
                       <div class="box">4</div>
                    </div>
            </div>
        </div>

         <div class="body">
            <div class="container">
                <div class="head">
                     <h2>Display : Flex(Parent Property) Align-content  : space-between </h2> 
                    <li>The items are evenly distribution container along the cross axis . the spacing between each pair of adjacent itms is the same .the first item is flush with the start edge
                        of the alignment content in the cross axis, and the last item is flush with the end edge of the alignment container in the cross axis. 
                    </li>
                </div>

                <div class="sub-box box-11">
                    <div class="box">1</div>
                     <div class="box">2</div>
                      <div class="box">3</div>
                       <div class="box">4</div>
                       <div class="box">5</div>
                     <div class="box">6</div>
                      <div class="box">7</div>
                       <div class="box">8</div>
                       <div class="box">9</div>
                     <div class="box">10</div>
                      <div class="box">11</div>
                       <div class="box">12</div>
                       <div class="box">13</div>
                     <div class="box">14</div>
                      <div class="box">15</div>
                       <div class="box">16</div>

                       
                    </div>
            </div>
        </div>


         <div class="body">
            <div class="container">
                <div class="head">
                     <h2>Display : Flex(Parent Property) Align-content  : space-arround </h2> 
                    <li>The items are evenly distribution with the alignment container along the cross rows.the spacing between pair of
                        adjacent itemsis the same .the empty
                        space before the first and after the last item equais half of the space between 
                        each pair of adjacent items. 
                    </li>
                </div>

                <div class="sub-box box-12">
                    <div class="box">1</div>
                     <div class="box">2</div>
                      <div class="box">3</div>
                       <div class="box">4</div>
                       <div class="box">5</div>
                     <div class="box">6</div>
                      <div class="box">7</div>
                       <div class="box">8</div>
                       <div class="box">9</div>
                     <div class="box">10</div>
                      <div class="box">11</div>
                       <div class="box">12</div>
                       <div class="box">13</div>
                     <div class="box">14</div>
                      <div class="box">15</div>
                       <div class="box">16</div>

                       
                    </div>
            </div>
        </div>


        <div class="body">
            <div class="container">
                <div class="head">
                     <h2>Display : Flex(Parent Property) Align-content  : space-evenly  </h2> 
                    <li>The items are evenly distribution with the alignment container along the cross axis.the spacing between each pair of
                        adjacent items , the start edge and the first item, and the end edge and the last item, are all exactly the same . 
                    </li>
                </div>

                <div class="sub-box box-13">
                    <div class="box">1</div>
                     <div class="box">2</div>
                      <div class="box">3</div>
                       <div class="box">4</div>
                       <div class="box">5</div>
                     <div class="box">6</div>
                      <div class="box">7</div>
                       <div class="box">8</div>
                       <div class="box">9</div>
                     <div class="box">10</div>
                      <div class="box">11</div>
                       <div class="box">12</div>
                       <div class="box">13</div>
                     <div class="box">14</div>
                      <div class="box">15</div>
                       <div class="box">16</div>

                       
                    </div>
            </div>
        </div>

       

        
    </div>
    
</body>
</html>