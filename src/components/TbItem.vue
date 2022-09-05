<template>
    <div>
      <table class="box" border="1px solid black">
        <tr>
          <th>Day/period</th>
          <th>I<br>9:30-10:20</th>
          <th>II<br>10:20-11:10</th>
          <th>III<br>11:10-12:00</th>
          <th>12.00-12.40</th>
          <th>IV<br>12:40-1:30</th>
          <th>V<br>1:30-2:20</th>
          <th>VI<br>2:20-3:10</th>
          <th>VII<br>3:10-4:00</th>
        </tr>
        <!-- first data table -->
       <tr>
        <td>Monday</td>
        <td>Eng</td>
        <td>Mat</td>
        <td>che</td>
        <td rowspan="6">
<b>
        L<br>
        u<br>
        n<br>
        c<br>
        h<br>
</b>
        </td>
        <td colspan="3">Lab</td>
        <td>Phy</td>
       </tr>
       <!-- second data table -->

       <tr>
        <td>Tuesday</td>
        <td colspan="3">lab</td>
        <td>Eng</td>
        <td>Che</td>
        <td>Mat</td>
        <td>Sports</td>
       </tr>
       <!-- third data -->
       <tr>
        <td>Wednesday</td>
        <td>Mat</td>
        <td>Phy</td>
        <td>Eng</td>
        <td>Che</td>
        <td colspan="3">Libary</td>
       </tr>
       <!-- four data -->
       <tr>
        <td>Thursday</td>
        <td>Phy</td>
        <td>Eng</td>
        <td>Che</td>
        <td colspan="3">Lab</td>
        <td>Mat</td>
       </tr>
       <!-- five data -->
       <tr>
        <td>Friday</td>
        <td colspan="3">Lab</td>
        <td>Mat</td>
        <td>Che</td>
        <td>Eng</td>
        <td>Phy</td>
       </tr>
       <!-- data six -->
       <tr>
        <td>Saturday</td>
        <td>Eng</td>
        <td>Che</td>
        <td>Mat</td>
        <td colspan="3">Seminar</td>
        <td>sports</td>
       </tr>






        <!--

           <tr>
          <td>
            Monday
          </td>

          <td>eng</td>
          <td>mat</td>
          <td>che</td>
          <td rowspan="6">
            <p>l</p>
            <p>u</p>
            <p>n</p>
            <p>c</p>
            <p>h</p>
          </td>
          <td colspan="3">
            lab
          </td>
        </tr>
        -->
        <tr>
        </tr>
      </table>
      
    </div>
  </template>
  
  <script>
  
  
  export default {
    name: 'TbItem'
    
  }
  </script>
  
  <style scoped>
    .box{
      border-collapse: collapse;
      margin: auto;
    }
    table td{
      width:8%

    }
    table{
      text-align: center;
    }
  

  
  </style>
  