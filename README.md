<!DOCTYPE html>
<html>
    <head>
        <title></title>
        <script type="text/javascript"></script>
        <style type="text/css" media="all">
            body{
                background-color: #EED426;
            }    
            h1{
                color: #006666;
                font-family: Verdana;
                text-align: center;
            }
            #rentalcost td,th{
                border: 1px solid;
            }
            #rentalcost
            {
                border:1px solid;
            }
        </style>

    </head>
    <body >
       
            <h1>College details</h1>
        <center>
            <form>
            <table>
            <tr>
                <td><label>Name</label></td>
                <td><input type="text" name="name" id="name" value="" placeholder="Enter the college name" pattern="[A-Za-z/s]+" required=""/></td>
            </tr>
            <tr>
                <td><label>Reg id</label></td>
                <td><input type="text" name="rid" id="rid" value="" placeholder="xxxx@dept" required/></td>
            </tr>
            <tr>
                <td><label>Year founded</label></td>
                <td><input type="text" name="year" id="year" value="" pattern="[7-9]{1}[0-9]{9}" placeholder="Enter ther founded year" required=""/></td>
            </tr>
            <tr>
                <td><label>City</label></td>
                <td><input type="text" name="city" id="city" value="" placeholder="Enter the city name" pattern="[A-Za-z/s]+" required=""/></td>
            </tr>
            <tr>
                <td><label>No of students</label></td>
                <td><input type="number" name="num_student" id="num_student" value="" required/></td>
            </tr>
            <tr>
                <td><label>Courses</label></td>
                <td><select name="courses" id="courses" required>
                    <option value="Computer science">Computer science</option>
                    <option value="Electronics">Electronics</option>
                    <option value="IT">IT</option>
                    <option value="MECH">MECH</option>
                    <option value="Electrical">Electrical</option>
                </select></td>
            </tr>
            <tr>
                <td><input type="submit" name="submit" id="submit" value="Submit"></td>
                <td><input type="reset" name="clear" id="reset" value="Reset"></td>
            </tr>
        </table>
        </form>
        <div id="result" name="result"></div>
        <label for="Rental Cost Table">Student details</label>
        <table id="rentalcost">
            <tr>
                <th>Name</th>
                <th>ID</th>
                <th>Year of batch</th>
                <th>
                    <td><select name="skills" id="sills" required>
                        <option value="C++">C++</option>
                        <option value="Java">Java</option>
                        <option value="C">C</option>
                        <option value="verilog">verilog</option>
                        <option value="C#">C#</option>
                    </select></td>
                </th>
            </tr>
        <tr><td>    </td><td>   </td><td>   </td><td>   </td><td>   </td></tr>
        <tr><td>    </td><td>   </td><td>   </td><td>   </td><td>   </td></tr>
        <tr><td>    </td><td>   </td><td>   </td><td>   </td><td>   </td></tr>
        <tr><td>    </td><td>   </td><td>   </td><td>   </td><td>   </td></tr>
        <tr><td>    </td><td>   </td><td>   </td><td>   </td><td>   </td></tr>
        </table>
    </center>
    </body>
</html>
