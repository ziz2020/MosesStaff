# MosesStaff
The Moses Staff tool is a tool for connecting to different databases on Visual Studio, so that it facilitates a lot of work and with just a few lines it accomplishes a lot of work

kinds of ٍStaff

1: MosesSqlStaff for SqlServer

2: MosesFBStaff for FireBird

3: MosesOldStaff for Access

4: MosesSqLiteStaff for Sqlite

5: MosesPosStaff for Posgres

A: Download the tool from the link

<a href="https://mega.nz/file/CwkFkQJK#9yD_iAME0wTGfxlAFmnNxoU8U2SEHk3Az-udvUGDn4g">Download MosesSqlStaff</a>


B: Once you drop the tool on the form, click on Connect, and the wizard will take care of adding what you need .

<img src="https://i.pinimg.com/originals/d9/30/62/d93062d5db5055d0f521a1e8fc2f341a.jpg" />

<a href="https://www.youtube.com/watch?v=OEKfnNqXhMY">Video On Youtube</a>

Compiler by FrameWork 4.8



# commands to use

To fill Yor DataSet use 
<table>
  <tr>
    <th>StaffSqlTable1.Fill()</th>
  </tr>
</table>


To Add New Row
<table>
  <tr>
    <th>StaffSqlTable1.NewData()</th>
  </tr>
</table>

To Save DataChanged
<table>
  <tr>
    <th>StaffSqlTable1.Save()</th>
  </tr>
</table>

To Delete Row
<table>
  <tr>
    <th>StaffSqlTable1.Delete()</th>
  </tr>
</table>

Cancel the changes you made
<table>
  <tr>
    <th>StaffSqlTable1.Cancel()</th>
  </tr>
</table>

To add a primary key through the tool automatically
<table>
  <tr>
    <th>Set AutoPrimaryKey = True and AutoPrimaryKeyName = "Your_ID" </th>
  </tr>
</table>

To get the Table
<table>
  <tr>
    <th>StaffSqlTable1.GetTABLE()</th>
  </tr>
</table>
The function will return the Datatable






