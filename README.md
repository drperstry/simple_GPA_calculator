# simple_GPA_Calculator

important setup:
<b>important setup: </b>
<br>
in the inputfilepath, the file should have the courses grades in the following format:
<br>
course	weight	letter
<br>
-this is an example of the input file:
<br>
MATH101 4 C+
<br>
MATH102 4 -
<br>
MATH102 3 D
<br>
<br>
how to use the code:
<br>
course_records = Get_records_from_file(inputfilepath="courses_records.txt", GPA_weight=4)
<br>
print(Put_data_in_file(course_records=course_records, outputfile="Final_GPA.txt"))
