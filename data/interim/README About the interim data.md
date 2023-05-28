# About the interim data

* The CSV file has columns which indicate which document each row comes from, but the doc_page_number doesn't match exactly due to the non-table pages within the document which didn't get parsed. 
    * To match things up, the "index" column on the very right will correspond with the row number in the corresponding document.