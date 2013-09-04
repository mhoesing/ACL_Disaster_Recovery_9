ACL_Disaster_Recovery_9
=======================
This script has the precedent that in another donor ACL project, the user has created a PDF of the desired table layouts using File --> Print Project Contents with the printer set to a PDF file creation tool (I use Bullzip).

This script will import the PDF, parse for the table names and the field information. Build a list of tables and create each table layout within the recirpient ACL project using a series of DEFINE FIELD commands based on the lists created.

This will handle ASCII, DATE and PRINT field types.

This script deals only with physical fields. If you create a version that handles computed fields, particularly conditional computed fields, or additional physical field types please publish that version.
