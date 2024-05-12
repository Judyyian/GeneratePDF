# GeneratePDF
讀取excel/txt檔案，將欄位中不同ID分組產出不同PDF檔案，寄至欄位中對應信箱收件者

##Service層
ReadFileService 讀取excel檔案
PDFService 將檔案內容中ID分組，組成PDF檔案，一個ID一個檔案
MailService PDF檔分別寄至對應Email

##SMTP mail server
host="" port="25" userName="workflow" password="workflow" enableSsl="true"

