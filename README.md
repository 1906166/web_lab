<!DOCTYPE html>
<html>
	<head>
		<style>
			table
			 {
			 	align:center;
			 }
            body
             {
             	background-color:pink;
             }
            legend
             {
             	color:blue;
             	font-size:14;
             }
            h1
            {
            	color:red;
            }
           input
            {
            	background-color:cream;
            }
           form
            {
            	background-color:#c0cfce;
            	align:center;
            }
            fieldset
             {
             	align:center;
             	
             }

		</style>
	</head>
	<body >
		<h1 align="center">REGISTRATION FORM</h1>
		
        <fieldset style="background-color: lightyellow">
        	

            <legend style="font-color:blue; font-size:25;" >BASIC DETAILS</legend>
            <table>
               <tr>
               	 <td>Form Number</td>
               	 <td><input type="text"></td>
               	 </tr>
               <tr>
               	 <td>Name</td>
               	 <td><input type="text"></td>
               	 </tr>
               <tr>
               	 <td>Roll Number</td>
               	 <td><input type="number"></td>
               </tr>
               <tr>
               	 <td>Gender</td>
               	 <td>Male<input type="radio" value="Male" name="gender">Female<input type="radio" value="Female" name="gender">Other<input type="radio" value="Other" name="gender"></td>
               </tr>
               <tr>
               	 <td>DOB</td>
               	 <td><input type="date"></td>
               </tr>
               <tr>
               	 <td>PWD</td>
               	 <td>YES<input type="radio" value="YES" name="PWD"WIDTH="100PX" >NO<input type="radio" value="NO" name="PWD" WIDTH="100PX"></td>
               </tr>
               <tr>
               	 <td>Category</td>
               	 <td><select value=" ">
                     <option value="GEN">GENERAL</option>
                     <option value="GEN">OBC</option>
                     <option value="GEN">SC</option>
                     <option value="GEN">ST</option>
                     </select>
                 </td>
                </tr>
              <table>
                 <tr>
                 	<td>Adress</td>
                  </tr><br>
                 <tr>
                 	<td><textarea rows="5" cols="50" maxlength="10"></textarea></td>
                 </tr><br>
              <table>
              	 <tr><td>PLEASE INPUT THE CORRECT PINCODE</td></tr>
                 <tr><td>Pin Code</td><td><input type="number"></td></tr>
                 <tr><td>Phone Number of Student</td><td><input type="number"></td></tr>
                 <tr><td>Phone Number of Guardian</td><td><input type="text"></td></tr>

              </table>
      </fieldset>
      <fieldset style="background-color: lightgreen">
         <legend style="font-color:blue; font-size:25;" >ACADEMIC INFORMATION</legend>
              <table>
                 <tr>
                 	<td>Course</td>
                 	<td><select value="Select">
                        <option value="B.Tech">B.Tech</option>
                        <option value="B.Arch">B.Arch</option>
                        <option value="M.Tech">M.Tech</option>
                        <option value="M.Arch">M.Arch</option>
                        <option value="M.Tech(Dual Degree)">M.Tech(Dual Degree)</option>
                        <option value="M.Sc.Int">M.Sc.Int</option>
                        <option value="Ph.D">Ph.D.</option>
                        </select>
                   </td>
                 </tr>

                 <tr>
                 	<td>Semester</td>
                 	<td><select value="Select">
                        <option value="1st">1st</option>
                        <option value="2nd">2nd</option>
                        <option value="3rd">3rd</option>
                        <option value="4th">4th</option>
                        <option value="5th">5th</option>
                        <option value="6th">6th</option>
                        <option value="7th">7th</option>
                        <option value="8th">8th</option>
                    </select>
                    </td>
                  </tr>

                  <tr>
                  	<td>All India Rank</td>
                  	<td><input type="number"></td>
                  </tr>
                  <tr>
                  	<td>Category Rank</td>
                  	<td><input type="number"></td>
                  </tr>
                  <tr>
                  	<td>CGPA</td>
                  	<td><input type="number"></td>
                  </tr>

                  <tr>
                  	<td>Backlog</td>
                  	<td>YES<input type="radio" value="YES" name="Backlog"WIDTH="100PX">NO<input type="radio" value="NO" name="Backlog"WIDTH="100PX"></td>
                  </tr>

                  <tr>
                  	<td>Hostel Accomodation</td>
                  	<td>YES<input type="radio" value="YES" name="Hostel Accomodation"WIDTH="100PX">NO<input type="radio" value="NO" name="Hostel Accomodation" WIDTH="100PX">(IF ANY)<td>
                  </tr>

                  <tr>
                  	<td>Name Of Hostel</td>
                  	<td><input type="text"></td>
                  </tr>
                  <tr>
                  	<td>Room Number</td>
                  	<td><input type="number"></td>
                  </tr>

          </table>
        </fieldset>

        <form align="center">
          <fieldset>
          <legend style="font-color:red; font-size:25;">ACCOUNT DETAILS FOR REFUNDING PROCESS</legend>
             <table>
                <tr>
                	<td>Account Holder Name</td>
                	<td><input type="text"></td>
                </tr>
                <tr>
                	<td>Account Number</td>
                	<td><input type="Number"></td>
                </tr>
                <tr>
                	<td>IFSC Code</td>
                	<td><input type="Number"></td>
                </tr>
                <tr>
                	<td>Branch Name</td>
                	<td><input type="text"></td>
                </tr>
                <tr>
                	<td>Bank Branch</td>
                	<td><input type="text"></td>
                </tr>
              </table>
           </fieldset>
         </form>
      
      <p align="center"><input type="submit"  style="width:170px;height:35px; background-color:red;" value="Submit"></p><br>
      <h2><center>SUBMITTED BY<BR>SAURABH KUMAR PATIL<BR>
        ROLL NO-1906166<center></h2>

	</body>
</html>
