# HTML

# HTML Headings
    <h1>Heading1</h1>
    <h2>Heading2</h2>
    <h3>Heading3</h3>
    <h4>Heading 4</h4>
    <h5>Heading 5</h5>
    <h6>Heading 6</h6>
    
#  HTML Images
    <!--  Static Image -->
    <img src="./images/nature_image.jpg" alt="nature image" width="500px" height="500px">

    <!--Dynamic Image-->
    <img src="https://img.etimg.com/thumb/msid-98912259,width-650,height-488,imgsize-67876,,resizemode-75/virat-kohli.jpg" alt="Virat Kholi">

#  HTML Tables

  <table border="1" style="width: 100%;">
        <thead> <!-- table head -->
            <tr> <!--  table row   -->
                <th>S.NO </th> <!-- table heading -->
                <th>CRICKTER NAME</th>
                <th>AGE</th>
                <th>Team</th>
                <th>BATESMAN/BOWLER</th>
            </tr>
        </thead>
        <tbody>
            <tr> <!-- 1st row -->
                <td>1</td> <!--  table data -->
                <td>VIRAT KHOLI</td>
                <td>36</td>
                <td>IND</td>
                <td>BATSMEN</td>
            </tr>
            <tr> <!-- 2nd row -->
                <td>2</td> <!--  table data -->
                <td>MAXWELL</td>
                <td>34</td>
                <td>AUS</td>
                <td>ALL ROUNDER</td>
            </tr>
        </tbody>
    </table>

# HTML Lists

  <ol>
    <!-- Ordered List -->
    <li>Rishab Pant</li>
    <!--  li-> list item -->
    <li>Brett Lee</li>
    <li>Tim Southee</li>
    <ol>
      <ol type="I">
        <!-- Ordered List -->
        <li>Rishab Pant</li>
        <!--  li-> list item -->
        <li>Brett Lee</li>
        <li>Tim Southee</li>
        <ol>
          <h3>Un Ordered List</h3>
          <ul>
            <!-- Unordered List -->
            <li>HTML</li>
            <li>CSS</li>
            <li>JS</li>
            <li>TS</li>
            <li>Angular</li>
          </ul>
          <h3>Nested List</h3>
          <ul>
            <li>HTML <ul>
                <li>head</li>
                <li>html</li>
                <li>body</li>
              </ul>
            </li>
          </ul>
            <ul>
            <li>CSS <ul>
                <li>width</li>
                <li>height</li>
              </ul>
            </li>
          </ul>


# HTML Links

      <!-- Dynamic Links-->
     
     <a href="https://google.com" target="_blank">Google</a>
     <a href="https://facebook.com" target="_blank">Facebook</a>
     <a href="https://myntra.com" target="_blank">Myntra</a>


     <!-- Static Links-->

      <h4>Top Wear</h4>
      <div><a href="./shirts/t_shirts.html" target="_blank">T-Shirts</a></div> <!-- divison tag-->
      <div><a href="./shirts/causual_shirts.html" target="_blank">Causual Shirts</a> </div>
      <div><a href="./shirts/formal_shirts.html" target="_blank">Formal Shirts</a> </div>

